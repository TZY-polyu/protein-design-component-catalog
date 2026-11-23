# BioDesignBench 六维评分表

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

六维的算法分/评委分依次为10/10、7/8、35/0、10/5、3/2、7/3，合计72/28。多样性算法部分用两两序列差异和 Shannon 熵。

## 输入、输出与 LLM 参与

- **输入**　最终候选、结构证据和执行过程。
- **输出**　策略20、编排15、质量35、可行性15、新颖性5、多样性10，以及总分。
- **LLM 参与**　混合（算法72分，LLM评委28分）

## 结果解读

总分由 72 分算法评分和 28 分跨模型评审组成。六个维度各有独立上限，可据此区分过程表现与候选质量。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为提交后评分。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **Shannon entropy 的原始出处**　[Shannon (1948), A Mathematical Theory of Communication](<https://doi.org/10.1002/j.1538-7305.1948.tb01338.x>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　六维权重与72/28分评测安排由本文定义。

## 下载与访问

- [下载 pipeline.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/pipeline.py>)　该项目的源码文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md) · [Shannon entropy](../../%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/Shannon%20entropy/Shannon%20entropy.md)
