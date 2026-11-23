# GPTProteinPretrained

[数据与知识](../../README.md) / 文献与研究数据

## 用途

为 ProteinForceGPT 的预训练提供蛋白序列文本，使模型先学习序列规律，再接受针对力学性质的监督。

## 输入、输出与 LLM 参与

- **输入**　从作者的数据集读取训练划分中的 text 字段，每条记录是一段序列训练文本。
- **输出**　训练程序可读取的序列样本集合。经编码后可用于语言建模。
- **LLM 参与**　下载或读取数据无需 LLM。使用它训练的是专用语言模型。

## 结果解读

这是预训练语料。ProtAgents 描述的力学监督来自另外的 ForceGen 数据来源，单条预训练记录不必含有力学标签。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinForceGPT 训练数据组合](../ProteinForceGPT%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E7%BB%84%E5%90%88/ProteinForceGPT%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E7%BB%84%E5%90%88.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Laboratory for Atomistic and Molecular Mechanics, MIT, GPTProteinPretrained（预训练数据集。ProtAgents 于 2024 年说明其用途）](<https://huggingface.co/datasets/lamm-mit/GPTProteinPretrained>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　作者直接发布在 Hugging Face 的原始数据集，未核实单独发表的数据论文。

## 下载与访问

- [作者发布的预训练数据集](<https://huggingface.co/datasets/lamm-mit/GPTProteinPretrained>)　Hugging Face 数据集页面，Files 可下载文件，查看器可检查字段。
