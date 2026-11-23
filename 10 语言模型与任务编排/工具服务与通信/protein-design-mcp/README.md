# protein-design-mcp

将蛋白结构预测、生成与分析引擎接入统一的 MCP 工具服务，使上游程序可以查询参数和启动计算。

## 输入与输出

- **输入**　指定的工具名与结构化参数。具体工具可接收序列、结构文件或任务标识。
- **输出**　按工具返回计算产物、指标、错误或任务状态，供上层智能体记录和判断。

## 接入条件

- **LLM 参与**　通信与分派本身无需 LLM。运行时可由通用 LLM 选工具，底层模型因工具而异。
- **运行条件**　Python 运行环境、MCP 客户端以及需要调用的具体科学引擎。源代码归档未包括所有外部模型、硬件或商业许可证。

每个工具有自己的参数、结果类型和外部依赖。部署时应使服务版本与工具清单保持一致。

## 原始来源与公开实现

Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design

[论文或原始出版物](https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1)

- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](https://github.com/jasonkim8652/protein-design-mcp)
- **实现入口**　[查看源代码](https://github.com/jasonkim8652/protein-design-mcp/tree/e9e1c89fedf335aad03a2564b93682dc4748494d/src/protein_design_mcp)

开发者公开的服务实现和工具清单。

## 下载

- [固定版本源码 ZIP](https://github.com/jasonkim8652/protein-design-mcp/archive/e9e1c89fedf335aad03a2564b93682dc4748494d.zip)　包含上述实现及其同仓库配套文件。
