# EV+OneHot

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

将序列的独热编码与进化耦合模型给出的分数结合，用带有实测标签的变体训练监督回归器。

## 输入、输出与 LLM 参与

- **输入**　带测定值的序列样本、用同源序列比对估算的进化分数，以及待预测序列。
- **输出**　各个变体的预测测定值或排序分数。训练后得到可用于同一任务的回归模型。
- **LLM 参与**　无需通用 LLM，也不要求蛋白语言模型。

## 结果解读

输出尺度取决于训练标签的实验定义。对新蛋白或不同测定条件不能直接沿用原任务的数值解释。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Hsu et al. (2022), Learning protein fitness models from evolutionary and assay-labeled data](<https://doi.org/10.1038/s41587-021-01146-5>)
- **GitHub 仓库**　[chloechsu/combining-evolutionary-and-assay-labelled-data](<https://github.com/chloechsu/combining-evolutionary-and-assay-labelled-data>)
- **归属说明**　作者在仓库中将 ev+onehot 对应到 augmented Potts。

## 下载与访问

- [仓库源码 ZIP · chloechsu/combining-evolutionary-and-assay-labelled-data](<https://github.com/chloechsu/combining-evolutionary-and-assay-labelled-data/archive/fdaa5bba8ffbb8ab25de57736fed8f9126838ae3.zip>)　该仓库的固定快照。

## 关联组件

[EV+OneHot MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/EV%2BOneHot%20MCP/EV%2BOneHot%20MCP.md)
