---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

  You can find a full list of my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=S3ybh7cAAAAJ&hl=en)

{% include base_path %}

## AI in oncology

{% for post in site.publications reversed %}
  {% if post.path contains "number-6" or post.path contains "number-7" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## NeuroImaging ML Method developement

{% for post in site.publications reversed %}
  {% if post.path contains "number-1" or post.path contains "number-2" or post.path contains "number-3" or post.path contains "number-4" or post.path contains "number-5" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
