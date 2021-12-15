---
caption: #what displays in the portfolio grid:
  title: Example
  subtitle: subtitle
  thumbnail: 'assets/img/portfolio/04-thumbnail.jpg'
  
#what displays when the item is clicked:
title: Title
subtitle: subtitle lorem ipsum dolor sit amet consectetur.
image: 'assets/img/portfolio/04-thumbnail.jpg'

carousel:
    - images: 
      - image: /assets/img/portfolio/04-thumbnail.jpg
      - image: /assets/img/portfolio/04-thumbnail.jpg
      - image: /assets/img/portfolio/04-thumbnail.jpg
      - image: /assets/img/portfolio/04-thumbnail.jpg
    - images: 
      - image: /assets/img/portfolio/04-thumbnail.jpg
      - image: /assets/img/portfolio/04-thumbnail.jpg
      - image: /assets/img/portfolio/04-thumbnail.jpg
      - image: /assets/img/portfolio/04-thumbnail.jpg
---

{% include carousel.html height="50" unit="%" duration="7" number="1" %}
{% include carousel.html height="50" unit="%" duration="7" number="2" %}
