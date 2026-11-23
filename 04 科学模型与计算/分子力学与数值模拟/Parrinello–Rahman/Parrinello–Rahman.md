# Parrinello–Rahman

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

在分子动力学中调节模拟盒的尺寸或形状，使体系压力随动力学演化与指定条件相联系。

## 输入、输出与 LLM 参与

- **输入**　模拟盒与粒子状态、瞬时压力信息及模拟定义中的压力耦合条件。
- **输出**　随时间更新的盒矩阵、体积和相关轨迹数据。
- **LLM 参与**　属于数值压力耦合方法，无需通用 LLM。

## 结果解读

MAESD 报告在 GROMACS 中采用此法。原算法、软件实现和一次模拟所得的压力轨迹是三种不同层次的对象。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　在分子动力学平衡阶段控制压力。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Parrinello 与 Rahman (1980). Crystal Structure and Pair Potentials: A Molecular-Dynamics Study.](<https://doi.org/10.1103/PhysRevLett.45.1196>)
- **GitHub 仓库**　[gromacs/gromacs](<https://github.com/gromacs/gromacs>)
- **归属说明**　原作者于 1981 年进一步发表完整方法（doi:10.1063/1.328693）。GitHub 为本文所用的 GROMACS 实现。

## 下载与访问

- [GROMACS 2021 源码包](<https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz>)　论文所用软件系列中的压力耦合实现。
- [仓库源码 ZIP · gromacs/gromacs](<https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip>)　该仓库的固定快照。

## 关联组件

[GROMACS](../GROMACS/GROMACS.md)
