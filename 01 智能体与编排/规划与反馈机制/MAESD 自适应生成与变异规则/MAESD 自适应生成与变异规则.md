# MAESD 自适应生成与变异规则

[智能体与编排](../../README.md) / 规划与反馈机制

## 用途

用本轮反馈调整下一轮生成条件，支持手动补充调节。

## 输入、输出与 LLM 参与

- **输入**　筛选反馈、同源序列统计、当前序列多样性和结构置信度。
- **输出**　给生成模型的采样多样性、位点固定和残基偏好设置。
- **LLM 参与**　混合。残基偏好推理使用大模型先验，另有统计更新与预设规则。

## 结果解读

该模块产出供下一轮调用采用的设置。候选序列由各生成模型输出。用户也可以补充调整。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时反馈。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　指本文按迭代反馈调整生成参数的实现。变异是通用概念。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。
- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。

## 关联组件

[MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
