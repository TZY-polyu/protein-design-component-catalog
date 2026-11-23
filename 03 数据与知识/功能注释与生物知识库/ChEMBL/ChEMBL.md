# ChEMBL

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

汇集公开研究中的化合物、靶标、实验与生物活性数据，便于按实体关联检索相关证据。

## 输入、输出与 LLM 参与

- **输入**　化合物、靶标或活性记录的标识符、关键词及查询条件。
- **输出**　与记录关联的结构、实验类型、活性值、单位和文献出处等。
- **LLM 参与**　数据库查询和数据导出不需要 LLM。

## 结果解读

不同实验的活性读数依赖测定条件和单位。官方 Python 仓库是访问客户端，完整数据库由 EMBL-EBI 单独分发。

## 在六篇研究中的用法

- **Latent-Y**（平台可用／知识检索）　作者列作可查询的数据源。未指明哪项案例实际调用。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Gaulton et al. (2012), ChEMBL: a large-scale bioactivity database for drug discovery](<https://doi.org/10.1093/nar/gkr777>)
- **GitHub 仓库**　[chembl/chembl_webresource_client](<https://github.com/chembl/chembl_webresource_client>)
- **归属说明**　官方 API 客户端。论文仅明确访问数据库。

## 下载与访问

- [ChEMBL 官方数据文件](<https://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBLdb/latest/>)　提供数据库转储、结构及序列等下载。 此次连接超时，文件下载状态未确认。
- [关联软件源码 ZIP · chembl/chembl_webresource_client](<https://github.com/chembl/chembl_webresource_client/archive/c71675979531218776107546451146a094930d6d.zip>)　该仓库的固定快照。
