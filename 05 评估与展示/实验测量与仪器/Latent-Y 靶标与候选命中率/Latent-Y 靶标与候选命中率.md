# Latent-Y 靶标与候选命中率

[评估与展示](../../README.md) / 实验测量与仪器

## 用途

全部实验设置合计 6/9 个目标命中。21 项文献任务中仅 1 项送实验。

## 输入、输出与 LLM 参与

- **输入**　按目标归类的实验命中、实际送检候选数。
- **输出**　有命中的目标比例、每一目标的命中候选比例。
- **LLM 参与**　否，基于实验分组计数。

## 结果解读

靶标级以被测试的目标总数为分母，候选级以各目标实际送检的分子数为分母，两个比例应分别报告。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为结果统计。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　成功率分母及本研究的结果定义见图 1、6。比例计数是通用统计方法。 论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
