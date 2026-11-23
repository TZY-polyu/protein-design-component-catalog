# RFdiffusion2

按给定的局部原子几何条件生成蛋白结构样本，用来研究几何约束与骨架构象的相容性。

## 输入与输出

- **输入**　分子几何描述、可用的结构上下文及任务要求。
- **输出**　与几何条件对应的候选结构坐标和相关生成记录。

## 接入条件

- **LLM 参与**　使用专用生成模型，无需通用 LLM。
- **运行条件**　需要项目兼容的 GPU 环境、预训练权重及其指定的结构依赖文件。

输出是依模型采样得到的几何候选。采样结果的结构与物理性质需要分别验证。

## 原始来源与公开实现

Ahern et al. (2025 在线 / 2026 刊期), Atom-level enzyme active site scaffolding using RFdiffusion2

[论文或原始出版物](https://doi.org/10.1038/s41592-025-02975-x)

- **GitHub 仓库**　[RosettaCommons/RFdiffusion2](https://github.com/RosettaCommons/RFdiffusion2)
- **实现入口**　[查看源代码](https://github.com/RosettaCommons/RFdiffusion2)

RosettaCommons 发布的第二代实现，附环境和资源说明。

## 下载

- [下载源码快照（ZIP）](https://github.com/RosettaCommons/RFdiffusion2/archive/d365cbf4db3958814a9f8e4f6f94fa309dfebc2b.zip)　该链接固定到仓库中的一个提交。
- [作者模型权重下载目录](https://ipd.graylab.jhu.edu/rfdiffusion2/model_weights/)　由作者维护的下载站点。
