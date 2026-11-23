# EV+OneHot

将序列的独热编码与进化耦合模型给出的分数结合，用带有实测标签的变体训练监督回归器。

## 输入与输出

- **输入**　带测定值的序列样本、用同源序列比对估算的进化分数，以及待预测序列。
- **输出**　各个变体的预测测定值或排序分数。训练后得到可用于同一任务的回归模型。

## 接入条件

- **LLM 参与**　无需通用 LLM，也不要求蛋白语言模型。
- **运行条件**　需要目标蛋白的带标签序列及预先计算的进化模型分数。已有分数时可以直接训练组合回归模型。

输出尺度取决于训练标签的实验定义。对新蛋白或不同测定条件不能直接沿用原任务的数值解释。

## 原始来源与公开实现

Hsu et al. (2022), Learning protein fitness models from evolutionary and assay-labeled data

[论文或原始出版物](https://doi.org/10.1038/s41587-021-01146-5)

- **GitHub 仓库**　[chloechsu/combining-evolutionary-and-assay-labelled-data](https://github.com/chloechsu/combining-evolutionary-and-assay-labelled-data)
- **实现入口**　[查看源代码](https://github.com/chloechsu/combining-evolutionary-and-assay-labelled-data/blob/fdaa5bba8ffbb8ab25de57736fed8f9126838ae3/src/predictors/__init__.py)

作者在仓库中将 ev+onehot 对应到 augmented Potts。

## 下载

- [下载实现源码（ZIP）](https://github.com/chloechsu/combining-evolutionary-and-assay-labelled-data/archive/fdaa5bba8ffbb8ab25de57736fed8f9126838ae3.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。

## 可选调用接口

- **EV+OneHot MCP**　调用可在本地拟合的模型及回归器。训练需要带测量值的序列表及演化模型所需输入。 [接口源码](https://github.com/MacromNex/ev_onehot_mcp/blob/d67b70d643d1c4acc1dc718bb09aef4f44869425/src/tools/train.py) · [适配器下载](https://github.com/MacromNex/ev_onehot_mcp/archive/d67b70d643d1c4acc1dc718bb09aef4f44869425.zip)
