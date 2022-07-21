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
excerpt: "Putting the horses first"
intro: 
  - excerpt: 'horses are horses because horses are horses so they are all actaully horses'
feature_row:
  - image_path: /assets/images/BW2.jpg
    alt: "placeholder image 1"
    title: "Services"
    excerpt: "You can find out more about what **sevices** Emma provides and how to book in here."
    url: /services/
    btn_label: "See More"
    btn_class: "btn--primary"
  - image_path: /assets/images/homeequines.jpg
    alt: "placeholder 2"
    title: "Equines"
    excerpt: "Meet the team of horses"
    url: /equines/
    btn_label: "See More"
    btn_class: "btn--primary"
  - image_path: /assets/images/homeabout.jpg
    title: "About"
    excerpt: "Learn more about what Emma stands for and why she does what she does"
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