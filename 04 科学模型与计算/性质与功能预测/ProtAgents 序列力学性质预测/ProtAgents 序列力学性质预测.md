# ProtAgents 序列力学性质预测

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

从序列估算蛋白材料的力学行为。专用模型支持双向任务，论文中的智能体只用正向预测。

## 输入、输出与 LLM 参与

- **输入**　氨基酸序列。
- **输出**　预测的最大展开力与展开能。
- **LLM 参与**　依赖专用蛋白语言模型 ProteinForceGPT。通用 GPT-4 仅在上层组织调用。

## 结果解读

项目调用 ProteinForceGPT 的正向预测，将序列映射到最大展开力和展开能。这两个量是模型预测，论文使用它们对候选作计算比较。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 III–IV 属性预测。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **ProteinForceGPT（ForceGPT） 的原始出处**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　ProtAgents 作者在本文训练并报告 ProteinForceGPT。Buehler 2023 是类似模型工作。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md) · [ProteinForceGPT（ForceGPT）](../ProteinForceGPT%EF%BC%88ForceGPT%EF%BC%89/ProteinForceGPT%EF%BC%88ForceGPT%EF%BC%89.md)
