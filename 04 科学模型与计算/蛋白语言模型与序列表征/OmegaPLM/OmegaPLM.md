# OmegaPLM

[科学模型与计算](../../README.md) / 蛋白语言模型与序列表征

## 用途

作为 OmegaFold 的蛋白语言模型子模块，学习序列上下文并为后续折叠网络提供表示。

## 输入、输出与 LLM 参与

- **输入**　氨基酸序列经模型词表编码后的残基符号。
- **输出**　逐残基或残基对的内部特征，作为后续几何与结构预测模块的输入。
- **LLM 参与**　自身属于专用蛋白语言模型。推理无需通用对话 LLM。

## 结果解读

OmegaPLM 提供中间表示，最终结构坐标由完整 OmegaFold 生成。作者的完整检查点包含这部分参数。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 序列折叠接口](../../%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/ProtAgents%20%E5%BA%8F%E5%88%97%E6%8A%98%E5%8F%A0%E6%8E%A5%E5%8F%A3/ProtAgents%20%E5%BA%8F%E5%88%97%E6%8A%98%E5%8F%A0%E6%8E%A5%E5%8F%A3.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Wu et al. (2022), High-resolution de novo structure prediction from primary sequence](<https://doi.org/10.1101/2022.07.21.500999>)
- **GitHub 仓库**　[HeliXonProtein/OmegaFold](<https://github.com/HeliXonProtein/OmegaFold>)
- **归属说明**　OmegaFold 内部蛋白语言模型，随 OmegaFold 发表和发布。

## 下载与访问

- [包含该模块的 OmegaFold 模型 2 权重](<https://helixon.s3.amazonaws.com/release2.pt>)　完整折叠模型参数。未核实该子模块有独立分发包。 此次连接超时，文件下载状态未确认。
- [仓库源码 ZIP · HeliXonProtein/OmegaFold](<https://github.com/HeliXonProtein/OmegaFold/archive/313c873ad190b64506a497c926649e15fcd88fcd.zip>)　该仓库的固定快照。
