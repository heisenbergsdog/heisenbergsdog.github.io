---
title: "Splash Page"
layout: splash
permalink: /splash-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/coffee.jpg
  actions:
    - label: "Download"
      url: "#test-link"
excerpt: "Tester page for tester things. Hope no one manages to find this site while experimental things are being conducted."
intro: 
  - excerpt: 'Secret tunnel. Secret tunnel. Through the mountains. Secret. Secret. Secret. Secret. Tunnel.'

feature_row:
  - image_path: /assets/images/galaxyDrawing.png
    title: "Galaxy"
    excerpt: "I made this in photoshop one time. Pretty cool, huh?"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/chalkboard.png
    title: "Placeholder 2"
    excerpt: "I wrote these equations just so I'd have a not-boring picture for some application. They're related to inflation (cosmological, not economical)."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/batia_and_charlie.jpg
    title: "Placeholder 3"
    excerpt: "This is my baby, Charlie Girl (ע״ה). I should put on a picture of my other baby, Sammie (ע״ה). "
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row_left:
  - image_path: /assets/images/galaxyDrawing.png
    title: "Left aligned placeholder 1"
    excerpt: "Left-aligned image"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row_right:
  - image_path: /assets/images/chalkboard.png
    title: "Placeholder 1"
    excerpt: "Right-aligned image"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row_left" type="left" %}

{% include feature_row id="feature_row_right" type="right" %}
