# Latent-Y 质量保证子智能体

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

整合去重、相似性与序列风险检查结果。

## 输入、输出与 LLM 参与

- **输入**　计算筛选后的候选、用户的数量与多样性要求。
- **输出**　质检结论、候选清单及选择理由。
- **LLM 参与**　是，子智能体整合。基础检查独立运行。

## 结果解读

该角色整合多项检查后解释筛选理由。计算质控与随后进行的实验验证在论文中分别报告。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为在线推理／质控。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　作者命名的质控子代理，未发现单独发布的代码或方法论文。 论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
