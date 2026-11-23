# MPNNsol

使用针对可溶性蛋白数据的 ProteinMPNN 变体，根据给定骨架评估或提出序列。

## 输入与输出

- **输入**　蛋白主链几何、链与残基的对应关系，以及适用的可溶性模型权重。
- **输出**　与该骨架相容的候选氨基酸序列，或模型给出的序列概率与打分。

## 接入条件

- **LLM 参与**　由专用图神经网络推理，无需通用对话 LLM。
- **运行条件**　ProteinMPNN 推理程序、PyTorch，以及 soluble_model_weights 内的相应参数。

MPNNsol 是 ProteinMPNN 的模型变体。使用这类权重不会自动给出候选在特定实验条件下的实测溶解度。

## 原始来源与公开实现

Goverde et al. (2024), Computational design of soluble and functional membrane protein analogues

[论文或原始出版物](https://doi.org/10.1038/s41586-024-07601-y)

- **GitHub 仓库**　[dauparas/ProteinMPNN](https://github.com/dauparas/ProteinMPNN)
- **实现入口**　[查看源代码](https://github.com/dauparas/ProteinMPNN/blob/8907e6671bfbfc92303b5f79c4b5e6ce47cdef57/protein_mpnn_run.py)

MPNNsol 使用 ProteinMPNN 推理代码及作者发布的 soluble_model_weights 参数。

## 下载

- [下载实现源码（ZIP）](https://github.com/dauparas/ProteinMPNN/archive/8907e6671bfbfc92303b5f79c4b5e6ce47cdef57.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [作者提供的可溶性权重目录](https://github.com/dauparas/ProteinMPNN/tree/main/soluble_model_weights)　可查看和下载相应的检查点文件。
