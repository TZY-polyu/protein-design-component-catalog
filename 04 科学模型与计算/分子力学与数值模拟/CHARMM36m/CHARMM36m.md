# CHARMM36m

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

为蛋白质分子动力学模拟提供经验力场参数，描述键合、静电和非键相互作用。

## 输入、输出与 LLM 参与

- **输入**　指定了原子类型、连接关系和坐标的体系，以及与模拟引擎相容的参数文件。
- **输出**　力场定义的势能与由模拟引擎计算的原子受力，进一步可形成模拟轨迹。
- **LLM 参与**　经验函数和参数表不需要通用或蛋白语言模型。

## 结果解读

CHARMM36m 是参数化的力场，推进时间并产生轨迹的是模拟引擎。使用时需区分力场版本和引擎版本。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　提供蛋白质原子间相互作用的参数和物理模型。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Huang 等 (2016 在线，2017 刊期). CHARMM36m: an improved force field for folded and intrinsically disordered proteins.](<https://doi.org/10.1038/nmeth.4067>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　力场参数由 MacKerell 实验室发布。未核实其独立官方 GitHub。

## 下载与访问

- [MacKerell 实验室力场发布页](<https://mackerell.umaryland.edu/charmm_ff.shtml>)　原始开发团队提供参数与不同引擎适配资源。

## 关联组件

[GROMACS](../GROMACS/GROMACS.md)
