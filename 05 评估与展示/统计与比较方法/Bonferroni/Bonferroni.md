# Bonferroni

[评估与展示](../../README.md) / 统计与比较方法

## 用途

在一组假设检验中控制把至少一个真零假设误判为显著的总体风险。

## 输入、输出与 LLM 参与

- **输入**　待校正的一组原始 p 值、比较次数。或家族显著性水平和假设总数。
- **输出**　校正后的 p 值，或者每个检验适用的判定阈值。
- **LLM 参与**　确定性的统计校正，无需 LLM。

## 结果解读

结果取决于把哪些比较视为同一家族。该方法的数学出处与现代统计软件的实现应分别记录。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 配对检验与稳健性分析](../BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90/BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Bonferroni (1936), Teoria statistica delle classi e calcolo delle probabilità（不等式原理出处）](<https://books.google.com/books?id=3CY-HQAACAAJ>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　该出处为不等式专著书目。本组论文将它用于多重比较校正。

## 下载与访问

- [R 统计库的 Bonferroni 实现说明](<https://stat.ethz.ch/R-manual/R-devel/library/stats/html/p.adjust.html>)　基础统计软件的标准实现示例，方法本身没有单独安装包。
