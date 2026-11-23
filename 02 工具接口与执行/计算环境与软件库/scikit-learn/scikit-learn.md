# scikit-learn

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

提供统一的特征预处理、监督学习、模型选择和性能评估接口，便于比较科学数据上的多个回归器。

## 输入、输出与 LLM 参与

- **输入**　训练特征矩阵、标签以及估计器设置。预测时输入与训练定义一致的特征。
- **输出**　已拟合的估计器、预测数组、交叉验证结果或评价指标。
- **LLM 参与**　软件库及传统回归器无需 LLM，特征可由外部模型预先生成。

## 结果解读

在 ProteinMCP 中它属于计算后端。仅据库名无法确定某一个回归分析使用的全部实现细节。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录／计算层）　为模型特征和常规分析提供 CPU 运算。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Pedregosa et al. (2011), Scikit-learn: Machine Learning in Python](<https://www.jmlr.org/papers/v12/pedregosa11a.html>)
- **GitHub 仓库**　[scikit-learn/scikit-learn](<https://github.com/scikit-learn/scikit-learn>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [scikit-learn 发行文件](<https://pypi.org/project/scikit-learn/#files>)　选择适配本地 Python 和平台的二进制包或源码包。
- [仓库源码 ZIP · scikit-learn/scikit-learn](<https://github.com/scikit-learn/scikit-learn/archive/21626d67d47889da8d19f3dd2a819a0cf527f27f.zip>)　该仓库的固定快照。

## 关联组件

[NumPy](../NumPy/NumPy.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [SciPy](../SciPy/SciPy.md)
