# BioDesignBench 任务集与任务分类

[数据与知识](../../README.md) / 文献与研究数据

## 用途

抗体9、酶12、小型结合蛋白19、支架25、荧光蛋白11。从头设计47、重新设计29。原题与逐题真值未公开。

## 输入、输出与 LLM 参与

- **输入**　专家根据2024–2026年文献整理的设计任务。
- **输出**　76条自然语言任务，按5类分子与2类设计目的分类。
- **LLM 参与**　否（专家整理）

## 结果解读

76 项任务由设计目的和分子类型交叉分类，实际有任务的组合为 9 类。作者开放评测框架与汇总结果，逐题规格和真值保留访问限制。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为评测输入。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　文献来源期在正文列为2024–2026，补充 A.6 列为2024–2025。原始任务和逐题真值未公开。

## 下载与访问

76 道题的逐题规范、完整输入、参考答案和逐题输出未公开。作者发布汇总结果及演示任务，复现实验的数据访问需向作者申请数据使用协议。

- [下载 taxonomy.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/taxonomy.py>)　公开任务分类定义。完整基准输入需要向作者申请。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)
