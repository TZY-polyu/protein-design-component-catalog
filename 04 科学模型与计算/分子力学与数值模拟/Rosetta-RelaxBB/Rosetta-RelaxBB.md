# Rosetta-RelaxBB

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

在允许骨架参与调整的条件下松弛候选构象，使局部几何与所选 Rosetta 评分更加相容。

## 输入、输出与 LLM 参与

- **输入**　待松弛的蛋白三维结构，以及宿主协议指定的可动自由度与评分规则。
- **输出**　调整后的结构坐标，配合相同评分设置可比较松弛前后的得分。
- **LLM 参与**　结构优化通过数值计算完成，无需通用 LLM。

## 结果解读

已找到早期使用 RelaxBB 名称的文献。MAESD 未公开足够信息来确定其具体脚本与早期论文完全相同。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算）　检查能量合理性，并对选中的候选做骨架松弛。

## 原始来源与 GitHub

- **原始论文或方法出处**　[同名方案的早期公开描述：Anand 等 (2022). Protein sequence design with a learned potential.](<https://doi.org/10.1038/s41467-022-28313-9>)
- **GitHub 仓库**　[RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta>)
- **归属说明**　该文 Methods 明确使用 Rosetta-RelaxBB 一名。与 MAESD 采用的具体实现是否相同未披露，首发归属未完全确定。GitHub 为 Rosetta 套件。

## 下载与访问

- [Rosetta 官方软件分发](<https://rosettacommons.org/software/download/>)　可获取底层套件。未核实 MAESD 所用 RelaxBB 封装的独立下载。
- [仓库源码 ZIP · RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [Rosetta](../Rosetta/Rosetta.md) · [Rosetta ref2015](../Rosetta%20ref2015/Rosetta%20ref2015.md)
