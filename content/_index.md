---
title: Home
date: 2020-03-22
description: "An astronomer and science communicator passionate about machine learning, software and statistics."
sections:
- template: hero
  options:
    paddingTop: false
    paddingBottom: false
    borderTop: false
    borderBottom: false
    classes: 'my-example-class'
    theme: base
  headings:
    heading: "Astronomy, software and scicomm"
    text: "todo"
  height: auto
  alignHorizontal: left
  alignVertical: middle
  background:
    backgroundImage: ''
    monotone: false
    opacity: ''
  image:
    image: "images/pages/photo-1596128446017-1106bd96ef89-1170.jpg"
    overlap: false
    border: false
    borderRadius: true
    shadow: false
    altText: "Hugo Paradigm"
  buttons:
    - button: 
      url: "https://www.zerostatic.io/theme/hugo-paradigm/"
      text: Buy Theme
      external: true
    - button: 
      url: "https://www.zerostatic.io/docs/hugo-paradigm/install-theme/"
      text: Documentation
      external: true

- template: info
  options:
    theme: base-offset
  heading: "Repeat, reorder and insert sections anywhere"
  description: "Use info sections to place configurable image, text and button blocks. Alternate image alignment or hide the image altogether, it still looks great."
  align: right
  image: "images/pages/photo-1593055454503-531d165c2ed8-1170.jpg"
  buttons:
  - button: 
    url: "/custom-page-1"
    text: Custom Page Example
    external: false
    theme: base-text
    
- template: grid
  options:
    theme: base
  heading: "Create dynamic page layouts using front-matter sections"
  subHeading: ''
  contentType: features
  sortBy: weight
  limit: 3
  columns: 4
  columnsMobile: 12
  marginBottom: 2
  align: left
  card:
    partial: card
    border: true
    padding: true
    shadow: true
    showThumbnail: true
    showThumbnailLink: true
    showFooter: true
    showTitle: true
    showTitleLink: true
    showDate: false
    
- template: hero
  options:
    paddingTop: false
    paddingBottom: false
    borderTop: true
    theme: base
  heading: "Configure everything in the front-matter"
  description: ''
  align: center
  image:
    image: "images/code.png"
    border: false
    shadow: true
    altText: "Markdown view of homepage, showing sections in the front-matter"
    
- template: cta
  options:
    theme: primary
  heading: "Kickstart your Hugo project"
  description: "Save days and weeks with our best practice templates."
  buttons:
  - button: 
    url: "https://www.zerostatic.io/theme/hugo-paradigm/"
    text: "Buy Theme"
    external: true
---
