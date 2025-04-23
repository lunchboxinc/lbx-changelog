---
title: Lunchbox Changelog
---

<h1>What changed:</h1>

<div class="tab-buttons">
  <button onclick="showTab('core-products')">Core Products</button>
  <button onclick="showTab('core-service-revel')">Core Service Revel</button>
</div>

<div id="core-products" class="tab active">
  {% include_relative changelogs/core-products.md %}
</div>

<div id="core-service-revel" class="tab">
  {% include_relative changelogs/core-service-revel.md %}
</div>

<script>
function showTab(id) {
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}
</script>

<style>
.tab { display: none; }
.tab.active { display: block; }
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
