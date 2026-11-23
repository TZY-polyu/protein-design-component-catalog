# BioMedLM

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

针对生物医学文献预训练的文本语言模型，可作为领域问答或术语识别的对照后端。

## 输入、输出与 LLM 参与

- **输入**　自然语言提示及生物医学上下文，编码后为文本 token。
- **输出**　后续文本 token 的分布和生成的回答，可进一步提取术语或标签。
- **LLM 参与**　该组件本身是生物医学文本语言模型。它处理自然语言，与专门表征氨基酸序列的 pLM 不同。

## 结果解读

MAESD 用它比较文本到生物学概念的映射能力。生成文本不等于已核实的生物学注释。

## 在六篇研究中的用法

- **MAESD**（仅对照）　与 IRA、单独运行的 GPT-4 和 DeepSeek-V3 比较语义转换。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Bolton et al. (2024), BioMedLM: A 2.7B Parameter Language Model Trained On Biomedical Text](<https://arxiv.org/abs/2403.18421>)
- **GitHub 仓库**　[stanford-crfm/BioMedLM](<https://github.com/stanford-crfm/BioMedLM>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [作者发布的模型权重和配置](<https://huggingface.co/stanford-crfm/BioMedLM/tree/main>)　模型文件页列出权重、分词器与配置。
- [仓库源码 ZIP · stanford-crfm/BioMedLM](<https://github.com/stanford-crfm/BioMedLM/archive/9e35fddada3e7e5638f5dc55b9e5c74502de6c86.zip>)　该仓库的固定快照。

## 关联组件

[Gene Ontology](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/Gene%20Ontology/Gene%20Ontology.md) · [MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
