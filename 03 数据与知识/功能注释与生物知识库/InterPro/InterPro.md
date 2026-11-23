# InterPro

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

整合成员数据库中的签名及其解释，以家族、结构域、位点等类别组织蛋白注释。

## 输入、输出与 LLM 参与

- **输入**　InterPro 编号、名称、蛋白数据库标识或已知签名编号。
- **输出**　整合条目与描述、成员签名、层级与交叉引用，并可返回已有条目的序列匹配记录。
- **LLM 参与**　数据库查询无需 LLM。

## 结果解读

数据库记录了已有注释。对新序列运行签名扫描通常由 InterProScan 等程序执行，数据库本体和扫描器应分别记录版本。

## 在六篇研究中的用法

- **MAESD**（运行时知识。评测标签）　支持识别结构域组合及估计其天然位置分布。

使用此来源的研究组件包括 [MAESD 意图识别智能体（IRA）](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89.md)、[MAESD 结构域排列评分](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%8A%9F%E8%83%BD%E7%BA%A6%E6%9D%9F%E4%B8%8E%E5%80%99%E9%80%89%E7%AD%9B%E9%80%89/MAESD%20%E7%BB%93%E6%9E%84%E5%9F%9F%E6%8E%92%E5%88%97%E8%AF%84%E5%88%86/MAESD%20%E7%BB%93%E6%9E%84%E5%9F%9F%E6%8E%92%E5%88%97%E8%AF%84%E5%88%86.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Apweiler et al. (2000), InterPro—an integrated documentation resource for protein families, domains and functional sites](<https://doi.org/10.1093/bioinformatics/16.12.1145>)
- **GitHub 仓库**　[ProteinsWebTeam/interpro-docs](<https://github.com/ProteinsWebTeam/interpro-docs>)
- **归属说明**　InterPro 官方文档仓库。数据库记录由 EMBL-EBI 提供，无单一数据库源码库。

## 下载与访问

- [InterPro 官方数据下载](<https://www.ebi.ac.uk/interpro/download/>)　EMBL-EBI 提供的数据库文件与相关资源。
- [仓库源码 ZIP · ProteinsWebTeam/interpro-docs](<https://github.com/ProteinsWebTeam/interpro-docs/archive/ddc698a355bf45390c6b4f37f2ef0bf30beb00f7.zip>)　该仓库的固定快照。

## 关联组件

[InterPro MCP（社区封装）](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/InterPro%20MCP%EF%BC%88%E7%A4%BE%E5%8C%BA%E5%B0%81%E8%A3%85%EF%BC%89/InterPro%20MCP%EF%BC%88%E7%A4%BE%E5%8C%BA%E5%B0%81%E8%A3%85%EF%BC%89.md) · [InterPro（项目封装） MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/InterPro%EF%BC%88%E9%A1%B9%E7%9B%AE%E5%B0%81%E8%A3%85%EF%BC%89%20MCP/InterPro%EF%BC%88%E9%A1%B9%E7%9B%AE%E5%B0%81%E8%A3%85%EF%BC%89%20MCP.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
