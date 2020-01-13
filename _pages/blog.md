---
layout: archive
permalink: /blog/
title: "Projects"
author_profile: true
header:
  image: "/images/blog/blog.png"
---

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}
