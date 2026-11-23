# RFdiffusion2

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

第二代结构生成工具支持原子级几何条件，应用于需要显式表达局部原子环境的骨架建模问题。

## 输入、输出与 LLM 参与

- **输入**　分子几何描述、可用的结构上下文及任务要求。
- **输出**　与几何条件对应的候选结构坐标和相关生成记录。
- **LLM 参与**　使用专用生成模型，无需通用 LLM。

## 结果解读

ProteinMCP 将第二代作为独立工具列出。第一代与第二代的代码、权重和原始论文各自独立。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　架构图列入蛋白设计模块。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ahern et al. (2025 在线 / 2026 刊期), Atom-level enzyme active site scaffolding using RFdiffusion2](<https://doi.org/10.1038/s41592-025-02975-x>)
- **GitHub 仓库**　[RosettaCommons/RFdiffusion2](<https://github.com/RosettaCommons/RFdiffusion2>)
- **归属说明**　第二代工具的论文与仓库。

## 下载与访问

- [官方权重与容器获取说明](<https://github.com/RosettaCommons/RFdiffusion2#readme>)　仓库说明划分推理代码、模型权重和运行容器。
- [仓库源码 ZIP · RosettaCommons/RFdiffusion2](<https://github.com/RosettaCommons/RFdiffusion2/archive/d365cbf4db3958814a9f8e4f6f94fa309dfebc2b.zip>)　该仓库的固定快照。

## 关联组件

[RFdiffusion2 MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/RFdiffusion2%20MCP/RFdiffusion2%20MCP.md)
