---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

  {% for post in site.files %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}

Education
======
* B.S. in Mathematics, Universidad Nacional Autonoma de Mexico
* M.S. in Mathematics, Universidad Nacional Autonoma de Mexico
* Ph.D in Mathematics, University of Virginia (in progress)

Publications
======
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
Talks
======
  {% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
  
Teaching
======
  {% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
