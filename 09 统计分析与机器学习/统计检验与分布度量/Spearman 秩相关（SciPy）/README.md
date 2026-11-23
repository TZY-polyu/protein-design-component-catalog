# Spearman 秩相关（SciPy）

把成对观察转换成秩，再衡量两组排名的单调关联，可比较预测分数与实测标签的排序一致性。

## 输入与输出

- **输入**　针对同一批对象配对的两列数值，或已正确对应的两组秩。
- **输出**　Spearman 秩相关系数。带推断功能的实现可另给 p 值。

## 接入条件

- **LLM 参与**　无需 LLM，依据对应样本的秩计算。
- **运行条件**　Python 与 SciPy。两列数据应按同一批观测对应，常量列的相关系数没有定义。

接近 1 表明排序高度一致，即使预测数值与真实数值之间仍存在明显尺度差异。

**最小运行核验**　SciPy 1.17.1 以两组各 4 个观测计算 Spearman 秩相关，得到 ρ = −0.4、p = 0.6。

## 原始来源与公开实现

Spearman (1904), The Proof and Measurement of Association between Two Things

[论文或原始出版物](https://doi.org/10.2307/1412159)

- **GitHub 仓库**　[scipy/scipy](https://github.com/scipy/scipy)
- **实现入口**　[查看源代码](https://github.com/scipy/scipy/blob/v1.18.0/scipy/stats/_stats_py.py)

SciPy 提供 spearmanr。Spearman 的论文提出统计方法，现代 Python 代码由 SciPy 维护。

## 下载

- [SciPy 发行包](https://pypi.org/project/scipy/#files)　包含 scipy.stats.spearmanr。
- [函数参考](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.spearmanr.html)　输入形状、缺失值及返回值的定义。
- [下载本次索引的源码快照（ZIP）](https://github.com/scipy/scipy/archive/2dd345a7824adb2af902d939a7ba9385c4de4351.zip)
