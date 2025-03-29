---
layout: default
permalink: /teaching/
title: Teaching
nav: true
nav_order: 3
---
## Green University of Bangladesh

{% assign courses_by_semester = site.teaching | group_by: "semester" %}
{% for group in courses_by_semester %}
  <h2>{{ group.name }}</h2>
  <ul>
    {% for course in group.items %}
      <li>
        <a href="{{ course.url }}">{{ course.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}


