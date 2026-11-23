# RFdiffusion

用扩散式生成模型构建蛋白骨架，为后续结构分析或独立序列建模提供候选三维构象。

## 输入与输出

- **输入**　生成任务的结构条件。也支持不指定外部结构模板的骨架采样。
- **输出**　候选蛋白骨架的三维坐标及对应记录。

## 接入条件

- **LLM 参与**　使用专用结构扩散模型，无需通用 LLM。
- **运行条件**　本地推理需要兼容的 PyTorch、GPU 环境及另行下载的模型权重。

产生的坐标是模型样本。序列、实验结构与生物学性质需要分别判读。

## 原始来源与公开实现

Watson et al. (2023), De novo design of protein structure and function with RFdiffusion

[论文或原始出版物](https://doi.org/10.1038/s41586-023-06415-8)

- **GitHub 仓库**　[RosettaCommons/RFdiffusion](https://github.com/RosettaCommons/RFdiffusion)
- **实现入口**　[查看源代码](https://github.com/RosettaCommons/RFdiffusion)

RosettaCommons 维护的作者推理实现。

## 下载

- [下载源码快照（ZIP）](https://github.com/RosettaCommons/RFdiffusion/archive/86507b6538f51fce57b5a72477165f03999ed7ae.zip)　该链接固定到仓库中的一个提交。
- [模型权重下载索引](https://sites.google.com/omsf.io/rfdiffusion/reference-docs/model-checkpoints)　项目支持文档列出的官方权重。
