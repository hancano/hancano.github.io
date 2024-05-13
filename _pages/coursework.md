---
layout: page
title: coursework
permalink: /coursework/
---

<ul>
  {% for course in site.data.coursework %}
    <li>{{ course }}</li>
  {% endfor %}
</ul>