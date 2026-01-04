---
title: "Textbooks"
permalink: /textbooks/
---

<ul>
  {% for item in site.data.course_links.textbooks %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      {% if item.note %} — {{ item.note }}{% endif %}
    </li>
  {% endfor %}
</ul>
