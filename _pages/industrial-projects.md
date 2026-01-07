---
layout: archive
title: "Industrial Research Projects"
permalink: /industrial-projects/
author_profile: true
---

{% include base_path %}

{% assign projects = site.industrial_projects | sort: "date" | reverse %}
{% for post in projects %}
  {% include archive-single.html %}
{% endfor %}
