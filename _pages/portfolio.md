---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Blender
------
<!-- ![Satisfying Pendulum](/images/Pendulum.mp4) -->
<video src="/images/Pendulum.mp4">
</video>

Breakthrough Junior Challenge
------
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

