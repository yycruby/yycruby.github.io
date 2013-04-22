---
layout: page
title: Ruby Warrior Install Notes!
tagline: 23/04/13
---
{% include JB/setup %}


Past Meetups

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


