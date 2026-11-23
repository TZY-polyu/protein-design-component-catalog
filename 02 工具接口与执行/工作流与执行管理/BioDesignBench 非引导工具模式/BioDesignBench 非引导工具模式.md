# BioDesignBench 非引导工具模式

[工具接口与执行](../../README.md) / 工作流与执行管理

## 用途

测量智能体自行选择和衔接工具的能力。

## 输入、输出与 LLM 参与

- **输入**　原子工具与各自的描述。
- **输出**　16个原子接口（表S1），各有独立说明。
- **LLM 参与**　否（接口本身）

## 结果解读

智能体看到原子接口及独立说明。这一条件用于观察它自行组织工具调用的能力。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为工具呈现／对照。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　本文设计的 MCP 非引导对照条件。

## 下载与访问

- [下载 protein_design_provider.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/tools/protein_design_provider.py>)　对应预印本时期的注册与呈现代码。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [protein-design-mcp](../../%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/protein-design-mcp/protein-design-mcp.md)
