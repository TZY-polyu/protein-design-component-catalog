# BLAST

[科学模型与计算](../../README.md) / 序列检索与注释

## 用途

将查询序列与数据库序列进行局部相似性搜索。BLASTP 是其中用于蛋白序列之间比较的程序。

## 输入、输出与 LLM 参与

- **输入**　查询序列，以及目标序列数据库或一组参照序列。通常使用 FASTA 或预先建立的数据库。
- **输出**　命中序列、局部比对范围、比对分数、序列一致性与 E 值等。
- **LLM 参与**　传统序列搜索算法无需 LLM。

## 结果解读

相似性与 E 值要结合查询覆盖率及目标数据库解释。BLAST+ 是现行官方软件实现，原始算法有更早的论文。

## 在六篇研究中的用法

- **Latent-Y**（平台可用／序列比较）　查找与查询序列局部相似的参考序列。单次调用未逐项披露。
- **MAESD**（离线评估）　衡量序列新颖性、相似性和消融条件下的局部保守性。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Altschul et al. (1990), Basic local alignment search tool](<https://pubmed.ncbi.nlm.nih.gov/2231712/>)
- **GitHub 仓库**　[ncbi/ncbi-cxx-toolkit-public](<https://github.com/ncbi/ncbi-cxx-toolkit-public/tree/main/src/algo/blast>)
- **归属说明**　GitHub 链接指向 NCBI 官方 BLAST+ 的算法代码。具体使用版本依各系统的披露。

## 下载与访问

- [NCBI BLAST+ 安装包](<https://ftp.ncbi.nlm.nih.gov/blast/executables/blast%2B/LATEST/>)　NCBI 按操作系统分发命令行工具。
- [仓库源码 ZIP · ncbi/ncbi-cxx-toolkit-public](<https://github.com/ncbi/ncbi-cxx-toolkit-public/archive/e5a9364ea3dc1b25c87ea7ce6e7cffeae6ecde87.zip>)　该仓库的固定快照。

## 关联组件

[Swiss-Prot](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Swiss-Prot/Swiss-Prot.md)
