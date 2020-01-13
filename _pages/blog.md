---
layout: archive
permalink: /blog/
title: "Projects"
author_profile: true
header:
  image: "/images/sjsharks.jpg"
---

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}
