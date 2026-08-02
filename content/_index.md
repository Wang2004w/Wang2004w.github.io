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
      text: '团队基于单分子生物物理学、分子生物学等多学科技术，围绕疾病相关的基因转录调控过程开展研究工作，系统解析转录因子、RNA聚合酶及相关信号通路的调控效应，及药物干预机制，力求以定量化、精准化的研究手段为生命科学与中医药研究提供新理论与技术支撑。

现阶段正在开展的研究内容:

（1）疾病机制研究方面，团队关注肌萎缩侧索硬化症4型（ALS4）的关键蛋白——Senataxin及其同源蛋白Sen1，利用单分子磁镊、单分子荧光成像及冷冻电镜等技术，通过研究它们与RNA聚合酶的动态相互作用过程，来揭示其调控转录的分子机制。

（2）免疫炎症机制研究方面，团队重点关注转录共生的R-loop的形成、解离，探讨其调控炎症基因及对细胞功能的影响，从而揭示免疫炎症过程中R-loop的重要功能及其调控转录的分子机制。

（3）基于生命过程机制的中药活性成分筛选与作用机制研究方面，团队结合分子生物学、单分子生物物理学与系统药理学方法，建立以生命过程关键事件（如转录起始、应激响应、氧化还原平衡）为导向的中药活性成分筛选策略。通过解析天然产物对RNA聚合酶及其调控因子的作用机制，探索中药活性分子在维持细胞稳态、抗氧化与抗炎反应中的分子基础，为中医药现代化和精准药物研发提供科学依据。

欢迎感兴趣的联系合作！ 😃'
    design:
      columns: 1
  - block: collection
    id: papers
    content:
      title: '发表论文'
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
      title: '科研项目'
      filters:
        folders:
          - project
        featured_only: false
    design:
      view: article-grid
    columns: 2
  - block: collection
    id: news
    content:
      title: '新闻动态'
      filters:
        folders:
          - news
    design:
      # Choose a layout view
      view: card
      columns: 1
  - block: collection
    id: contact
    content:
      title: '招生招聘'
      filters:
        folders:
          - contact
    design:
     # view: 🗃️card
      columns: 1
  
---
