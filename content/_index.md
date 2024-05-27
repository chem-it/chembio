---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: collection
    content:
      title: Welcome
      subtitle: 'My latest posts and thoughts on science'
      text: 'Welcome to my page. Read my latest thoughts on science in the fields of antiviral research, medicinal chemistry and organic chemistry. I also share daily stories from my life as I enjoy exploring the countryside and culture in Hong Kong and follow my passion for [photography](https://unsplash.com/de/@chromatograph).<br>
      Follow me on <a href="https://fediscience.org/@chem_synthesis" rel="me">Mastodon</a> for updates.<br>'
        - block: collection
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      # Filter on criteria
      filters:
        folders:
          - post
          - blog
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
      view: compact
      columns: '2'
---