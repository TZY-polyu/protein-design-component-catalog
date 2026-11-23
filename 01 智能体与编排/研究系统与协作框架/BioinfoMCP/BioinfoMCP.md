# BioinfoMCP

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

将现有生物信息命令行工具的帮助文档转成可以由智能体访问的 MCP 服务，并提供工具接口验证框架。

## 输入、输出与 LLM 参与

- **输入**　命令行工具的手册或帮助文本、拟接入的程序和评测任务。
- **输出**　生成的 MCP 服务代码、参数定义和验证记录。
- **LLM 参与**　转换器用通用 LLM 阅读文档和生成封装。封装部署后，实际科学计算由被包装的程序执行。

## 结果解读

ProteinMCP 将其列为外部平台对照。生成的封装仍需原命令行工具及必要的运行环境。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinMCP 平台功能定性对照](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/ProteinMCP%20%E5%B9%B3%E5%8F%B0%E5%8A%9F%E8%83%BD%E5%AE%9A%E6%80%A7%E5%AF%B9%E7%85%A7/ProteinMCP%20%E5%B9%B3%E5%8F%B0%E5%8A%9F%E8%83%BD%E5%AE%9A%E6%80%A7%E5%AF%B9%E7%85%A7.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Widjaja et al. (2025), BioinfoMCP: A Unified Platform Enabling MCP Interfaces in Agentic Bioinformatics](<https://arxiv.org/abs/2510.02139>)
- **GitHub 仓库**　[florensiawidjaja/BioinfoMCP](<https://github.com/florensiawidjaja/BioinfoMCP>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [仓库源码 ZIP · florensiawidjaja/BioinfoMCP](<https://github.com/florensiawidjaja/BioinfoMCP/archive/7ada7918b9e515604d3c0ae264d3a9af10bf6e54.zip>)　该仓库的固定快照。
