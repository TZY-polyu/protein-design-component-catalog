# Open Targets Platform MCP

通过官方客户端检索 Open Targets 中的基因、疾病和药物条目，并查询平台所收录的关联证据。适合需要标准化标识符或将证据引入分析程序的任务。

## 输入与输出

- **输入**　实体名称、标准标识符，或带变量的 GraphQL 查询。批量查询可使用多组变量。
- **输出**　匹配实体及其标识符，或查询选中的关联、支持证据与其他字段，按结构化数据返回。

## 接入条件

- **LLM 参与**　检索和结果解析均无需 LLM。需要自然语言问答时，可由上层程序另行调用模型。
- **运行条件**　Python 环境及项目依赖，或官方容器。客户端可在本地运行，默认查询在线 Open Targets GraphQL API。代码许可为 Apache-2.0。

关联证据与平台数据版本相关。输出中的关联分数表达证据支持程度，不能单独确立因果作用。

## 原始来源与公开实现

Open Targets 团队发布的 Platform MCP 软件。未查到该 MCP 客户端的独立原始论文。

- **GitHub 仓库**　[opentargets/platform-mcp](https://github.com/opentargets/platform-mcp)
- **实现入口**　[查看源代码](https://github.com/opentargets/platform-mcp/blob/742f7ef452a2d4a2bfdace32e9fe689fc6c717c1/src/open_targets_platform_mcp/client/graphql.py)

Open Targets 官方发布。仓库包括 GraphQL 客户端、工具定义和本地服务程序。

## 下载

- [固定版本源码 ZIP](https://github.com/opentargets/platform-mcp/archive/742f7ef452a2d4a2bfdace32e9fe689fc6c717c1.zip)　该快照包含组件实现及配套项目文件。
- [平台 API 说明](https://platform-docs.opentargets.org/data-access/graphql-api)　说明平台的可查询数据和 API。
