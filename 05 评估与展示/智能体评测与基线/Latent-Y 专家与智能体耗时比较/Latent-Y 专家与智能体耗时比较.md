# Latent-Y 专家与智能体耗时比较

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

比较专家独立完成的估计时间与代理辅助条件的实测时间。未进行同一任务的人类对照计时。

## 输入、输出与 LLM 参与

- **输入**　10 名专家对各阶段的估时、5 次代理运行计时。
- **输出**　分阶段和总耗时、约 56 倍估算比值。
- **LLM 参与**　统计无需。代理侧运行使用通用 LLM。

## 结果解读

人类一侧是专家估时，智能体一侧有运行计时。约 56 倍是这两种口径之比，需保留数据收集差异。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为效率评测／对照。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　专家访谈和计时的设计、实施与结果均来自本文附录 D。 论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
