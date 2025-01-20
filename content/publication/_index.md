---
title: Publications
type: landing
# cms_exclude: true

# # View.
# view: citation

# # Optional header image (relative to `static/media/` folder).
# banner:
#   caption: ''
#   image: ''


sections:
  - block: collection
    id: publications
    content:
      title: Peer-Reviewed Publications
      filters:
        folders:
          - publication
    design:
      view: citation

  - block: collection
    id: Preprints
    content:
      title: Pre-prints
      filters:
        folders:
          - preprints
    design:
      view: citation
---
