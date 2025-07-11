---
layout: post
title: Markov Decision Processes (MDPs)
date: 2025-07-05 08:57:00-0400
description: Markov Decision Processes (MDPs) a blog post with jupyter notebook
tags: formatting jupyter
categories: ML Code
giscus_comments: true
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/Markov_Decision_Processes_(MDPs).ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/lecture1-introduction.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
