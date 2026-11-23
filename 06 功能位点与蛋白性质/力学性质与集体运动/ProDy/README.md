# ProDy

支持结构读取与动力学分析，可利用蛋白弹性网络的正常模态描述集体运动。

## 输入与输出

- **输入**　原子坐标、所选结构区域或原子集合。执行正常模态分析时需确定对应的网络模型。
- **输出**　模态方向、特征值、位移涨落或相关性等数值及可视化所需数据。

## 接入条件

- **LLM 参与**　按线性代数和生物物理模型计算，无需通用 LLM。
- **运行条件**　Python 与 NumPy、SciPy 等依赖。编译源码时需要对应编译工具。

可用特征向量比较不同区域的协同位移。模态反映所选网络模型与输入构象的性质。

## 原始来源与公开实现

Bakan, Meireles & Bahar (2011), ProDy: Protein Dynamics Inferred from Theory and Experiments

[论文或原始出版物](https://doi.org/10.1093/bioinformatics/btr168)

- **GitHub 仓库**　[prody/ProDy](https://github.com/prody/ProDy)
- **实现入口**　[查看源代码](https://github.com/prody/ProDy/tree/cfbbacc60722074c9e91f802f04dba0caee2f1f9/prody)

ProDy 团队公开维护的 Python 包。

## 下载

- [ProDy 发布包](https://pypi.org/project/ProDy/#files)　提供 Python 软件包下载。
- [固定版本源码 ZIP](https://github.com/prody/ProDy/archive/cfbbacc60722074c9e91f802f04dba0caee2f1f9.zip)　包含上述实现及其同仓库配套文件。
