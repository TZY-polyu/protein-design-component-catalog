# BioDesignBench 设计功能映射

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

以10种抽象功能计分，让不同工具完成同类工作时得到相应认可。

## 输入、输出与 LLM 参与

- **输入**　MCP 接口调用记录及任务所需的设计功能。
- **输出**　已执行的功能及其与期望功能的覆盖程度。
- **LLM 参与**　否（确定性映射）

## 结果解读

程序把不同工具名归到十类抽象设计功能，再计算任务所需功能的覆盖情况，可在工具实现不同的运行间进行比较。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为提交后／策略评价。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　由本基准定义的功能分类与映射。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md) · [protein-design-mcp](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/protein-design-mcp/protein-design-mcp.md)
