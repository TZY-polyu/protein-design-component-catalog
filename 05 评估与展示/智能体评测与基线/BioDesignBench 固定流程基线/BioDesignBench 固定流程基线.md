# BioDesignBench 固定流程基线

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

论文正文概括为固定工具流程。补充A.7说明按任务类别确定性选择五个预定义变体。

## 输入、输出与 LLM 参与

- **输入**　同一批任务及预设工具流程。
- **输出**　固定决策产生的候选与基准分数。
- **LLM 参与**　否（固定规则）

## 结果解读

预定义流程按任务类别执行，决策不依赖对话模型。与 LLM 智能体比较时保留了科学工具自身的计算和采样。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为评测基线／干预对照。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　为本文评测设定的非 LLM 参考流程。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md)
