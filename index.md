---
title: DIGH
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Introduction to Digital Humanities Research and Computing, Fall 2015
---

Welcome to the course website for DIGH, Introduction to Digital Humanities Research and Computing.

This course is offered by the [Center for Textual Studies and Digital Humanities](http://www.luc.edu/ctsdh/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}
* {{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})

  {{ post.summary }}
{% endfor %}
