# ProtAgents 群聊管理员

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

按当前对话上下文调度参与者、接收和转发消息。

## 输入、输出与 LLM 参与

- **输入**　角色列表、已有对话和各角色响应。
- **输出**　下一位发言者及广播给全组的消息。
- **LLM 参与**　本文的动态选人属于 LLM 驱动的群聊。消息转发是框架操作。

## 结果解读

GroupChatManager 根据对话安排下一位发言者并共享回复。发言调度和消息传递由不同机制承担。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为在线调度。

## 原始来源与 GitHub

- **AutoGen 的原始出处**　[Wu et al. (2023), AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](<https://arxiv.org/abs/2308.08155>)
- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　GroupChatManager 是 AutoGen 类，论文描述它在蛋白任务中的调度职责。

## 下载与访问

- [下载作者的角色定义文件](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agents.py>)　项目级 Python 源文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[AutoGen](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoGen/AutoGen.md) · [ProtAgents](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
