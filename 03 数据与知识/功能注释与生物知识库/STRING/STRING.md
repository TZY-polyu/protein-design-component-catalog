# STRING

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

整合多类证据，为蛋白之间的功能关联分配置信度，支持从蛋白名称或标识查找关联网络。

## 输入、输出与 LLM 参与

- **输入**　蛋白标识或基因名称、物种及需要查看的证据类别。
- **输出**　蛋白关联边、置信度和可用证据通道，也可下载完整物种网络。
- **LLM 参与**　数据库查询和分数读取无需 LLM。

## 结果解读

STRING 的边可以来自功能关联、共同通路或其他证据。有边不能单独证明两种蛋白直接物理结合。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　查询已知或预测的蛋白关联。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Snel et al. (2000), STRING: a web-server to retrieve and display the repeatedly occurring neighbourhood of a gene](<https://doi.org/10.1093/nar/28.18.3442>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　早期 STRING 网络资源论文。数据源与后续版本见 string-db.org。

## 下载与访问

- [STRING 官方网络下载](<https://string-db.org/cgi/download>)　可按物种、证据及文件类型选择数据。

## 关联组件

[STRING DB MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/STRING%20DB%20MCP/STRING%20DB%20MCP.md)
