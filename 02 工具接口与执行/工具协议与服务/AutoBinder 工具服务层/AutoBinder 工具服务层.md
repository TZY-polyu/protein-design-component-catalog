# AutoBinder 工具服务层

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

封装、路由和执行各科学模块，把结果返回给上层。

## 输入、输出与 LLM 参与

- **输入**　带参数的模块调用请求。
- **输出**　相应工具的序列化计算结果。
- **LLM 参与**　否。上游智能体选择工具。

## 结果解读

接收结构化工具请求并返回序列化结果，使上层可以用统一接口访问不同科学模块。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为系统架构。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　本文的模块封装、路由与结果返回层。 论文及其 arXiv 页面未提供可核实的整套系统仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [MCP](../MCP/MCP.md)
