---
layout: archive
title: "Mathematics Notes"
permalink: /notes/
author_profile: true
---

I love writing and there are some mathematics notes. Feel free to use these notes. If you find out some mistakes, please contact me.



{% include base_path %}

{% for post in site.notes reversed %}
  {% include archive-single.html %}
{% endfor %}
