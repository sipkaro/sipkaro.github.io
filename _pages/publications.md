---
layout: archive
title: "Publications"
permalink: /permalink/
author_profile: true
---


{% if site.author.googlescholar %}
  <div class="wordwrap">
    <a href="https://scholar.google.com/citations?user=-f-uRoYAAAAJ&hl=en" target="_blank"><strong>Google Scholar profile</strong></a>.
  </div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
