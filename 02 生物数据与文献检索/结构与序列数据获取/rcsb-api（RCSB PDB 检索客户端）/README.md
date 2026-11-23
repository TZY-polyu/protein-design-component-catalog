# rcsb-api（RCSB PDB 检索客户端）

从 Python 查询 RCSB PDB 的结构标识符和元数据，可把数据库检索纳入数据处理脚本。

## 输入与输出

- **输入**　搜索条件或 PDB 标识符，以及要读取的数据字段。搜索条件可包含结构实体、实验方法或注释。
- **输出**　匹配的条目或实体标识符，以及查询所选的结构元数据。坐标文件可根据标识符另行获取。

## 接入条件

- **LLM 参与**　检索和结果解析无需 LLM。
- **运行条件**　Python 环境及对 RCSB 公共数据服务的网络访问。

这是查询客户端。检索覆盖范围随 RCSB 数据发布更新，复现分析时应记录查询和检索日期。

## 原始来源与公开实现

Piehl 等（2025），rcsb-api: Python Toolkit for Streamlining Access to RCSB Protein Data Bank APIs。

[论文或原始出版物](https://doi.org/10.1016/j.jmb.2025.168970)

- **GitHub 仓库**　[rcsb/py-rcsb-api](https://github.com/rcsb/py-rcsb-api)
- **实现入口**　[查看源代码](https://github.com/rcsb/py-rcsb-api/tree/master/rcsbapi)

RCSB PDB 维护的 Python 客户端。

## 下载

- [下载源码快照（ZIP）](https://github.com/rcsb/py-rcsb-api/archive/215a6f3ef97da6ac14a6370d9b99cd6e23ba610e.zip)　该链接固定到仓库中的一个提交。
- [rcsb-api 发行包](https://pypi.org/project/rcsb-api/#files)　Python 软件包。
