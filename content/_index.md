---
title: '个人主页'
summary: 'Guixiang Zhu 的个人主页'
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ''
      button:
        text: 访问我的官方主页
        url: http://cie.nufe.edu.cn/info/1053/7546.htm
      headings:
        about: 关于我
        education: 教育经历
        interests: 兴趣方向
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
