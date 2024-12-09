---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-09
type: landing

sections:
  - block: hero
    content:
      title: |
        NDEMobil
        Research Group
      image:
        filename: ndemobil-team.jpg
      text: |
        <br>
        
        The **NDEMobil Research Group** is a junior research group supported by the German Federal Ministry for Research and Education through the German Medical Informatics Initiative. Its focus is on the analysis of mobile data for monitoring disease progression in neurodegenerative diseases.
  
  - block: collection
    content:
      title: Latest News
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---