# Latent-Y

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

在平台内把研究目标组织成文献调查、数据分析、模型调用和质控等工作，并保存平台作业和评审记录。

## 输入、输出与 LLM 参与

- **输入**　研究目标、论文或背景说明、平台可用的科学资源，以及可选的专家反馈。
- **输出**　任务计划、工具运行记录、候选清单和质量分析结果，实验送测属于独立阶段。
- **LLM 参与**　依赖通用 LLM 驱动的主智能体和子智能体，分子生成由专用 Latent-X2 完成。

## 结果解读

Latent-Y 同时报告计算和实验结果。比较不同任务的成功率时，应区分任务是否进入实验验证阶段。

## 在六篇研究中的用法

使用此来源的研究组件包括 [Latent-Y 主智能体](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/Latent-Y%20%E4%B8%BB%E6%99%BA%E8%83%BD%E4%BD%93/Latent-Y%20%E4%B8%BB%E6%99%BA%E8%83%BD%E4%BD%93.md)、[Latent-Y 系统提示与探索策略](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/Latent-Y%20%E7%B3%BB%E7%BB%9F%E6%8F%90%E7%A4%BA%E4%B8%8E%E6%8E%A2%E7%B4%A2%E7%AD%96%E7%95%A5/Latent-Y%20%E7%B3%BB%E7%BB%9F%E6%8F%90%E7%A4%BA%E4%B8%8E%E6%8E%A2%E7%B4%A2%E7%AD%96%E7%95%A5.md)、[Latent-Y 热点研究子智能体](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/Latent-Y%20%E7%83%AD%E7%82%B9%E7%A0%94%E7%A9%B6%E5%AD%90%E6%99%BA%E8%83%BD%E4%BD%93/Latent-Y%20%E7%83%AD%E7%82%B9%E7%A0%94%E7%A9%B6%E5%AD%90%E6%99%BA%E8%83%BD%E4%BD%93.md)、[Latent-Y 质量保证子智能体](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/Latent-Y%20%E8%B4%A8%E9%87%8F%E4%BF%9D%E8%AF%81%E5%AD%90%E6%99%BA%E8%83%BD%E4%BD%93/Latent-Y%20%E8%B4%A8%E9%87%8F%E4%BF%9D%E8%AF%81%E5%AD%90%E6%99%BA%E8%83%BD%E4%BD%93.md)、[Latent-Y 专家与智能体耗时比较](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/Latent-Y%20%E4%B8%93%E5%AE%B6%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E8%80%97%E6%97%B6%E6%AF%94%E8%BE%83/Latent-Y%20%E4%B8%93%E5%AE%B6%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E8%80%97%E6%97%B6%E6%AF%94%E8%BE%83.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

未核实主智能体或整套平台的公开源码与离线下载。

- [Latent-Y 官方平台入口](<https://www.latentlabs.com/latent-y/>)　页面提供产品与可用访问方式。
- [下载作者论文及附录（PDF）](<https://arxiv.org/pdf/2603.29727v2>)　包含本研究报告和附表。
