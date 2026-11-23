# UniProt

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

汇集蛋白质序列、功能注释及跨数据库标识，可用来核实研究对象、语义标签或序列信息。

## 输入、输出与 LLM 参与

- **输入**　条目标识、蛋白名、物种、功能或组合查询条件。
- **输出**　匹配条目的序列、功能描述、证据、注释与参考文献。可导出多种结构化格式。
- **LLM 参与**　数据库读写接口无需通用 LLM。智能体可代为检索并解读条目。

## 结果解读

使用 UniProtKB 时应分清人工审阅的 Swiss-Prot 与自动注释的 TrEMBL，并记录检索版本。

## 在六篇研究中的用法

- **MAESD**（运行时知识。评测数据）　支持术语扩展、同源统计和参考标签，并用于 BLASTP 自然同源检索。
- **ProteinMCP**（架构目录。输入输出按功能归纳）　查找蛋白条目和相关知识。
- **Latent-Y**（在线取数）　核对目标身份与生物学注释。

使用此来源的研究组件包括 [MAESD 测试集与同源过滤](../../%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4.md)、[MAESD 意图识别标签评测](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%A0%87%E7%AD%BE%E8%AF%84%E6%B5%8B/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%A0%87%E7%AD%BE%E8%AF%84%E6%B5%8B.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Apweiler 等 (2004). UniProt: the Universal Protein knowledgebase.](<https://doi.org/10.1093/nar/gkh131>)
- **GitHub 仓库**　[ebi-uniprot/uniprot-rest-api](<https://github.com/ebi-uniprot/uniprot-rest-api>)
- **归属说明**　UniProt 首篇数据库论文。GitHub 为官方 REST API 后端，数据由 UniProt 网站发布。

## 下载与访问

- [UniProtKB 官方批量文件](<https://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/complete/>)　提供分开发布的 Swiss-Prot、TrEMBL 序列和注释。 此次连接超时，文件下载状态未确认。
- [关联软件源码 ZIP · ebi-uniprot/uniprot-rest-api](<https://github.com/ebi-uniprot/uniprot-rest-api/archive/8073ae7918cd1b6622b1f322fecb2ada553f4f1c.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [Swiss-Prot](../Swiss-Prot/Swiss-Prot.md) · [UniProt MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/UniProt%20MCP/UniProt%20MCP.md)
