---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Robotics projects spanning humanoid systems, dexterous manipulation, robot perception, soft robot sensing, and robust 3D vision.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
