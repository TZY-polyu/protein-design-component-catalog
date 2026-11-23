# UniRef

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

将相近的蛋白序列归入簇，提供不同聚类粒度下的代表序列，降低大规模序列集合中的冗余。

## 输入、输出与 LLM 参与

- **输入**　蛋白序列标识、UniRef 簇号，或按 UniRef100、90、50 选定的整库发行版。
- **输出**　代表序列、簇标识、成员集合及其对应关系，可导出 FASTA 或 XML。
- **LLM 参与**　数据库检索及既有聚类数据的使用无需 LLM。

## 结果解读

簇代表表达的是序列相似关系。同簇成员能否共享某项具体功能，仍需相应注释或独立证据。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录／计算层。输入输出按功能归纳）　为相似序列搜索提供去冗余参考集合。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Suzek 等，UniRef: comprehensive and non-redundant UniProt reference clusters（2007）](<https://doi.org/10.1093/bioinformatics/btm098>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　UniProt 提供的序列聚类数据资源。

## 下载与访问

- [EMBL-EBI UniRef 下载中心](<https://www.ebi.ac.uk/uniprot/download-center>)　提供各聚类级别的 FASTA 与 XML 文件入口。

## 关联组件

[UniProt](../UniProt/UniProt.md)
