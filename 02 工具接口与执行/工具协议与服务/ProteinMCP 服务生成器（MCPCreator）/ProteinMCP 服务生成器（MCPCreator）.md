# ProteinMCP 服务生成器（MCPCreator）

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

接入新工具，识别示例、验证功能、生成脚本和文档、更新配置。

## 输入、输出与 LLM 参与

- **输入**　本地或 GitHub 软件仓库、目标函数、输出目录。
- **输出**　可供宿主调用的 MCP 服务及说明。
- **LLM 参与**　需要通用 LLM。作者使用 Claude 分析和生成。

## 结果解读

它将现有软件功能包装并登记为服务。生成的接口沿用上游软件，科学算法仍应追溯至原作者。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为平台建置／扩展。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **Claude Code 的原始出处**　[Anthropic, Claude Code 官方产品（无单独原始研究论文）](<https://github.com/anthropics/claude-code>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文开发 MCP 创建流程，调用 Claude 产生封装代码。

## 下载与访问

- [下载 mcp_creator.py](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/mcp_creator.py>)　项目的服务创建器源码。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[Claude Code](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Claude%20Code/Claude%20Code.md) · [FastMCP](../FastMCP/FastMCP.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
