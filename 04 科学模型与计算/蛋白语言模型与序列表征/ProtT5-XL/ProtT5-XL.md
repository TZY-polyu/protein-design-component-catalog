# ProtT5-XL

[科学模型与计算](../../README.md) / 蛋白语言模型与序列表征

## 用途

评估 ProtTrans 中 T5 架构的蛋白编码器。

## 输入、输出与 LLM 参与

- **输入**　蛋白序列。
- **输出**　供监督回归使用的序列表征。
- **LLM 参与**　需要蛋白语言模型。无需通用 LLM 推断表征。

## 结果解读

该蛋白语言模型使用 T5 架构。在 ProteinMCP 的案例中，序列先变成数值表征，再由监督回归头预测适应度。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为案例1表征提取。

## 原始来源与 GitHub

- **ProtTrans 的原始出处**　[Elnaggar et al. (2021 在线 / 2022 刊期), ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning](<https://doi.org/10.1109/TPAMI.2021.3095381>)
- **GitHub 仓库**　[agemagician/ProtTrans](<https://github.com/agemagician/ProtTrans>)（ProtTrans 模型家族）。
- **归属说明**　与 ProtAlbert 来自同一篇 ProtTrans 工作。

## 下载与访问

- [ProtT5-XL-UniRef50 权重文件](<https://huggingface.co/Rostlab/prot_t5_xl_uniref50/tree/main>)　Rostlab 发布的 UniRef50 版本。论文未公布该案例所加载的精确检查点。
- [ProtTrans 家族源码 ZIP](<https://github.com/agemagician/ProtTrans/archive/27c02f07e65feff8a3e7875f52b8b51225eb3c1c.zip>)　训练权重由模型发布页提供。

## 关联组件

[ProtTrans](../ProtTrans/ProtTrans.md) · [ProtTrans MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ProtTrans%20MCP/ProtTrans%20MCP.md)
