# NumPy

用多维数组统一表示数值数据，并提供向量化运算、矩阵计算和基础统计操作。

## 输入与输出

- **输入**　可转换为数组的标量、向量、矩阵或更高维数据，以及所选运算。
- **输出**　数值数组、标量或统计汇总，形状和数值类型由输入及运算决定。

## 接入条件

- **LLM 参与**　基础数值计算库，无需通用 LLM。
- **运行条件**　Python 及与平台兼容的 NumPy 安装包。直接下载二进制包可省去本地编译。

数组形状、计算精度和缺失值处理规则会影响数值分析。领域模型和科学假设由调用方提供。

**最小运行核验**　NumPy 1.26.4 对二维数组按列求均值，得到 [2, 3, 4]。

## 原始来源与公开实现

Harris et al. (2020), Array programming with NumPy（软件代表论文）

[论文或原始出版物](https://doi.org/10.1038/s41586-020-2649-2)

- **GitHub 仓库**　[numpy/numpy](https://github.com/numpy/numpy)
- **实现入口**　[查看源代码](https://github.com/numpy/numpy/blob/d592eb072efbd8dcabb5d624ba3706e675ec3538/numpy/_core/src/multiarray/arrayobject.c)

上游作者仓库

## 下载

- [下载实现源码（ZIP）](https://github.com/numpy/numpy/archive/d592eb072efbd8dcabb5d624ba3706e675ec3538.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [NumPy 发布包](https://pypi.org/project/numpy/#files)　可按 Python 版本和平台选择二进制包或源码分发包。
