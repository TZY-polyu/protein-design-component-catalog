# ProtAgents 序列折叠接口

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

与 Chroma 给出的结构进行独立重折叠比较。无需多序列比对。

## 输入、输出与 LLM 参与

- **输入**　一条氨基酸序列及结果名。
- **输出**　预测的三维折叠结构、PDB 文件名。
- **LLM 参与**　专用蛋白语言模型参与。OmegaFold 内含 OmegaPLM，无需通用对话 LLM。

## 结果解读

接口在给定序列上调用 OmegaFold，保存预测结构作为独立比较对象。论文中使用的模型 2 属于 OmegaFold 的实现版本。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 II 结构预测。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **OmegaFold 的原始出处**　[Wu et al. (2022), High-resolution de novo structure prediction from primary sequence](<https://doi.org/10.1101/2022.07.21.500999>)
- **OmegaPLM 的原始出处**　[Wu et al. (2022), High-resolution de novo structure prediction from primary sequence](<https://doi.org/10.1101/2022.07.21.500999>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　fold_protein 为 ProtAgents 封装，折叠模型及其内部 OmegaPLM 见 OmegaFold 原论文。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[OmegaFold](../OmegaFold/OmegaFold.md) · [OmegaPLM](../../%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/OmegaPLM/OmegaPLM.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
