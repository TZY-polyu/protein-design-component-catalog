# ProteinMCP 技能解析器（Skill Parser）

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

让主智能体理解可复用的流程。

## 输入、输出与 LLM 参与

- **输入**　用户命令或请求、Markdown 技能文件。
- **输出**　待执行步骤、参数与工具依赖。
- **LLM 参与**　需要通用 LLM 参与技能解释。独立实现未说明。

## 结果解读

主智能体利用技能文档确定步骤和工具依赖。架构图给出了这一职责，论文未列独立解析模型。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为核心编排。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **Claude Code 的原始出处**　[Anthropic, Claude Code 官方产品（无单独原始研究论文）](<https://github.com/anthropics/claude-code>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　图1b的编排职责，由宿主智能体解释技能。

## 下载与访问

- [下载 architecture.md](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/docs/architecture.md>)　作者提供的系统架构说明。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[Claude Code](../../%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Claude%20Code/Claude%20Code.md) · [ProteinMCP](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
