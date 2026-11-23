# SAbDab

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

整理 PDB 中的抗体结构与链配对、抗原和结构注释，为抗体参考结构检索和序列比较提供数据。

## 输入、输出与 LLM 参与

- **输入**　PDB 标识、抗体类型、链或其他查询条件。
- **输出**　匹配的抗体条目、序列与链注释、结构坐标，以及汇总表。
- **LLM 参与**　数据库查询与导出无需 LLM。

## 结果解读

可用数据随 PDB 和数据库发布变化。当前下载页与论文分析时的快照可能不同，比较时应记录版本。

## 在六篇研究中的用法

- **Latent-Y**（在线质控／参考数据）　在候选质检中提供新颖性比较参照。

使用此来源的研究组件包括 [Latent-Y 序列质控](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%8A%9F%E8%83%BD%E7%BA%A6%E6%9D%9F%E4%B8%8E%E5%80%99%E9%80%89%E7%AD%9B%E9%80%89/Latent-Y%20%E5%BA%8F%E5%88%97%E8%B4%A8%E6%8E%A7/Latent-Y%20%E5%BA%8F%E5%88%97%E8%B4%A8%E6%8E%A7.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Dunbar et al. (2014), SAbDab: the structural antibody database](<https://doi.org/10.1093/nar/gkt1043>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　Oxford Protein Informatics Group 在线数据库。未核实论文所用版本的独立官方 GitHub。

## 下载与访问

- [SAbDab 数据及结构下载](<https://sabdab.opig.stats.ox.ac.uk/about>)　当前 SAbDab2 官方页面提供汇总表和结构数据下载。
- [官方文件下载接口](<https://sabdab.opig.stats.ox.ac.uk/api/docs>)　File downloads 区列出全部或筛选结果的下载服务。
