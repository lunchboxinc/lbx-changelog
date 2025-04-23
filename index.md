---
title: Lunchbox Changelog
---

<h1>What changed:</h1>

<div class="tab-buttons">
  <button onclick="showTab('core-products')">Core Products</button>
  <button onclick="showTab('core-service-revel')">Core Service Revel</button>
</div>

<div id="core-products" class="tab">
{% include_relative changelogs/core-products.md %}
</div>

<div id="core-service-revel" class="tab">
{% include_relative changelogs/core-service-revel.md %}
</div>

<script>
function showTab(id) {
  document.querySelectorAll('.tab').forEach(t => t.style.display = 'none');
  document.getElementById(id).style.display = 'block';
}
// Optional: Set default tab on load
window.onload = () => showTab('core-products');
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
