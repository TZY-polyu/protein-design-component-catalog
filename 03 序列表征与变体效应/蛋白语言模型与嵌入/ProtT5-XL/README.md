# ProtT5-XL

将氨基酸序列编码为带有上下文信息的逐残基向量，用作结构特征预测、分类或回归等下游任务的输入。

## 输入与输出

- **输入**　单条或多条氨基酸序列、与所选变体匹配的分词器和模型权重。
- **输出**　每个残基的向量表示。对有效残基求平均可得到每条蛋白一组定长特征。

## 接入条件

- **LLM 参与**　需要专用蛋白语言模型 ProtT5。提取特征无需通用对话 LLM。
- **运行条件**　需要 Python、PyTorch、Transformers、SentencePiece 及相应检查点。显存或内存需求随模型版本和序列长度变化。

ProtT5-XL 有不同训练数据和权重版本。所列模型文件为明确标注的 UniRef50 版本。与 ProtAlbert 共享论文，但权重与网络结构不同。

## 原始来源与公开实现

Elnaggar 等，ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning，IEEE Transactions on Pattern Analysis and Machine Intelligence，2021 年在线发表。

[论文或原始出版物](https://doi.org/10.1109/TPAMI.2021.3095381)

- **GitHub 仓库**　[agemagician/ProtTrans](https://github.com/agemagician/ProtTrans)
- **实现入口**　[查看源代码](https://github.com/agemagician/ProtTrans/blob/27c02f07e65feff8a3e7875f52b8b51225eb3c1c/Embedding/prott5_embedder.py)

ProtTrans 作者公开了序列编码程序、使用示例和对应模型文件。

## 下载

- [ProtT5-XL-UniRef50 模型权重和词表](https://huggingface.co/Rostlab/prot_t5_xl_uniref50/tree/main)　作者发布的模型文件。
- [下载固定版本源码（ZIP）](https://github.com/agemagician/ProtTrans/archive/27c02f07e65feff8a3e7875f52b8b51225eb3c1c.zip)　解压后可按上面的实现入口定位组件。

## 可选调用接口

- **ProtTrans MCP**　使用 Transformers 加载 ProtT5 或 ProtAlbert，提供氨基酸序列向量表征。 [接口源码](https://github.com/MacromNex/prottrans_mcp/blob/d946c8cb76a7ec6b47f349cc3db5aed6150d1c96/scripts/prottrans_embedding.py) · [适配器下载](https://github.com/MacromNex/prottrans_mcp/archive/d946c8cb76a7ec6b47f349cc3db5aed6150d1c96.zip)
