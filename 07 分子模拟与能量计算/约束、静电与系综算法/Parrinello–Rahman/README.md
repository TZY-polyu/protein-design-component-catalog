# Parrinello–Rahman

在分子动力学中调节模拟盒的尺寸或形状，使体系压力随动力学演化与指定条件相联系。

## 输入与输出

- **输入**　模拟盒与粒子状态、瞬时压力信息及模拟定义中的压力耦合条件。
- **输出**　随时间更新的盒矩阵、体积和相关轨迹数据。

## 接入条件

- **LLM 参与**　属于数值压力耦合方法，无需通用 LLM。
- **运行条件**　含此压力耦合方法的分子动力学软件和能提供压力信息的模拟体系。

压力耦合器决定模拟盒如何演化。测量瞬时压力和分析平衡后的平均体积应分别处理。

## 原始来源与公开实现

Parrinello 与 Rahman (1980). Crystal Structure and Pair Potentials: A Molecular-Dynamics Study.

[论文或原始出版物](https://doi.org/10.1103/PhysRevLett.45.1196)

- **GitHub 仓库**　[gromacs/gromacs](https://github.com/gromacs/gromacs)
- **实现入口**　[查看源代码](https://github.com/gromacs/gromacs/blob/bc88adaf4e6c918646aba6d3495d3383c6aca6b4/src/gromacs/modularsimulator/parrinellorahmanbarostat.cpp)

原作者于 1981 年发表完整方法（DOI 10.1063/1.328693）。这里链接 GROMACS 中实现该方法的模块。

## 下载

- [下载实现源码（ZIP）](https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [GROMACS 源码发行包](https://manual.gromacs.org/current/download.html)　包含压力耦合算法的模拟引擎下载。
