---
# Leave the homepage title empty to use the site title
title:
type: landing

sections:
  - block: hero
    content:
      title: |
        CoMind Lab
      image:
        filename: landingpage.jpg
      text: |
        <br>
        
        At the **CoMind Lab**, we study how people make diagnostic decisions under uncertainty, especially in high-stakes settings like the emergency room, to better understand and improve collaborative decision-making in medicine and beyond.
  
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Publication
      text: ""
      count: 5
      filters:
        folders:
          - publications
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./team/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
