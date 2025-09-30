---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-09-12
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 个人简介
        education: 教育经历
        interests: 科研兴趣
  - block: markdown
    content:
      title: '📚 科研内容'
      subtitle: ''
      text: '现阶段正在开展的研究内容:
（1）Sen1及其同源蛋白质Senataxin（SETX）介导的转录终止机制的研究，运用单分子磁镊和单分子荧光示踪方法，实时追踪Sen1/SETX与RNA聚合酶的动态相互作用过程，确定转录调控过程中关键复合物功能组分的空间分布及随时间演变的催化机理。
（2）疾病相关转录因子与RNA聚合酶的相互作用而调节转录动态过程的机制；内源性转录终止机制的研究，通过追踪RNA的动力学行为来揭示内源性转录终止机制；rho介导的转录终止机制的研究，借助单分子磁镊操控方法，来实时追踪rho催化转录终止的化学反应过程，揭示相关终止机制。
（3）基于现有的生物大分子之间的相互作用工作基础，借助应用单分子精密技术，开展中药活性成分精准筛选和干预方面的研究。
欢迎感兴趣的联系合作！ 😃'
    design:
      columns: 1
  - block: collection
    id: papers
    content:
      title: 发表论文
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: 科研项目
      filters:
        folders:
          - project
        featured_only: false    
    columns: 2
  - block: collection
    id: teaching
    content:
      title: 教学
      filters:
        folders:
          - teaching
    design:
       view: card
  - block: collection
    id: news
    content:
      title: 新闻
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      columns: 1
  - block: collection
    id: contact
    content:
      title: 联系我们
      filters:
        folders:
          - contact
    design:
      view: card
      columns: 1
  
---
