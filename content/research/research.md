---
title: Research
url: "/research"
date: 2023-09-20
description: An overview of my research experience. I work with machine learning and statistical techniques to analyse big datasets.
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
    heading: Unlocking the full potential of huge astronomy datasets
    subHeading: 
    text: "with machine learning, statistics and software"
  background:
    backgroundImage: "/images/content/research/gaia.jpg"
    opacity: 1.0
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
  description: The Gaia satellite is revolutionising our understanding of the Milky Way, with around 1 billion reliable sources in the latest release (DR3). Thousands of star clusters can be found within this data, but doing so requires efficient ways to autonomously and reliably search through it. I used clustering algorithms to create the largest ever catalogue of star clusters within our own galaxy.
  image: "/images/content/research/ocs_artist_impression.jpg"
  buttons:
  - button: 
    text: Related blog posts
    external: false
    url: "/categories/star-clusters"
  - button: 
    text: Latest paper
    external: false
    url: "/posts/230324-gaia-cluster-catalogue/"
    theme: base-text
  
  
- template: info
  heading: Validation and characterisation of star clusters
  options:
    theme: base-offset
  align: right
  description: It's important to not only catalogue star clusters but to do so as reliably as possible. To enhance our catalogue, I'm working on statistical ways to validate star clusters based on their density, photometry, and dynamical properties. This uses a range of techniques, including a Bayesian convolutional neural network and a statistical model for whether or not a candidate cluster is gravitationally bound.
  image: "/images/content/research/cst_with_distance.jpg"
  buttons:
  - button: 
    text: Related blog posts
    external: false
    url: "/categories/star-clusters"
  - button: 
    text: Latest paper
    external: false
    url: "/posts/230324-gaia-cluster-catalogue/"
    theme: base-text
    

- template: info
  heading: Open source software
  options:
    paddingTop: true
    paddingBottom: true
    borderTop: false
    borderBottom: false
    theme: base
    classes: ""
  align: left
  description: Open source software has been key to my PhD, and I'd really love to give some things back to the community. All of the code from my PhD will be open sourced in the near future - watch this space! In addition, I'm currently developing open source software to help astronomers communicate on the Bluesky social network.
  image: "/images/content/research/ocelot.png"
  buttons:
  - button: 
    url: https://github.com/emilyhunt
    text: Check out my GitHub
    external: true
  

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
    theme: primary-text
  - button: 
    url: /categories/paper-summaries/
    text: Blog posts about my papers
    external: false
    theme: primary-text
    
    
- template: grid
  options:
    theme: base
  heading: Other research
  text: Here's some other stuff I did before my PhD.
  contentType: research_other
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