---
title: "Wildstyle"
layout: splash
permalink: /splash-page/
date: 2020-01-06
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/images/freestyle/graffiti.jpg"
  actions:
    - label: "Instagram"
      url: "https://www.instagram.com/whoisdevonjones/"
  caption: "Photo Credit [**Me**](https://www.instagram.com/whoisdevonjones/)"
excerpt: "Free-spirited, creativity at its finest, who doesn't like a little bit of photography from the instagram! Follow me @whoisdevonjones"
intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: "/images/freestyle/11s.jpg"
    alt: "11's"
    title: "Air Jordan Retro 'Concord' 11s"
    excerpt: "These are one of my favorite pairs of kicks all time."
  - image_path: "/images/freestyle/12s.jpg"
    image_caption: "Image courtesy of [StockX](https://stockx.com/)"
    alt: "12's"
    title: "Air Jordan Retro 'The Master' 12s"
    excerpt: "One of my go to kicks for everyday use *periodt*."
    url: "https://stockx.com/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "/images/freestyle/13s.jpg"
    title: "Air Jordan Retro 'Black Cat' 13s"
    excerpt: "If you don't own a pair of these... well you don't own a pair I guess"
feature_row2:
  - image_path: "/images/freestyle/11s.jpg"
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: "/images/freestyle/13s.jpg"
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: "/images/freestyle/jordan.jpg"
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
