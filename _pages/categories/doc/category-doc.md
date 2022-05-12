---
title: "Dan's Documents"
layout: archive
permalink: categories/doc
sidebar:
    - nav: "docs"
---

---

## Python
---
{% assign posts = site.categories.python %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}

&nbsp;

## Pytorch
---
{% assign posts = site.categories.pytorch %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}


## Deep Learning
---
{% assign posts = site.categories.DL %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}