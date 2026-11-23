# Bonferroni 多重检验校正

在一组假设检验中控制把至少一个真零假设误判为显著的总体风险。

## 输入与输出

- **输入**　待校正的一组原始 p 值、比较次数。或家族显著性水平和假设总数。
- **输出**　校正后的 p 值，或者每个检验适用的判定阈值。

## 接入条件

- **LLM 参与**　确定性的统计校正，无需 LLM。
- **运行条件**　采用此公开实现需 Python、statsmodels 及其数值库依赖，另需提供待校正的同一组 p 值。

结果取决于把哪些比较视为同一家族。该方法的数学出处与现代统计软件的实现应分别记录。

## 原始来源与公开实现

Dunn（1961），Multiple Comparisons Among Means，介绍 Bonferroni 不等式在多重比较中的应用。不等式本身见 Bonferroni（1936）。

[论文或原始出版物](https://doi.org/10.1080/01621459.1961.10482090)

- **GitHub 仓库**　[statsmodels/statsmodels](https://github.com/statsmodels/statsmodels)
- **实现入口**　[查看源代码](https://github.com/statsmodels/statsmodels/blob/main/statsmodels/stats/multitest.py)

statsmodels 的 multipletests 是该经典统计方法的现代可运行实现。

## 下载

- [statsmodels 安装包](https://pypi.org/project/statsmodels/#files)　包含多重检验校正模块。
- [下载项目源码（ZIP）](https://github.com/statsmodels/statsmodels/archive/HEAD.zip)
