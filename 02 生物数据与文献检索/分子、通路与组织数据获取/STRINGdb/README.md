# STRINGdb

在 R 中把蛋白编号映射到 STRING 标识，查询指定物种的蛋白功能关联网络和富集结果。

## 输入与输出

- **输入**　一种生物的标识符，以及一组基因名、蛋白编号或已映射的 STRING ID。做富集分析时还可指定背景集。
- **输出**　标识符映射表、带关联分数的网络边表或图对象，以及功能富集表。

## 接入条件

- **LLM 参与**　无需 LLM。标识符映射、网络查询与统计按程序执行。
- **运行条件**　R 与兼容的 Bioconductor 版本。初次下载物种数据或调用在线功能需要联网，代码许可为 GPL-2。

功能关联分数汇总多种证据。只有相应证据支持时，才能把一条边解释为直接物理结合。

## 原始来源与公开实现

Szklarczyk 等，STRING v10: protein–protein interaction networks, integrated over the tree of life（2015）。文中专节介绍并展示 STRINGdb R 包。

[论文或原始出版物](https://doi.org/10.1093/nar/gku1003)

- **GitHub 仓库**　[bioc/STRINGdb](https://github.com/bioc/STRINGdb)
- **实现入口**　[查看源代码](https://github.com/bioc/STRINGdb/blob/a43eee52e7737ed496801543435145f91767314e/R/rstring.R)

Bioconductor 发布，GitHub 链接为 Bioconductor 源码库的只读镜像。

## 下载

- [固定版本源码 ZIP](https://github.com/bioc/STRINGdb/archive/a43eee52e7737ed496801543435145f91767314e.zip)　该快照包含组件实现及配套项目文件。
- [Bioconductor 源码包与版本说明](https://bioconductor.org/packages/STRINGdb/)　在 Source Package 栏可获取发布版源码。
