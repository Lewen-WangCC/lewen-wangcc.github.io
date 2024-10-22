---
title: "用机器学习力场建模自旋交叉晶格"
summary: 由Prof. Ben Powell和Dr Carla Verdi指导
authors:
- admin
date: 2024-01-29
doi: ""

abstract: 机器学习力场（MLFF）因其能够以量子级精度描述原子间势并扩展到经典系统，近年来受到了越来越多的关注。机器学习势的精度高度依赖于所选的从头算参考方法。然而，使用密度泛函理论（DFT）对自旋交叉（SCO）晶格进行建模仍存在挑战，尤其是在预测高低自旋状态能量差（在0 K时称为焓差）时难以平衡精度与效率。本文中，采用了一种半经验DFT方法，在分子动力学（MD）模拟过程中即时训练[Fe(ptz)~6~]\(BF~4~)~2~（ptz = 1-丙基四唑）的机器学习力场。所开发的MLFF在在一系列基准测试中表现出与DFT相当的精度，同时具有更高的计算效率，并成功通过拟谐波近似预测了SCO系统的热膨胀效应。本研究为使用DFT建模SCO系统提供了关键见解，强调了在焓差计算中零点效应的重要性。将可靠的DFT参考与MLFF结合，为精确且高效模拟SCO系统晶格动力学提供了一种有前景的策略。此外，本文还提出了一种基于MLFF驱动MD模拟的潜在方案。

tags:
  - ML
  - AIMD
  - VASP
featured: false

url_pdf: HonoursThesis.pdf

image:
  caption: 'Image credit: Huiwen Tan'
  focal_point: ""
  preview_only: ture

projects: []

slides: ""
---