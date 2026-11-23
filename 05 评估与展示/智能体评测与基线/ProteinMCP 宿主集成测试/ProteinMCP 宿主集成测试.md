# ProteinMCP 宿主集成测试

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

检验新服务可否被智能体正确调用。

## 输入、输出与 LLM 参与

- **输入**　新创建的 MCP 服务、测试用例。
- **输出**　通信和运行结果。
- **LLM 参与**　需要宿主 LLM。方法详述 Claude Code，图2另列 Gemini。

## 结果解读

测试结果说明新服务能否被指定宿主发现和调用。作者详细描述 Claude Code，Gemini 的使用范围仅在架构图中出现。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为工具接入验证。Gemini 使用范围限图示。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **Claude Code 的原始出处**　[Anthropic, Claude Code 官方产品（无单独原始研究论文）](<https://github.com/anthropics/claude-code>)
- **Gemini 的原始出处**　[Gemini Team (2023), Gemini: A Family of Highly Capable Multimodal Models（系列来源）](<https://arxiv.org/abs/2312.11805>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文的集成测试。图2另列 Gemini，方法部分详述 Claude Code。

## 下载与访问

- [下载 mcp_creation_validator.md](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/mcp-skills/mcp_creation_validator.md>)　作者发布的服务验证说明。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[Claude Code](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Claude%20Code/Claude%20Code.md) · [Gemini](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Gemini/Gemini.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
