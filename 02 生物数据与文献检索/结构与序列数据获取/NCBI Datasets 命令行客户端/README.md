# NCBI Datasets 命令行客户端

按生物分类或数据库标识检索 NCBI 数据资源，并把序列、注释及元数据打包供本地分析。

## 输入与输出

- **输入**　基因、物种或已提交记录的标识符，以及请求的数据种类。
- **输出**　可下载的数据包，内容可含 FASTA 序列、基因组注释和结构化元数据报告。

## 接入条件

- **LLM 参与**　搜索、批量取数和整理数据包无需通用 LLM。
- **运行条件**　对应平台的 CLI 程序和 NCBI 访问网络。查询量或数据访问规则以官方服务说明为准。

NCBI Datasets 是 NCBI 的数据分发服务。下载客户端用于取数，资料范围随所选资源和版本而变。

## 原始来源与公开实现

O’Leary et al. (2024), Exploring and retrieving sequence and metadata for species across the tree of life with NCBI Datasets

[论文或原始出版物](https://doi.org/10.1038/s41597-024-03571-y)

- **GitHub 仓库**　[ncbi/datasets](https://github.com/ncbi/datasets)
- **实现入口**　[查看源代码](https://github.com/ncbi/datasets/blob/9d66d2bcb321612e0e03fc1b43cc18f5e75137eb/client/apps/public/Datasets/v2/cmd/datasets/main.go)

NCBI 官方仓库公开 datasets 客户端的 Go 实现。在线数据库由 NCBI 独立维护。

## 下载

- [下载实现源码（ZIP）](https://github.com/ncbi/datasets/archive/9d66d2bcb321612e0e03fc1b43cc18f5e75137eb.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [官方命令行工具下载](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/command-line-tools/download-and-install/)　页面提供 datasets 与 dataformat 的各平台分发入口。
- [NCBI 数据查询与下载](https://www.ncbi.nlm.nih.gov/datasets/)　可查找记录并选取所需的数据包。
