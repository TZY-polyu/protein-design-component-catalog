# OpenMM

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

为分子力学系统计算能量和力，支持结构能量最小化及分子动力学模拟。

## 输入、输出与 LLM 参与

- **输入**　分子拓扑、初始坐标、选定的力场和系统定义。
- **输出**　视任务返回调整后的坐标、能量和力，或随时间记录的模拟轨迹。
- **LLM 参与**　由数值计算引擎执行，无需通用 LLM。

## 结果解读

BioDesignBench 将其列作能量最小化接口的后端。能量值依赖所选力场及建模条件。

## 在六篇研究中的用法

- **BioDesignBench**（运行时／结构计算）　补充A.2明确它是 energy_minimize 的计算后端，接口及其科学引擎可分别追溯。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Eastman & Pande (2010), OpenMM: A Hardware Independent Framework for Molecular Simulations.](<https://pmc.ncbi.nlm.nih.gov/articles/PMC4486654/>)
- **GitHub 仓库**　[openmm/openmm](<https://github.com/openmm/openmm>)
- **归属说明**　具名框架论文。Friedrichs 等（2009）另述早期 GPU 实现。

## 下载与访问

- [OpenMM 发布包](<https://pypi.org/project/OpenMM/#files>)　按操作系统与 Python 版本提供软件包。
- [仓库源码 ZIP · openmm/openmm](<https://github.com/openmm/openmm/archive/b5282630278e6c78e92691ed411543f73aabba75.zip>)　该仓库的固定快照。

## 关联组件

[energy_minimize](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/energy_minimize/energy_minimize.md)
