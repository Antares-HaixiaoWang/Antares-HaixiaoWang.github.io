---
layout: archive
title: "Mathematics Notes"
permalink: /notes/
author_profile: true
---

I love writing and there are some mathematics notes. Feel free to use these notes. If you find out some mistakes, please contact me.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
