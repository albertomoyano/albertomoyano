---
layout: default
title: "Inicio"
---

# Bienvenido a mi blog

Gracias por visitar mi blog personal. Aquí­ comparto reflexiones, ideas, avances y experiencias personales.

## Publicaciones recientes

<ul>
  {% for post in site.posts %}
    <li>
    <a href="{{ post.url }}">{{ post.title }} ({{ post.date | date: "%d-%m-%Y" }})</a>
    </li>
  {% endfor %}
</ul>
