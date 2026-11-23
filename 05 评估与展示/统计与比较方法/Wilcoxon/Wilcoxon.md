# Wilcoxon

[评估与展示](../../README.md) / 统计与比较方法

## 用途

用配对差值的方向与绝对差的秩检验两条件的差异，适合对同一任务在两种运行条件下的成绩作配对分析。

## 输入、输出与 LLM 参与

- **输入**　逐一配对的两组观测，或每一对的差值，以及备择假设和零差值处理方式。
- **输出**　秩统计量和相应 p 值，用于检验配对差值是否与以零为中心的对称分布相容。
- **LLM 参与**　无需 LLM，统计推断按秩完成。

## 结果解读

样本配对规则、重复值和零差值处理会改变结果，p 值也不能代替效应幅度。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 配对检验与稳健性分析](../BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90/BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Wilcoxon (1945), Individual Comparisons by Ranking Methods](<https://doi.org/10.2307/3001968>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　统计方法。P6 未披露具体软件包。

## 下载与访问

- [SciPy Wilcoxon 参考实现](<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.wilcoxon.html>)　提供配对符号秩检验选项。
- [可下载实现](<https://pypi.org/project/scipy/#files>)　SciPy 软件包。
