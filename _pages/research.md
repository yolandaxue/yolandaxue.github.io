---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research interests include economics of innovation, information disclosure, intellectual property rights, and digitization. My research develops novel methods to measure innovation, explores the fundamental forces that drive firms' decisions on public disclosure of innovation activities, and investigates how patent right enforcement impacts innovation disclosure.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
  <ul>
      {% for post in site.research | sort:"order_number" %}
    {% include archive-single.html %}
  {% endfor %}</ul>
