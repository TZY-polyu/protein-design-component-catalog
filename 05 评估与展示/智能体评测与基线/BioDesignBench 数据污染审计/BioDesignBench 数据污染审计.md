# BioDesignBench 数据污染审计

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

补充A.6/E详列元数据剥离、限制访问与事后痕迹比对。正文另提改写、虚构目标与n-gram。不同章节的五层定义有差异。

## 输入、输出与 LLM 参与

- **输入**　原始任务及其元数据、评分真值、工具运行轨迹和参考文献。
- **输出**　去线索任务、独立存放的真值、逐题污染审计标记。
- **LLM 参与**　否（规则审计。受测 LLM 接受相应提示）

## 结果解读

在任务发布与执行后分别检查可能暴露答案的线索。逐题标记是对任务或轨迹的审计结果，各章节对具体分层的表述有差异。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为任务构建／数据审计。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　本文把任务筛选、诱饵和重叠审计组合用于本基准。n-gram 重叠是通用指标。

## 下载与访问

- [下载 contamination.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/contamination.py>)　公开的数据污染审计实现。 此次连接超时，文件下载状态未确认。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md)
