# Rosetta ref2015

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

把原子相互作用、构象偏好和溶剂化等分项组合为 Rosetta 的全原子构象分数。MAESD 用它检查结构的能量合理性。

## 输入、输出与 LLM 参与

- **输入**　带原子坐标和残基信息的蛋白构象、Rosetta 对原子和化学状态的表示。
- **输出**　加权总分及各项能量贡献，一般按 Rosetta 能量单位报告。
- **LLM 参与**　评分按给定函数执行，无需 LLM。

## 结果解读

同一设置内的相对比较最容易解释。总分不能直接当成实验测得的结合自由能。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算）　检查能量合理性，并对选中的候选做骨架松弛。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Alford 等 (2017). The Rosetta All-Atom Energy Function for Macromolecular Modeling and Design.](<https://doi.org/10.1021/acs.jctc.7b00125>)
- **GitHub 仓库**　[RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta>)
- **归属说明**　REF2015 的系统定义。参数优化另见 Park 等（2016，doi:10.1021/acs.jctc.6b00819）。

## 下载与访问

- [ref2015 官方权重文件](<https://github.com/RosettaCommons/rosetta/blob/main/database/scoring/weights/ref2015.wts>)　可在文件页下载权重设置，具体能量项的实现还依赖 Rosetta。
- [仓库源码 ZIP · RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [Rosetta](../Rosetta/Rosetta.md) · [Rosetta-RelaxBB](../Rosetta-RelaxBB/Rosetta-RelaxBB.md)
