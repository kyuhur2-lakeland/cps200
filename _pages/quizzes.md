---
title: "Quizzes"
permalink: /quizzes/
---

<ul>
  {% for item in site.data.course_links.quizzes %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      {% if item.note %} — {{ item.note }}{% endif %}
    </li>
  {% endfor %}
</ul>
