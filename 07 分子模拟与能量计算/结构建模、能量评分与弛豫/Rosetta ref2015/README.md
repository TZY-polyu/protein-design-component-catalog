# Rosetta ref2015

用 Rosetta 的全原子能量函数对构象打分，查看不同能量项对总分的贡献，并在相同设置下比较结构。

## 输入与输出

- **输入**　带原子坐标和残基信息的蛋白构象、Rosetta 对原子和化学状态的表示。
- **输出**　加权总分及各项能量贡献，一般按 Rosetta 能量单位报告。

## 接入条件

- **LLM 参与**　评分按给定函数执行，无需 LLM。
- **运行条件**　需要 Rosetta 或 PyRosetta 的兼容版本与结构输入。非商业和商业用途适用 Rosetta 的不同许可条件。

同一设置内的相对比较最容易解释。总分不能直接当成实验测得的结合自由能。

## 原始来源与公开实现

Alford 等 (2017). The Rosetta All-Atom Energy Function for Macromolecular Modeling and Design.

[论文或原始出版物](https://doi.org/10.1021/acs.jctc.7b00125)

- **GitHub 仓库**　[RosettaCommons/rosetta](https://github.com/RosettaCommons/rosetta)
- **实现入口**　[查看源代码](https://github.com/RosettaCommons/rosetta/blob/main/database/scoring/weights/ref2015.wts)

Rosetta 官方源码库内的 ref2015 权重文件。能量项的计算由同库中的评分代码执行。

## 下载

- [下载源码快照（ZIP）](https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip)　该链接固定到仓库中的一个提交。
- [下载 ref2015 权重文件](https://raw.githubusercontent.com/RosettaCommons/rosetta/main/database/scoring/weights/ref2015.wts)　源码中的评分权重定义，可随 Rosetta 发行包使用。
