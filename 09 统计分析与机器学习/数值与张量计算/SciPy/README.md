# SciPy

提供统计检验、概率分布、数值优化和线性代数等科学计算函数，支撑结果汇总与统计比较。

## 输入与输出

- **输入**　数值数组、配对观测、统计假设或指定函数的参数。
- **输出**　检验统计量和 p 值、相关系数，或相应数值例程的优化和求解结果。

## 接入条件

- **LLM 参与**　无需 LLM。函数依据输入与设定的统计或数值规则运算。
- **运行条件**　与目标平台兼容的 Python、NumPy 和 SciPy 安装包。

具体返回值、缺失值处理和统计假设由所选函数决定。报告结果时记录函数名及与解读相关的选项。

**最小运行核验**　SciPy 1.17.1 以两组各 4 个观测计算 Spearman 秩相关，得到 ρ = −0.4、p = 0.6。

## 原始来源与公开实现

Virtanen et al. (2020), SciPy 1.0: fundamental algorithms for scientific computing in Python

[论文或原始出版物](https://doi.org/10.1038/s41592-019-0686-2)

- **GitHub 仓库**　[scipy/scipy](https://github.com/scipy/scipy)
- **实现入口**　[查看源代码](https://github.com/scipy/scipy)

SciPy 官方数值与统计计算库。

## 下载

- [下载源码快照（ZIP）](https://github.com/scipy/scipy/archive/2dd345a7824adb2af902d939a7ba9385c4de4351.zip)　该链接固定到仓库中的一个提交。
- [SciPy 发行文件](https://pypi.org/project/scipy/#files)　包含受支持环境下的 wheel 或源码包。
