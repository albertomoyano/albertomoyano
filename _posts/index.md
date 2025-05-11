---
layout: default
title: "Bienvenido a mi blog"
---

# 👋 ¡Hola!

Bienvenido a mi blog personal. Aquí comparto ideas, avances y experiencias relacionadas con mis proyectos.

## 📝 Últimos artículos

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d-%m-%Y" }})</small>
    </li>
  {% endfor %}
</ul>

