# ChEMBL 数据服务

以程序化方式查询 ChEMBL 的化合物、靶标、测定及生物活性记录。

## 输入与输出

- **输入**　化合物、靶标或活性记录的标识符、关键词及查询条件。
- **输出**　与记录关联的结构、实验类型、活性值、单位和文献出处等。

## 接入条件

- **LLM 参与**　数据库查询及结果序列化无需 LLM。
- **运行条件**　使用公共服务需要联网，自建服务需匹配的数据库与运行依赖。

活性值的解释取决于测定类型、单位和实验条件。

## 原始来源与公开实现

Davies 等（2015），ChEMBL web services: streamlining access to drug discovery data and utilities。底层数据库由 Gaulton 等（2012）介绍。

[论文或原始出版物](https://doi.org/10.1093/nar/gkv352)

- **GitHub 仓库**　[chembl/chembl_webservices_2](https://github.com/chembl/chembl_webservices_2)
- **实现入口**　[查看源代码](https://github.com/chembl/chembl_webservices_2)

ChEMBL 项目组公开的服务端实现，另提供官方 Python 客户端。

## 下载

- [ChEMBL 官方数据文件](https://ftp.ebi.ac.uk/pub/databases/chembl/ChEMBLdb/latest/)　提供数据库转储、结构及序列等下载。
- [服务端源码 ZIP](https://github.com/chembl/chembl_webservices_2/archive/refs/heads/master.zip)　官方服务端代码快照。
- [官方 Python 客户端](https://github.com/chembl/chembl_webresource_client)　用于访问部署好的数据服务。
