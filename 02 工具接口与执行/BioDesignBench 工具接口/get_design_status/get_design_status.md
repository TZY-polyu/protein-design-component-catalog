# get_design_status

[工具接口与执行](../../README.md) / BioDesignBench 工具接口

## 用途

查询先前提交的异步作业是否仍在运行，以及结果是否可获取。

## 输入、输出与 LLM 参与

- **输入**　已经提交的工作对应的任务标识。
- **输出**　作业状态，以及已完成时可用的结果位置或状态信息。
- **LLM 参与**　查询作业状态无需通用 LLM。智能体和普通程序均可读取返回状态。

## 结果解读

“完成”描述任务生命周期。它本身没有评价候选的结构、性质或实验质量。

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
