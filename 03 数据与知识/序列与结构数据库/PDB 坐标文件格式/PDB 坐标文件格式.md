# PDB 坐标文件格式

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

规定传统 PDB 文本记录怎样表示分子结构及元数据，使不同软件能够识别相同字段。

## 输入、输出与 LLM 参与

- **输入**　待表示的原子坐标、残基与链标识，以及相关结构记录。
- **输出**　符合固定列规则的 .pdb 文本，或解析后得到的坐标、标识与关联字段。
- **LLM 参与**　文件格式自身无需语言模型。

## 结果解读

AutoBinder 接受用户给定的坐标文件。一个符合该格式的文件可以来自实验、计算或本地编辑，来源要另行核实。

## 在六篇研究中的用法

- **AutoBinder Agent**（工作流输入）　提供案例的结构输入。表I也以 PDB 文件描述请求。

## 原始来源与 GitHub

- **原始文献或官方出处**　[wwPDB, Protein Data Bank Contents Guide: Atomic Coordinate Entry Format Description（格式规范）](<https://www.wwpdb.org/documentation/file-format-content/format33/v3.3.html>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　wwPDB 官方格式规范。坐标文件是数据输入。

## 下载与访问

- [wwPDB 格式规范](<https://www.wwpdb.org/documentation/file-format-content/format33/v3.3.html>)　按记录类型给出字段定义和示例。
- [结构文件下载入口](<https://www.wwpdb.org/ftp/pdb-ftp-sites>)　具体条目的可用文件格式依档案记录而定。 此次连接超时，文件下载状态未确认。

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
