---
layout: page
title: Next Meetup, To Be Announced.
tagline: May/June 2013
---
{% include JB/setup %}

#To Be Announced


<br/>
<br/>
<br/>
<br/>

###Meeting Location
Assembly YYC
Suite 400  |  119 14th Street NW
Calgary, AB, Canada

<br/>
<br/>
<br/>


A big thanks to everyone! See you all on the 14th.


Past Meetups

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


