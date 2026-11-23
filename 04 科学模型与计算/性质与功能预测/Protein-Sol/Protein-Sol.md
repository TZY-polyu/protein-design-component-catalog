# Protein-Sol

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

根据序列的理化及组成特征估计蛋白质相对溶解倾向，供不同序列作计算比较。

## 输入、输出与 LLM 参与

- **输入**　蛋白氨基酸序列。输入需满足该工具支持的序列字符与格式。
- **输出**　序列级预测溶解性分数，以及部分输入特征相对于参考群体的偏差。
- **LLM 参与**　通过序列特征与统计模型预测，无需通用 LLM。

## 结果解读

分数来自参考表达数据上的模型预测。实际溶解度还与实验体系、条件有关，分数没有实验浓度单位。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供可溶性估计。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Hebditch et al. (2017), Protein–Sol: a web tool for predicting protein solubility from sequence](<https://doi.org/10.1093/bioinformatics/btx345>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　曼彻斯特大学官方站提供程序下载，未核实上游 GitHub。

## 下载与访问

- [曼彻斯特大学离线软件](<https://www.protein-sol.manchester.ac.uk/software>)　选择 Solubility from protein sequence prediction 的 Download Zip。同页还列有其他软件。

## 关联组件

[Protein-Sol MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/Protein-Sol%20MCP/Protein-Sol%20MCP.md)
