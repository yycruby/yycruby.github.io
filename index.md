---
show_full_header: true
layout: page
title: YYC.rb
tagline: Calgary Ruby User Group
description: We meet once a month to code, do talks and meet others doing Ruby development in the Calgary area.
---
{% include JB/setup %}

<div class="row">
  <div class="blog-index col-md-6">

    {% include current_event.html %}

    <div class="panel panel-success">
      <div class="panel-heading">
        <h3 class="panel-title">Regular Meetup</h3>
      </div>
      <div class="panel-body">
        <p>The First Tuesday of every month.</p>
        <a href="http://startupcalgary.ca"><img src="/assets/images/startup-calgary.png"></img></a>
        <p>
          Part of the Startup Calgary Hack night series.
        </p>
        
      </div>
    </div>

  </div>


  <div class="col-md-6">

    <div class="panel panel-info">
      <div class="panel-heading">
        <h3 class="panel-title">Calendar of Events</h3>
      </div>
      {% include calendar.html %}
    </div>

    {% include assembly.html %}

  </div>

</div>


###Past Meetups

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>