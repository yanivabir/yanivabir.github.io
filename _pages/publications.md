---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
      <li><a href="{{ author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i> Google Scholar</a></li>
{% endif %}
{% if author.googlescholar %}
  You can also find my papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
