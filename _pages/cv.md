---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- M.S. Mechatronics and Robotics, New York University
- B.S. Mechanical Engineering, Beijing Jiaotong University

Current Position
======
- Research Assistant, ShanghaiTech University

Research Interests
======
- Humanoid Robotics
- Dexterous Manipulation
- Robot Perception
- Reinforcement Learning
- World Models
- Vision-Language-Action Models

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Projects
======
<ul>{% for post in site.portfolio %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Links
======
- [Google Scholar](https://scholar.google.com/scholar?q=%22Ke+Yang%22+robotics)
- [GitHub](https://github.com/Rookie629)
- [Email](mailto:REPLACE_WITH_EMAIL@shanghaitech.edu.cn)
