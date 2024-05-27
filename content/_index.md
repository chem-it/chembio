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
      text: 'My name is Stephan Scheeff, and I am a chemist working on the design and synthesis of antiviral compounds. Since the end of 2021, I have been actively engaged in research on nucleoside analogues as part of the research group led by [Prof. Billy Ng at the Chinese University of Hong Kong](https://www.ngwailung.com/). In this role, I can use my expertise in synthetic and medicinal chemistry to develop structurally novel antiviral agents. For this work I was awarded with the [Hong Kong Postdoctoral Fellowship 2022/2023](https://www.ugc.edu.hk/eng/rgc/funding_opport/pdfs/). 

      I received my doctoral degree (Dr. rer. nat., equivalent to a PhD) for my total synthesis studies of polyketides from the University of Bonn under supervision of Prof Dirk Menche.

      Aside from conducting research, I enjoy exploring the countryside and culture in Hong Kong and follow in my passion for [photography](https://unsplash.com/de/@chromatograph).

      Follow me on <a href="https://fediscience.org/@chem_synthesis" rel="me">Mastodon</a> for updates.'
      
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: 'My latest posts and thoughts on science'
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Post-Doctoral Researcher
          company: Chinese University of Hong Kong
          company_url: 'https://www.cuhk.edu.hk'
          #company_logo: org-CUHK
          location: Hong Kong
          date_start: '2021-11-01'
          date_end: ''
          description: Synthesis of antiviral drugs @ Prof Billy Ng
        - title: Post-Doctoral Researcher
          company: Hong Kong University
          company_url: 'https://www.hku.hk'
          #company_logo: org-HKU
          location: Hong Kong
          date_start: '2018-11-01'
          date_end: '2021-11-01'
          description: Organic chemistry and methods development @ Prof Pauline Chiu
        - title: Research Assistant
          company: TU Dresden
          company_url: 'https://www.tu-dresden.de'
          #company_logo: org-HKU
          location: Germany
          date_start: '2018-04-01'
          date_end: '2021-09-30'
          description: Total synthesis of natural products @ Prof Peter Metz
        - title: Research Assistant
          company: University of Bonn
          company_url: 'https://www.uni-bonn.de'
          #company_logo: org-HKU
          location: Germany
          date_start: '2015-01-01'
          date_end: '2018-03-31'
          description: Total synthesis of natural products @ Prof Dirk Menche
    design:
      columns: '2'  
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
---