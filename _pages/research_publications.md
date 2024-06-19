---
layout: archive
title: "Research and Publications"
permalink: /researchpublications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">This is a list of my first author publications. You can also find my full list of publications on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

