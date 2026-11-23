# BioDesignBench 评估深度干预

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

比较默认、限制指标种类和要求多指标评估三种条件。固定规则流水线另作对照。

## 输入、输出与 LLM 参与

- **输入**　18项分层抽样任务、DeepSeek V3、GPT-5 与干预条件。
- **输出**　各条件的任务分数、工具调用资源和行为差异。
- **LLM 参与**　混合（受测智能体用 LLM，统计对照无需）

## 结果解读

研究在同一组抽样任务上改变评估要求，并将任务得分与调用资源一起比较，以解释多指标评估的作用。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为行为干预／对照。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　在18道题设置的三条件受控干预由本文设计。

## 下载与访问

- [下载 interventions.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/interventions.py>)　该项目的源码文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md) · [DeepSeek-V3](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/DeepSeek-V3/DeepSeek-V3.md) · [GPT-5](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/GPT-5/GPT-5.md)
