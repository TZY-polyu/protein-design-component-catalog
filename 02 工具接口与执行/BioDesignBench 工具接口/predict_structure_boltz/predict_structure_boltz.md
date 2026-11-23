# predict_structure_boltz

[工具接口与执行](../../README.md) / BioDesignBench 工具接口

## 用途

通过 Boltz-2 后端计算结构预测，以独立接口返回结果。

## 输入、输出与 LLM 参与

- **输入**　待建模的分子序列及组成信息。
- **输出**　Boltz-2 预测坐标及相应的置信度信息。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

这是结构预测接口。基准另设亲和力接口，两种返回值对应不同的科学问题。

## 在六篇研究中的用法

- **BioDesignBench**　表 S1 原子工具，两种模式均可用。

## 原始来源与 GitHub

- **接口定义**　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)。[作者补充材料与工具表 S1](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)
- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp/tree/7a45f13d5c7667513f4b3cfc47e472f3209b1be1>)（含该接口的工具包，固定版本）。
- **Boltz-2 的原始出处**　[Passaro et al. (2025), Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction](<https://doi.org/10.1101/2025.06.14.659707>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/jasonkim8652/protein-design-mcp/archive/7a45f13d5c7667513f4b3cfc47e472f3209b1be1.zip>)　下载同期工具包，含本接口及其他已注册接口。
- [作者补充材料 PDF（工具表 S1）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Boltz-2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/Boltz-2/Boltz-2.md)
