# ProtAgents 用户代理

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

代表人类提出问题，提供批准或追加要求的入口。

## 输入、输出与 LLM 参与

- **输入**　人类给出的任务、追问或审批意见。
- **输出**　进入群聊的任务、反馈或计划确认。
- **LLM 参与**　本身不要求。承担人机接口。

## 结果解读

UserProxyAgent 将任务、批准或追加要求写入共享对话。输入可以来自研究者，角色本身可独立于通用模型。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为在线交互。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **AutoGen 的原始出处**　[Wu et al. (2023), AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](<https://arxiv.org/abs/2308.08155>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　角色定义和职责见 ProtAgents，UserProxyAgent 类源自 AutoGen。

## 下载与访问

- [下载作者的角色定义文件](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agents.py>)　项目级 Python 源文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[AutoGen](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoGen/AutoGen.md) · [ProtAgents](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
