---
layout: default
permalink: /teaching/
title: Teaching
nav: true
nav_order: 3
display_categories: [2025, 2024]
horizontal: true
---
## Green University of Bangladesh
### Spring 2025 Courses

<table style="width:100%; border-collapse: collapse; text-align: center; border: 1px solid black;">
  <thead>
    <tr style="border: 1px solid black;">
      <th style="border: 1px solid black; padding: 8px;">Course Code</th>
      <th style="border: 1px solid black; padding: 8px;">Course Title</th>
      <th style="border: 1px solid black; padding: 8px;">Course Page</th>
    </tr>
  </thead>
  <tbody>
    {% assign sorted_courses = site.teaching | sort: "title" %}
    {% for course in sorted_courses %}
    <tr style="border: 1px solid black;">
      {% assign parts = course.title | split: "_" %}
      <td style="border: 1px solid black; padding: 8px;">{{ parts[1] }}</td>
      <td style="border: 1px solid black; padding: 8px;">{{ parts[2] | replace: "-", " " }}</td>
      <td style="border: 1px solid black; padding: 8px;"><a href="{{ course.url | relative_url }}">Course Page</a></td>
    </tr>
    {% endfor %}
  </tbody>
</table>




