# design_binder

[工具接口与执行](../../README.md) / BioDesignBench 工具接口

## 用途

在一次接口调用中返回面向给定参考对象的蛋白候选及其计算评价。

## 输入、输出与 LLM 参与

- **输入**　参考分子结构和描述候选应满足条件的任务信息。
- **输出**　候选序列、结构模型及计算置信度。
- **LLM 参与**　底层计算包含专用蛋白语言模型。接口可接受智能体调用，也可由普通程序调用，均无需通用对话 LLM。

## 结果解读

补充表 S1 将它列为仅引导模式可用的复合接口。一次记录的外部调用可以包含多项内部计算。

## 在六篇研究中的用法

- **BioDesignBench**　表 S1 复合工具，仅引导模式。

## 原始来源与 GitHub

- **接口定义**　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)。[作者补充材料与工具表 S1](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)
- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp/tree/7a45f13d5c7667513f4b3cfc47e472f3209b1be1>)（含该接口的工具包，固定版本）。
- **RFdiffusion 的原始出处**　[Watson et al. (2023), De novo design of protein structure and function with RFdiffusion](<https://doi.org/10.1038/s41586-023-06415-8>)
- **ProteinMPNN 的原始出处**　[Dauparas et al. (2022), Robust deep learning–based protein sequence design using ProteinMPNN](<https://doi.org/10.1126/science.add2187>)
- **ESMFold 的原始出处**　[Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model](<https://doi.org/10.1126/science.ade2574>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/jasonkim8652/protein-design-mcp/archive/7a45f13d5c7667513f4b3cfc47e472f3209b1be1.zip>)　下载同期工具包，含本接口及其他已注册接口。
- [作者补充材料 PDF（工具表 S1）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [ESMFold](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/ESMFold/ESMFold.md) · [ProteinMPNN](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/ProteinMPNN/ProteinMPNN.md) · [RFdiffusion](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/RFdiffusion/RFdiffusion.md)
