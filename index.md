---
layout: default
title: SLACKHA
---

# Welcome to SLACKHA!

Site under development---please check back soon!

# Updates

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Team

 * [Kyle Niemeyer](http://kyleniemeyer.com), Oregon State University
 * [Chih-Jen Sung](http://combdiaglab.engr.uconn.edu), University of Connecticut
 * [Nicholas Curtis], University of Connecticut
 * Himakar Ganti, University of Connecticut
 * Christopher Stone, Computational Science & Engineering

# Thanks

![NSF logo](/public/img/nsf1.jpg){:width="224px" class="inset right img-circle"}

We gratefully acknowledge funding from the NSF through the [SI2 program](www.nsf.gov/si2/)
under grants [1535065](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1535065&HistoricalAwards=false) (Oregon State)
and [1534688](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1534688&HistoricalAwards=false) (UConn).
