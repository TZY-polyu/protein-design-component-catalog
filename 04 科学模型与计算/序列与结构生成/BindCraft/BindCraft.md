# BindCraft

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

在一个软件流程中协调蛋白结构和序列模型，计算蛋白结合候选并汇总其预测质量。

## 输入、输出与 LLM 参与

- **输入**　研究对象的三维结构、需求描述和流程配置。
- **输出**　候选蛋白的序列、结构文件，以及各候选的计算质量记录。
- **LLM 参与**　工作流程运行专用模型和科学程序，本身不依赖通用 LLM。ProteinMCP 在工作流外使用智能体调度。

## 结果解读

输出记录是对候选的计算表征。仓库中的流程代码与其依赖模型的权重分别由相应项目分发。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Pacesa et al. (2025), One-shot design of functional protein binders with BindCraft](<https://doi.org/10.1038/s41586-025-09429-6>)
- **GitHub 仓库**　[martinpacesa/BindCraft](<https://github.com/martinpacesa/BindCraft>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [仓库源码 ZIP · martinpacesa/BindCraft](<https://github.com/martinpacesa/BindCraft/archive/7713aa0d0d351e4117a8befeb8541f3a8ebd3368.zip>)　该仓库的固定快照。

## 关联组件

[BindCraft MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/BindCraft%20MCP/BindCraft%20MCP.md)
