---
layout: page
title: Semi-Pro Beaglebone Bricker
tagline: I hate computers
---
{% include JB/setup %}

This is the closest thing I have to a website.

[My PGP Key](James_Johnson_pub.asc)


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



