---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  You can also find my papers on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2>Exploration and curiosity</h2>
{% for post in site.publications reversed %}
  {% if post.section == 'exploration' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Prioritization for consciousness</h2>
{% for post in site.publications reversed %}
  {% if post.section == 'consciousness' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
