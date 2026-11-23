# ProDy

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

支持结构读取与动力学分析，可利用蛋白弹性网络的正常模态描述集体运动。

## 输入、输出与 LLM 参与

- **输入**　原子坐标、所选结构区域或原子集合。执行正常模态分析时需确定对应的网络模型。
- **输出**　模态方向、特征值、位移涨落或相关性等数值及可视化所需数据。
- **LLM 参与**　按线性代数和生物物理模型计算，无需通用 LLM。

## 结果解读

在 ProtAgents 中，ProDy 是执行各向异性网络模型分析的软件，ANM 则是底层科学方法。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 简正模态分析](../ProtAgents%20%E7%AE%80%E6%AD%A3%E6%A8%A1%E6%80%81%E5%88%86%E6%9E%90/ProtAgents%20%E7%AE%80%E6%AD%A3%E6%A8%A1%E6%80%81%E5%88%86%E6%9E%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Bakan, Meireles & Bahar (2011), ProDy: Protein Dynamics Inferred from Theory and Experiments](<https://doi.org/10.1093/bioinformatics/btr168>)
- **GitHub 仓库**　[prody/ProDy](<https://github.com/prody/ProDy>)
- **归属说明**　原作者软件仓库。

## 下载与访问

- [ProDy 发布包](<https://pypi.org/project/ProDy/#files>)　提供 Python 软件包下载。
- [仓库源码 ZIP · prody/ProDy](<https://github.com/prody/ProDy/archive/cfbbacc60722074c9e91f802f04dba0caee2f1f9.zip>)　该仓库的固定快照。
