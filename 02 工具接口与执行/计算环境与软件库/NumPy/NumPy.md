# NumPy

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

用多维数组统一表示数值数据，并提供向量化运算、矩阵计算和基础统计操作。

## 输入、输出与 LLM 参与

- **输入**　可转换为数组的标量、向量、矩阵或更高维数据，以及所选运算。
- **输出**　数值数组、标量或统计汇总，形状和数值类型由输入及运算决定。
- **LLM 参与**　基础数值计算库，无需通用 LLM。

## 结果解读

ProteinMCP 将其用于 CPU 端科学计算环境。NumPy 负责数值表示与运算，具体科学假设由使用它的分析方法定义。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录／计算层）　为模型特征和常规分析提供 CPU 运算。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Harris et al. (2020), Array programming with NumPy（软件代表论文）](<https://doi.org/10.1038/s41586-020-2649-2>)
- **GitHub 仓库**　[numpy/numpy](<https://github.com/numpy/numpy>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [NumPy 发布包](<https://pypi.org/project/numpy/#files>)　可按 Python 版本和平台选择二进制包或源码分发包。
- [仓库源码 ZIP · numpy/numpy](<https://github.com/numpy/numpy/archive/d592eb072efbd8dcabb5d624ba3706e675ec3538.zip>)　该仓库的固定快照。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [scikit-learn](../scikit-learn/scikit-learn.md) · [SciPy](../SciPy/SciPy.md)
