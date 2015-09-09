---
layout: page
title: Semi-Pro Beaglebone Bricker
tagline: I hate computers
---
{% include JB/setup %}

My name is James Johnson. I have a PhD in Computer Science. I work for [a startup](http://www.synercontechnologies.com). This is my website. 

[My PGP Key](James_Johnson_pub.asc)


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



