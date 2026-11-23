# BioDesignBench（评测代码）

按共同规则给蛋白设计任务的结果评分，汇总工具调用记录和系统行为指标。

## 输入与输出

- **输入**　任务规范、候选提交、工具调用轨迹，以及部分评分所需的参照信息。
- **输出**　任务级或系统级评分、行为指标、分组比较和可展示的基准结果。

## 接入条件

- **LLM 参与**　结构或序列指标可独立计算，完整评分中的文本评审部分使用 LLM 评委。
- **运行条件**　可用公开示例运行评分代码。正式任务集通过作者的受控评测服务访问。

作者公开了评分与分析代码及示例任务。正式榜单的完整题目输入、参考答案及 oracle 输出未公开。

## 原始来源与公开实现

Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design

[论文或原始出版物](https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1)

- **GitHub 仓库**　[RomeroLab/BioDesignBench](https://github.com/RomeroLab/BioDesignBench)
- **实现入口**　[查看源代码](https://github.com/RomeroLab/BioDesignBench/tree/main/biodesignbench/eval)

作者发布的评测代码、分析程序和演示任务。

## 下载

- [基准代码与资料的发布说明](https://github.com/RomeroLab/BioDesignBench#readme)　在项目说明中核对公开的代码和受限制的逐题材料。
- [项目源码 ZIP](https://github.com/RomeroLab/BioDesignBench/archive/718e452e3f73f8be423e954b6c05f3aa3f42859c.zip)　公开项目的源码快照。
