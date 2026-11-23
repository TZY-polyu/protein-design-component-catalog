# ProteinForceGPT（ForceGPT）

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

从蛋白序列预测其在拉伸情境下的力学响应，使研究者能比较候选的计算力学特征。

## 输入、输出与 LLM 参与

- **输入**　氨基酸序列。模型的前向任务把序列映射为表征力学性质的模型输出。
- **输出**　预测的最大展开力、展开能等力学量。ProtAgents 的相关实验使用前向预测。
- **LLM 参与**　这是 GPT 架构的专用蛋白语言模型。组织实验的通用 GPT-4 与该科学模型承担不同职责。

## 结果解读

微调数据来自模拟，预测对应相应数据和假定。模型卡指定引用 ProtAgents 作为模型出处。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinForceGPT 训练数据组合](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/ProteinForceGPT%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E7%BB%84%E5%90%88/ProteinForceGPT%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E7%BB%84%E5%90%88.md)、[ProtAgents 序列力学性质预测](../ProtAgents%20%E5%BA%8F%E5%88%97%E5%8A%9B%E5%AD%A6%E6%80%A7%E8%B4%A8%E9%A2%84%E6%B5%8B/ProtAgents%20%E5%BA%8F%E5%88%97%E5%8A%9B%E5%AD%A6%E6%80%A7%E8%B4%A8%E9%A2%84%E6%B5%8B.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)
- **归属说明**　原作者模型卡指定引用此文。GitHub 为项目使用代码，模型发布于 https://huggingface.co/lamm-mit/ProteinForceGPT。

## 下载与访问

- [作者模型文件与权重](<https://huggingface.co/lamm-mit/ProteinForceGPT/tree/main>)　文件列表内可下载模型权重、配置及词表。
- [仓库源码 ZIP · lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents/archive/7a73af3f746ca472a8524d1659547de7a54e65f5.zip>)　该仓库的固定快照。
