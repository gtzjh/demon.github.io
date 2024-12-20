---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        EASE
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        EASE, the name of our research group, is an acronym for Emerging Air pollution and Sustainable Environment.
        
        We focus on Emerging Air pollution and Sustainable Environment.
  
  - block: collection
    content:
      title: Latest News & Events
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Our team →" %}}
    design:
      columns: '1'
---
