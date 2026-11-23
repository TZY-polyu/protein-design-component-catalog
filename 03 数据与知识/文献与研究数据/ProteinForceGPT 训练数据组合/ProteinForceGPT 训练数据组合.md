# ProteinForceGPT 训练数据组合

[数据与知识](../../README.md) / 文献与研究数据

## 用途

提供序列统计信息与力学监督。模拟数据供离线训练。

## 输入、输出与 LLM 参与

- **输入**　约 80 万条氨基酸序列。分子动力学模拟产生的序列–力学数据。
- **输出**　经序列预训练和力学任务微调的专用模型。
- **LLM 参与**　数据本身不需要。训练对象是专用蛋白语言模型。

## 结果解读

预训练部分提供序列，微调部分提供力学监督。训练后得到的 ProteinForceGPT 模型另有模型发布页。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为离线模型训练。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GPTProteinPretrained 的原始出处**　[Laboratory for Atomistic and Molecular Mechanics, MIT, GPTProteinPretrained（预训练数据集。ProtAgents 于 2024 年说明其用途）](<https://huggingface.co/datasets/lamm-mit/GPTProteinPretrained>)
- **ForceGen 的原始出处**　[Ni, Kaplan & Buehler (2024), ForceGen: End-to-end de novo protein generation based on nonlinear mechanical unfolding responses using a language diffusion model](<https://doi.org/10.1126/sciadv.adl4000>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　预训练序列来源见作者数据集 GPTProteinPretrained。Ni 等人的 ForceGen（2023 年预印本、2024 年期刊版）提供分子动力学数据所对应的研究。

## 下载与访问

- [作者预训练集的文件列表](<https://huggingface.co/datasets/lamm-mit/GPTProteinPretrained/tree/main>)　公开序列集，力学微调数据另有来源。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [GPTProteinPretrained 原始发布入口](<https://huggingface.co/datasets/lamm-mit/GPTProteinPretrained>)
- [ForceGen 原始发布入口](<https://doi.org/10.1126/sciadv.adl4000>)
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[ForceGen](../ForceGen/ForceGen.md) · [GPTProteinPretrained](../GPTProteinPretrained/GPTProteinPretrained.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md) · [ProteinForceGPT（ForceGPT）](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E6%80%A7%E8%B4%A8%E4%B8%8E%E5%8A%9F%E8%83%BD%E9%A2%84%E6%B5%8B/ProteinForceGPT%EF%BC%88ForceGPT%EF%BC%89/ProteinForceGPT%EF%BC%88ForceGPT%EF%BC%89.md)
