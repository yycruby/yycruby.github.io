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
  Tuesday February 18th, 6:30
  
  [Google Calendar](http://www.google.com/calendar/event?action=TEMPLATE&dates=20140219T013000Z%2f20140219T043000Z&sprop=website%3ahttp%3a%2f%2fwww.meetup.com%2fCalgaryRails%2fevents%2f159650582%2f&text=Rubygems%2C+Rails+4.1+and+RSpec+syntax%3A+Oh+my%21&location=Assembly+-+119+-+14+Street+NW+%28Floor+4%29+-+Calgary%2C+AB+%2C+Canada&sprop=name:Calgary+Ruby+on+Rails+Group&details=For+full+details%2C+including+the+address%2C+and+to+RSVP+see%3A%0Ahttp%3A%2F%2Fwww.meetup.com%2FCalgaryRails%2Fevents%2F159650582%2F%0ACalgary+Ruby+on+Rails+Group%0AThree+smaller+presentations.%0AMore+info+posted+as+it+becomes+solidified.%0ASpeakers%0ATim+Uruski+%26amp%3B+Ben+Stevenson%0ARails+4.1%3A+Nifty+Bits+-+Ben%0AI%26%23%26hellip%3B)

  [iCal](http://www.meetup.com/CalgaryRails/events/159650582/ical/Rubygems%2C+Rails+4.1+and+RSpec+syntax%3A+Oh+my%21.ics)

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


