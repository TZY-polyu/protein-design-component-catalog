# Biopython

提供读写、转换和处理生物序列、结构与注释的 Python 接口。可充当结构分析流程中的文件解析和数据组织层。

## 输入与输出

- **输入**　FASTA、PDB、mmCIF 等生物信息文件，或由调用者传入的序列与结构对象。
- **输出**　可供程序操作的序列、结构和比对对象，或重新导出的数据文件。

## 接入条件

- **LLM 参与**　软件库自身无需 LLM。具体算法或外部工具取决于调用的子模块。
- **运行条件**　需 Python 及 Biopython。处理本地文件可离线，访问 KEGG 等网络数据库需联网。调用 DSSP 等外部工具时须另行安装。

例如结合 DSSP 时，Biopython 可以负责调用和解析结果，二级结构分类规则来自 DSSP。

**最小运行核验**　Biopython 1.87 读取两条 FASTA，返回 ACDE（4 个残基）和 GGS（3 个残基）。

## 原始来源与公开实现

Cock et al. (2009), Biopython: freely available Python tools for computational molecular biology and bioinformatics

[论文或原始出版物](https://doi.org/10.1093/bioinformatics/btp163)

- **GitHub 仓库**　[biopython/biopython](https://github.com/biopython/biopython)
- **实现入口**　[查看源代码](https://github.com/biopython/biopython)

原作者软件仓库。

## 下载

- [Biopython 官方下载页](https://biopython.org/wiki/Download)　按系统和 Python 环境取得安装文件。
- [KEGG REST 查询模块](https://biopython.org/docs/latest/api/Bio.KEGG.REST.html)　Biopython 含公开查询客户端。KEGG 公共 REST 服务限学术用途。
- [项目源码 ZIP](https://github.com/biopython/biopython/archive/3c32ad9b14d1d52a468d072c1288376f60071d19.zip)　公开项目的源码快照。
