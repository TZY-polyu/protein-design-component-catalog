# KEGG

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

组织基因、同源功能组、化合物、反应和通路之间的人工整理关系，用于查询对象的代谢或通路背景。

## 输入、输出与 LLM 参与

- **输入**　KEGG 标识符、基因或化合物名、物种与通路等查询条件。
- **输出**　匹配的条目、通路图或结构化通路文件，以及相关对象之间的链接。
- **LLM 参与**　数据库查询无需 LLM。

## 结果解读

不同物种可以映射到共同的通路框架。解释某个基因是否参与特定过程时，应同时核对物种和功能证据。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　检索生物通路背景。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Kanehisa (1996), Toward Pathway Engineering: A New Database of Genetic and Molecular Pathways](<https://www.kanehisa.jp/docs/archive/stj.pdf>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　KEGG 官方书目第 1 项。项目始于 1995 年。1997 年和 2000 年另有数据库专文。

## 下载与访问

- [KEGG 官方批量数据与许可](<https://www.kegg.jp/kegg/download/>)　完整 FTP 数据涉及订阅或许可。页面区分各数据获取路径。

## 关联组件

[KEGG MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/KEGG%20MCP/KEGG%20MCP.md)
