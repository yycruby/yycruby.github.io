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

    <div class="panel panel-success">
      <div class="panel-heading">
        <h3 class="panel-title">Announcements</h3>
      </div>
      <div class="panel-body">
        <p>Help us make 2015 a great year for Ruby in Calgary by filling out our
        short survey. <a
        href="https://yycruby.typeform.com/to/KYTtFM">https://yycruby.typeform.com/to/KYTtFM</a></p>
        <p>We also have a new Twitter account if you'd prefer to hear about
        upcoming events that way and send us questions. <a
        href="https://twitter.com/yyc_ruby">@yyc_ruby</a></p>
      </div>
    </div>

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