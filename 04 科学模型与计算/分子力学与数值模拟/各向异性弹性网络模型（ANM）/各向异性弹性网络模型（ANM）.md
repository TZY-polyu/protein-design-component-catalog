# 各向异性弹性网络模型（ANM）

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

用空间节点与弹性联系近似蛋白结构，估计结构整体偏好沿哪些方向发生协同运动。

## 输入、输出与 LLM 参与

- **输入**　经选择的结构坐标和节点之间的连接关系。
- **输出**　正常模态的特征值与位移方向，可进一步得到节点波动和相关性统计。
- **LLM 参与**　求解弹性网络矩阵，无需语言模型。

## 结果解读

低频模态刻画在参考构象附近容易发生的集体运动，不提供真实时间尺度。ProtAgents 通过 ProDy 获得这类计算结果。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 简正模态分析](../ProtAgents%20%E7%AE%80%E6%AD%A3%E6%A8%A1%E6%80%81%E5%88%86%E6%9E%90/ProtAgents%20%E7%AE%80%E6%AD%A3%E6%A8%A1%E6%80%81%E5%88%86%E6%9E%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Doruker, Atilgan & Bahar (2000), Dynamics of proteins predicted by molecular dynamics simulations and analytical approaches: application to alpha-amylase inhibitor](<https://pubmed.ncbi.nlm.nih.gov/10861943/>)
- **原始论文或方法出处**　[Atilgan et al. (2001), Anisotropy of fluctuation dynamics of proteins with an elastic network model](<https://doi.org/10.1016/S0006-3495(01)76033-X>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　ANM 的原始方法论文之一。实际代码实现另见 ProDy。

## 下载与访问

- [ProDy 发布包](<https://pypi.org/project/ProDy/#files>)　含 ANM 的独立实现，不是原始论文作者随文发布的软件。
