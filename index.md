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

    <div class="panel panel-primary">
      <div class="panel-heading">
        <h3 class="panel-title">Next Meetup</h3>
      </div>
      <div class="panel-body">
        {% assign post = site.posts.first %}
        {% assign content = post.content %}
        {% include post_detail.html %}

        <h3>Time/Date</h3>
        Tuesday, July 8th, 2014


        <a href="http://www.google.com/calendar/event?action=TEMPLATE&dates=20140709T003000Z%2f20140709T033000Z&sprop=website%3ahttp%3a%2f%2fwww.meetup.com%2fCalgaryRails%2fevents%2f189361682%2f&text=RTanque&location=Assembly+-+119+-+14+Street+NW+%28Floor+4%29+-+Calgary%2C+AB+%2C+Canada&sprop=name:Calgary+Ruby+on+Rails&details=For+full+details%2C+including+the+address%2C+and+to+RSVP+see%3A%0Ahttp%3A%2F%2Fwww.meetup.com%2FCalgaryRails%2Fevents%2F189361682%2F%0ACalgary+Ruby+on+Rails%0AA+little+more+laid+back+than+months+past.%0AJust+install+RTanque%2C+code+a+tank%2C+and+compete+with+others.+Regular+networking+and+hanging+as+always+wi%26hellip%3B">
          Google Calendar
        </a>

        <a href="http://www.meetup.com/CalgaryRails/events/189361682/ical/RTanque.ics">
          iCal
        </a>
      </div>
    </div>
  </div>
  <div class="col-md-6">

    <div class="panel panel-info">
      <div class="panel-heading">
        <h3 class="panel-title">Regular Meetup</h3>
      </div>
      <div class="panel-body">
        The First Tuesday of every month.
      </div>
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