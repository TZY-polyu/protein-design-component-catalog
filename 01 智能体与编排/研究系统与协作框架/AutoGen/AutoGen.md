# AutoGen

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

为多个智能体建立会话，组织消息路由、角色分工和工具执行。ProtAgents 使用其早期 Python 实现。

## 输入、输出与 LLM 参与

- **输入**　角色配置、消息历史、工具函数及可选模型客户端。
- **输出**　按会话规则形成的交互记录、工具调用和任务结果。
- **LLM 参与**　框架的消息传递与函数执行可以不调用 LLM。ProtAgents 的规划、执行决策和审查角色调用 GPT-4。

## 结果解读

框架版本影响接口。复核 ProtAgents 时应对照论文使用的 pyautogen 0.2.2。

## 在六篇研究中的用法

- **ProtAgents**（系统基础设施）　创建角色、传递消息、连接工具。工作站运行 Python 3.10，配 NVIDIA GPU。

使用此来源的研究组件包括 [ProtAgents 用户代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E7%94%A8%E6%88%B7%E4%BB%A3%E7%90%86/ProtAgents%20%E7%94%A8%E6%88%B7%E4%BB%A3%E7%90%86.md)、[ProtAgents 规划代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E8%A7%84%E5%88%92%E4%BB%A3%E7%90%86/ProtAgents%20%E8%A7%84%E5%88%92%E4%BB%A3%E7%90%86.md)、[ProtAgents 执行代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%90%86/ProtAgents%20%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%90%86.md)、[ProtAgents 审查代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E5%AE%A1%E6%9F%A5%E4%BB%A3%E7%90%86/ProtAgents%20%E5%AE%A1%E6%9F%A5%E4%BB%A3%E7%90%86.md)、[ProtAgents 群聊管理员](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E7%BE%A4%E8%81%8A%E7%AE%A1%E7%90%86%E5%91%98/ProtAgents%20%E7%BE%A4%E8%81%8A%E7%AE%A1%E7%90%86%E5%91%98.md)、[ProtAgents 函数注册与执行](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/ProtAgents%20%E5%87%BD%E6%95%B0%E6%B3%A8%E5%86%8C%E4%B8%8E%E6%89%A7%E8%A1%8C/ProtAgents%20%E5%87%BD%E6%95%B0%E6%B3%A8%E5%86%8C%E4%B8%8E%E6%89%A7%E8%A1%8C.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Wu et al. (2023), AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](<https://arxiv.org/abs/2308.08155>)
- **GitHub 仓库**　[microsoft/autogen](<https://github.com/microsoft/autogen>)
- **归属说明**　AutoGen 原作者仓库。本研究使用 pyautogen 0.2.2。

## 下载与访问

- [论文使用的 pyautogen 0.2.2](<https://pypi.org/project/pyautogen/0.2.2/#files>)　按已报告版本提供官方 Python 发布文件。
- [仓库源码 ZIP · microsoft/autogen](<https://github.com/microsoft/autogen/archive/8390985108cb1e3881f5f7297765758d8ad2540c.zip>)　该仓库的固定快照。

## 关联组件

[ProtAgents](../ProtAgents/ProtAgents.md)
