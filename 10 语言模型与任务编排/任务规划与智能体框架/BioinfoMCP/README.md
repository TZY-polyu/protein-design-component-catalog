# BioinfoMCP

将现有生物信息命令行工具的帮助文档转成可以由智能体访问的 MCP 服务，并提供工具接口验证框架。

## 输入与输出

- **输入**　命令行工具的手册或帮助文本、拟接入的程序和评测任务。
- **输出**　生成的 MCP 服务代码、参数定义和验证记录。

## 接入条件

- **LLM 参与**　转换器用通用 LLM 阅读文档和生成封装。封装部署后，实际科学计算由被包装的程序执行。
- **运行条件**　接口生成需要可用的通用 LLM。

生成服务代码之后，执行具体科学计算仍需要被封装的程序和相应的运行环境。

## 原始来源与公开实现

Widjaja et al. (2025), BioinfoMCP: A Unified Platform Enabling MCP Interfaces in Agentic Bioinformatics

[论文或原始出版物](https://arxiv.org/abs/2510.02139)

- **GitHub 仓库**　[florensiawidjaja/BioinfoMCP](https://github.com/florensiawidjaja/BioinfoMCP)
- **实现入口**　[查看源代码](https://github.com/florensiawidjaja/BioinfoMCP)

上游作者仓库

## 下载

- [项目源码 ZIP](https://github.com/florensiawidjaja/BioinfoMCP/archive/7ada7918b9e515604d3c0ae264d3a9af10bf6e54.zip)　公开项目的源码快照。
