# SPIRED-Stab

估计氨基酸替换引起的稳定性变化，适合对同一参考蛋白的已知变体进行计算比较。

## 输入与输出

- **输入**　一个含两条等长序列的 FASTA 文件，依次存放参考序列和变体序列。推理脚本逐位比对，自动标记替换位置。
- **输出**　pred.csv 记录预测的自由能变化差 ddG 与熔解温度差 dTm。

## 接入条件

- **LLM 参与**　使用 ESM-2 蛋白语言模型提取序列表征，无需通用对话 LLM。
- **运行条件**　Python、PyTorch、SPIRED-Stab 参数及 ESM-2 权重。作者给出的容器配置要求至少 50 GB 内存。

解释预测时需保留参考序列与变体的方向，预测值还受训练数据范围影响。

## 原始来源与公开实现

Chen et al. (2024), An end-to-end framework for the prediction of protein structure and fitness from single sequence

[论文或原始出版物](https://doi.org/10.1038/s41467-024-51776-x)

- **GitHub 仓库**　[Gonglab-THU/SPIRED-Fitness](https://github.com/Gonglab-THU/SPIRED-Fitness)
- **实现入口**　[查看源代码](https://github.com/Gonglab-THU/SPIRED-Fitness/blob/main/run_SPIRED-Stab.py)

SPIRED-Stab 与 SPIRED-Fitness 共享作者仓库，有独立推理脚本。

## 下载

- [作者发布的模型参数](https://doi.org/10.5281/zenodo.12560925)　作者仓库指向的模型参数存档，包含同一研究系列的模型。
- [下载本次索引的源码快照（ZIP）](https://github.com/Gonglab-THU/SPIRED-Fitness/archive/dae6f00fa6f5be84657560b2c9b1f8b5e22fb9e3.zip)
