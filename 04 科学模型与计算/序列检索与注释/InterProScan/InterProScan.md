# InterProScan

[科学模型与计算](../../README.md) / 序列检索与注释

## 用途

将蛋白序列与成员数据库的签名和统计模型匹配，找出可能的家族、结构域和功能位点。

## 输入、输出与 LLM 参与

- **输入**　待注释的蛋白序列，以及相应 InterProScan 发行版和配套的签名数据库。
- **输出**　每条匹配的签名、序列区间、条目标识和可选功能注释，可输出为表格或结构化文件。
- **LLM 参与**　扫描和注释本身无需 LLM。

## 结果解读

使用的成员库集合和版本直接影响命中结果。InterProScan 5 的逻辑及数据文件与其他主版本需分别核对。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Zdobnov & Apweiler (2001), InterProScan—an integration platform for the signature-recognition methods in InterPro.](<https://doi.org/10.1093/bioinformatics/17.9.847>)
- **GitHub 仓库**　[ebi-pf-team/interproscan](<https://github.com/ebi-pf-team/interproscan>)
- **归属说明**　EMBL-EBI 官方第 5 代代码。首篇论文描述早期版本。

## 下载与访问

- [InterProScan 5 官方发行包下载说明](<https://interproscan-docs.readthedocs.io/en/v5/HowToDownload.html>)　列出软件、成员库和校验文件的获取方式。
- [仓库源码 ZIP · ebi-pf-team/interproscan](<https://github.com/ebi-pf-team/interproscan/archive/26256cbb70357846da3c8275df59397c537f1aca.zip>)　该仓库的固定快照。

## 关联组件

[InterPro MCP（社区封装）](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/InterPro%20MCP%EF%BC%88%E7%A4%BE%E5%8C%BA%E5%B0%81%E8%A3%85%EF%BC%89/InterPro%20MCP%EF%BC%88%E7%A4%BE%E5%8C%BA%E5%B0%81%E8%A3%85%EF%BC%89.md) · [InterPro（项目封装） MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/InterPro%EF%BC%88%E9%A1%B9%E7%9B%AE%E5%B0%81%E8%A3%85%EF%BC%89%20MCP/InterPro%EF%BC%88%E9%A1%B9%E7%9B%AE%E5%B0%81%E8%A3%85%EF%BC%89%20MCP.md)
