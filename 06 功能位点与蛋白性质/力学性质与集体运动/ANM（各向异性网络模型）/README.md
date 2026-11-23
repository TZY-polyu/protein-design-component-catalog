# ANM（各向异性网络模型）

用空间节点与弹性联系近似蛋白结构，估计结构整体偏好沿哪些方向发生协同运动。

## 输入与输出

- **输入**　经选择的结构坐标和节点之间的连接关系。
- **输出**　正常模态的特征值与位移方向，可进一步得到节点波动和相关性统计。

## 接入条件

- **LLM 参与**　求解弹性网络矩阵，无需语言模型。
- **运行条件**　公开的 ProDy 实现需要 Python、ProDy 和数值计算依赖，以及可读取的参考结构坐标。

低频模态描述参考构象附近易发生的运动方向。它们不能单独给出相应的真实时间尺度。

## 原始来源与公开实现

Atilgan 等（2001），Anisotropy of fluctuation dynamics of proteins with an elastic network model。Doruker、Atilgan 与 Bahar（2000）给出更早的相关工作。

[论文或原始出版物](https://doi.org/10.1016/S0006-3495(01)76033-X)

- **GitHub 仓库**　[prody/ProDy](https://github.com/prody/ProDy)
- **实现入口**　[查看源代码](https://github.com/prody/ProDy/blob/main/prody/dynamics/anm.py)

ProDy 提供 ANM 的可运行实现，由 ProDy 团队维护。

## 下载

- [ProDy 发布包](https://pypi.org/project/ProDy/#files)　含 ANM 的独立实现，不是原始论文作者随文发布的软件。
- [早期方法论文](https://pubmed.ncbi.nlm.nih.gov/10861943/)　Doruker、Atilgan 与 Bahar，2000。
- [项目源码 ZIP](https://github.com/prody/ProDy/archive/cfbbacc60722074c9e91f802f04dba0caee2f1f9.zip)　公开项目的源码快照。
