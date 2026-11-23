# BioDesignBench 工具使用行为指标

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

算法直接从日志计算覆盖、评估/生成调用比、每个候选的指标种类、相对专家的分阶段调用率和候选筛除情况。

## 输入、输出与 LLM 参与

- **输入**　分阶段的工具调用、每个候选的评价和提交记录。
- **输出**　阶段覆盖、各阶段调用数、每个候选的评估调用数和指标类别数、筛除行为。
- **LLM 参与**　否（统计分析）

## 结果解读

阶段覆盖描述任务环节是否出现。评估量和评估种类分别描述尝试次数及每个候选接受了多少类检查。指标均从运行记录汇总。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为运行后／行为分析。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　阶段覆盖、每候选评估量、类别多样性与筛除被本文组织为行为指标。

## 下载与访问

- [下载 tool_audit.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/tool_audit.py>)　公开的工具使用审计代码。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md)
