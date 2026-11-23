# PME（GROMACS 实现）

在周期性边界条件下利用网格方法计算长程静电相互作用，降低直接求和的计算成本。

## 输入与输出

- **输入**　原子部分电荷、坐标、周期性模拟盒，以及软件中的静电计算设置。
- **输出**　长程静电的能量与力贡献，供分子动力学积分或能量分析使用。

## 接入条件

- **LLM 参与**　由经典数值算法执行，无需通用 LLM。
- **运行条件**　安装或编译带 FFT 支持的 GROMACS，准备包含电荷与周期边界的模拟体系。

PME 是静电计算方法。它与力场参数、短程相互作用及积分算法共同决定完整的模拟结果。

## 原始来源与公开实现

Darden、York 与 Pedersen (1993). Particle mesh Ewald: An N·log(N) method for Ewald sums in large systems.

[论文或原始出版物](https://doi.org/10.1063/1.464397)

- **GitHub 仓库**　[gromacs/gromacs](https://github.com/gromacs/gromacs)
- **实现入口**　[查看源代码](https://github.com/gromacs/gromacs/tree/bc88adaf4e6c918646aba6d3495d3383c6aca6b4/src/gromacs/ewald)

原论文提出 PME 算法。链接指向 GROMACS 团队维护的实现，包含实际的网格、FFT 及力计算代码。

## 下载

- [GROMACS 2021 源码包](https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz)　包含粒子网格 Ewald 静电计算实现。
- [固定版本源码 ZIP](https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip)　包含上述实现及其同仓库配套文件。
