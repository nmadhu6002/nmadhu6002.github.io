---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

## [Words for Light (Movie Reviews)](https://nandanamadhukara.blogspot.com/)

## Blender

### Donuts
<p align="center">
<video src="/images/Donuts.mp4" controls="controls" style="max-width: 800px;" autoplay loop muted>
</video>
</p>

### Satisfying Pendulums
<p align="center">
<video src="/images/Pendulum.mp4" controls="controls" style="max-width: 600px;" autoplay loop muted>
</video>
</p>

### Motion Tracking
<p align="center">
<video src="/images/MotionTracking_Monkey.mp4" controls="controls" style="max-width: 800px;" autoplay loop muted>
</video>
</p>

### SciFi Modeling
<p align="center">
<img src='/images/SciFi_Tool.png' style="max-width: 650px;">
</p>

## Breakthrough Junior Challenge
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}

