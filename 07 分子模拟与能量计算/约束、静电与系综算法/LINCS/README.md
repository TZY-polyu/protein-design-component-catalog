# LINCS

在分子动力学积分中校正受约束的键长，让分子几何满足拓扑文件给定的约束。

## 输入与输出

- **输入**　当前积分步的原子坐标、受约束的原子对、目标距离与质量信息。
- **输出**　满足约束条件的坐标修正，交给模拟引擎继续积分并形成轨迹。

## 接入条件

- **LLM 参与**　线性代数约束算法，自身无需语言模型。
- **运行条件**　含 LINCS 的 GROMACS 发行版本以及定义几何约束的分子体系。

在模拟引擎中，LINCS 负责恢复指定几何约束。轨迹还取决于积分器、力场和初始状态。

## 原始来源与公开实现

Hess、Bekker、Berendsen 与 Fraaije (1997). LINCS: A linear constraint solver for molecular simulations.

[论文或原始出版物](https://doi.org/10.1002/%28SICI%291096-987X%28199709%2918%3A12%3C1463%3A%3AAID-JCC4%3E3.0.CO%3B2-H)

- **GitHub 仓库**　[gromacs/gromacs](https://github.com/gromacs/gromacs)
- **实现入口**　[查看源代码](https://github.com/gromacs/gromacs/blob/bc88adaf4e6c918646aba6d3495d3383c6aca6b4/src/gromacs/mdlib/lincs.cpp)

算法来自 1997 年原论文，这里链接 GROMACS 维护的具体实现。

## 下载

- [下载实现源码（ZIP）](https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [GROMACS 2021 源码包](https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz)　包含 LINCS 的 GROMACS 实现。
