# AutoBinder MCP 通信层

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

连接智能体与工具服务，规范调用并管理上下文生命周期。

## 输入、输出与 LLM 参与

- **输入**　会话配置、工具请求、上下文、返回消息。
- **输出**　建立的会话、跨进程异步消息及受管理的上下文。
- **LLM 参与**　否。可传递 LLM 生成的请求。

## 结果解读

MCP 规范定义工具通信方式，AutoBinder 的会话管理和跨进程消息处理属于该项目的实现。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为系统架构。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **MCP 的原始出处**　[Anthropic (2024), Introducing the Model Context Protocol（官方首发公告）](<https://www.anthropic.com/news/model-context-protocol>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　异步消息和上下文管理是本文的集成设计。MCP 协议原始发布方是 Anthropic（2024）。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [MCP](../MCP/MCP.md)
