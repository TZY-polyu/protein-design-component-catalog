# Biomni

用通用 LLM 对生物医学任务进行规划，并调用计算工具、数据库或程序执行相应分析。

## 输入与输出

- **输入**　研究者的自然语言问题、可用数据资源以及配置的模型与工具。
- **输出**　分析结果、程序执行产物和推理说明，具体类型由任务决定。

## 接入条件

- **LLM 参与**　通用 LLM 参与规划和解释。外部数据库和计算工具独立执行各自功能。
- **运行条件**　需要可用的模型后端及所选任务依赖的外部工具。

分析所需的数据和外部工具依任务而定。编排实现、各工具和模型服务有各自的访问条件。

## 原始来源与公开实现

Huang et al. (2025), Biomni: A General-Purpose Biomedical AI Agent

[论文或原始出版物](https://doi.org/10.1101/2025.05.30.656746)

- **GitHub 仓库**　[snap-stanford/biomni](https://github.com/snap-stanford/biomni)
- **实现入口**　[查看源代码](https://github.com/snap-stanford/biomni)

上游作者仓库

## 下载

- [斯坦福项目入口](https://biomni.stanford.edu/)　查看作者发布的软件、平台和配套资料。
- [项目源码 ZIP](https://github.com/snap-stanford/Biomni/archive/77488682d7f687486742a19f5177a1ea37cfb698.zip)　公开项目的源码快照。
