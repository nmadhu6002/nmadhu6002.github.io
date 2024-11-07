---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<!-- ## [Words for Light (Movie Reviews)](https://nandanamadhukara.blogspot.com/) -->

## Blender

### Satisfying Pendulums
This is a simulation I created where I matched up the phase of the pendulums and ring.
<p align="center">
<video src="/images/Pendulum.mp4" controls="controls" style="max-width: 600px;" autoplay loop muted>
</video>
</p>

### Lorentz Transformation
As you may know, Albert Einstein's special theory of relativity predicts that for an inertial observer, moving objects contract, known as Lorentz contraction. Here I wanted to see how an object contracted as the object accelerated.
<p align="center">
<video src="/images/Lorentz_Transformation.mp4" controls="controls" style="max-width: 800px;" autoplay loop muted>
</video>
</p>

<!-- ### Donuts
<p align="center">
<video src="/images/Donuts.mp4" controls="controls" style="max-width: 800px;" autoplay loop muted>
</video>
</p> -->

<!-- ### Motion Tracking
<p align="center">
<video src="/images/MotionTracking_Monkey.mp4" controls="controls" style="max-width: 800px;" autoplay loop muted>
</video>
</p> -->

<!-- ### SciFi Modeling
<p align="center">
<img src='/images/SciFi_Tool.png' style="max-width: 650px;">
</p> -->

## Breakthrough Junior Challenge
(Click on the image to get directed to the video)
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}

