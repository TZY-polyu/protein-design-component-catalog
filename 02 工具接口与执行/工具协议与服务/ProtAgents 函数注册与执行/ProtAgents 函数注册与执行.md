# ProtAgents 函数注册与执行

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

固定函数库连接领域软件和智能体。智能体可调用，不能改写这些工具。

## 输入、输出与 LLM 参与

- **输入**　Python 函数、名称、用途、参数类型及说明。
- **输出**　执行代理可选择的工具及其返回结果。
- **LLM 参与**　注册和运行机制不要求。选择工具由 GPT-4 参与。

## 结果解读

智能体看到函数名称、用途和参数约定，并通过注册表执行已有实现。不同工具的原始模型和数据库各自有来源。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为工具集成。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **AutoGen 的原始出处**　[Wu et al. (2023), AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](<https://arxiv.org/abs/2308.08155>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　函数注册接口由 AutoGen 提供，ProtAgents 注册并描述自己的领域工具。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[AutoGen](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoGen/AutoGen.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
