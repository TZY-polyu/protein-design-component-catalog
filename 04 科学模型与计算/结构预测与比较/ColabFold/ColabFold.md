# ColabFold

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

把同源序列检索、序列比对和结构预测后端串接起来。可只调用其比对服务，也可完成结构预测。

## 输入、输出与 LLM 参与

- **输入**　蛋白质序列或链组。也可输入预先计算的多序列比对。
- **输出**　单独检索时返回多序列比对。运行预测后返回三维坐标、预测置信度及相关结果文件。
- **LLM 参与**　这些计算无需通用 LLM。智能体可通过封装调用 ColabFold。

## 结果解读

需要确认论文使用的环节。ProteinMCP 在 MSA 环节提到 ColabFold，生成比对并不等于已执行结构预测。

## 在六篇研究中的用法

- **ProteinMCP**（架构列为 MSA 后端，未逐次标明调用）　在 MSA 服务中提供检索与比对能力。
- **BioDesignBench**（运行时／结构预测）　ColabFold/AF2 是容器依赖。补充A.5把 AF2 与 AF2-Multimer 写作独立质量核验工具，与正文及补充D所写的 Boltz-2 并列记录。

使用此来源的研究组件包括 [BioDesignBench 结构质量独立复算](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Mirdita et al. (2022), ColabFold: making protein folding accessible to all](<https://doi.org/10.1038/s41592-022-01488-1>)
- **GitHub 仓库**　[sokrypton/ColabFold](<https://github.com/sokrypton/ColabFold>)
- **归属说明**　作者工具仓库。为调用结构预测提供另一实现与入口。

## 下载与访问

- [ColabFold 软件发布](<https://github.com/sokrypton/ColabFold/releases>)　作者发布的版本和变更记录。预测后端的参数有独立来源。
- [仓库源码 ZIP · sokrypton/ColabFold](<https://github.com/sokrypton/ColabFold/archive/eb061aa6706959fdffe15e86d27ca08083d6ed8d.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold-Multimer](../AlphaFold-Multimer/AlphaFold-Multimer.md) · [AlphaFold2](../AlphaFold2/AlphaFold2.md) · [MSA MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/MSA%20MCP/MSA%20MCP.md)
