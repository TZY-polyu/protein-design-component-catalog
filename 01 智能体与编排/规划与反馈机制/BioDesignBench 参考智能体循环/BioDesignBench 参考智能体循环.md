# BioDesignBench 参考智能体循环

[智能体与编排](../../README.md) / 规划与反馈机制

## 用途

规划、调用、观察和调整由同一智能体完成。

## 输入、输出与 LLM 参与

- **输入**　自然语言任务、可用工具说明、之前的返回值。
- **输出**　工具调用、继续或停止的决定、最终候选与证据包。
- **LLM 参与**　是（通用 LLM）

## 结果解读

工具反馈会影响下一步选择，停止决定也计入行为轨迹。ReAct 是所参考的范式，具体运行程序由基准提供。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为运行时编排。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **ReAct 的原始出处**　[Yao et al. (ICLR 2023), ReAct: Synergizing Reasoning and Acting in Language Models](<https://arxiv.org/abs/2210.03629>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　Kim 与 Romero 将 ReAct 的推理与行动思想改为本文可记录的循环。图1a和文献26区分参考智能体与原始方法。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [protein-design-mcp](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/protein-design-mcp/protein-design-mcp.md) · [ReAct](../../%E6%8E%A8%E7%90%86%E4%B8%8E%E6%A3%80%E7%B4%A2%E7%BC%96%E6%8E%92/ReAct/ReAct.md)
