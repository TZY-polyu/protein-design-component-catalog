# 香农熵（SciPy entropy）

根据类别出现频率计算分布的不确定性。例如可把每种氨基酸的计数转换成一个组成多样性指标。

## 输入与输出

- **输入**　类别概率或可转为概率的计数，例如序列中各氨基酸出现的频数。
- **输出**　一个非负标量。对数底数决定单位，若再归一化则同时取决于所选类别集合。

## 接入条件

- **LLM 参与**　无需 LLM。计算依赖概率分布和对数运算。
- **运行条件**　Python 和 SciPy。比较不同样本时需要使用相同的类别定义、计数规则和对数底。

组成熵只取决于类别频率。调换同一组残基的排列，组成熵保持不变。

## 原始来源与公开实现

Shannon (1948), A Mathematical Theory of Communication

[论文或原始出版物](https://doi.org/10.1002/j.1538-7305.1948.tb01338.x)

- **GitHub 仓库**　[scipy/scipy](https://github.com/scipy/scipy)
- **实现入口**　[查看源代码](https://github.com/scipy/scipy/blob/main/scipy/stats/_entropy.py)

SciPy 对这一信息论指标的公开实现。原始方法来自 Shannon 1948 年论文。

## 下载

- [下载源码快照（ZIP）](https://github.com/scipy/scipy/archive/2dd345a7824adb2af902d939a7ba9385c4de4351.zip)　该链接固定到仓库中的一个提交。
- [SciPy 统计实现说明](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.entropy.html)　通用实现。研究自定义的归一化与评分另见基准代码。
- [SciPy 分发包](https://pypi.org/project/scipy/#files)　可下载含统计函数的实现。
