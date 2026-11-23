# BioDesignBench 专家参照上界

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

正文描述为执行专家所选顺序，补充A.7描述为复算发表参考序列并对部分分项直接赋值。图2d与A.7对各分项的呈现也不同。

## 输入、输出与 LLM 参与

- **输入**　正文描述的专家工具顺序。补充A.7所述来自发表文献的参考序列。
- **输出**　基准上界参照分及参考序列的独立质量指标。
- **LLM 参与**　否（专家预设）

## 结果解读

正文概括为执行专家工具顺序，补充材料描述为复算已发表参照序列并对部分分项直接计分。解读上界时需注明两处口径。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为评测基线。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　作者材料的 oracle 定义和分项值并不一致，不将其解释为可直接复现的统一规则。

## 下载与访问

- [下载 oracle.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/tier2/oracle.py>)　公开的上界方法代码。完整参照输出由作者控制访问。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md)
