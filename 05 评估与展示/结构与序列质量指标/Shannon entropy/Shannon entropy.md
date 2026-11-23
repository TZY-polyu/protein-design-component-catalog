# Shannon entropy

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

以类别概率分布计算不确定性或组成多样性，BioDesignBench 在其评测口径下使用序列熵。

## 输入、输出与 LLM 参与

- **输入**　类别概率或可转为概率的计数，例如序列中各氨基酸出现的频数。
- **输出**　一个非负标量。对数底数决定单位，若再归一化则同时取决于所选类别集合。
- **LLM 参与**　无需 LLM。计算依赖概率分布和对数运算。

## 结果解读

不同序列的熵可以相同。组成熵描述频率分布，不包含残基顺序或三维结构信息。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 六维评分表](../../%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E5%85%AD%E7%BB%B4%E8%AF%84%E5%88%86%E8%A1%A8/BioDesignBench%20%E5%85%AD%E7%BB%B4%E8%AF%84%E5%88%86%E8%A1%A8.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Shannon (1948), A Mathematical Theory of Communication](<https://doi.org/10.1002/j.1538-7305.1948.tb01338.x>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　信息熵的原始理论论文。P6 定义序列层面的归一化和评分。

## 下载与访问

- [SciPy 统计实现说明](<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.entropy.html>)　通用实现。研究自定义的归一化与评分另见基准代码。
- [SciPy 分发包](<https://pypi.org/project/scipy/#files>)　可下载含统计函数的实现。
