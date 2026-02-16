---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">My research interests span machine learning, image/signal processing and medical imaging. I am especially active in the <a href="https://en.wikipedia.org/wiki/Anomaly_detection">anomaly detection</a> community, furthermore when it involves representation learning, support estimation, auto-encoders or SVMs. Please find bellow a list of my publications.<br>You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
