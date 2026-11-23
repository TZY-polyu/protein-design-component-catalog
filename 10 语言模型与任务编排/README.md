# 语言模型与任务编排

运行通用或生物医学文本模型，为任务规划、工具调用和检索建立执行框架。

[返回功能目录](../README.md)

## 文本语言模型与推理服务

| 组件 | 主要用途 |
| --- | --- |
| [BioMedLM](%E6%96%87%E6%9C%AC%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E6%8E%A8%E7%90%86%E6%9C%8D%E5%8A%A1/BioMedLM/README.md) | 在生物医学文献上训练的自然语言模型，用于专业文本续写、问答，或作为下游任务微调的起点。 |
| [DeepSeek-V3](%E6%96%87%E6%9C%AC%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E6%8E%A8%E7%90%86%E6%9C%8D%E5%8A%A1/DeepSeek-V3/README.md) | 用于自然语言理解、文本和代码生成，可作为对话程序的推理后端。 |
| [Qwen3](%E6%96%87%E6%9C%AC%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E6%8E%A8%E7%90%86%E6%9C%8D%E5%8A%A1/Qwen3/README.md) | 用公开权重进行文本生成和对话推理。支持工具调用的宿主还可以把模型生成的请求交给相应工具执行。 |
| [vLLM](%E6%96%87%E6%9C%AC%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E6%8E%A8%E7%90%86%E6%9C%8D%E5%8A%A1/vLLM/README.md) | 将已支持的生成模型部署成推理服务，以批处理和显存管理处理同时到达的请求。 |

## 任务规划与智能体框架

| 组件 | 主要用途 |
| --- | --- |
| [AutoGen](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/AutoGen/README.md) | 为多个智能体建立会话，管理消息路由、角色和工具执行。 |
| [BioinfoMCP](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/BioinfoMCP/README.md) | 将现有生物信息命令行工具的帮助文档转成可以由智能体访问的 MCP 服务，并提供工具接口验证框架。 |
| [Biomni](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/Biomni/README.md) | 用通用 LLM 对生物医学任务进行规划，并调用计算工具、数据库或程序执行相应分析。 |
| [Paper2Agent](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/Paper2Agent/README.md) | 将论文附带的科研代码、教程与文档整理成可由智能体调用的工具，使文献方法可以交互使用。 |
| [ProtAgents](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/ProtAgents/README.md) | 以多角色对话协调文献检索和蛋白结构、力学分析。公开实现包括代理定义、已注册的工具函数和示例笔记本。 |
| [ProteinMCP](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/ProteinMCP/README.md) | 管理蛋白计算工具的 MCP 服务，并可由智能体通过工作流技能调用不同工具。提供服务创建、部署和管理代码。 |
| [pskill](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/pskill/README.md) | 创建、检查和安装可复用的工作流说明，并查看每项技能声明的工具依赖。 |
| [ReAct](%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E4%B8%8E%E6%99%BA%E8%83%BD%E4%BD%93%E6%A1%86%E6%9E%B6/ReAct/README.md) | 让语言模型依据任务和环境反馈选择下一项动作，使工具调用结果参与后续决策。 |

## 工具服务与通信

| 组件 | 主要用途 |
| --- | --- |
| [FastMCP](%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E4%B8%8E%E9%80%9A%E4%BF%A1/FastMCP/README.md) | 把可调用函数、资源和提示模板暴露成 MCP 服务，让工具宿主发现接口、传入参数并读取结果。 |
| [MCP Python SDK](%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E4%B8%8E%E9%80%9A%E4%BF%A1/MCP%20Python%20SDK/README.md) | 提供 Model Context Protocol 的 Python 客户端和服务端实现，支持发现工具、传递参数和接收响应。 |
| [pmcp](%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E4%B8%8E%E9%80%9A%E4%BF%A1/pmcp/README.md) | 查找工具服务、检查安装状态并管理本地注册，也提供从现有代码创建 MCP 服务的入口。 |
| [protein-design-mcp](%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E4%B8%8E%E9%80%9A%E4%BF%A1/protein-design-mcp/README.md) | 将蛋白结构预测、生成与分析引擎接入统一的 MCP 工具服务，使上游程序可以查询参数和启动计算。 |
