# Pfam

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

按蛋白家族或结构域组织序列、种子比对和剖面隐马尔可夫模型，为序列功能注释提供依据。

## 输入、输出与 LLM 参与

- **输入**　可按家族标识、名称或注释关键词查找。序列归属分析还可使用相应家族模型。
- **输出**　家族条目、种子多序列比对、模型文件及覆盖的蛋白结构域信息。
- **LLM 参与**　条目检索、模型读取与比对均无需通用 LLM。

## 结果解读

家族成员共享一定序列特征。Pfam 的家族或结构域匹配可以支持功能推断，不能单独确证具体生化作用。

## 在六篇研究中的用法

- **MAESD**（运行时知识。离线评测）　Pfam 支持结构域检索。Pfam-A Seed 是生成模块的评测数据来源之一。

使用此来源的研究组件包括 [MAESD 意图识别智能体（IRA）](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89.md)、[MAESD 测试集与同源过滤](../../%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Sonnhammer et al. (1997), Pfam: a comprehensive database of protein domain families based on seed alignments](<https://pubmed.ncbi.nlm.nih.gov/9223186/>)
- **GitHub 仓库**　[ProteinsWebTeam/Pfam](<https://github.com/ProteinsWebTeam/Pfam>)
- **归属说明**　GitHub 收录 Pfam 项目软件。家族、比对与 HMM 数据由 EMBL-EBI 发布。

## 下载与访问

- [EMBL-EBI 发布文件](<https://ftp.ebi.ac.uk/pub/databases/Pfam/current_release/>)　含种子比对、家族 HMM 和其他资料。 此次连接超时，文件下载状态未确认。
- [InterPro 上的 Pfam 浏览入口](<https://www.ebi.ac.uk/interpro/entry/pfam/>)　可根据条目查看当前注释和跨库链接。
- [仓库源码 ZIP · ProteinsWebTeam/Pfam](<https://github.com/ProteinsWebTeam/Pfam/archive/b50c13eeb3fbf9d8f9db03a4416effb9ba18438d.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
