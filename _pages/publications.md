---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

  You can find a full list of my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=S3ybh7cAAAAJ&hl=en)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
