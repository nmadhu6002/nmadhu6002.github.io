---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<!-- ## [Words for Light (Movie Reviews)](https://nandanamadhukara.blogspot.com/) -->

## Blender

### Lorentz Transformation
As you may know, Albert Einstein's special theory of relativity predicts that for an inertial observer, moving objects contract, known as Lorentz contraction. Here I wanted to see how an object contracted as it accelerated.
<p align="center">
<video src="/images/Lorentz_Transformation.mp4" controls="controls" style="max-width: 800px;" autoplay loop muted>
</video>
</p>

<!-- {% for post in site.portfolio2 reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Breakthrough Junior Challenge
(Click on the image to get directed to the video)
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}

