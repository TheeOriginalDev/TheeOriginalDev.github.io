---
layout: archive
permalink: /blog/
author_profile: false
title: "Blog"
entries_layout: list
header:
  image: "/images/blog/blog.png"
---

{% for post in site.blogs %}
    {% include archive-double.html %}
{% endfor %}
