---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Blender
------
<p align="center">
<video src="/images/Pendulum.mp4" controls="controls" style="max-width: 750px;">
</video>
</p>

Breakthrough Junior Challenge
------
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

