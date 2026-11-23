# BioDesignBench Leaderboard

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

发布 BioDesignBench 的汇总比较结果，提供浏览和提交排行榜结果的入口。

## 输入、输出与 LLM 参与

- **输入**　评测产生的系统名称、设置、分数和要求的提交材料。
- **输出**　网页中的比较表、排名和结果说明。
- **LLM 参与**　排行榜展示与数据发布无需再次调用 LLM。分数来源可以包含模型评审。

## 结果解读

该前端用于展示已有结果，与底层任务的生成、执行和计分框架分开维护。

## 在六篇研究中的用法

- **BioDesignBench**（发布／比较）　接受外部提交并展示结果。原始任务、逐题输出与真值未公开。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench/tree/main/biodesignbench-leaderboard>)
- **归属说明**　作者仓库中排行榜子目录。线上提交入口在 Hugging Face Spaces。

## 下载与访问

- [官方在线排行榜](<https://huggingface.co/spaces/RomeroLab-Duke/BioDesignBench-Leaderboard>)　作者维护的 Hugging Face Space。前端代码位于基准仓库子目录。
- [仓库源码 ZIP · RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench/archive/718e452e3f73f8be423e954b6c05f3aa3f42859c.zip>)　该仓库的固定快照。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md) · [Hugging Face Spaces](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E6%89%98%E7%AE%A1%E4%B8%8E%E5%9C%A8%E7%BA%BF%E6%9C%8D%E5%8A%A1/Hugging%20Face%20Spaces/Hugging%20Face%20Spaces.md)
