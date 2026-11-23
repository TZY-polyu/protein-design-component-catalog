# V-rescale

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

以随机速度重缩放调节分子动力学体系与热浴间的能量交换，用于维持指定的温度分布。

## 输入、输出与 LLM 参与

- **输入**　当前速度或动能、目标温度及模拟引擎的热耦合设置。
- **输出**　更新后的速度与动能分布，随时间积分进入体系轨迹。
- **LLM 参与**　无需 LLM，热浴算法通过数值运算执行。

## 结果解读

它影响轨迹采样的热力学分布，与描述原子间势能的力场属于不同组件。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算（补充材料确认））　调节模拟体系的温度。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Bussi、Donadio 与 Parrinello (2007). Canonical sampling through velocity rescaling.](<https://doi.org/10.1063/1.2408420>)
- **GitHub 仓库**　[GiovanniBussi/StochasticVelocityRescaling](<https://github.com/GiovanniBussi/StochasticVelocityRescaling>)
- **归属说明**　GitHub 为原作者的独立参考实现。MAESD 补充材料表明实际在 GROMACS 中使用。

## 下载与访问

- [仓库源码 ZIP · GiovanniBussi/StochasticVelocityRescaling](<https://github.com/GiovanniBussi/StochasticVelocityRescaling/archive/92e3b46b3b8f80b81096a79eb3e77befd03ccd53.zip>)　该仓库的固定快照。

## 关联组件

[GROMACS](../GROMACS/GROMACS.md)
