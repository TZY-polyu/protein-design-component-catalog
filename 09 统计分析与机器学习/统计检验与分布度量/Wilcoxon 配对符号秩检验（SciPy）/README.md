# Wilcoxon 配对符号秩检验（SciPy）

用配对差值的方向与绝对差的秩检验两条件的差异，适合对同一任务在两种运行条件下的成绩作配对分析。

## 输入与输出

- **输入**　逐一配对的两组观测，或每一对的差值，以及备择假设和零差值处理方式。
- **输出**　秩统计量和相应 p 值，用于检验配对差值是否与以零为中心的对称分布相容。

## 接入条件

- **LLM 参与**　无需 LLM，统计推断按秩完成。
- **运行条件**　Python 与 SciPy，需要可一一对应的两组观测或预先求好的差值。

样本配对规则、重复值和零差值处理会改变结果，p 值也不能代替效应幅度。

## 原始来源与公开实现

Wilcoxon (1945), Individual Comparisons by Ranking Methods

[论文或原始出版物](https://doi.org/10.2307/3001968)

- **GitHub 仓库**　[scipy/scipy](https://github.com/scipy/scipy)
- **实现入口**　[查看源代码](https://github.com/scipy/scipy/blob/v1.18.0/scipy/stats/_morestats.py)

SciPy 提供 scipy.stats.wilcoxon 函数，原始统计方法来自 Wilcoxon 1945 年论文。

## 下载

- [SciPy 发行包](https://pypi.org/project/scipy/#files)　可下载源代码包或匹配平台的安装包。
- [函数参数及统计含义](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.wilcoxon.html)　说明差值、零值和备择假设的处理。
- [下载本次索引的源码快照（ZIP）](https://github.com/scipy/scipy/archive/2dd345a7824adb2af902d939a7ba9385c4de4351.zip)
