# Gene Ontology

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

为基因产物的分子功能、生物过程和细胞组分提供结构化术语和术语之间的关系。MAESD 使用这些术语表示功能约束。

## 输入、输出与 LLM 参与

- **输入**　查询词、GO 标识符或需要映射的功能描述。如需查询某个蛋白的注释，还需相应的注释记录。
- **输出**　GO 条目的名称、定义及上下位关系。注释数据另外给出基因产物与术语、证据代码之间的联系。
- **LLM 参与**　本体文件与查询无需 LLM。自然语言到 GO 的映射可在外层使用 LLM。

## 结果解读

GO 本体定义概念，注释文件承载具体生物学对象上的证据。下载其一并不自动包含另一种数据。

## 在六篇研究中的用法

- **MAESD**（运行时知识。评测标签）　为设计意图和注释评测提供统一语义词表。

使用此来源的研究组件包括 [MAESD 意图识别智能体（IRA）](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89.md)、[MAESD 意图识别标签评测](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%A0%87%E7%AD%BE%E8%AF%84%E6%B5%8B/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%A0%87%E7%AD%BE%E8%AF%84%E6%B5%8B.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ashburner et al. (2000), Gene ontology: tool for the unification of biology](<https://doi.org/10.1038/75556>)
- **GitHub 仓库**　[geneontology/go-ontology](<https://github.com/geneontology/go-ontology>)
- **归属说明**　官方本体源文件。

## 下载与访问

- [GO 本体下载](<https://geneontology.org/docs/download-ontology/>)　官方页面提供 OBO、OWL、JSON 和历史版本入口。
- [仓库源码 ZIP · geneontology/go-ontology](<https://github.com/geneontology/go-ontology/archive/190f462729f20606899c6fad0c29c8fe32f71c43.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
