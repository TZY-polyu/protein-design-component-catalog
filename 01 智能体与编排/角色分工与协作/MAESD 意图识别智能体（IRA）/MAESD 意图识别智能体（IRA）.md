# MAESD 意图识别智能体（IRA）

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

把自然语言需求翻译成可用于生成和检验的条件。

## 输入、输出与 LLM 参与

- **输入**　用户描述的蛋白功能或性质。
- **输出**　GO 术语、候选结构域组合及生物学约束。
- **LLM 参与**　需要通用 LLM 做语义拆分。结合知识库检索。

## 结果解读

输出采用可供后续模块检索和检查的生物学术语。模型返回的语义片段仍需与词表及结构域注释对照。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为系统主模块。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　IRA 是 MAESD 定义的角色。其所用的语言模型及数据库各列原始来源。

## 下载与访问

- [下载 ira.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/ira.py>)　该项目的源码文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[Gene Ontology](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/Gene%20Ontology/Gene%20Ontology.md) · [InterPro](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/InterPro/InterPro.md) · [MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [Pfam](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Pfam/Pfam.md)
