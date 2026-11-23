# BioDesignBench 配对检验与稳健性分析

[评估与展示](../../README.md) / 统计与比较方法

## 用途

正文有 Wilcoxon、Bonferroni 与 Spearman。补充B另用 Kruskal–Wallis、Mann–Whitney U、Cohen’s d 等，注明 SciPy 1.11 与 Pingouin 0.5。

## 输入、输出与 LLM 参与

- **输入**　各任务和条件的评分、评估指标类别数与行为量。
- **输出**　Wilcoxon 配对检验、Bonferroni 校正、Spearman 相关及排除部分条件后的分析结果。
- **LLM 参与**　否（统计分析）

## 结果解读

比较和相关分析的对象是任务得分与运行行为。应注明分析单元、检验名称及多重比较校正。正文与补充方法对部分检验的称谓有差异。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为结果分析。

## 原始来源与 GitHub

- **Wilcoxon 的原始出处**　[Wilcoxon (1945), Individual Comparisons by Ranking Methods](<https://doi.org/10.2307/3001968>)
- **Spearman 的原始出处**　[Spearman (1904), The Proof and Measurement of Association between Two Things](<https://doi.org/10.2307/1412159>)
- **Bonferroni 的原始出处**　[Bonferroni (1936), Teoria statistica delle classi e calcolo delle probabilità（不等式原理出处）](<https://books.google.com/books?id=3CY-HQAACAAJ>)
- **SciPy 的原始出处**　[Virtanen et al. (2020), SciPy 1.0: fundamental algorithms for scientific computing in Python](<https://doi.org/10.1038/s41592-019-0686-2>)
- **Pingouin 的原始出处**　[Vallat (2018), Pingouin: statistics in Python](<https://doi.org/10.21105/joss.01026>)
- **本研究中的用法**　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　既有统计检验与软件。正文和补充B对跨条件两两检验名称记载不同，干预的配对分析另见图4。

## 下载与访问

- [下载 statistics.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/statistics.py>)　该项目的源码文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Bonferroni](../Bonferroni/Bonferroni.md) · [Pingouin](../Pingouin/Pingouin.md) · [SciPy](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/SciPy/SciPy.md) · [Spearman](../Spearman/Spearman.md) · [Wilcoxon](../Wilcoxon/Wilcoxon.md)
