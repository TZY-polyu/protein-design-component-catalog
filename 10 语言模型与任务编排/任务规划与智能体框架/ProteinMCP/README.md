# ProteinMCP

管理蛋白计算工具的 MCP 服务，并可由智能体通过工作流技能调用不同工具。提供服务创建、部署和管理代码。

## 输入与输出

- **输入**　自然语言任务或技能命令，以及相应的序列、结构、实验标签等输入资料。
- **输出**　所选工具产生的计算结果和报告。开发或管理任务还可产生新封装和服务注册状态。

## 接入条件

- **LLM 参与**　命令行中的服务管理与单项计算可独立运行。使用自然语言技能编排时需要兼容的通用 LLM 宿主。
- **运行条件**　Python 及对应 MCP 服务运行环境。交互式技能需要兼容宿主。计算引擎按上游分别配置，部分需要 GPU。

服务管理与具体科学模型可以分别使用。选择某个工具前应核对该工具的权重、资源和输入要求。

## 原始来源与公开实现

Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering

[论文或原始出版物](https://doi.org/10.1002/pro.70547)

- **GitHub 仓库**　[charlesxu90/ProteinMCP](https://github.com/charlesxu90/ProteinMCP)
- **实现入口**　[查看源代码](https://github.com/charlesxu90/ProteinMCP/tree/ae90810d0f354272ca33e4a61892499760b61c1d/src)

作者仓库中包含软件源码、服务配置和技能文件。

## 下载

- [固定版本源码 ZIP](https://github.com/charlesxu90/ProteinMCP/archive/ae90810d0f354272ca33e4a61892499760b61c1d.zip)　包含上述实现及其同仓库配套文件。
