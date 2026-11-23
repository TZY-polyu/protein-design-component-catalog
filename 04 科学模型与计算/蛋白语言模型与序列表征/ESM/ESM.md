# ESM

[科学模型与计算](../../README.md) / 蛋白语言模型与序列表征

## 用途

利用蛋白序列的统计规律学习残基与整条序列的数值表征，为结构或功能分析提供输入。

## 输入、输出与 LLM 参与

- **输入**　一个或多个氨基酸序列以及所选 ESM 检查点。
- **输出**　残基或序列嵌入向量，部分型号也输出各位置的氨基酸分布。
- **LLM 参与**　使用专用蛋白语言模型，推理无需通用对话 LLM。

## 结果解读

ESM 是模型家族。用于变体效应、逆折叠和结构预测的分支有不同的输入、训练目标及权重。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Rives et al. (2021), Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences](<https://doi.org/10.1073/pnas.2016239118>)
- **GitHub 仓库**　[Biohub/esm-archive](<https://github.com/Biohub/esm-archive>)
- **归属说明**　ESM 系列初期模型。版本专文另列。

## 下载与访问

- [官方预训练模型目录](<https://github.com/Biohub/esm-archive#pre-trained-models>)　列明早期 ESM 及后续分支的模型标识和下载地址。
- [仓库源码 ZIP · Biohub/esm-archive](<https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip>)　该仓库的固定快照。

## 关联组件

[ESM MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ESM%20MCP/ESM%20MCP.md)
