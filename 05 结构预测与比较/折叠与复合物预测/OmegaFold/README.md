# OmegaFold

从单条蛋白序列预测其折叠构象，把序列表示转换为三维坐标。

## 输入与输出

- **输入**　一条氨基酸序列，常以 FASTA 表示。模型使用随版本发布的检查点。
- **输出**　包含原子坐标的预测蛋白结构文件，以及模型置信度信息。

## 接入条件

- **LLM 参与**　内部使用 OmegaPLM 蛋白语言模型，无需外部通用 LLM。
- **运行条件**　作者发布的 OmegaFold 检查点以及兼容的 PyTorch 环境。

预测结构中的坐标和置信度描述模型推断，实际构象取决于实验环境和分子状态。

## 原始来源与公开实现

Wu et al. (2022), High-resolution de novo structure prediction from primary sequence

[论文或原始出版物](https://doi.org/10.1101/2022.07.21.500999)

- **GitHub 仓库**　[HeliXonProtein/OmegaFold](https://github.com/HeliXonProtein/OmegaFold)
- **实现入口**　[查看源代码](https://github.com/HeliXonProtein/OmegaFold/blob/313c873ad190b64506a497c926649e15fcd88fcd/omegafold/model.py)

OmegaFold 原作者公开结构预测网络及预训练权重入口。

## 下载

- [下载实现源码（ZIP）](https://github.com/HeliXonProtein/OmegaFold/archive/313c873ad190b64506a497c926649e15fcd88fcd.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [OmegaFold 模型 2 权重](https://helixon.s3.amazonaws.com/release2.pt)　这是官方程序为模型 2 指定的权重地址。
