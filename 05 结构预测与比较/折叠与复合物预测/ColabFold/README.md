# ColabFold

把同源序列检索、序列比对和结构预测后端串接起来。可只调用其比对服务，也可完成结构预测。

## 输入与输出

- **输入**　蛋白质序列或链组。也可输入预先计算的多序列比对。
- **输出**　单独检索时返回多序列比对。运行预测后返回三维坐标、预测置信度及相关结果文件。

## 接入条件

- **LLM 参与**　比对和专用模型推理均无需通用 LLM。
- **运行条件**　折叠功能需相应后端模型参数。检索可以使用公共 MSA 服务或本地序列数据库。

同源比对可作为独立的检索结果。启用折叠模型后才会产生结构及相应的置信度。

## 原始来源与公开实现

Mirdita et al. (2022), ColabFold: making protein folding accessible to all

[论文或原始出版物](https://doi.org/10.1038/s41592-022-01488-1)

- **GitHub 仓库**　[sokrypton/ColabFold](https://github.com/sokrypton/ColabFold)
- **实现入口**　[查看源代码](https://github.com/sokrypton/ColabFold)

作者工具仓库。为调用结构预测提供另一实现与入口。

## 下载

- [ColabFold 软件发布](https://github.com/sokrypton/ColabFold/releases)　作者发布的版本和变更记录。预测后端的参数有独立来源。
- [项目源码 ZIP](https://github.com/sokrypton/ColabFold/archive/eb061aa6706959fdffe15e86d27ca08083d6ed8d.zip)　公开项目的源码快照。
