# analyze_interface

[工具接口与执行](../../README.md) / BioDesignBench 工具接口

## 用途

用坐标描述复合物链间界面的几何特征。

## 输入、输出与 LLM 参与

- **输入**　给定的复合物结构和需要分析的分子链。
- **输出**　界面埋藏面积、氢键或接触图等可计算的几何统计。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

这些量刻画当前构象的接触方式。坐标来源和链的选择都会影响数值。

## 在六篇研究中的用法

- **BioDesignBench**　表 S1 原子工具，两种模式均可用。

## 原始来源与 GitHub

- **接口定义**　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)。[作者补充材料与工具表 S1](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)
- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp/tree/7a45f13d5c7667513f4b3cfc47e472f3209b1be1>)（含该接口的工具包，固定版本）。
- **计算或资源出处**　没有足够信息认定单一底层方法或它的首发论文。

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/jasonkim8652/protein-design-mcp/archive/7a45f13d5c7667513f4b3cfc47e472f3209b1be1.zip>)　下载同期工具包，含本接口及其他已注册接口。
- [作者补充材料 PDF（工具表 S1）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)
