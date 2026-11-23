# DeepSeek-V3

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

在 MAESD 中用于自然语言意图解析，在 BioDesignBench 中作为被评测的决策后端。

## 输入、输出与 LLM 参与

- **输入**　文本指令、研究语境与工具定义。进行多步任务时还包括此前工具结果。
- **输出**　语义判断、自然语言答复或供运行器解析的工具调用信息。
- **LLM 参与**　它本身是通用 LLM。

## 结果解读

原始 V3 权重与其后更新的同系列模型有独立版本标识。只写 API 品牌不足以固定实际检查点。

## 在六篇研究中的用法

- **MAESD**（运行时推理。另作实验对照）　论文分别评估两种后端的 MAESD，并将两个模型单独运行作基线。
- **BioDesignBench**（运行时决策／模型比较）　在引导和非引导两种模式下作决策，记录候选与工具轨迹。

使用此来源的研究组件包括 [BioDesignBench 评估深度干预](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%AF%84%E4%BC%B0%E6%B7%B1%E5%BA%A6%E5%B9%B2%E9%A2%84/BioDesignBench%20%E8%AF%84%E4%BC%B0%E6%B7%B1%E5%BA%A6%E5%B9%B2%E9%A2%84.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[DeepSeek-AI (2024), DeepSeek-V3 Technical Report](<https://arxiv.org/abs/2412.19437>)
- **GitHub 仓库**　[deepseek-ai/DeepSeek-V3](<https://github.com/deepseek-ai/DeepSeek-V3>)
- **归属说明**　模型官方仓库。

## 下载与访问

- [DeepSeek-V3 官方权重文件](<https://huggingface.co/deepseek-ai/DeepSeek-V3/tree/main>)　模型发布方提供的配置和分片权重。
- [仓库源码 ZIP · deepseek-ai/DeepSeek-V3](<https://github.com/deepseek-ai/DeepSeek-V3/archive/9b4e9788e4a3a731f7567338ed15d3ec549ce03b.zip>)　该仓库的固定快照。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
