# Latent-Y 序列质控

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

为最终候选选择提供自动分析。聚类算法与所有阈值未统一列出。

## 输入、输出与 LLM 参与

- **输入**　候选序列与已知参考序列。
- **输出**　去重清单、多样性分组、相似性及序列风险标记。
- **LLM 参与**　否，自动检测。质检代理负责综合。

## 结果解读

该环节给每组候选附加重复性、多样性和质量标记，以便后续选择。质控通过表示满足研究的计算检查条件。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为在线序列质检。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **SAbDab 的原始出处**　[Dunbar et al. (2014), SAbDab: the structural antibody database](<https://doi.org/10.1093/nar/gkt1043>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　质控组合由作者定义。SAbDab 用于新颖性比较，聚类和搜索的具体后端未逐项对应。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [SAbDab](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/SAbDab/SAbDab.md)
