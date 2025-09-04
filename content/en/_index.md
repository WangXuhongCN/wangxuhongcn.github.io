---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 Big Picture'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  - block: markdown
    content:
      title: '📚 Selected News'
      subtitle: ''
      text: |-
        [2025.8] Released the SOTA CoT-PRM model ([VRPRM](https://arxiv.org/abs/2508.03556)), achieving Test-time Scaling effect of Best-of-N approaching the theoretical limit value Pass@K, surpassing the SOTA model by 118% with only 1/8 of traning data.

        [2025.8] A unified model [NaviMaster](https://iron-boyy.github.io/navimaster/) has been released that can operate both the digital GUI interface and real-world navigation simultaneously.

        [2025.8] As the sole corresponding author, he directed the internship student to submit a paper, which was published in EMNLP2025 Oral. The main research focuses on the impact of "Uncertainty" on the reasoning RL training process.

        [2025.7] [As Core Lead, responsible for knowledge enhancement of SafeWork-R1 and "Deliberation Mode" related modules, the relevant results are published at WAIC2025.](https://arxiv.org/pdf/2507.18576)

        [2025.6] As the corresponding author, he guided the internship student to submit a paper, which was included in ICCV 2025. The relevant achievements have refreshed the SOTA of multi-modal retrieval, and it can provide the function of precise memory retrieval for embodied AI with 500,000 frames.[demo](https://bwliu01.github.io/IDMR/)

        [2025.5] [A comprehensive review article on AI tracing was published in Artificial Intelligence Review, spanning 60 pages and comprising 20,000 words.](https://link.springer.com/article/10.1007/s10462-025-11222-w)

        [2024.10] Join Safety and Trustworthy AI Center in the Shanghai AI Laboratory, responsible for knowledge enhancement for LLMs.

        [2023.10] First author paper, [using a dynamic graph network evolution engine for accelerated simulation of complex transportation systems].(https://ieeexplore.ieee.org/abstract/document/10422572/)。

        [2022.10] Join Shanghai AI Laboratory, mainly responsible for  AI security evaluation systems and multi-agent simulation platforms. I earned an 'Excellent' performance rating for two consecutive years.

        [2022.11] [A paper is included in the 1st Learning on Graphs Conference, mainly studying the evolution issue of dynamic graphs.](https://proceedings.mlr.press/v198/wang22c.html)

        [2022.3] [Collaborative paper published in Nature Machine Intelligence.](https://www.nature.com/articles/s42256-022-00459-7)

        [2021.9] [The first author's graph computing paper has been published in SIGMOD 2021 Oral, which is the result of an internship at Ant Group.](https://dl.acm.org/doi/abs/10.1145/3448016.3457564)

        [2020.2] [Life's first paper was published in Knowledge-Based Systems](https://www.sciencedirect.com/science/article/abs/pii/S0950705119305283)
    design:
      columns: '1' 

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
