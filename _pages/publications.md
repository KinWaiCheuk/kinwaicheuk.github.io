---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  You can find the full list of my publications on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
