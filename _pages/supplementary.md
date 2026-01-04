---
title: "Supplementary"
permalink: /supplementary/
---

<ul>
  {% for item in site.data.course_links.supplementary %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      {% if item.note %} — {{ item.note }}{% endif %}
    </li>
  {% endfor %}
</ul>
