# AutoBinder 用户界面

[工具接口与执行](../../README.md) / 用户与服务入口

## 用途

提供人机交互入口。正文明确描述命令行，架构图同时列出聊天入口。

## 输入、输出与 LLM 参与

- **输入**　研究者输入的自然语言目标或命令。
- **输出**　传至智能体的请求。展示返回结果。
- **LLM 参与**　否。理解请求时由下游智能体调用。

## 结果解读

命令行入口在正文有说明，聊天入口列于架构图。意图解析发生在后续智能体层。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为系统架构。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　本系统的人机交互层见图1。终端和聊天是通用界面形式。 论文及其 arXiv 页面未提供可核实的整套系统仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
