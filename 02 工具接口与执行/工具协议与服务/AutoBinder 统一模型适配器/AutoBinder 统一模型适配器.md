# AutoBinder 统一模型适配器

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

统一 DeepSeek 的 API 接入与 Qwen3 的本地推理服务。

## 输入、输出与 LLM 参与

- **输入**　统一推理请求、模型后端配置。
- **输出**　发送至相应后端的请求及返回的响应。
- **LLM 参与**　接口本身否。处理的是 LLM 推理请求。

## 结果解读

同一编排层可连接 DeepSeek 的兼容 API 或由 vLLM 服务的 Qwen。兼容的消息格式不决定底层模型来源。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为系统架构。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **OpenAI-compatible API (DeepSeek) 的原始出处**　[DeepSeek 官方 API 接口文档（无独立提出论文）](<https://api-docs.deepseek.com/en/>)
- **vLLM 的原始出处**　[Kwon et al. (2023), Efficient Memory Management for Large Language Model Serving with PagedAttention](<https://arxiv.org/abs/2309.06180>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　适配层由本文描述。外部接口兼容性见 DeepSeek 文档，本地推理引擎见 vLLM 原始论文。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [OpenAI-compatible API (DeepSeek)](../OpenAI-compatible%20API%20%28DeepSeek%29/OpenAI-compatible%20API%20%28DeepSeek%29.md) · [vLLM](../../%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/vLLM/vLLM.md)
