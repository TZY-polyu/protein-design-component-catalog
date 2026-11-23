# BioDesignBench 失败与终止行为分类

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

补充G定义深层成功、浅层成功、工具缺口、科学推理缺口、偶然成功五类。深浅再按执行深度区分。

## 输入、输出与 LLM 参与

- **输入**　执行轨迹、失败记录、任务类别与设计目的。
- **输出**　按模型和任务分组的失败分布、执行深度及终止行为。
- **LLM 参与**　未说明（分类标注方式）

## 结果解读

研究依据工具覆盖、科学推理与执行深度将运行分组，检查智能体在不同任务上的终止与失败模式。分类结果可回查相应轨迹。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为运行后／行为诊断。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　失败归类及任务分层分析由本文用于诊断智能体行为。

## 下载与访问

- [下载 failure_analysis.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/failure_analysis.py>)　该项目的源码文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md)
