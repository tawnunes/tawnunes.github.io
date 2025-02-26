---
layout: default
title: "Portfólio"
lang: pt
---

# Meu Portfólio

<div class="portfolio-grid">
{% for item in site.data.portfolio %}
  <div class="portfolio-box" onclick="window.location='{{ item.link }}';">
    <h3>{{ item.title }}</h3>
    <p><strong>Categoria:</strong> {{ item.category }}</p>
    <p>{{ item.description }}</p>
  </div>
{% endfor %}
</div>

