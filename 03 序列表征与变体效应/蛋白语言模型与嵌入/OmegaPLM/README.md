# OmegaPLM

作为 OmegaFold 的蛋白语言模型子模块，学习序列上下文并为后续折叠网络提供表示。

## 输入与输出

- **输入**　氨基酸序列经模型词表编码后的残基符号。
- **输出**　逐残基或残基对的内部特征，作为后续几何与结构预测模块的输入。

## 接入条件

- **LLM 参与**　自身属于专用蛋白语言模型。推理无需通用对话 LLM。
- **运行条件**　对应版本的 OmegaFold 完整检查点和包内编码器。没有单独核实到仅含 OmegaPLM 的官方权重包。

OmegaPLM 提供中间表示，最终结构坐标由完整 OmegaFold 生成。作者的完整检查点包含这部分参数。

## 原始来源与公开实现

Wu et al. (2022), High-resolution de novo structure prediction from primary sequence

[论文或原始出版物](https://doi.org/10.1101/2022.07.21.500999)

- **GitHub 仓库**　[HeliXonProtein/OmegaFold](https://github.com/HeliXonProtein/OmegaFold)
- **实现入口**　[查看源代码](https://github.com/HeliXonProtein/OmegaFold/blob/313c873ad190b64506a497c926649e15fcd88fcd/omegafold/omegaplm.py)

OmegaFold 内部蛋白语言模型，随 OmegaFold 发表和发布。

## 下载

- [下载实现源码（ZIP）](https://github.com/HeliXonProtein/OmegaFold/archive/313c873ad190b64506a497c926649e15fcd88fcd.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [包含该模块的 OmegaFold 模型 2 权重](https://helixon.s3.amazonaws.com/release2.pt)　完整折叠模型参数。未核实该子模块有独立分发包。
