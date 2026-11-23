# Pingouin

为实验比较提供统计检验、效应量与相关分析，便于用统一的表格格式记录结果。

## 输入与输出

- **输入**　样本观测值、组别或配对标识，以及所选检验需要的变量。
- **输出**　统计量、自由度、p 值、效应量或区间估计，字段依具体方法而变。

## 接入条件

- **LLM 参与**　统计程序无需通用 LLM。
- **运行条件**　Python 与该版本声明的数值和统计依赖。

比较实验组时，根据观测值是否配对以及分布假设选择检验，并同时报告效应量和不确定性。

## 原始来源与公开实现

Vallat (2018), Pingouin: statistics in Python

[论文或原始出版物](https://doi.org/10.21105/joss.01026)

- **GitHub 仓库**　[raphaelvallat/pingouin](https://github.com/raphaelvallat/pingouin)
- **实现入口**　[查看源代码](https://github.com/raphaelvallat/pingouin/tree/3d4db6573fb76e6aa2580b6ff8d797a874c5e147/src/pingouin)

软件作者发布的统计库源码。

## 下载

- [Pingouin 发布包](https://pypi.org/project/pingouin/#history)　可选历史版本，再从对应版本的下载文件区获取软件。
- [固定版本源码 ZIP](https://github.com/raphaelvallat/pingouin/archive/3d4db6573fb76e6aa2580b6ff8d797a874c5e147.zip)　包含上述实现及其同仓库配套文件。
