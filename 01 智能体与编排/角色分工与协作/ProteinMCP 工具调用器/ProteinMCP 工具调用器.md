# ProteinMCP 工具调用器

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

连接任务计划和具体科学工具。

## 输入、输出与 LLM 参与

- **输入**　主智能体选定的工具及参数。
- **输出**　MCP 调用及其返回值。
- **LLM 参与**　由通用 LLM 选择调用。调用传输本身无需 LLM。

## 结果解读

将计划中选定的工具及参数发往对应服务，并把结构化结果交回编排层。实际计算由服务后端承担。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为核心编排。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **MCP 的原始出处**　[Anthropic (2024), Introducing the Model Context Protocol（官方首发公告）](<https://www.anthropic.com/news/model-context-protocol>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　图1b的调用组件，底层使用 MCP 协议。

## 下载与访问

- [下载 architecture.md](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/docs/architecture.md>)　作者提供的系统架构说明。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/MCP/MCP.md) · [ProteinMCP](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
