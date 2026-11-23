# MMseqs2

[科学模型与计算](../../README.md) / 序列检索与注释

## 用途

从大型序列库中搜索相似条目，也能对序列聚类，为同源分析或多序列比对提供候选。

## 输入、输出与 LLM 参与

- **输入**　查询序列、待搜索的蛋白或核酸序列库。按任务选择检索或聚类。
- **输出**　相似序列命中名单、比对区间及统计量，或以代表序列标记的聚类结果。
- **LLM 参与**　使用序列搜索与比对算法，无需通用 LLM。

## 结果解读

命中受检索库版本与序列覆盖范围影响。ProteinMCP、Latent-Y 的调用侧重不同，使用情形见下方记录。

## 在六篇研究中的用法

- **ProteinMCP**（架构列为 MSA 工具与后端）　快速序列搜索和聚类，支持 MSA 构建。
- **Latent-Y**（平台可用／序列比较）　高通量序列相似性检索。论文未把每次检索指派到具体程序。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Steinegger & Söding (2017), MMseqs2 enables sensitive protein sequence searching for the analysis of massive data sets](<https://doi.org/10.1038/nbt.3988>)
- **GitHub 仓库**　[soedinglab/MMseqs2](<https://github.com/soedinglab/MMseqs2>)
- **归属说明**　作者工具仓库。

## 下载与访问

- [官方编译版](<https://github.com/soedinglab/MMseqs2/releases>)　发布页列出适用于不同操作系统和处理器的包及源码。
- [仓库源码 ZIP · soedinglab/MMseqs2](<https://github.com/soedinglab/MMseqs2/archive/ae60ef6964f3de689139bcfe290d9fad18f70b06.zip>)　该仓库的固定快照。

## 关联组件

[MMseqs2 MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/MMseqs2%20MCP/MMseqs2%20MCP.md) · [MSA MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/MSA%20MCP/MSA%20MCP.md)
