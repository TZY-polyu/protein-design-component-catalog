# Latent-Y 系统提示与探索策略

[智能体与编排](../../README.md) / 规划与反馈机制

## 用途

允许根据证据修改策略及选择分子形式。论文实验集中于 VHH。

## 输入、输出与 LLM 参与

- **输入**　预设领域指导、用户约束、前批次结果。
- **输出**　下一轮任务、资源分配或停止决定。
- **LLM 参与**　是，LLM 解释提示和结果。

## 结果解读

决策会结合先前批次结果和用户约束。论文描述策略及观察到的行为，未公开完整提示模板的独立软件实现。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为在线决策。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　领域提示与调度策略在 §3.1 报告，未放出独立实现或提示全集。 论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
