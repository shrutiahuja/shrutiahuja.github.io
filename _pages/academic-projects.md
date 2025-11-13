---
layout: archive
title: "Academic Research Projects"
permalink: /academic-projects/
author_profile: true
---

{% include base_path %}

{% for post in site.academic_projects reversed %}
  {% include archive-single.html %}
{% endfor %}
