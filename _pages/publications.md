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

<h2>Learning and exploration</h2>
<p>The aim of my PhD work was to gain an understanding of how humans seek information. We are very effective in exploring our complex environment, collecting the information we need to pursue our goals. How do we do that? Consequently, we seem to be very curious creatures. Some economists have calculated that we are too curious. What guides our motivation to seek information that appears useless?</p> 

<p>My postdoctoral work at the UCL Max Planck Centre for Computational Psychiatry builds on these questions, studying how learning processes shape mood and motivation—and how they may underlie the therapeutic effects of antidepressants.</p>

{% for post in site.publications reversed %}
  {% if post.section == 'learning' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Prioritization for consciousness</h2>
<p>Before graduate school, I worked with <a href="http://labconscious.huji.ac.il/">Ran Hassin</a>, studying how our conscious perceptions are selected from the multitude of stimulation feeding into our visual systems.</p>
{% for post in site.publications reversed %}
  {% if post.section == 'consciousness' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
