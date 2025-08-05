---
layout: default
title: Tradecraft
---
<ul>
  {% for post in site.tradecraft %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

