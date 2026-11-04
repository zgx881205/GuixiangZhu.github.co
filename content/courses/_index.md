---
# Template examples are kept in source for later customization.
# Remove these build/cascade rules after replacing their sample content.
<details>
build:
  render: never
  list: never
  publishResources: false
title: Courses
summary: My courses
type: landing

cascade:
  - build:
      render: never
      list: never
      publishResources: false
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true
<\details> 

sections:
  - block: collection
    id: courses
    content:
      title: Courses
      filters:
        tag: Course
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---
