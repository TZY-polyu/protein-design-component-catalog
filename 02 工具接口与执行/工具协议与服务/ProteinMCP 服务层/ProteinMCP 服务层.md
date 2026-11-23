# ProteinMCP 服务层

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

让编排器通过同一协议访问异构软件。作者报告集成 38 个服务器。

## 输入、输出与 LLM 参与

- **输入**　工具标识、计算请求、对应参数。
- **输出**　结构化返回或结果文件。
- **LLM 参与**　协议本身无需。主智能体通过它发起调用。

## 结果解读

论文报告集成 38 个服务器。同期项目目录还区分自研包装和社区包装。工具出现在目录中不等于各案例都调用过它。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为平台架构。图1同时包含资源、依赖与工具，未提供38个服务标识的逐项对照。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **MCP 的原始出处**　[Anthropic (2024), Introducing the Model Context Protocol（官方首发公告）](<https://www.anthropic.com/news/model-context-protocol>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文实现服务器集成层，MCP 协议由 Anthropic 发布。

## 下载与访问

- [下载 architecture.md](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/docs/architecture.md>)　作者提供的系统架构说明。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[MCP](../MCP/MCP.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
