---
layout: default
title: SLACKHA
---

# Welcome to SLACKHA!

Site under development---please check back soon!

## Software

 * [pyJac](https://github.com/SLACKHA/pyJac): Python-based software that creates C and CUDA analytical Jacobians for chemical kinetics ODE systems
 * [accelerInt](https://github.com/SLACKHA/accelerInt): Library of tested and verified ODE solvers for chemical kinetics

## Updates

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Team

 * [Kyle Niemeyer](http://kyleniemeyer.com), Oregon State University
 * [Chih-Jen Sung](http://combdiaglab.engr.uconn.edu), University of Connecticut
 * [Nicholas Curtis](https://github.com/arghdos), University of Connecticut
 * Christopher Stone, Computational Science & Engineering

## Thanks

<img style="float: right;" src="/public/img/nsf1.jpg" width="224px">

We gratefully acknowledge funding from the NSF through the [SI2 program](www.nsf.gov/si2/)
under grants [1535065](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1535065&HistoricalAwards=false) (Oregon State)
and [1534688](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1534688&HistoricalAwards=false) (UConn).

In addition, we thank [Convergent Science](https://convergecfd.com) for providing access to their CFD
software and working with us.
