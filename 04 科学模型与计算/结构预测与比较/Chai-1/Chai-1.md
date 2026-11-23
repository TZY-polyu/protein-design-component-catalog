# Chai-1

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

对包含蛋白质、核酸、配体等分子的体系预测复合结构，供结构比较和候选分析使用。

## 输入、输出与 LLM 参与

- **输入**　各分子实体的序列或化学描述，可提供序列比对、模板等上下文。
- **输出**　预测复合物坐标、结构置信度和模型给出的相关评分。
- **LLM 参与**　使用专用分子结构模型。输入特征可能包含蛋白语言表征，无需通用对话 LLM。

## 结果解读

工具仓库与模型权重分别获取。论文列为可用后端时，只能据实说明已列入目录。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供复合物结构预测选项。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Chai Discovery (2024), Chai-1: Decoding the molecular interactions of life](<https://doi.org/10.1101/2024.10.10.615955>)
- **GitHub 仓库**　[chaidiscovery/chai-lab](<https://github.com/chaidiscovery/chai-lab>)
- **归属说明**　开发团队官方仓库所引技术报告。

## 下载与访问

- [Chai 官方 Python 软件包](<https://pypi.org/project/chai_lab/#files>)　权重由官方运行库按需下载并缓存。细节见仓库的模型权重说明。
- [仓库源码 ZIP · chaidiscovery/chai-lab](<https://github.com/chaidiscovery/chai-lab/archive/27e6055bed9e2abeb455674108aaec453a42d84e.zip>)　该仓库的固定快照。

## 关联组件

[Chai-1 MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/Chai-1%20MCP/Chai-1%20MCP.md)
