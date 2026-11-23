# CATH

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

按照结构类别、架构、拓扑与同源超家族对蛋白结构域分组，用于查询已知结构的分类或组织参照集合。

## 输入、输出与 LLM 参与

- **输入**　PDB 链或结构域标识、CATH 分类号或下载集合。
- **输出**　结构域范围、层次分类标识、同源分组及发布版本对应的数据文件。
- **LLM 参与**　读取分类与下载数据库无需 LLM。

## 结果解读

CATH 的基本条目是结构域。一条蛋白链可包含多个分类结果，不能把结构域标签直接当作整条链唯一的属性。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents CATH 分类查询](../../%E6%A3%80%E7%B4%A2%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86/ProtAgents%20CATH%20%E5%88%86%E7%B1%BB%E6%9F%A5%E8%AF%A2/ProtAgents%20CATH%20%E5%88%86%E7%B1%BB%E6%9F%A5%E8%AF%A2.md)、[ProtAgents 结构类别条件生成](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/ProtAgents%20%E7%BB%93%E6%9E%84%E7%B1%BB%E5%88%AB%E6%9D%A1%E4%BB%B6%E7%94%9F%E6%88%90/ProtAgents%20%E7%BB%93%E6%9E%84%E7%B1%BB%E5%88%AB%E6%9D%A1%E4%BB%B6%E7%94%9F%E6%88%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Orengo et al. (1997), CATH—a hierarchic classification of protein domain structures](<https://doi.org/10.1016/S0969-2126(97)00260-8>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　原始资源为分类数据库：https://www.cathdb.info/。

## 下载与访问

- [CATH 官方数据下载](<https://www.cathdb.info/download>)　提供各版本的分类、结构域边界及其他发布文件。
