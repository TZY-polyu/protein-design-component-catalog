# Biotite

为 Python 提供蛋白序列、分子结构和文件格式处理功能，可支持结构数据读写、选择与几何分析。

## 输入与输出

- **输入**　序列、坐标文件，或已载入的原子数组及分析条件。
- **输出**　序列对象、原子数组、结构或比对分析结果及导出文件。

## 接入条件

- **LLM 参与**　数据读写和数值运算无需通用 LLM。
- **运行条件**　需 Python 及兼容的 Biotite 发行包。读取本地结构无需联网，查询 AlphaFold DB 等远程数据库时需联网。

比较坐标或导出文件时，需保留相应的模型、原子和链标识，以免误配条目。

## 原始来源与公开实现

Kunzmann & Hamacher (2018), Biotite: a unifying open source computational biology framework in Python

[论文或原始出版物](https://doi.org/10.1186/s12859-018-2367-z)

- **GitHub 仓库**　[biotite-dev/biotite](https://github.com/biotite-dev/biotite)
- **实现入口**　[查看源代码](https://github.com/biotite-dev/biotite)

作者工具仓库。

## 下载

- [Biotite 官方发布包](https://pypi.org/project/biotite/#files)　PyPI 提供源码和适配各平台的 Python 安装包。
- [AlphaFold DB 结构获取函数](https://www.biotite-python.org/latest/apidoc/biotite.database.afdb.fetch.html)　Biotite 以公开客户端代码按 UniProt ID 从 AlphaFold DB 获取预测结构。
- [项目源码 ZIP](https://github.com/biotite-dev/biotite/archive/2effe8f30543602fc9ee58759a4e16066062b290.zip)　公开项目的源码快照。
