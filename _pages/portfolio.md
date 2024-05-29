---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

## Blender

### Satisfying Pendulums
<p align="center">
<video src="/images/Pendulum.mp4" controls="controls" style="max-width: 600px;" autoplay loop muted>
</video>
</p>

## Breakthrough Junior Challenge
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

