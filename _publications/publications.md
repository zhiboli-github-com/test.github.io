---
layout: archive
title: "Publications"
permalink: /publications/2021_AR_Does CRA-40 outperform other reanalysis products in evaluating near-surface wind speed changes over China.pdf
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
