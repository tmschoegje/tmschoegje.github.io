---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

{% for post in site.cv reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
