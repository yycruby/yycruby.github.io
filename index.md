---
layout: page
title: YYC Ruby
tagline: Calgary Ruby User Group
---
{% include JB/setup %}
#Rails Performance Optimization
## w/ [Tyler Mercier](https://twitter.com/tylermercier) and [Mo Khan](https://twitter.com/mocheen) of [Uppercut](http://madebyuppercut.com/)

Learn how to test the performance of your rails applications and ways to improve. We will demonstrate simple changes to increase throughput and reduce response time for a rails app. Topics will include asset optimization, using a CDN, caching and more.

Thanks! See you all then! 
[@TylerMercier](https://twitter.com/tylermercier)

###Location
<address>
  <a href="http://www.assemblycs.com">Assembly YYC</a><br />
  Suite 400  |  119 14th Street NW<br />
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


