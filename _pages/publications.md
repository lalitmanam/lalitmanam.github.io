---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}
<!--
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
-->

You can also find my articles on <u><a href="https://scholar.google.co.in/citations?user=9UpkJwMAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
