# Claude Code

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

在开发环境中理解用户指令、读取上下文并调用工具或程序。ProteinMCP 用它解释研究任务、工作流技能和工具描述。

## 输入、输出与 LLM 参与

- **输入**　用户指令、可访问的文件上下文、工具列表和经过配置的模型服务。
- **输出**　模型答复、工具调用、执行记录及被调用工具产生的文件。
- **LLM 参与**　需要 Claude 系列通用 LLM 提供推理。底层科学工具按各自的实现运行。

## 结果解读

Claude Code 是面向使用者的智能体客户端。下载它可获得软件客户端，不会同时获得 Claude 模型权重。

## 在六篇研究中的用法

- **ProteinMCP**（核心编排。三个案例均使用）　解释请求并执行整项工作流。

使用此来源的研究组件包括 [ProteinMCP 技能解析器（Skill Parser）](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProteinMCP%20%E6%8A%80%E8%83%BD%E8%A7%A3%E6%9E%90%E5%99%A8%EF%BC%88Skill%20Parser%EF%BC%89/ProteinMCP%20%E6%8A%80%E8%83%BD%E8%A7%A3%E6%9E%90%E5%99%A8%EF%BC%88Skill%20Parser%EF%BC%89.md)、[ProteinMCP 错误恢复与对话调试](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/ProteinMCP%20%E9%94%99%E8%AF%AF%E6%81%A2%E5%A4%8D%E4%B8%8E%E5%AF%B9%E8%AF%9D%E8%B0%83%E8%AF%95/ProteinMCP%20%E9%94%99%E8%AF%AF%E6%81%A2%E5%A4%8D%E4%B8%8E%E5%AF%B9%E8%AF%9D%E8%B0%83%E8%AF%95.md)、[ProteinMCP 自然语言与技能命令入口](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E7%94%A8%E6%88%B7%E4%B8%8E%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3/ProteinMCP%20%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E4%B8%8E%E6%8A%80%E8%83%BD%E5%91%BD%E4%BB%A4%E5%85%A5%E5%8F%A3/ProteinMCP%20%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E4%B8%8E%E6%8A%80%E8%83%BD%E5%91%BD%E4%BB%A4%E5%85%A5%E5%8F%A3.md)、[ProteinMCP 服务生成器（MCPCreator）](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/ProteinMCP%20%E6%9C%8D%E5%8A%A1%E7%94%9F%E6%88%90%E5%99%A8%EF%BC%88MCPCreator%EF%BC%89/ProteinMCP%20%E6%9C%8D%E5%8A%A1%E7%94%9F%E6%88%90%E5%99%A8%EF%BC%88MCPCreator%EF%BC%89.md)、[ProteinMCP 宿主集成测试](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/ProteinMCP%20%E5%AE%BF%E4%B8%BB%E9%9B%86%E6%88%90%E6%B5%8B%E8%AF%95/ProteinMCP%20%E5%AE%BF%E4%B8%BB%E9%9B%86%E6%88%90%E6%B5%8B%E8%AF%95.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[Anthropic, Claude Code 官方产品（无单独原始研究论文）](<https://github.com/anthropics/claude-code>)
- **GitHub 仓库**　[anthropics/claude-code](<https://github.com/anthropics/claude-code>)
- **归属说明**　官方工具仓库。不提供底层 Claude 模型权重。

## 下载与访问

- [Claude Code 官方安装入口](<https://code.claude.com/docs/en/setup>)　按所在平台获取客户端，后端模型使用权限另计。
- [仓库源码 ZIP · anthropics/claude-code](<https://github.com/anthropics/claude-code/archive/db6aabc5910e5c82a171618dfa50b05f45ad7eb1.zip>)　该仓库的固定快照。

## 关联组件

[ProteinMCP](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
