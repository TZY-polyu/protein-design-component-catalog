# OmegaFold

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

从单条蛋白序列预测其折叠构象，把序列表示转换为三维坐标。

## 输入、输出与 LLM 参与

- **输入**　一条氨基酸序列，常以 FASTA 表示。模型使用随版本发布的检查点。
- **输出**　包含原子坐标的预测蛋白结构文件，以及模型置信度信息。
- **LLM 参与**　内部使用 OmegaPLM 蛋白语言模型，无需外部通用 LLM。

## 结果解读

ProtAgents 明确使用模型 2。预测置信度用于描述模型对局部构象的判断，结构仍可能偏离实验状态。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 序列折叠接口](../ProtAgents%20%E5%BA%8F%E5%88%97%E6%8A%98%E5%8F%A0%E6%8E%A5%E5%8F%A3/ProtAgents%20%E5%BA%8F%E5%88%97%E6%8A%98%E5%8F%A0%E6%8E%A5%E5%8F%A3.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Wu et al. (2022), High-resolution de novo structure prediction from primary sequence](<https://doi.org/10.1101/2022.07.21.500999>)
- **GitHub 仓库**　[HeliXonProtein/OmegaFold](<https://github.com/HeliXonProtein/OmegaFold>)
- **归属说明**　原作者模型仓库，ProtAgents 使用模型 2。

## 下载与访问

- [OmegaFold 模型 2 权重](<https://helixon.s3.amazonaws.com/release2.pt>)　这是官方程序为模型 2 指定的权重地址。 此次连接超时，文件下载状态未确认。
- [仓库源码 ZIP · HeliXonProtein/OmegaFold](<https://github.com/HeliXonProtein/OmegaFold/archive/313c873ad190b64506a497c926649e15fcd88fcd.zip>)　该仓库的固定快照。
