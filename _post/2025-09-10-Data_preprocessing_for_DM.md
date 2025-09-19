---
layout: post
title: 	Data Preprocessing for Data Mining
date: 2025-09-10 08:57:00-0400
description: Introduction to ML- Introduction data and relevant Python libraries a blog post with jupyter notebook
tags: formatting jupyter
categories: DM Code
giscus_comments: true
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/Introduction_to_ML.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/Data Preprocessing in Data Mining.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
