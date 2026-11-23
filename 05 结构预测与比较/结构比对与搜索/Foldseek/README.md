# Foldseek

在大型结构数据库中快速寻找与查询蛋白有相似三维折叠的条目，用于检索结构邻居。

## 输入与输出

- **输入**　查询结构与目标结构数据库，或两组待比较的结构。
- **输出**　按相似性排序的结构命中，以及比对区间、显著性或结构比对分数。

## 接入条件

- **LLM 参与**　无需通用 LLM。
- **运行条件**　预编译程序或兼容的 C++ 构建环境，以及可供比较的结构集合。

高相似命中提示共享折叠或局部几何模式。是否具有相同生物学功能，还需结合序列、位点及实验信息判断。

## 原始来源与公开实现

van Kempen et al. (2024), Fast and accurate protein structure search with Foldseek

[论文或原始出版物](https://doi.org/10.1038/s41587-023-01773-0)

- **GitHub 仓库**　[steineggerlab/foldseek](https://github.com/steineggerlab/foldseek)
- **实现入口**　[查看源代码](https://github.com/steineggerlab/foldseek/blob/4f5c00ccb5590f08a261b9144fd9a5d28a71fa0e/src/workflow/EasyStructureSearch.cpp)

上游作者仓库

## 下载

- [下载实现源码（ZIP）](https://github.com/steineggerlab/foldseek/archive/4f5c00ccb5590f08a261b9144fd9a5d28a71fa0e.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [Foldseek 发布与预编译程序](https://github.com/steineggerlab/foldseek/releases)　按平台下载软件版本。
