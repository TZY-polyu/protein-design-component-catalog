# InterProScan

将蛋白序列与成员数据库的签名和统计模型匹配，找出可能的家族、结构域和功能位点。

## 输入与输出

- **输入**　待注释的蛋白序列，以及相应 InterProScan 发行版和配套的签名数据库。
- **输出**　每条匹配的签名、序列区间、条目标识和可选功能注释，可输出为表格或结构化文件。

## 接入条件

- **LLM 参与**　扫描和注释本身无需 LLM。
- **运行条件**　InterProScan 5 软件发行包、配套签名库和运行所需的 Java 环境。部分成员方法另有依赖或许可。

使用的成员库集合和版本直接影响命中结果。InterProScan 5 的逻辑及数据文件与其他主版本需分别核对。

## 原始来源与公开实现

Zdobnov & Apweiler (2001), InterProScan—an integration platform for the signature-recognition methods in InterPro.

[论文或原始出版物](https://doi.org/10.1093/bioinformatics/17.9.847)

- **GitHub 仓库**　[ebi-pf-team/interproscan](https://github.com/ebi-pf-team/interproscan)
- **实现入口**　[查看源代码](https://github.com/ebi-pf-team/interproscan/blob/26256cbb70357846da3c8275df59397c537f1aca/core/jms-implementation/src/main/java/uk/ac/ebi/interpro/scan/jms/main/Run.java)

EMBL-EBI 官方第 5 代代码。首篇论文描述早期版本。

## 下载

- [下载实现源码（ZIP）](https://github.com/ebi-pf-team/interproscan/archive/26256cbb70357846da3c8275df59397c537f1aca.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [InterProScan 5 官方发行包下载说明](https://interproscan-docs.readthedocs.io/en/v5/HowToDownload.html)　列出软件、成员库和校验文件的获取方式。
