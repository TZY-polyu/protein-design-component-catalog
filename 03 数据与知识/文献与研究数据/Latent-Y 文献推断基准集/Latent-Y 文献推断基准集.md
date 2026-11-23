# Latent-Y 文献推断基准集

[数据与知识](../../README.md) / 文献与研究数据

## 用途

测试从论文理解科学意图的能力。选题时排除已有指定表位抗体复合物结构的情况。

## 输入、输出与 LLM 参与

- **输入**　论文 PDF、用于消歧的目标名称。
- **输出**　21 项任务及其参照机制、结构和表位。
- **LLM 参与**　否，资料集。执行任务的代理使用 LLM。

## 结果解读

每个任务关联一篇输入论文及参考结构，用来判断系统能否从文献中识别研究意图。21 项任务中有 1 项进入后续实验验证。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为评测数据。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **Protein Data Bank 的原始出处**　[Crystallography: Protein Data Bank (1971). Nature New Biology 233, 223.](<https://doi.org/10.1038/newbio233223b0>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　21 篇论文组成的基准首次见本文表 S2。PDB 提供结构记录，21 篇研究是各任务材料。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

研究结果和附表随 arXiv v2 论文发表。平台私有实现、运行记录和底层模型权重的公开下载未获核实。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [Protein Data Bank](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Protein%20Data%20Bank/Protein%20Data%20Bank.md)
