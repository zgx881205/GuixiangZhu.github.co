---
# Template examples are kept in source for later customization.
# Remove these build/cascade rules after replacing their sample content.
# build:
 # render: never
 # list: never
 # publishResources: false
# title: Courses
# summary: My courses
# type: landing

# cascade:
  # - build:
     # render: never
     # list: never
     # publishResources: false
  # - target:
     # path: '{/courses/*/**}'
    # type: docs
    # params:
      # show_breadcrumb: true
# Page sections
title: 'AI+课题组在校学子'
date: 2024-05-19
type: landing
sections:
  - block: collection
    content:
      title: AI+课题组在校学子
      text: 南京财经大学计算机与人工智能学院电商实验室AI+课题组在校学子
      count: 0
      filters:
        folders:
          - students
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
---
