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
        [2026.6] Appointed as **Adjunct PhD Co-Supervisor** at **Shanghai Jiao Tong University**, focusing on AI safety and trustworthy AI systems, advancing joint talent development and frontier research between the PuJiang National Lab and academia.

        [2026.6] Appointed as **Lead Principal Investigator** (课题负责人) of the **"Science Intelligence (AI4S) Secure Service Middleware" sub-project** under China's **"New Generation AI" National Major Project**, with total funding of **¥10 million**, building security infrastructure for scientific computing, drug discovery, and industry simulation.

        [2026.5] [Released the Safactory technical report](https://arxiv.org/abs/2605.06230), presenting a scalable agentic infrastructure for training trustworthy autonomous intelligence through a closed-loop pipeline spanning parallel simulation, trustworthy data, and autonomous evolution.

        [2026.5] [NaviMaster](https://arxiv.org/abs/2508.02046) was accepted to **ACL 2026 Main**, unifying GUI and embodied navigation with a mixed-trajectory reinforcement learning framework for stronger cross-domain generalization.

        [2026.4] [Released Mokai](https://mp.weixin.qq.com/s/ITZm3asvjCbbD_540ezqqw), a full-stack agent security toolbox with 150+ tools spanning risk simulation, trusted data, and evolutionary defense for practical deployment.

        [2026.4] [Deliberative Searcher](https://arxiv.org/abs/2507.16727) was accepted to **ACL 2026 Oral**, integrating certainty calibration and retrieval-based search into constrained reinforcement learning to improve reliability and calibration in open-domain QA.

        [2026.4] [From Coarse to Fine](https://arxiv.org/abs/2604.27453) was accepted to **ACL 2026 Findings**, introducing the fine-grained WEval benchmark and WRL reward modeling framework for writing-centric generation with more precise requirement adherence.

        [2026.3] [Released DRIFT](https://mp.weixin.qq.com/s/19OFUdNd5RS8QcEVkvr74A), later accepted to **ACL 2026**; the related [paper](https://arxiv.org/abs/2602.10021) proposes a dual-model framework that decouples knowledge extraction from reasoning through implicit fact tokens for efficient long-context inference, stronger robustness, and resistance to jailbreak prompts.

        [2026.2] [Released the AOT perceptual robustness project](https://yicbao.github.io/To-Deceive-is-to-Teach-Forging-Perceptual-Robustness-via-Adversarial-Reinforcement-Learning/); the related [paper](https://arxiv.org/abs/2602.22227) introduces the AOT-SFT adversarial dataset and an attacker-defender self-play framework that continually improves multimodal perceptual robustness in visually complex scenes while reducing hallucinations.

        [2026.2] [TPRU](https://arxiv.org/abs/2602.18884) was accepted to **ICLR 2026 Oral**, introducing a temporal and procedural understanding dataset plus an RL training pipeline that substantially improves lightweight multimodal models across robotics and GUI scenarios.

        [2026.2] [Released SafeVerse: a safe and trustworthy digital twin arena for embodied AI](/en/post/safeverse/), turning ordinary videos into interactive, physics-aware 3D twin scenes within minutes, then extending them with attack-oriented editing and online agent evolution.

        [2025.12] [Released BioBridge: letting LLMs truly understand proteins without sacrificing general ability](/en/post/biobridge/); the related [paper](https://arxiv.org/abs/2602.17680) was presented at **BIBM 2025 (CCF-B)**, combining specialist protein reading with LLM reasoning to reach near-specialist performance on real biological tasks.

        [2025.11] As the sole corresponding author, a LLM reward model based on uncertainty modeling was presented at **EMNLP 2025 Main (Oral)**, which can significantly improve the content thinking quality of large model inference training. 

        [2025.9] [Released a roadmap for Safe and Trustworthy Embodied AI](https://mp.weixin.qq.com/s/CgBf-ZvMgfsWOrFlGKPZ8g) with Xin Tan, Chaochao Lu, and [Bowen Zhou](https://c3i.ee.tsinghua.edu.cn/author/%E5%91%A8%E4%BC%AF%E6%96%87/), defining the field with ten core principles and an L1-L5 maturity model.
        
        [2025.8] As the sole corresponding author, a distributed KV Cache architecture optimized for MoE models was released ([PiKV: KV Cache Management System for Mixture of Experts](https://arxiv.org/abs/2508.06526)).

        [2025.8] Released the SOTA CoT-PRM model ([VRPRM](https://arxiv.org/abs/2508.03556)), achieving Test-time Scaling effect of Best-of-N approaching the theoretical limit value Pass@K, surpassing the SOTA model by 118% with only 1/8 of traning data.

        [2025.7] [As Core Lead, I led the knowledge enhancement and "Deliberation Search Mode" related modules of SafeWork-R1, with the results released at WAIC 2025.](/en/post/safework-r1/); the related [paper](https://arxiv.org/abs/2507.18576) presents the SafeLadder framework for jointly improving multimodal reasoning safety and general capability.

        [2025.6] As the corresponding author, he guided the internship student to submit a paper, which was included in ICCV 2025. The relevant achievements have refreshed the SOTA of multi-modal retrieval, and it can provide the function of precise memory retrieval for embodied AI with 500,000 frames. [demo](https://bwliu01.github.io/IDMR/)

        [2025.5] [A comprehensive review article on AI tracing was published in Artificial Intelligence Review, spanning 60 pages and comprising 20,000 words.](https://link.springer.com/article/10.1007/s10462-025-11222-w)

        [2024.10] Join Safety and Trustworthy AI Center in the Shanghai AI Laboratory, responsible for knowledge enhancement for LLMs.

        [2023.10] First author paper, [using a dynamic graph network evolution engine for accelerated simulation of complex transportation systems](https://ieeexplore.ieee.org/abstract/document/10422572/).

        [2022.10] Join Shanghai AI Laboratory, mainly responsible for  AI security evaluation systems and multi-agent simulation platforms. I earned an 'Excellent' performance rating for two consecutive years.

        [2022.11] [A paper is included in the 1st Learning on Graphs Conference, mainly studying the evolution issue of dynamic graphs.](https://proceedings.mlr.press/v198/wang22c.html)

        [2022.3] [Collaborative paper published in Nature Machine Intelligence.](https://www.nature.com/articles/s42256-022-00459-7)

        [2021.9] [The first author's graph computing paper has been published in SIGMOD 2021 Oral, which is the result of an internship at Ant Group.](https://dl.acm.org/doi/abs/10.1145/3448016.3457564)

        [2020.2] [Life's first paper was published in Knowledge-Based Systems](https://www.sciencedirect.com/science/article/abs/pii/S0950705119305283)
    design:
      columns: '1' 

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # - block: collection
  #   id: talks
  #   content:
  #     title: '🎤 Talks'
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 2
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
