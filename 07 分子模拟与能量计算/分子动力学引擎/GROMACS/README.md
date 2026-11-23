# GROMACS

利用分子力场推进体系的运动方程，执行能量计算或动力学模拟，并记录轨迹。

## 输入与输出

- **输入**　初始结构坐标、拓扑和力场定义、溶剂模型及模拟设置。
- **输出**　坐标轨迹、能量和日志等文件，供后续统计距离、构象或相互作用。

## 接入条件

- **LLM 参与**　模拟及轨迹写出无需 LLM。
- **运行条件**　适合当前平台的 GROMACS 安装、分子拓扑和对应力场文件。

轨迹是由所选力场和初始体系得到的模拟样本。统计性质依赖采样充分性和分析定义。

## 原始来源与公开实现

Berendsen et al. (1995), GROMACS: A message-passing parallel molecular dynamics implementation

[论文或原始出版物](https://doi.org/10.1016/0010-4655(95)00042-E)

- **GitHub 仓库**　[gromacs/gromacs](https://github.com/gromacs/gromacs)
- **实现入口**　[查看源代码](https://github.com/gromacs/gromacs/blob/bc88adaf4e6c918646aba6d3495d3383c6aca6b4/src/programs/mdrun/mdrun.cpp)

早期原始软件论文。2015 年文献介绍后续高性能版本。GitHub 是官方镜像。

## 下载

- [下载实现源码（ZIP）](https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [GROMACS 2021 源码包](https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz)　GROMACS 2021 官方下载页列出的具体版本。
- [2021 版本校验与下载说明](https://manual.gromacs.org/2021/download.html)　可核对源码包校验值和回归测试包。

## 可选调用接口

- **GROMACS MCP**　调度本机 gmx 可执行程序并接收输出。需要先配置 GROMACS。 [接口源码](https://github.com/MacromNex/gromacs_mcp/blob/2611e952b06981cd8527e61787361de99422d53a/scripts/gromacs_command.py) · [适配器下载](https://github.com/MacromNex/gromacs_mcp/archive/2611e952b06981cd8527e61787361de99422d53a.zip)
