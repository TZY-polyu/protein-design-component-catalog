# MutCompute

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

从残基周围的三维化学环境预测该位置与不同氨基酸的相容性，为蛋白变体分析提供计算依据。

## 输入、输出与 LLM 参与

- **输入**　蛋白结构与待分析的残基位置，模型读取位置周围的局部原子环境。
- **输出**　各氨基酸的预测概率或相容性排序，以及相应位置的模型建议。
- **LLM 参与**　由专用三维神经网络计算，无需通用 LLM。

## 结果解读

原始论文研究的是一代 MutCompute。结构环境评分与具体蛋白活性、稳定性的实验变化属于不同量。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　架构图将其列入适应度建模。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Shroff et al. (2020), Discovery of Novel Gain-of-Function Mutations Guided by Structure-Based Deep Learning](<https://doi.org/10.1021/acssynbio.0c00345>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　一代模型工作。未核实该版本的上游 GitHub。MutComputeX 和 2.0 为不同实现。可另列项目适配器。

## 下载与访问

尚未核实一代上游程序或权重的公开下载。

- [作者在线平台](<https://mutcompute.com/>)　可核实的访问入口。一代独立软件或权重下载尚未确认。

## 关联组件

[MutCompute MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/MutCompute%20MCP/MutCompute%20MCP.md)
