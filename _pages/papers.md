---
layout: archive
title: "Selected Papers"
permalink: /papers/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">For a full list of my published and unpublished manuscripts, please see my <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
