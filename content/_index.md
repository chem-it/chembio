---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: post
    content:
      title: Recent Posts
      filters:
        folders:
          - post
        featured_only: false
    design:
      columns: '2'
      view: card

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