# BLAST

将查询序列与数据库序列进行局部相似性搜索。BLASTP 是其中用于蛋白序列之间比较的程序。

## 输入与输出

- **输入**　查询序列，以及目标序列数据库或一组参照序列。通常使用 FASTA 或预先建立的数据库。
- **输出**　命中序列、局部比对范围、比对分数、序列一致性与 E 值等。

## 接入条件

- **LLM 参与**　传统序列搜索算法无需 LLM。
- **运行条件**　本地运行需要与操作系统匹配的 NCBI BLAST+ 程序，以及已建立索引的目标序列数据库或可供逐对比较的目标序列。

相似性与 E 值要结合查询覆盖率及目标数据库解释。BLAST+ 是现行官方软件实现，原始算法有更早的论文。

## 原始来源与公开实现

Altschul et al. (1990), Basic local alignment search tool

[论文或原始出版物](https://pubmed.ncbi.nlm.nih.gov/2231712/)

- **GitHub 仓库**　[ncbi/ncbi-cxx-toolkit-public](https://github.com/ncbi/ncbi-cxx-toolkit-public)
- **实现入口**　[查看源代码](https://github.com/ncbi/ncbi-cxx-toolkit-public/tree/main/src/algo/blast)

NCBI 官方 BLAST+ 计算核心。BLAST+ 软件套件的发展晚于最初 BLAST 方法论文。

## 下载

- [NCBI BLAST+ 安装包](https://ftp.ncbi.nlm.nih.gov/blast/executables/blast%2B/LATEST/)　NCBI 按操作系统分发命令行工具。
- [项目源码 ZIP](https://github.com/ncbi/ncbi-cxx-toolkit-public/archive/e5a9364ea3dc1b25c87ea7ce6e7cffeae6ecde87.zip)　公开项目的源码快照。
