# SciPy

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

提供统计检验、概率分布、数值优化和线性代数等科学计算函数，支撑结果汇总与统计比较。

## 输入、输出与 LLM 参与

- **输入**　数值数组、配对观测、统计假设或指定函数的参数。
- **输出**　检验统计量和 p 值、相关系数，或相应数值例程的优化和求解结果。
- **LLM 参与**　无需 LLM。函数依据输入与设定的统计或数值规则运算。

## 结果解读

BioDesignBench 补充材料指明使用 SciPy 1.11。并列秩、缺失值和检验选项会影响部分统计结果。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录／计算层）　为模型特征和常规分析提供 CPU 运算。

使用此来源的研究组件包括 [BioDesignBench 配对检验与稳健性分析](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%9F%E8%AE%A1%E4%B8%8E%E6%AF%94%E8%BE%83%E6%96%B9%E6%B3%95/BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90/BioDesignBench%20%E9%85%8D%E5%AF%B9%E6%A3%80%E9%AA%8C%E4%B8%8E%E7%A8%B3%E5%81%A5%E6%80%A7%E5%88%86%E6%9E%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Virtanen et al. (2020), SciPy 1.0: fundamental algorithms for scientific computing in Python](<https://doi.org/10.1038/s41592-019-0686-2>)
- **GitHub 仓库**　[scipy/scipy](<https://github.com/scipy/scipy>)
- **归属说明**　SciPy 官方仓库。补充资料指明 v1.11。

## 下载与访问

- [SciPy 1.11 系列的发行文件](<https://pypi.org/project/scipy/1.11.4/#files>)　1.11.4 为该系列的一个可获取版本。论文未进一步锁定补丁号。
- [仓库源码 ZIP · scipy/scipy](<https://github.com/scipy/scipy/archive/2dd345a7824adb2af902d939a7ba9385c4de4351.zip>)　该仓库的固定快照。

## 关联组件

[NumPy](../NumPy/NumPy.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [scikit-learn](../scikit-learn/scikit-learn.md)
