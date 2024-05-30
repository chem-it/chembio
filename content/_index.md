---
# Leave the homepage title empty to use the site title
title: 'Exploring Science, Nature and Culture'
date: 2024-05-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: 'Welcome'
      subtitle: ''
      text: |-
        ![Skyline of HK at night](/images/landing.jpg)

        ## Exploring Science, Nature and Culture

        I am researcher currently in the field of developing novel antivirals. On this page I will share my latest insights and perspectives on antiviral research, medicinal chemistry and organic chemistry. Currently based in the vibrant city of Hong Kong, I am eager to learn more about the local Cantonese culture. Therefore, I am not only exploring the city, but also traveling around Guangdong and learning Cantonese. 
        
        For the latest updates on my research and adventures, please feel free to follow my <a href="https://fediscience.org/@chem_synthesis" rel="me">Mastodon</a> account.  
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['40px', '10px', '40px', '10px']
  - block: collection
    id: news
    content:
      title: My latest thoughts
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: article-grid
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---