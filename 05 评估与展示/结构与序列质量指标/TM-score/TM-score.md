# TM-score

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

以长度归一化的距离评分汇总两个结构在空间叠合后的匹配程度，常用于结构相似性和折叠质量评估。

## 输入、输出与 LLM 参与

- **输入**　两组三维坐标、相应残基的对应关系及归一化时选取的参考长度。
- **输出**　无量纲 TM-score，数值越大表示在所选对应与归一化下结构越接近。
- **LLM 参与**　无需 LLM，按几何距离和参考长度计算。

## 结果解读

TM-score 是指标，TM-align 则会搜索结构对齐。相同分数在对齐覆盖范围和参考长度不同时需要分别解释。

## 在六篇研究中的用法

使用此来源的研究组件包括 [MAESD 结构新颖性与序列多样性评测](../MAESD%20%E7%BB%93%E6%9E%84%E6%96%B0%E9%A2%96%E6%80%A7%E4%B8%8E%E5%BA%8F%E5%88%97%E5%A4%9A%E6%A0%B7%E6%80%A7%E8%AF%84%E6%B5%8B/MAESD%20%E7%BB%93%E6%9E%84%E6%96%B0%E9%A2%96%E6%80%A7%E4%B8%8E%E5%BA%8F%E5%88%97%E5%A4%9A%E6%A0%B7%E6%80%A7%E8%AF%84%E6%B5%8B.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Zhang & Skolnick (2004). Scoring function for automated assessment of protein structure template quality.](<https://doi.org/10.1002/prot.20264>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　独立的原始评分论文。作者软件发布页 https://seq2fun.dcmb.med.umich.edu/TM-score/。未确认其独立原始 GitHub。

## 下载与访问

- [作者的 TM-score 程序下载](<https://seq2fun.dcmb.med.umich.edu/TM-score/>)　软件发布页提供计算程序，并说明结构比较方式。
