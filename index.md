---
layout: page
title: YYC Ruby
tagline: Calgary Ruby User Group
---
{% include JB/setup %}

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>

###Time/Date
  Tuesday, May 13, 2014
  
  [Google Calendar](http://www.google.com/calendar/event?action=TEMPLATE&dates=20140514T003000Z%2f20140514T033000Z&sprop=website%3ahttp%3a%2f%2fwww.meetup.com%2fCalgaryRails%2fevents%2f176442912%2f&text=Lightning+Talks%21&location=Assembly+-+119+-+14+Street+NW+%28Floor+4%29+-+Calgary%2C+AB+%2C+Canada&sprop=name:Calgary+Ruby+on+Rails+Group&details=For+full+details%2C+including+the+address%2C+and+to+RSVP+see%3A%0Ahttp%3A%2F%2Fwww.meetup.com%2FCalgaryRails%2Fevents%2F176442912%2F%0ACalgary+Ruby+on+Rails+Group%0ALightning+Talks+are+short+talks+given+by+anyone+in+the+group.+300+seconds+long+max.%0AThis+is+your+chance+to+talk+about+whatever+you+want.%0ARuby%2C+%26hellip%3B)

  [iCal](http://www.meetup.com/CalgaryRails/events/176442912/ical/Lightning+Talks%21.ics)

###Location
<address>
  <a href="http://www.assemblycs.com">Assembly YYC</a><br />
  Suite 400  |  119 14th Street NW
  <br />
  Calgary, AB, Canada
</address>

<iframe width="100%" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.ca/maps?f=q&amp;source=s_q&amp;hl=en&amp;geocode=&amp;q=119+14th+Street+Northwest,+Calgary,+AB&amp;aq=0&amp;oq=119+14th+Street+NW&amp;sll=51.013117,-114.088499&amp;sspn=0.661826,1.674042&amp;t=h&amp;ie=UTF8&amp;hq=&amp;hnear=119+14+St+NW,+Calgary,+Division+No.+6,+Alberta+T2N&amp;z=14&amp;ll=51.05309,-114.094895&amp;output=embed">
</iframe>




###Past Meetups

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


