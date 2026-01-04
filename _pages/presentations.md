---
title: "Presentations"
permalink: /presentations/
---

<ul>
  {% for item in site.data.course_links.presentations %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      {% if item.note %} — {{ item.note }}{% endif %}
    </li>
  {% endfor %}
</ul>
