# MMseqs2

从大型序列库中搜索相似条目，也能对序列聚类，为同源分析或多序列比对提供候选。

## 输入与输出

- **输入**　查询序列、待搜索的蛋白或核酸序列库。按任务选择检索或聚类。
- **输出**　相似序列命中名单、比对区间及统计量，或以代表序列标记的聚类结果。

## 接入条件

- **LLM 参与**　使用序列搜索与比对算法，无需通用 LLM。
- **运行条件**　预编译 MMseqs2 或受支持的构建环境，以及查询和参考序列。

命中的相似度、比对覆盖范围和参考库版本会影响结论。序列相似性是解释同源关系的一项证据。

## 原始来源与公开实现

Steinegger & Söding (2017), MMseqs2 enables sensitive protein sequence searching for the analysis of massive data sets

[论文或原始出版物](https://doi.org/10.1038/nbt.3988)

- **GitHub 仓库**　[soedinglab/MMseqs2](https://github.com/soedinglab/MMseqs2)
- **实现入口**　[查看源代码](https://github.com/soedinglab/MMseqs2/blob/ae60ef6964f3de689139bcfe290d9fad18f70b06/src/workflow/Search.cpp)

作者工具仓库。

## 下载

- [下载实现源码（ZIP）](https://github.com/soedinglab/MMseqs2/archive/ae60ef6964f3de689139bcfe290d9fad18f70b06.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [官方编译版](https://github.com/soedinglab/MMseqs2/releases)　发布页列出适用于不同操作系统和处理器的包及源码。

## 可选调用接口

- **MMseqs2 本地多序列比对 MCP**　执行本机 mmseqs 程序，查询本地安装的序列数据库并形成多序列比对。 [接口源码](https://github.com/MacromNex/mmseqs2_mcp/blob/9cb7fb5addb27a97e03af57749b08ee3a1dab92d/src/server.py) · [适配器下载](https://github.com/MacromNex/mmseqs2_mcp/archive/9cb7fb5addb27a97e03af57749b08ee3a1dab92d.zip)
