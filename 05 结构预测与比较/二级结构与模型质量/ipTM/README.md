# ipTM

利用复合物结构预测器内部的对齐误差分布，估计其对链间相对位置的信心。

## 输入与输出

- **输入**　预测器产生的残基对对齐误差分布，以及用于识别不同链的链标识。
- **输出**　0 至 1 范围的界面预测 TM 分数，通常更高表示模型更确信链间相对排布。

## 接入条件

- **LLM 参与**　指标本身通过数值计算得到，无需通用 LLM。
- **运行条件**　预测器产生的对齐误差 logits、误差分箱及链标识。计算已有输出上的指标无需重新做结构预测。

分数表示对链间相对排布的置信度。计算不要求实验参考结构，也不产生实测亲和力。

## 原始来源与公开实现

Evans et al. (2021), Protein complex prediction with AlphaFold-Multimer, bioRxiv v1.

[论文或原始出版物](https://www.biorxiv.org/content/10.1101/2021.10.04.463034v1)

- **GitHub 仓库**　[google-deepmind/alphafold](https://github.com/google-deepmind/alphafold)
- **实现入口**　[查看源代码](https://github.com/google-deepmind/alphafold/blob/c77e5d2a8961d1a353632c462914ff0a32a950f6/alphafold/common/confidence.py)

AlphaFold 作者给出的 ipTM 参考实现位于 confidence.py 的预测 TM 分数函数中。

## 下载

- [下载实现源码（ZIP）](https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [AlphaFold 官方指标实现](https://github.com/google-deepmind/alphafold/blob/main/alphafold/common/confidence.py)　可查看产生界面预测 TM 分数的参考实现。
