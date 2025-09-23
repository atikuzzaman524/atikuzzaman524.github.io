---
layout: post
title: 	Classification with Decision Trees and SVMs
date: 2025-09-10 09:00:00-0400
description: Introduction to Data Mining - Introduction data and relevant Python libraries a blog post with jupyter notebook
tags: formatting jupyter
categories: DM Code
giscus_comments: true
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/Classification with Decision Trees and SVMs.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/Classification with Decision Trees and SVMs.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
