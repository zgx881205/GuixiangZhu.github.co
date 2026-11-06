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

sections:
  - block: collection
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
      columns: 2
---
