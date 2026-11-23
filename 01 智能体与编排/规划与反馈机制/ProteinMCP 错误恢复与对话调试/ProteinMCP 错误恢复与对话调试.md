# ProteinMCP 错误恢复与对话调试

[智能体与编排](../../README.md) / 规划与反馈机制

## 用途

定位失败步骤并恢复运行。

## 输入、输出与 LLM 参与

- **输入**　MCP 错误日志、运行状态、可选的用户反馈。
- **输出**　重试、更正的代码或技能文件、重新执行结果。
- **LLM 参与**　需要通用 LLM 分析和修改。可有人参与。

## 结果解读

日志和用户反馈帮助定位失败步骤。修订后的工具或技能可以再次执行，运行结果用于确认是否解决问题。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为异常处理。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **Claude Code 的原始出处**　[Anthropic, Claude Code 官方产品（无单独原始研究论文）](<https://github.com/anthropics/claude-code>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　论文描述的重试和对话式调试机制。

## 下载与访问

- [下载 mcp_docker_debug.md](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/mcp-skills/mcp_docker_debug.md>)　作者提供的容器故障排查文档。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[Claude Code](../../%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Claude%20Code/Claude%20Code.md) · [ProteinMCP](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
