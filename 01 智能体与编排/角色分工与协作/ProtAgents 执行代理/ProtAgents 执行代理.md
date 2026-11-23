# ProtAgents 执行代理

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

准备参数，调用预定义工具，将结果返回群聊。

## 输入、输出与 LLM 参与

- **输入**　计划、函数说明、已得到的数据及批评意见。
- **输出**　函数调用、给其他角色的结果或错误消息。
- **LLM 参与**　是，GPT-4 负责组织调用。下层计算见各工具。

## 结果解读

执行代理把计划转化为已注册函数的调用，参数错误或工具失败会以消息返回群聊，供后续处理。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为在线执行协调。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **AutoGen 的原始出处**　[Wu et al. (2023), AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](<https://arxiv.org/abs/2308.08155>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　工具执行角色由 ProtAgents 配置，基于 AutoGen 的 AssistantAgent。

## 下载与访问

- [下载作者的角色定义文件](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agents.py>)　项目级 Python 源文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[AutoGen](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoGen/AutoGen.md) · [GPT-4](../../%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/GPT-4/GPT-4.md) · [ProtAgents](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
