---
layout: default
permalink: /teaching/
title: teaching
nav: true
nav_order: 3
social: true # includes social icons at the bottom of the page
---

## Green University of Bangladesh

{% assign courses_by_semester = site.teaching | group_by: "semester" %}
{% for group in courses_by_semester %}
  <h3>{{ group.name }}</h3>
  <table>
    <thead>
      <tr>
        <th>Course Code</th>
        <th>Course Title</th>
      </tr>
    </thead>
    <tbody>
      {% for course in group.items %}
      <tr>
        <td>{{ course.course_code }}</td>
        <td><a href="{{ course.url }}">{{ course.title }}</a></td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
{% endfor %}
