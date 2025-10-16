---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: workingpaper
    content:
      title: Work in Progress
      filters:
        folders:
          - workingpaper
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: publications
    content:
      title: Publications
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
