# BioDesignBench 工具轨迹与证据包

[数据与知识](../../README.md) / 检索接口与数据处理

## 用途

把最终提交与过程行为关联，为逐题评分和行为分析提供输入。

## 输入、输出与 LLM 参与

- **输入**　任务、候选、逐次工具调用与返回值。
- **输出**　候选序列、预测结构、佐证资料及调用记录。
- **LLM 参与**　否（记录与封装本身）

## 结果解读

把最终提交和逐次调用的工具、返回值对应起来，评分时既可检查蛋白候选，也可检查决策依据。作者未公开逐题运行输出。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为运行记录／评测输入。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　执行证据包与调用轨迹是本文基准使用的记录对象。

## 下载与访问

- [下载 tool_audit.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/tool_audit.py>)　公开的工具使用审计代码。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)
