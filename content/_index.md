---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |-
        I am a researcher from Chile and currently a Ph.D. candidate in Urban Studies at the Department of Urbanism at TU Delft.

        My research focuses on integrating multivariate, multiscalar and longitudinal methods to better undertand the causes, patterns and consequences of urban inequalities.

        I am also interested in the role of time and space in the analysis of social stratification and how these concepts can be operationalized in urban analytics.

        Please feel free to contact me if you are interested in collaborating!
        
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_IgnacioUrria.pdf
      headings:
        about: 'About me'
        education: 'Educational Background'
        interests: 'Research Areas'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      #background:
      #  gradient_mesh:
      #    enable: true
      css_class: dark
      theme: dark
      spacing:
        padding: [1rem, 0, 2rem, 0]
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: rapa-nui.jpg
          filters:
            brightness: 0.3
          size: cover
          position: center
          parallax: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl
        
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publications
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
  - block: collection
    content:
      title: Featured Research
      text: ''
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
---
