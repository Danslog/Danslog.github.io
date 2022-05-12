---
title: "Python"
layout: archive
permalink: categories/python
sidebar:
    - nav: "docs"
---


{% assign posts = site.categories.python %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
