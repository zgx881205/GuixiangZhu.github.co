---
# Template examples are kept in source for later customization.
# Remove these build/cascade rules after replacing their sample content.
# build:
  # render: never
  # list: never
  # publishResources: false
#cascade:
 # build:
  #  render: never
  # list: never
  # publishResources: false

title: 'Projects'
date: 2024-05-19
type: landing

# Page sections
sections:
  - block: collection
    content:
      title: 主持或参与的基金项目/课题
      count: 0
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
