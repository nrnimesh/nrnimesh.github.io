---
layout: default
title: Dissected
permalink: /dissected/
---

<h1>Dissected Malware</h1>

<ul>
  {% for post in site.dissected %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

