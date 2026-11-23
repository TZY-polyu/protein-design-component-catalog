# TIP3P

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

以三个相互作用位点描述水分子，为显式溶剂分子动力学模拟提供水模型。

## 输入、输出与 LLM 参与

- **输入**　模拟引擎中的水拓扑、坐标、与所用力场配套的参数以及其他体系分子。
- **输出**　水分子的相互作用和力贡献，参与积分后生成包含溶剂的模拟轨迹。
- **LLM 参与**　无需 LLM，依靠经典力学模型。

## 结果解读

TIP3P 有力场相关的实现变体。MAESD 补充材料给出模型名称，未单独指定其变体文件。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　在分子动力学中表示显式溶剂。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Jorgensen 等 (1983). Comparison of simple potential functions for simulating liquid water.](<https://doi.org/10.1063/1.445869>)
- **GitHub 仓库**　[gromacs/gromacs](<https://github.com/gromacs/gromacs>)
- **归属说明**　GitHub 为本文所用 GROMACS 引擎的实现，并非水模型作者的独立仓库。补充材料未区分其 TIP3P 变体。

## 下载与访问

- [GROMACS 中的 TIP3P 拓扑示例](<https://github.com/gromacs/gromacs/blob/main/share/top/amber99sb.ff/tip3p.itp>)　一个明确的实现文件，可在网页下载。该例不锁定论文实际采用的变体。
- [仓库源码 ZIP · gromacs/gromacs](<https://github.com/gromacs/gromacs/archive/bc88adaf4e6c918646aba6d3495d3383c6aca6b4.zip>)　该仓库的固定快照。

## 关联组件

[GROMACS](../GROMACS/GROMACS.md)
