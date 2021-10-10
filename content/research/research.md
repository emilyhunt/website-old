---
title: Research
url: "/research"
date: 2020-03-22
description: An overview of my research experience
headerTransparent: true
layout: custom
sections:


- template: hero
  options:
    paddingTop: false
    paddingBottom: false
    borderTop: false
    borderBottom: false
    theme: primary
    classes: "my-custom-class another-custom-class"
  alignHorizontal: left
  alignVertical: middle
  height: 700px
  headings:
    heading: How can astronomy make the most of modern data?
    subHeading: 
    text: 'I work with a range of techniques to process and analyse our huge 21st century datasets.'
  background:
    backgroundImage: "/images/pages/lance-anderson-GOK4iscFSkA-unsplash-2000.jpg"
    opacity: 1
    monotone: false
  image:
    image: ''
    shadow: false
    border: false
    
    
- template: info
  heading: Detecting star clusters with Gaia
  options:
    paddingTop: true
    paddingBottom: true
    borderTop: false
    borderBottom: false
    theme: base
    classes: ""
  align: left
  description: TODO
  image: https://source.unsplash.com/qtYhAQnIwSE/800x600y
  
  
- template: info
  heading: Classification & validation of star clusters
  options:
    theme: base-offset
  align: right
  description: TODO
  image: https://source.unsplash.com/OfwiURcZwYw/800x600
  buttons:
  - button: 
    text: Features
    external: false
    url: "/features"
  - button: 
    text: Blog
    external: false
    url: "/posts"
    theme: base-text
    

- template: info
  heading: Bayesian open cluster parameters
  options:
    paddingTop: true
    paddingBottom: true
    borderTop: false
    borderBottom: false
    theme: base
    classes: ""
  align: left
  description: TODO
  image: https://source.unsplash.com/qtYhAQnIwSE/800x600y
  

- template: cta
  options:
    paddingTop: false
    paddingBottom: false
    theme: primary
  heading: Publications
  description: 
  buttons:
  - button: 
    url: https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-5555-8058&sort=date+desc
    text: View my publications on ADS
    external: true
    theme: primary-offset
    
    
- template: grid
  options:
    theme: base
  heading: Past research
  text: Here's a selection of other things I've worked on in the past.
  contentType: features
  sortBy: weight
  align: left
  limit: 4
  columns: 6
  columnsMobile: 12
  card:
    partial: card
    shadow: false
    border: false
    padding: true
    showTitle: true
    showDescription: true
    showDate: false
    showThumbnail: true
    showThumbnailLink: true
---