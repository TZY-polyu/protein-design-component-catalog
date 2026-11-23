# pskill

创建、检查和安装可复用的工作流说明，并查看每项技能声明的工具依赖。

## 输入与输出

- **输入**　技能名称、说明、步骤标题与文本、依赖的 MCP 服务名称，或已保存的步骤文件。
- **输出**　生成技能 Markdown 文件，可列出可用技能、展示技能详情并报告本机安装状态。

## 接入条件

- **LLM 参与**　创建和管理技能文件的基本命令无需通用 LLM。由模型解释并执行文档是后续环节。
- **运行条件**　需要 Python、项目打包依赖和可写的本地配置目录。运行技能所需的工具应另行安装。

仓库中 pskill 是可直接调用的命令行入口。安装技能会将说明文件注册到对应工作环境，具体计算仍由文档引用的工具提供。

## 原始来源与公开实现

Xu 等，ProteinMCP: An agentic AI framework for autonomous protein engineering，Protein Science，2026。

[论文或原始出版物](https://doi.org/10.1002/pro.70547)

- **GitHub 仓库**　[charlesxu90/ProteinMCP](https://github.com/charlesxu90/ProteinMCP)
- **实现入口**　[查看源代码](https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/skill_cli.py)

与 ProteinMCP 一起发布，技能管理与生成逻辑位于 src/skill。

## 下载

- [下载固定版本源码（ZIP）](https://github.com/charlesxu90/ProteinMCP/archive/f708d415ef03d9da7107046373160a2776cbd5ed.zip)　解压后可按上面的实现入口定位组件。
- [技能生成与管理模块](https://github.com/charlesxu90/ProteinMCP/tree/f708d415ef03d9da7107046373160a2776cbd5ed/src/skill)　可查阅输入格式及 Markdown 生成逻辑。
