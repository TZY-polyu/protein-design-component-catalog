# GPT-5.2

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

在 BioDesignBench 的补充材料中作为 GPT-5 受测条件的 API 型号，也出现在自动评审所用的模型名单中。

## 输入、输出与 LLM 参与

- **输入**　作为决策器时接收任务和工具上下文。作为评委时接收提交材料与评分标准。
- **输出**　任务行动、文字答复，或特定评分维度的评审判断。
- **LLM 参与**　它本身是通用 LLM。

## 结果解读

补充材料使用的标识是 gpt-5.2。评委标签和决策模型标签各自对应独立运行角色。

## 在六篇研究中的用法

- **BioDesignBench**（运行时决策／模型比较）　正文以 GPT-5 为标签，补充方法给出的 API 字符串为 gpt-5.2。

使用此来源的研究组件包括 [BioDesignBench 跨模型评审团](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[OpenAI (2025), Update to GPT-5 System Card: GPT-5.2（官方系统卡）](<https://openai.com/index/gpt-5-system-card-update-gpt-5-2/>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　专有通用模型。补充资料标明 API 标识 gpt-5.2，未注明 Codex 变体。

## 下载与访问

未公开可下载的模型权重。

- [GPT-5.2 官方模型说明](<https://developers.openai.com/api/docs/models/gpt-5.2>)　模型能力、可用接口和平台信息。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [GPT-5](../GPT-5/GPT-5.md)
