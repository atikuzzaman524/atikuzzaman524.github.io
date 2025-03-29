---
layout: default
permalink: /teaching/
title: teaching
nav: true
nav_order: 3
subtitle: Academic Courses & Learning Resources
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



<br><br>  

## More Information

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <strong>Location:</strong> Green University of Bangladesh, Purbachal American City, Kanchan, Rupganj, Narayanganj-1461, Dhaka, Bangladesh
    <br><br>
    <strong>Phone:</strong> +8801912961096  
    <br>
    <strong>Email:</strong> <a href="mailto:atik@cse.green.edu.bd">atik@cse.green.edu.bd</a>  
  </div>
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3649.6933383217!2d90.56373737556672!3d23.829501478616525!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755cb0a4c65ef27%3A0xf54f56affbffdc99!2sGreen%20University%20of%20Bangladesh!5e0!3m2!1sen!2sbd!4v1726748990452!5m2!1sen!2sbd&t=&z=13&ie=UTF8&iwloc=&output=embed" style="width: 400px; height: 300px; border:0;"></iframe>
</div>



