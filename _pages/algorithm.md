---
layout: archive
title: "Algo"
permalink: /algo/
author_profile: true
---

{% include base_path %}

{% for post in site.algo reversed %}
  {% include archive-single.html %}
{% endfor %}
