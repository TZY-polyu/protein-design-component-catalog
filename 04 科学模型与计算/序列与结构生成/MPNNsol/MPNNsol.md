# MPNNsol

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

使用针对可溶性蛋白数据的 ProteinMPNN 变体，根据给定骨架评估或提出序列。

## 输入、输出与 LLM 参与

- **输入**　蛋白主链几何、链与残基的对应关系，以及适用的可溶性模型权重。
- **输出**　与该骨架相容的候选氨基酸序列，或模型给出的序列概率与打分。
- **LLM 参与**　由专用图神经网络推理，无需通用对话 LLM。

## 结果解读

MPNNsol 是 ProteinMPNN 的模型变体。使用这类权重不会自动给出候选在特定实验条件下的实测溶解度。

## 在六篇研究中的用法

- **ProteinMCP**（案例2实际使用的变体）　BindCraft 案例采用偏向可溶性设计的 MPNN 变体。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Goverde et al. (2024), Computational design of soluble and functional membrane protein analogues](<https://doi.org/10.1038/s41586-024-07601-y>)
- **GitHub 仓库**　[dauparas/ProteinMPNN](<https://github.com/dauparas/ProteinMPNN/tree/main/soluble_model_weights>)
- **归属说明**　作者指认的可溶性变体权重目录。

## 下载与访问

- [作者提供的可溶性权重目录](<https://github.com/dauparas/ProteinMPNN/tree/main/soluble_model_weights>)　可查看和下载相应的检查点文件。
- [仓库源码 ZIP · dauparas/ProteinMPNN](<https://github.com/dauparas/ProteinMPNN/archive/8907e6671bfbfc92303b5f79c4b5e6ce47cdef57.zip>)　该仓库的固定快照。

## 关联组件

[BindCraft](../BindCraft/BindCraft.md) · [ProteinMPNN](../ProteinMPNN/ProteinMPNN.md)
