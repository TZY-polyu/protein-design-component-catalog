# TIP3P 水模型（GROMACS 拓扑）

在显式溶剂模拟中，用三个相互作用位点表示一个水分子。GROMACS 可读取这份拓扑并在分子动力学计算中应用。

## 输入与输出

- **输入**　与选用力场一致的水模型拓扑、体系坐标，以及 GROMACS 计算所需的完整系统拓扑。
- **输出**　拓扑为模拟引擎提供水分子的原子类型、电荷、几何和约束定义。轨迹、能量与力由引擎计算。

## 接入条件

- **LLM 参与**　无需 LLM，依靠经典力学模型。
- **运行条件**　GROMACS 或兼容其拓扑格式的引擎，以及匹配的力场参数。单个拓扑文件无法单独产生轨迹。

链接指向 GROMACS 的 amber99sb.ff 实现。其他力场也使用 TIP3P 名称，具体参数和约束约定可能不同。

## 原始来源与公开实现

Jorgensen 等 (1983). Comparison of simple potential functions for simulating liquid water.

[论文或原始出版物](https://doi.org/10.1063/1.445869)

- **GitHub 仓库**　[gromacs/gromacs](https://github.com/gromacs/gromacs)
- **实现入口**　[查看源代码](https://github.com/gromacs/gromacs/blob/main/share/top/amber99sb.ff/tip3p.itp)

GROMACS 发行树内的可直接载入的模型定义。原始水势模型由 Jorgensen 等提出。

## 下载

- [TIP3P 拓扑文件](https://raw.githubusercontent.com/gromacs/gromacs/main/share/top/amber99sb.ff/tip3p.itp)　GROMACS 力场格式的纯文本文件。
- [GROMACS 源码发行包](https://ftp.gromacs.org/gromacs/)　配套的计算引擎和力场参数。
- [下载本次索引的源码快照（ZIP）](https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip)
