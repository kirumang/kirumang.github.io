---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my Google Scholar profile. [Link](https://scholar.google.com/citations?user=6l7yKbQAAAAJ&hl=en)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
