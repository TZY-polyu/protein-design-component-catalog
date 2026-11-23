# Latent-Y 文献任务完成度评测

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

分别评价机制理解和候选交付。原文报告 21/21、17/21、16/21。

## 输入、输出与 LLM 参与

- **输入**　21 项任务、论文所述功能表位、过滤前后候选数。
- **输出**　表位一致率、质检前后数量达标率。
- **LLM 参与**　计数无需。表位一致性的评判主体未说明。

## 结果解读

表位是否与所给文献一致、质控前后交付数量是否达标，是三项独立判断。报告的分母均为 21 项文献任务。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为独立计算评测。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　本研究定义的三项提示满足度评价，见附录 B。 论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
