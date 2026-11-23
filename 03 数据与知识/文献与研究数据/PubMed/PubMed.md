# PubMed

[数据与知识](../../README.md) / 文献与研究数据

## 用途

检索生物医学论文及其书目信息，为文献检索界面和研究智能体提供可追溯的文献记录。

## 输入、输出与 LLM 参与

- **输入**　疾病、基因或主题关键词，作者、日期条件或 PubMed 标识符 PMID。
- **输出**　命中文献的 PMID、题名、作者、期刊、摘要（若提供）与外部全文链接。批量记录为 XML。
- **LLM 参与**　数据库检索和导出无需 LLM，智能体可生成查询或解释结果。

## 结果解读

PubMed 收录的是引文记录。涉及具体实验结论时，还要查看记录所指的全文。

## 在六篇研究中的用法

- **Latent-Y**（在线文献检索）　为机制判断和文献核查提供来源。作者参考文献 41 与 45 均指向 PubMed。

## 原始来源与 GitHub

- **原始论文或方法出处**　[美国国家医学图书馆 / NCBI：PubMed 于 1996 年上线，1997 年正式提供免费 MEDLINE 访问（资源发布）](<https://pubmed.ncbi.nlm.nih.gov/about/>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　NLM 文献检索数据库。未以 API 客户端或社区 MCP 包装代替数据库本体仓库。

## 下载与访问

- [NLM 年度基线数据](<https://ftp.ncbi.nlm.nih.gov/pubmed/baseline/>)　按文件下载压缩 XML 记录。 此次连接超时，文件下载状态未确认。
- [NLM 数据获取说明](<https://www.nlm.nih.gov/databases/download/pubmed_medline.html>)　提供年度基线、后续增量更新和使用条件。 此次连接超时，文件下载状态未确认。

## 关联组件

[PubMed MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/PubMed%20MCP/PubMed%20MCP.md)
