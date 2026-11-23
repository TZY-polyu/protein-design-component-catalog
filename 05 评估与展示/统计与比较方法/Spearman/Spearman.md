# Spearman

[评估与展示](../../README.md) / 统计与比较方法

## 用途

把成对观察转换成秩，再衡量两组排名的单调关联，可比较预测分数与实测标签的排序一致性。

## 输入、输出与 LLM 参与

- **输入**　针对同一批对象配对的两列数值，或已正确对应的两组秩。
- **输出**　Spearman 秩相关系数。带推断功能的实现可另给 p 值。
- **LLM 参与**　无需 LLM，依据对应样本的秩计算。

## 结果解读

接近 1 表明排序高度一致，即使预测数值与真实数值之间仍存在明显尺度差异。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinMCP 适应度交叉验证](../../%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/ProteinMCP%20%E9%80%82%E5%BA%94%E5%BA%A6%E4%BA%A4%E5%8F%89%E9%AA%8C%E8%AF%81/ProteinMCP%20%E9%80%82%E5%BA%94%E5%BA%A6%E4%BA%A4%E5%8F%89%E9%AA%8C%E8%AF%81.md)、[BioDesignBench 配对检验与稳健性分析](../BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90/BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Spearman (1904), The Proof and Measurement of Association between Two Things](<https://doi.org/10.2307/1412159>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　统计方法。P6 未披露具体软件包。

## 下载与访问

- [SciPy 参考实现](<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.spearmanr.html>)　含并列秩及返回值说明。该实现不代表所有论文的实际调用。
- [可下载实现](<https://pypi.org/project/scipy/#files>)　SciPy 软件包。
