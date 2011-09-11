---
layout: default
title: bmann on Github
---

* Tech blog: <http://blog.bmannconsulting.com>
* Personal blog: <http://bmann.ca>

## Sections

* [Class Afloat 1993 - 1994](/classafloat/)

## Posts

{% for post in site.posts limit:15 %}
 * [{{ post.title }}]({{ post.url }})
{% endfor %}

There should be a list of site posts above this text.