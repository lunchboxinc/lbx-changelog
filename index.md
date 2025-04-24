---
title: Lunchbox Changelog
---

<h1>Release Notes:</h1>

<div class="tab-buttons" id="tab-buttons"></div>
<div id="tab-contents"></div>

<script>
document.addEventListener("DOMContentLoaded", async () => {
  // Load repo names from changelog-index.json
  const res = await fetch('changelogs/changelog-index.json');
  const repos = await res.json();

  const buttons = document.getElementById('tab-buttons');
  const contents = document.getElementById('tab-contents');

  repos.forEach((repo, i) => {
    const btn = document.createElement('button');
    btn.textContent = repo.replace(/-/g, ' ');
    btn.onclick = () => showTab(repo);
    buttons.appendChild(btn);

    const div = document.createElement('div');
    div.id = repo;
    div.className = 'tab';
    contents.appendChild(div);
    fetch(`changelogs/${repo}.md`)
      .then(r => r.text())
      .then(markdown => {
        div.innerHTML = marked.parse(markdown);
      });
  });

  showTab(repos[0]); // Show first by default

  // Local time conversion for utc-date spans
  setTimeout(() => {
    document.querySelectorAll(".utc-date").forEach(el => {
      const utcDate = new Date(el.textContent.trim());
      if (!isNaN(utcDate)) {
        el.textContent = utcDate.toLocaleString();
        el.title = utcDate.toISOString();
      }
    });
  }, 500);
});

function showTab(id) {
  document.querySelectorAll('.tab').forEach(t => t.style.display = 'none');
  document.getElementById(id).style.display = 'block';
}
</script>

<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>


<style>
.tab { display: none; white-space: pre-wrap; }
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
