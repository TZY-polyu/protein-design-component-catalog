# AutoBinder 任务规划层

[智能体与编排](../../README.md) / 规划与反馈机制

## 用途

解释意图，分解任务并说明调用顺序。核心科学步骤由预设流程限定。

## 输入、输出与 LLM 参与

- **输入**　自然语言目标、会话上下文、可调用工具。
- **输出**　任务解释、工具选择、结构化调用请求及必要的恢复方案。
- **LLM 参与**　是。在线规划、解析和解释。

## 结果解读

论文围绕给定工作流评估指令理解、工具选择和错误恢复。每次调用科学模块后，结果再返回会话。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为系统核心。通过提示任务评估。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　Ge 等在本篇提出及描述系统集成。 论文及其 arXiv 页面未提供可核实的整套系统仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [DeepSeek（版本未披露）](../../%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/DeepSeek%EF%BC%88%E7%89%88%E6%9C%AC%E6%9C%AA%E6%8A%AB%E9%9C%B2%EF%BC%89/DeepSeek%EF%BC%88%E7%89%88%E6%9C%AC%E6%9C%AA%E6%8A%AB%E9%9C%B2%EF%BC%89.md) · [Qwen3](../../%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Qwen3/Qwen3.md)
