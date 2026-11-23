# LINCS

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

在分子动力学积分中校正受约束的键长，让分子几何满足拓扑文件给定的约束。

## 输入、输出与 LLM 参与

- **输入**　当前积分步的原子坐标、受约束的原子对、目标距离与质量信息。
- **输出**　满足约束条件的坐标修正，交给模拟引擎继续积分并形成轨迹。
- **LLM 参与**　线性代数约束算法，自身无需语言模型。

## 结果解读

研究中 LINCS 作为 GROMACS 的内部算法工作。最终得到的轨迹还取决于力场、环境模型与其他积分步骤。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　保持模拟中指定共价键的几何约束。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Hess、Bekker、Berendsen 与 Fraaije (1997). LINCS: A linear constraint solver for molecular simulations.](<https://doi.org/10.1002/%28SICI%291096-987X%28199709%2918%3A12%3C1463%3A%3AAID-JCC4%3E3.0.CO%3B2-H>)
- **GitHub 仓库**　[gromacs/gromacs](<https://github.com/gromacs/gromacs>)
- **归属说明**　GitHub 为本文所用的 GROMACS 实现。补充材料指名 LINCS。

## 下载与访问

- [GROMACS 2021 源码包](<https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz>)　包含 LINCS 的 GROMACS 实现。
- [仓库源码 ZIP · gromacs/gromacs](<https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip>)　该仓库的固定快照。

## 关联组件

[GROMACS](../GROMACS/GROMACS.md)
