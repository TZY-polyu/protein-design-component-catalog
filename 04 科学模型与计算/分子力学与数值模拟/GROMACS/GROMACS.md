# GROMACS

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

根据分子力场随时间推进原子体系，产生轨迹和能量记录。MAESD 补充材料说明使用 GROMACS 2021 分析结构微环境。

## 输入、输出与 LLM 参与

- **输入**　初始结构坐标、拓扑和力场定义、溶剂模型及模拟设置。
- **输出**　坐标轨迹、能量和日志等文件，供后续统计距离、构象或相互作用。
- **LLM 参与**　模拟及轨迹写出无需 LLM。

## 结果解读

轨迹是由所选力场和初始体系得到的模拟样本。统计性质依赖采样充分性和分析定义。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　对局部微环境进行模拟，轨迹用于评估非共价作用的保持程度。补充材料亦说明使用最速下降法做能量最小化。

使用此来源的研究组件包括 [MAESD 局部环境评分 SMR](../../%E5%8A%9F%E8%83%BD%E7%BA%A6%E6%9D%9F%E4%B8%8E%E5%80%99%E9%80%89%E7%AD%9B%E9%80%89/MAESD%20%E5%B1%80%E9%83%A8%E7%8E%AF%E5%A2%83%E8%AF%84%E5%88%86%20SMR/MAESD%20%E5%B1%80%E9%83%A8%E7%8E%AF%E5%A2%83%E8%AF%84%E5%88%86%20SMR.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Berendsen et al. (1995), GROMACS: A message-passing parallel molecular dynamics implementation](<https://doi.org/10.1016/0010-4655(95)00042-E>)
- **GitHub 仓库**　[gromacs/gromacs](<https://github.com/gromacs/gromacs>)
- **归属说明**　早期原始软件论文。2015 年文献介绍后续高性能版本。GitHub 是官方镜像。

## 下载与访问

- [GROMACS 2021 源码包](<https://ftp.gromacs.org/gromacs/gromacs-2021.tar.gz>)　GROMACS 2021 官方下载页列出的具体版本。
- [2021 版本校验与下载说明](<https://manual.gromacs.org/2021/download.html>)　可核对源码包校验值和回归测试包。
- [仓库源码 ZIP · gromacs/gromacs](<https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip>)　该仓库的固定快照。

## 关联组件

[GROMACS MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/GROMACS%20MCP/GROMACS%20MCP.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
