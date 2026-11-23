# GPT-5

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

BioDesignBench 正文以 GPT-5 为受测智能体标签，比较其在不同工具呈现方式下的任务执行表现。

## 输入、输出与 LLM 参与

- **输入**　任务说明、工具接口及当前工具调用返回的观察。
- **输出**　后续工具调用或最终答复，以及由运行器记录的决策轨迹。
- **LLM 参与**　它本身是通用 LLM。

## 结果解读

补充材料将该实验的 API 模型字符串具体写成 gpt-5.2。正文标签与实际请求标识应同时保留。

## 在六篇研究中的用法

- **BioDesignBench**（运行时决策／模型比较）　正文以 GPT-5 为标签，补充方法给出的 API 字符串为 gpt-5.2。

使用此来源的研究组件包括 [BioDesignBench 评估深度干预](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%AF%84%E4%BC%B0%E6%B7%B1%E5%BA%A6%E5%B9%B2%E9%A2%84/BioDesignBench%20%E8%AF%84%E4%BC%B0%E6%B7%B1%E5%BA%A6%E5%B9%B2%E9%A2%84.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[OpenAI (2025), GPT-5 System Card（官方系统卡）](<https://openai.com/index/gpt-5-system-card/>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　专有模型。未公开模型源码仓库。

## 下载与访问

未公开可下载的模型权重。

- [GPT-5 官方模型说明](<https://developers.openai.com/api/docs/models/gpt-5>)　官方模型说明与 API 入口。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [GPT-5.2](../GPT-5.2/GPT-5.2.md)
