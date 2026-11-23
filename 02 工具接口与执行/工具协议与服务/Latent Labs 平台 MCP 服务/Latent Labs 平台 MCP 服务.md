# Latent Labs 平台 MCP 服务

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

将代理接入 Latent Labs Platform 的后端能力。

## 输入、输出与 LLM 参与

- **输入**　代理的工具请求及平台返回的数据。
- **输出**　对模型、评分工具、平台服务与计算资源的标准访问。
- **LLM 参与**　否，协议传输和工具访问。调用者为 LLM。

## 结果解读

通用 MCP 协议提供交互规范，平台服务封装自有资源。把协议源码下载到本地不会获得商业平台后端。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为在线工具接口。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **MCP 的原始出处**　[Anthropic (2024), Introducing the Model Context Protocol（官方首发公告）](<https://www.anthropic.com/news/model-context-protocol>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　该平台的 MCP 服务端由本文描述。协议来自 Anthropic，引用发布文档。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [MCP](../MCP/MCP.md)
