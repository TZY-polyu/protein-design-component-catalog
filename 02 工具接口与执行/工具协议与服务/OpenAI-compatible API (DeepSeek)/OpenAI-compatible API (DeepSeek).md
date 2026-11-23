# OpenAI-compatible API (DeepSeek)

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

以与 OpenAI API 兼容的消息与工具格式访问 DeepSeek 后端，减少不同推理服务接入时需要改写的代码。

## 输入、输出与 LLM 参与

- **输入**　模型选择、会话消息、可选的工具定义，以及服务端要求的认证信息。
- **输出**　生成的文本、工具调用请求及请求状态等结构化响应。
- **LLM 参与**　接口属于通信层。实际生成回答或工具请求时调用所选 DeepSeek 通用 LLM。

## 结果解读

兼容的是调用格式。AutoBinder 的文献只给出 DeepSeek 名称，无法据此判明模型版本或权重。

## 在六篇研究中的用法

使用此来源的研究组件包括 [AutoBinder 统一模型适配器](../AutoBinder%20%E7%BB%9F%E4%B8%80%E6%A8%A1%E5%9E%8B%E9%80%82%E9%85%8D%E5%99%A8/AutoBinder%20%E7%BB%9F%E4%B8%80%E6%A8%A1%E5%9E%8B%E9%80%82%E9%85%8D%E5%99%A8.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[DeepSeek 官方 API 接口文档（无独立提出论文）](<https://api-docs.deepseek.com/en/>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　DeepSeek 官方 API 文档。兼容接口格式。

## 下载与访问

该 API 为托管接口，没有可据此确认的 AutoBinder 后端权重下载。

- [DeepSeek 官方接口入口与说明](<https://api-docs.deepseek.com/>)　在线服务，需按提供方要求申请 API 凭证。
