# ProtAlbert

用针对蛋白质序列预训练的 ALBERT 模型提取每个残基在全序列上下文中的特征。

## 输入与输出

- **输入**　氨基酸序列、ProtAlbert 的分词器和预训练权重。
- **输出**　逐残基的上下文向量，可继续汇总或输入单独训练的下游预测器。

## 接入条件

- **LLM 参与**　需要专用蛋白语言模型 ProtAlbert。序列编码无需通用对话 LLM。
- **运行条件**　需要 Python、兼容的 PyTorch 和 Transformers、分词器及模型文件。

ProtAlbert 和同一项目的 ProtT5-XL 采用不同的编码结构，二者的向量和参数不能直接互换。

## 原始来源与公开实现

Elnaggar 等，ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning，IEEE Transactions on Pattern Analysis and Machine Intelligence，2021 年在线发表。

[论文或原始出版物](https://doi.org/10.1109/TPAMI.2021.3095381)

- **GitHub 仓库**　[agemagician/ProtTrans](https://github.com/agemagician/ProtTrans)
- **实现入口**　[查看源代码](https://github.com/agemagician/ProtTrans/blob/27c02f07e65feff8a3e7875f52b8b51225eb3c1c/Embedding/PyTorch/Basic/ProtAlbert.ipynb)

作者提供可执行的 Python 笔记本，涵盖模型加载和序列特征提取。

## 下载

- [ProtAlbert 模型权重和词表](https://huggingface.co/Rostlab/prot_albert/tree/main)　作者发布的模型文件。
- [下载固定版本源码（ZIP）](https://github.com/agemagician/ProtTrans/archive/27c02f07e65feff8a3e7875f52b8b51225eb3c1c.zip)　解压后可按上面的实现入口定位组件。

## 可选调用接口

- **ProtTrans MCP**　使用 Transformers 加载 ProtT5 或 ProtAlbert，提供氨基酸序列向量表征。 [接口源码](https://github.com/MacromNex/prottrans_mcp/blob/d946c8cb76a7ec6b47f349cc3db5aed6150d1c96/scripts/prottrans_embedding.py) · [适配器下载](https://github.com/MacromNex/prottrans_mcp/archive/d946c8cb76a7ec6b47f349cc3db5aed6150d1c96.zip)
