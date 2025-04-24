---
title: Lunchbox Changelog
---

<h1>Release Notes:</h1>

<div class="tab-buttons">
  <button onclick="showTab('core-products')">Core Products</button>
  <button onclick="showTab('core-service-revel')">Core Service Revel</button>
</div>

<div id="core-products" class="tab" markdown="1">
{% include_relative changelogs/core-products.md %}
</div>

<div id="core-service-revel" class="tab" markdown="1">
{% include_relative changelogs/core-service-revel.md %}
</div>

<script>
function showTab(id) {
  document.querySelectorAll('.tab').forEach(t => t.style.display = 'none');
  document.getElementById(id).style.display = 'block';
}
// Optional: Set default tab on load
window.onload = () => showTab('core-products');


document.addEventListener("DOMContentLoaded", () => {
  document.querySelectorAll(".utc-date").forEach(el => {
    const utcDate = new Date(el.textContent.trim());
    if (!isNaN(utcDate)) {
      el.textContent = utcDate.toLocaleString();  // User’s local time
      el.title = utcDate.toISOString();           // Hover for raw UTC
    }
  });
  });


</script>

<style>
.tab { display: none; }
.tab-buttons button {
  margin: 0 10px;
  padding: 6px 12px;
  font-size: 16px;
  border-radius: 6px;
  border: none;
  background: #0366d6;
  color: white;
  cursor: pointer;
}
.tab-buttons button:hover {
  background: #024ea2;
}
</style>
