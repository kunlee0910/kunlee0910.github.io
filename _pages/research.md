---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from: 
  - /research/
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
## This is markdown
{% include base_path %}
This is new
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
