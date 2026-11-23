# GPT-4

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

在 ProtAgents 中支持角色间对话、任务规划与调用决策，在 MAESD 用于从用户描述中识别设计意图。

## 输入、输出与 LLM 参与

- **输入**　自然语言请求、系统或角色提示、对话历史，以及可选的工具结果。
- **输出**　任务解释、计划、文字反馈或供工具执行的调用信息。
- **LLM 参与**　它本身是通用 LLM。序列分析、结构预测等工具有各自的计算实现。

## 结果解读

不同版本、系统提示和可用的工具会影响回答。论文中使用 GPT-4 的记录不等同于公开了模型权重。

## 在六篇研究中的用法

- **ProtAgents**（在线对话）　为多个代理提供共享的通用语言模型。与科学模型分别记账。
- **MAESD**（运行时推理。另作实验对照）　论文分别评估两种后端的 MAESD，并将两个模型单独运行作基线。

使用此来源的研究组件包括 [ProtAgents 规划代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E8%A7%84%E5%88%92%E4%BB%A3%E7%90%86/ProtAgents%20%E8%A7%84%E5%88%92%E4%BB%A3%E7%90%86.md)、[ProtAgents 执行代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%90%86/ProtAgents%20%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%90%86.md)、[ProtAgents 审查代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E5%AE%A1%E6%9F%A5%E4%BB%A3%E7%90%86/ProtAgents%20%E5%AE%A1%E6%9F%A5%E4%BB%A3%E7%90%86.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[OpenAI (2023), GPT-4 Technical Report](<https://arxiv.org/abs/2303.08774>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　专有模型，通过 API 使用。

## 下载与访问

未公开可下载的模型权重。

- [GPT-4 官方模型说明](<https://developers.openai.com/api/docs/models/gpt-4>)　OpenAI 提供的模型与服务文档。

## 关联组件

[MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [ProtAgents](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
