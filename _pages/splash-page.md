---
title: "Splash Page"
layout: splash
permalink: /splash-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/coffee.jpeg
  actions:
    - label: "Download"
      url: "#test-link"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

feature_row:
  - image_path: /assets/images/galaxyDrawing.png
    title: "Placeholder 1"
    excerpt: "Sample text 1 with **markdown** formatting."
    `url: "#test-link"`
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/chalkboard.png
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    `url: "#test-link"`
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/batia_and_charlie.heic
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    `url: "#test-link"`
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row_left:
  - image_path: /assets/images/galaxyDrawing.jpg
    title: "Left aligned placeholder 1"
    excerpt: "Left-aligned image centered with"
    `url: "#test-link"`
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row_right:
  - image_path: /assets/images/chalkboard.png
    title: "Placeholder 1"
    excerpt: "Right-aligned image with"
    `url: "#test-link"`
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_left" type="left" %}

{% include feature_row id="feature_row_right" type="right" %}
