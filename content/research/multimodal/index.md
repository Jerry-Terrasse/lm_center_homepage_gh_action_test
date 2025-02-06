---
title: 多模态大模型研究小组
date: 1020-01-01 # to control the display order
# author: test
type: landing

design:
  # Section spacing
  spacing: '1rem'

sections:
  - block: markdown
    content:
      title: 
      text: |
        # 多模态大模型研究小组
  - block: collection
    id: members
    content:
      title: 团队成员
      filters:
        folders:
          - authors
        tag: mm_prof
      count: 0
    design:
      view: people-grid
      columns: 4
  - block: markdown
    content:
      title: 研究内容简介
      text: |
        ### 代表性成果1：书生多模态大模型系列-InternVL

        ### 代表性成果2：视频基础表征模型-VideoMAE系列
        ![VideoMAE](./videomae.png)
        本成果提出了视频掩码自编码器VideoMAE v1&v2，成功训练出了首个十亿参数量的视频Transformer模型，突破了视频自监督表征学习的性能瓶颈。VideoMAE系列工作引用超过1500次，已经成为视频自监督学习领域的基准方法，被牛津大学、微软、谷歌、Meta进行跟踪拓展研究，成为被开源社区Hugging Face收录的首个视频Transformer模型，全球调用下载超过320万次，位列Hugging Face视频识别模型榜下载量榜首。

        ### 代表性成果3：视频多模态大模型-VideoChat系列

        ![VideoChat](./videochat.png)

        本成果提出了全球首个以视频为中心的多模态对话大模型VideoChat，形成了对话交互驱动的通用视频理解能力，在多个多模态视频理解数据集上面取得了领先性能。Video相关技术被使用到快手可灵大模型的研发工作，GitHub星标超过3000，取得了较大的学术影响力。最近，相继提出了VideoChat-Online和VideoChat-Flash本版，从交互形式和高效长时建模方面，进一步提升了VideoChat综合性能。

        ### 代表性成果4：书生视频大模型-InternVideo系列

        ![InternVideo](./internvideo.png)

        本成果提出了全球首个通用视频理解大模型InternVideo，在2022年发布视频基础表征模型版本InternVideo 1.0，在视频基础感知、视频时空解析、视频开发识别等重点任务取得了世界领先水平；在2024年发布了视频多模态理解模型版本InternVideo 2.0，在超过60种视频理解任务上面取得领先性能，包括识别检索、开放问答、高阶推理等等；在2025年发布了深层次时空理解版本InternVideo 2.5，在视频理解的跨度和粒度上实现了显著提升，其“记忆力”更是较前代提升了6倍。
---

多模态大模型研究小组致力于推动多模态大模型的研究与应用，探索多模态信息融合、交互与推理等关键技术，推动多模态大模型在视觉、语音、文本等多模态数据上的应用，为多模态智能技术的发展提供技术支撑。