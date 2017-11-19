---
layout: post
title:  "Monitoring with kamon and prometheus"
categories: monitoring
---

# Kamon and Prometheus

Last november, I gave a talke about monitoring with *Kamon* and *Prometheus* in the PSUG.

In this talk I used both tools to monitor a web application:

* The [first one](https://github.com/fagossa/play-prometheus/tree/kamon-akka-http), build with _akka-http_ used a directive
to interact with a _minMaxCounter_.

* The [second](https://github.com/fagossa/play-prometheus/tree/prometheus-playFramework/app), used _playFramework_. Here, thanks to _ActionBuilder_ s we increase and decrease a _Gauge_.

The video is available here:

{% include youtubePlayer.html id="fVw_8BOTF3s" %}


For more information, I've written a couple of blog post covering monitoring and alerting:

* One covers [basic concepts and terminology](http://blog.xebia.fr/2017/07/28/superviser-mon-application-play-avec-prometheus).

* The other handles mostly [alerting](https://en.fabernovel.com/insights/tech-en/alerting-in-prometheus-or-how-i-can-sleep-well-at-night).
