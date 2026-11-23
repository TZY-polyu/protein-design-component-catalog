# PME

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

在周期性边界条件下利用网格方法计算长程静电相互作用，降低直接求和的计算成本。

## 输入、输出与 LLM 参与

- **输入**　原子部分电荷、坐标、周期性模拟盒，以及软件中的静电计算设置。
- **输出**　长程静电的能量与力贡献，供分子动力学积分或能量分析使用。
- **LLM 参与**　由经典数值算法执行，无需通用 LLM。

## 结果解读

PME 是静电计算方法。它与力场参数、短程相互作用及积分算法共同决定完整的模拟结果。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　计算周期边界下较远原子之间的静电作用。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Darden、York 与 Pedersen (1993). Particle mesh Ewald: An N·log(N) method for Ewald sums in large systems.](<https://doi.org/10.1063/1.464397>)
- **GitHub 仓库**　[gromacs/gromacs](<https://github.com/gromacs/gromacs>)
- **归属说明**　初始 PME 算法。GitHub 为本文所用的 GROMACS 实现。

## 下载与访问

- [GROMACS 2021 源码包](<https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz>)　包含粒子网格 Ewald 静电计算实现。
- [仓库源码 ZIP · gromacs/gromacs](<https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip>)　该仓库的固定快照。

## 关联组件

[GROMACS](../GROMACS/GROMACS.md)
