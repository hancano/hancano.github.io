---
layout: page
title: skills
permalink: /skills/
---

<ul>
  {% for skill in site.data.skills %}
    <li>{{ skill }}</li>
  {% endfor %}
</ul>