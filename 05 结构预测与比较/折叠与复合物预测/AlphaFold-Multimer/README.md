# AlphaFold-Multimer

扩展 AlphaFold2 的结构预测能力，对多条蛋白链联合建模，估计复合物中亚基的相对位置。

## 输入与输出

- **输入**　按链区分的蛋白序列。系统还可使用配对或非配对的多序列比对及模板。
- **输出**　多链复合物坐标、链内与链间置信度，包括用于判断界面对位可信程度的 ipTM。

## 接入条件

- **LLM 参与**　多链专用结构网络完成预测，无需通用对话 LLM。
- **运行条件**　需要多聚体模型参数。运行完整同源检索管线还需要相应的序列数据库。 作者的 Google Cloud 权重下载入口在本次核验地点返回 HTTP 403。使用前需确认运行环境可以取得参数。

与 AlphaFold2 共用程序仓库，但使用多聚体模型参数。链间置信度不会直接给出实验解离常数。

## 原始来源与公开实现

Evans et al. (2021), Protein complex prediction with AlphaFold-Multimer

[论文或原始出版物](https://doi.org/10.1101/2021.10.04.463034)

- **GitHub 仓库**　[google-deepmind/alphafold](https://github.com/google-deepmind/alphafold)
- **实现入口**　[查看源代码](https://github.com/google-deepmind/alphafold)

多聚体模型与 AlphaFold2 共用官方仓库，另有原始方法论文。

## 下载

- [官方模型参数包](https://storage.googleapis.com/alphafold/alphafold_params_2022-12-06.tar)　官方分发脚本列出的共享参数归档，含 AlphaFold2 单体与 Multimer 参数。
- [项目源码 ZIP](https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip)　公开项目的源码快照。
