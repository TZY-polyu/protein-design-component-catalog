# ProtTrans

[科学模型与计算](../../README.md) / 蛋白语言模型与序列表征

## 用途

用预训练模型将氨基酸序列变成数值表征，供下游分类器或回归器使用。ProteinMCP 的适应度分析比较了 ProtT5-XL 和 ProtAlbert。

## 输入、输出与 LLM 参与

- **输入**　蛋白质氨基酸序列和所选模型对应的分词器。
- **输出**　逐残基向量。对残基向量进行汇总后，可得到每个蛋白一条定长向量。
- **LLM 参与**　需要专用蛋白语言模型。其数值编码无需通用对话 LLM。

## 结果解读

不同模型的向量空间和维数可以不同，适应度预测值还取决于下游回归器及其训练标签。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtT5-XL](../ProtT5-XL/ProtT5-XL.md)、[ProtAlbert](../ProtAlbert/ProtAlbert.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Elnaggar et al. (2021 在线 / 2022 刊期), ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning](<https://doi.org/10.1109/TPAMI.2021.3095381>)
- **GitHub 仓库**　[agemagician/ProtTrans](<https://github.com/agemagician/ProtTrans>)
- **归属说明**　两种模型同属 ProtTrans。该项工作于 2020 年发布预印本。

## 下载与访问

- [ProtT5-XL 权重及配置](<https://huggingface.co/Rostlab/prot_t5_xl_uniref50/tree/main>)　Rostlab 发布的 UniRef50 版本。
- [ProtAlbert 权重及配置](<https://huggingface.co/Rostlab/prot_albert/tree/main>)　独立的 ALBERT 架构模型文件。
- [仓库源码 ZIP · agemagician/ProtTrans](<https://github.com/agemagician/ProtTrans/archive/27c02f07e65feff8a3e7875f52b8b51225eb3c1c.zip>)　该仓库的固定快照。

## 关联组件

[ProtTrans MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ProtTrans%20MCP/ProtTrans%20MCP.md)
