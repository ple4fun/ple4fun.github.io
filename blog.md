---
layout: default
title: Witaj na blogu
permalink: /blog
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">
<div class="hero">
  <p class="cta">
    <a href="{{ '/' | relative_url }}" class="btn">Strona główna</a>
    <a href="{{ '/kontakt' | relative_url }}" class="btn btn-secondary">Kontakt</a>
  </p>
</div>

### Dowiedz się więcej
{% assign posts = site.posts | slice: 0, 99999 %}
<ul>
{% for post in posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>— {{ post.date | date: "%Y-%m-%d" }}</small></li>
{% endfor %}
</ul>
