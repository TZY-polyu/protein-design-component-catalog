# pmcp

查找工具服务、检查安装状态并管理本地注册，也提供从现有代码创建 MCP 服务的入口。

## 输入与输出

- **输入**　管理操作需要 MCP 服务名称或检索词。创建操作需要待包装的项目路径或仓库及相应的说明。
- **输出**　可用服务列表、安装或注册状态，以及按所选操作生成的服务文件和配置。

## 接入条件

- **LLM 参与**　查询和管理已有服务无需通用 LLM。用 pmcp create 自动生成工具服务时，作者的创建流程会调用 LLM。
- **运行条件**　需要 Python、项目打包依赖和可写的本地配置目录。安装或生成服务时，还取决于目标程序的依赖、网络和所选模型服务配置。

这个命令行程序负责服务生命周期。它可以独立于蛋白质计算程序列出服务和检查配置，实际科学计算能力取决于所安装的后端。

## 原始来源与公开实现

Xu 等，ProteinMCP: An agentic AI framework for autonomous protein engineering，Protein Science，2026。

[论文或原始出版物](https://doi.org/10.1002/pro.70547)

- **GitHub 仓库**　[charlesxu90/ProteinMCP](https://github.com/charlesxu90/ProteinMCP)
- **实现入口**　[查看源代码](https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp_cli.py)

与 ProteinMCP 一起发布，可通过独立的 pmcp 命令使用。

## 下载

- [下载固定版本源码（ZIP）](https://github.com/charlesxu90/ProteinMCP/archive/f708d415ef03d9da7107046373160a2776cbd5ed.zip)　解压后可按上面的实现入口定位组件。
- [服务管理源码](https://github.com/charlesxu90/ProteinMCP/tree/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp)　含创建与安装模块。
