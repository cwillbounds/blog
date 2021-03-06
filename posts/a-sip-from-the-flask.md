---
publish_date: '2014-10-28'
title: A sip from the Flask
---

I had to do a Flask workshop last weekend for the anniversary of a local
Python users group. I’ve done a few introductory presentations for Flask
before but I’ve always hated running my examples. Normally I’ll have 3 windows
open: the presentation, my editor and a terminal. It’s a chore to switch
through them and very error prone. So I thought about how to do it better.
Turns out the solution was right in front of me. I was already running my
presentation’s Flask app inside a docker container. Why not do that as well
for all my examples? Using [docker-py](https://github.com/docker/docker-py), I
ran the examples inside containers using random ports and added them to the
presentation with `iframes`. Sweet and simple. You can check it out here:
<http://asftf.marksteve.com>