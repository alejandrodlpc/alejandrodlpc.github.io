---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---

Disclaimer: These monographs are not peer-reviewed and may contain errors. Some may have incomplete sections as well. Any corrections are welcome!

{% include base_path %}

{% for post in site.resources reversed %}
  {% include archive-single-resources.html %}
{% endfor %}
