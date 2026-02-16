---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

<div class="wordwrap">I delivered more than 200h of teaching, mainly to engineering students. Please find bellow the list of these courses.</div>

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
