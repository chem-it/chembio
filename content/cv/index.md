---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-05-29
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '10px', '20px', '10px']
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
         - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['0', '10px', '20px', '10px']
    sections:
  - block: resume-languages
    content:
      title: Languages
      username: admin
---