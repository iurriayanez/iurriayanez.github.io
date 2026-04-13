---
title: 'Research'
#cms_exclude: true
type: landing

sections:
  - block: collection
    content:
      title: Journal Articles
      text: ''
      filters:
        folders:
          - publications
        publication_type: article-journal
        featured_only: false
    design:
      view: citation

  - block: collection
    content:
      title: Working Papers
      text: ''
      filters:
        folders:
          - publications
        publication_type: preprint
        featured_only: false
    design:
      view: citation
      spacing:
        # Top, Right, Bottom, Left
        padding: ['0rem', '0', '0', '0']

# View.
#view: citation

# Optional header image (relative to `static/media/` folder).
#banner:
#  caption: ''
#  image: ''
---
