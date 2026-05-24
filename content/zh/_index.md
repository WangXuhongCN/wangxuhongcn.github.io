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
  #     title: '📚 主线故事'
  #     subtitle: ''
  #     text: |-
  #       致力于训练可进化的多模态智能体：
  #       1. 建立集工具调用、GUI点击、具身导航三位一体的逼真仿真环境。
  #       2. 依据环境自动生成
  #   design:
  #     columns: '1'
  - block: markdown
    content:
      title: '📚 Selected News'
      subtitle: ''
      text: |-
        [2026.5] [发布技术报告 Safactory](https://arxiv.org/abs/2605.06230)，提出首个面向可信自主智能训练的可扩展 Agentic Infra，打通并行仿真、可信数据与自主进化三大平台，支持下一代7x24自主智能体大规模闭环训练。

        [2026.4] [NaviMaster](https://arxiv.org/abs/2508.02046) 收录于 **ACL 2026 Main**，统一 GUI 与具身导航任务，在混合轨迹强化学习框架下同时提升跨界面与跨场景泛化能力。

        [2026.4] [发布『墨铠』全栈安全工具箱](https://mp.weixin.qq.com/s/ITZm3asvjCbbD_540ezqqw)，首批整合14类、150余个安全工具，覆盖风险推演、可信数据与进化防御三大中台，支持灵活部署与产业落地。

        [2026.4] [Deliberative Searcher](https://arxiv.org/abs/2507.16727) 收录于 **ACL 2026 Oral**，将置信校准与检索式搜索结合进约束强化学习，显著提升开放域问答中的可靠性与可校准性。

        [2026.4] [From Coarse to Fine](https://arxiv.org/abs/2604.27453) 收录于 **ACL 2026 Findings**，提出面向写作生成任务的细粒度评测管线 WEval 与奖励建模框架 WRL，更准确地刻画并优化模型对复杂写作要求的遵循能力。

        [2026.3] [发布新知识推理解耦方法DRIFT](https://mp.weixin.qq.com/s/19OFUdNd5RS8QcEVkvr74A)，并收录于 **ACL 2026**；相关 [paper](https://arxiv.org/abs/2602.10021) 提出知识读取与推理解耦的双模型框架，用隐式事实 token 替代冗余长文本，在长上下文任务上兼顾效率与性能，并天然增强抗越狱能力。

        [2026.2] [TPRU](https://arxiv.org/abs/2602.18884) 收录于 **ICLR 2026 Oral**，构建面向机器人操作与 GUI 导航的时序与过程理解数据集，并结合强化学习显著提升轻量多模态模型的程序性理解能力。

        [2025.12] 发布[BioBridge](https://arxiv.org/abs/2602.17680) 模型 **BIBM 2025（CCF-B）**，作为知识解耦在蛋白质理解任务中的典型应用，由蛋白语言模型负责“读懂蛋白”，LLM 专注任务推理，在保持接近 SOTA 蛋白模型能力的同时保留通用语言理解能力。

        [2025.11] 作为唯一通讯，在 **EMNLP 2025 Main（Oral）** 发表基于不确定度建模的大模型RL奖励模型（[C2RM](https://aclanthology.org/2025.emnlp-main.1385/)），可以大幅度提高大模型推理训练的内容思考质量。

        [2025.9] [发布首个安全可信具身智能框架与路线图综述](https://mp.weixin.qq.com/s/CgBf-ZvMgfsWOrFlGKPZ8g)，与谭鑫、陆超超、上海AILab主任[周伯文](https://c3i.ee.tsinghua.edu.cn/author/%E5%91%A8%E4%BC%AF%E6%96%87/)等合作，系统定义 Safe and Trustworthy EAI，给出十大核心原则与 L1-L5 成熟度模型。

        [2025.8] 作为唯一通讯，发布了针对MoE模型优化的分布式KV Cache架构（[PiKV: KV Cache Management System for Mixture of Experts](https://arxiv.org/abs/2508.06526)）。

        [2025.8] 作为唯一通讯，发布了SOTA的CoT-PRM模型（[VRPRM](https://arxiv.org/abs/2508.03556)），Best-of-N的Test-time Scaling效果逼近**理论极限值Pass@K**，仅用1/8的数据超越SOTA模型118%。

        [2025.7] [作为Core Lead，负责实验室SafeWork-R1的知识增强和“**慎思模式**”相关模块，相关成果发布于世界人工智能大会2025](https://arxiv.org/pdf/2507.18576)

        [2025.6] 作为通讯作者，指导实习生投稿论文，收录于ICCV2025。相关成果刷新多模态检索SOTA，可为具身AI提供**50万帧的精确记忆检索**功能,[查阅demo请点击](https://bwliu01.github.io/IDMR/)

        [2025.5] [作为第一作者，发表关于AI溯源的综述文章，收录于Artificial Intelligence Review期刊，**60页两万词**](https://link.springer.com/article/10.1007/s10462-025-11222-w)

        [2024.10] 加入上海人工智能实验室，安全可信AI中心，负责大模型可信知识增强相关模块

        [2023.10] 以第一作者发表论文，[使用动态图网络演化引擎作为底层代理，进行复杂交通系统的加速仿真](https://ieeexplore.ieee.org/abstract/document/10422572/)。

        [2022.10] 入职上海人工智能实验室，青年研究员，主要负责AI安全评测系统优化以及多智能体仿真平台, **连续两年绩效评估为优秀**。

        [2022.11] [一作论文收录于第一届Learning on Graphs Conference，主要研究动态图的演化问题](https://proceedings.mlr.press/v198/wang22c.html)

        [2022.3] [合作论文收录于Nature Machine Intelligence](https://www.nature.com/articles/s42256-022-00459-7)

        [2021.9] [一作图计算论文收录于**数据顶会SIGMOD 2021 Oral**，是在蚂蚁集团的实习成果](https://dl.acm.org/doi/abs/10.1145/3448016.3457564)

        [2020.2] [人生第一篇论文发表于Knowledge-Based Systems期刊](https://www.sciencedirect.com/science/article/abs/pii/S0950705119305283)
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
#   - block: cta-card
#     demo: true # Only display this section in the Hugo Blox Builder demo site
#     content:
#       title: 👉 Build your own academic website like this
#       text: |-
#         This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

#         <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

#         Easily build anything with blocks - no-code required!
        
#         From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#       button:
#         text: Get Started
#         url: https://hugoblox.com/templates/
#     design:
#       card:
#         # Card background color (CSS class)
#         css_class: "bg-primary-700"
#         css_style: ""
---
