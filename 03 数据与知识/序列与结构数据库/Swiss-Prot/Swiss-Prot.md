# Swiss-Prot

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

提供 UniProtKB 中经过人工审阅的蛋白序列和功能注释，常用作参考序列或评价用参考库。

## 输入、输出与 LLM 参与

- **输入**　UniProt 登录号、蛋白名称、分类信息或数据库筛选条件。
- **输出**　审阅条目，含氨基酸序列、功能描述、证据、参考文献及交叉引用。
- **LLM 参与**　读取、筛选及导出记录无需 LLM。

## 结果解读

人工审阅反映注释流程。某一功能是否有直接实验支持，需要进一步读取该注释的证据标记。

## 在六篇研究中的用法

- **MAESD**（运行时知识。评测数据）　支持术语扩展、同源统计和参考标签，并用于 BLASTP 自然同源检索。

使用此来源的研究组件包括 [MAESD 测试集与同源过滤](../../%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Bairoch & Boeckmann (1991). The SWISS-PROT protein sequence data bank.](<https://doi.org/10.1093/nar/19.suppl.2247>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　数据库于 1986 年首次发布，1991 年为早期建库者专文。现为 UniProtKB 人工审阅部分。

## 下载与访问

- [Swiss-Prot 序列 FASTA](<https://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/complete/uniprot_sprot.fasta.gz>)　当前发行版的已审阅序列压缩文件。 此次连接超时，文件下载状态未确认。
- [Swiss-Prot 注释数据目录](<https://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/complete/>)　可选带注释的 DAT 或 XML 文件。 此次连接超时，文件下载状态未确认。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [UniProt](../UniProt/UniProt.md)
