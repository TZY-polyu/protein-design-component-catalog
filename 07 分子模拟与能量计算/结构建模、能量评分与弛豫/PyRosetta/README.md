# PyRosetta

在 Python 中读取、操作和打分 Rosetta 的结构对象，可将结构分析嵌入现有科学计算程序。

## 输入与输出

- **输入**　分子三维坐标、待分析的链或残基，以及所选 Rosetta 评分或结构操作。
- **输出**　Rosetta 评分及其分项、界面几何或经处理的三维构象，取决于调用内容。

## 接入条件

- **LLM 参与**　无需通用 LLM。Python 接口执行 Rosetta 的数值模型。
- **运行条件**　需匹配的 Python 构建和 Rosetta 许可。官方为学术与其他非商业用途提供单独的 PyRosetta 非商业协议，商业用途需另行授权。

同一结构在不同评分函数下可获得不同数值。解释时应保留函数名称和计算条件。

## 原始来源与公开实现

Chaudhury et al. (2010), PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta

[论文或原始出版物](https://doi.org/10.1093/bioinformatics/btq007)

- **GitHub 仓库**　[RosettaCommons/rosetta](https://github.com/RosettaCommons/rosetta)
- **实现入口**　[查看源代码](https://github.com/RosettaCommons/rosetta/tree/main/source/src/python/PyRosetta)

Rosetta 官方源码树中的 Python 绑定与构建脚本。

## 下载

- [下载源码快照（ZIP）](https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip)　该链接固定到仓库中的一个提交。
- [官方 PyRosetta 发行包](https://www.pyrosetta.org/downloads)　依操作系统和 Python 版本选择。下载页说明非商业与商业授权。

## 可选调用接口

- **PyRosetta 结构优化 MCP**　使用 PyRosetta 执行本地优化。需遵循 PyRosetta 下载页面列出的非商业或商业许可。 [接口源码](https://github.com/MacromNex/rosetta_mcp/blob/a17e821af1d5b77b7067b3dd93553f4274da82e4/scripts/protein_refinement.py) · [适配器下载](https://github.com/MacromNex/rosetta_mcp/archive/a17e821af1d5b77b7067b3dd93553f4274da82e4.zip)
