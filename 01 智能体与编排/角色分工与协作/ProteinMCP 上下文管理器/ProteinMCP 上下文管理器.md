# ProteinMCP 上下文管理器

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

在多步任务间管理信息。

## 输入、输出与 LLM 参与

- **输入**　用户请求、执行状态、中间结果。
- **输出**　后续步骤可用的上下文。
- **LLM 参与**　属于 LLM 编排层。未报告独立模型调用。

## 结果解读

前一工具的结果成为后续步骤可读取的状态。论文用架构角色描述这项职责，未列单独的存储或推理组件。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为核心编排。按架构图归纳。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　图1b的系统内上下文管理模块。

## 下载与访问

- [下载 architecture.md](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/docs/architecture.md>)　作者提供的系统架构说明。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[ProteinMCP](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
