---
# Template examples are kept in source for later customization.
# Remove these build/cascade rules after replacing their sample content.
# build:
  # render: never
  # list: never
  # publishResources: false
# cascade:
 # build:
   # render: never
   # list: never
   # publishResources: false

title: 期刊会议
cms_exclude: true
type: landing

sections:
  - block: collection
    content:
      title: 期刊会议
      count: 0
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: 1
---
