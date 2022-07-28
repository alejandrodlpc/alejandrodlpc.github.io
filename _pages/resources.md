---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

{% for post in site.resources reversed %}
  {% include archive-single-resources.html %}
{% endfor %}
