# BoltzGen

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

按指定分子背景和约束进行生成式设计，产生待评估的蛋白或肽候选。

## 输入、输出与 LLM 参与

- **输入**　对象及其分子表示、候选类型与研究约束的结构化描述。
- **输出**　带有序列与坐标的候选结构，以及流程提供的指标或排序信息。
- **LLM 参与**　运行专用生成模型，内部生成与评分不需要通用 LLM。智能体可在外层提交和查询作业。

## 结果解读

BoltzGen 与同名家族的 Boltz-2 解决不同问题。生成候选的结构或排名本身不能确定实验表现。

## 在六篇研究中的用法

- **ProteinMCP**（案例3计算流程）　计算生成与筛选纳米抗体候选。

使用此来源的研究组件包括 [ProteinMCP 纳米抗体质量与结构展示](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/ProteinMCP%20%E7%BA%B3%E7%B1%B3%E6%8A%97%E4%BD%93%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%BB%93%E6%9E%84%E5%B1%95%E7%A4%BA/ProteinMCP%20%E7%BA%B3%E7%B1%B3%E6%8A%97%E4%BD%93%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%BB%93%E6%9E%84%E5%B1%95%E7%A4%BA.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Stark et al. (2025), BoltzGen: Toward Universal Binder Design](<https://doi.org/10.1101/2025.11.20.689494>)
- **GitHub 仓库**　[HannesStark/boltzgen](<https://github.com/HannesStark/boltzgen>)
- **归属说明**　作者仓库与预印本。区别于 Boltz-2。

## 下载与访问

- [作者发布的 BoltzGen 模型文件](<https://huggingface.co/boltzgen/boltzgen-1/tree/main>)　按模型卡和相应使用条件获取权重。
- [仓库源码 ZIP · HannesStark/boltzgen](<https://github.com/HannesStark/boltzgen/archive/6472b44e8072187e6eaa51271ae6838245206013.zip>)　该仓库的固定快照。

## 关联组件

[BoltzGen MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/BoltzGen%20MCP/BoltzGen%20MCP.md)
