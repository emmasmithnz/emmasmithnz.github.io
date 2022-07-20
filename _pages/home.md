---
title: "Emma Smith NZ"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Banner.JPG
  actions:
    - label: "Book a session now"
      url: /contact/
  caption: "Photo credit: [**Emma Smith**]"
excerpt: "Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/BW2.jpg
    alt: "placeholder image 1"
    title: "Services"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /services/
    btn_label: "See More"
    btn_class: "btn--primary"
  - image_path: /assets/images/homeequines.jpg
    alt: "placeholder 2"
    title: "Equines"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /equines/
    btn_label: "See More"
    btn_class: "btn--primary"
  - image_path: /assets/images/homeabout.jpg
    title: "About"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /about/
    btn_label: "See More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/BrightonRock.jpg
    alt: "placeholder image 2"
    title: "Contact"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "/contact/"
    btn_label: "Contact Emma"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/BrightonRock.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/BrightonRock.jpg
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