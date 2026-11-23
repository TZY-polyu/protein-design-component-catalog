# LigandMPNN

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

在蛋白逆折叠时把邻近非蛋白原子纳入环境表示，以评估序列与给定蛋白结构及分子上下文是否相容。

## 输入、输出与 LLM 参与

- **输入**　蛋白骨架坐标与可用的邻近小分子、金属等原子环境。评分时可另给候选序列。
- **输出**　结构条件下的序列候选、残基概率或序列评分，具体取决于任务模式。
- **LLM 参与**　属于专用图神经网络，不要求通用 LLM。

## 结果解读

与只描述蛋白骨架的模型相比，这一方法能使用周围原子环境。计算相容性仍需与针对用途的实验性质分开解释。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供考虑非蛋白组分的序列设计。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Dauparas et al. (2025), Atomic context-conditioned protein sequence design using LigandMPNN](<https://doi.org/10.1038/s41592-025-02626-1>)
- **GitHub 仓库**　[dauparas/LigandMPNN](<https://github.com/dauparas/LigandMPNN>)
- **归属说明**　作者仓库。该项工作于 2023 年先发布预印本。

## 下载与访问

- [作者提供的模型参数下载清单](<https://github.com/dauparas/LigandMPNN/blob/main/get_model_params.sh>)　官方文件列出各检查点的来源，权重独立于源码。
- [仓库源码 ZIP · dauparas/LigandMPNN](<https://github.com/dauparas/LigandMPNN/archive/26ec57ac976ade5379920dbd43c7f97a91cf82de.zip>)　该仓库的固定快照。

## 关联组件

[LigandMPNN MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/LigandMPNN%20MCP/LigandMPNN%20MCP.md)
