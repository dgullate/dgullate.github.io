---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: li-yang-5h_dMuX_7RE-unsplash.webp
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
#  - block: stats
#    content:
#      items:
#        - statistic: "15"
#          description: |
#            Publications
#        - statistic: "1,000+"
#          description: |
#            Citations
#        - statistic: "78"
#          description: |
#            h-index
#    design:
      # Section background color (CSS class)
#      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        I am Professor of Applied Mathematics and Head of Mathematics at IE University. My work bridges mathematical physics, approximation theory, and applied machine learning, with an emphasis on transferring mathematical research to practical industry applications.

        I lead projects on knowledge transfer and applied data science, and write about research, industry collaboration, and sustainable, impact-driven solutions.

        **Specialties:** Exceptional orthogonal polynomials, Mathematical Physics, Approximation Theory, Applied Machine Learning, Knowledge Transfer
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
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
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
