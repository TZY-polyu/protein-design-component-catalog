# BioMedLM

在生物医学文献上训练的自然语言模型，用于专业文本续写、问答，或作为下游任务微调的起点。

## 输入与输出

- **输入**　自然语言提示及生物医学上下文，编码后为文本 token。
- **输出**　后续文本 token 的分布和生成的回答，可进一步提取术语或标签。

## 接入条件

- **LLM 参与**　BioMedLM 本身是处理自然语言的领域 LLM，推理无需另一个通用模型。
- **运行条件**　推理需要可载入 BioMedLM 的 Transformers 环境、配套分词器和模型权重，以及足以容纳模型的内存或显存。作者为权重规定 BigScience Open RAIL-M 许可，模型卡将直接文本生成定位为研究用途。

输出是依照上下文生成的文本。其中的具体生物医学断言需要原始文献或数据库支撑。

## 原始来源与公开实现

Bolton et al. (2024), BioMedLM: A 2.7B Parameter Language Model Trained On Biomedical Text

[论文或原始出版物](https://arxiv.org/abs/2403.18421)

- **GitHub 仓库**　[stanford-crfm/BioMedLM](https://github.com/stanford-crfm/BioMedLM)
- **实现入口**　[查看源代码](https://github.com/stanford-crfm/BioMedLM)

Stanford CRFM 发布训练及微调代码，也提供配套预训练权重。

## 下载

- [作者发布的模型权重和配置](https://huggingface.co/stanford-crfm/BioMedLM/tree/main)　模型文件页列出权重、分词器与配置。
- [项目源码 ZIP](https://github.com/stanford-crfm/BioMedLM/archive/9e35fddada3e7e5638f5dc55b9e5c74502de6c86.zip)　公开项目的源码快照。
