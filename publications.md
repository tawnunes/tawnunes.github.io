---
layout: default
title: "Publicações"
lang: pt
---

# Minhas Publicações

<div class="publications-grid">
{% for post in site.data.publications %}
  <div class="publication-box" onclick="window.location='{{ post.link }}';">
    <h3>{{ post.title }}</h3>
    <p><strong>Revista:</strong> {{ post.journal }}</p>
    <p>{{ post.summary }}</p>
  </div>
{% endfor %}
</div>
