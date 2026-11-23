# BindCraft

在一个软件流程中协调蛋白结构和序列模型，计算蛋白结合候选并汇总其预测质量。

## 输入与输出

- **输入**　目标蛋白结构以及工作流配置。
- **输出**　候选蛋白的序列、结构文件，以及各候选的计算质量记录。

## 接入条件

- **LLM 参与**　依赖结构和序列专用模型，无需通用对话 LLM。
- **运行条件**　需分别取得依赖和模型参数。PyRosetta 的商业使用受其许可约束。

输出记录是对候选的计算表征。仓库中的流程代码与其依赖模型的权重分别由相应项目分发。

## 原始来源与公开实现

Pacesa et al. (2025), One-shot design of functional protein binders with BindCraft

[论文或原始出版物](https://doi.org/10.1038/s41586-025-09429-6)

- **GitHub 仓库**　[martinpacesa/BindCraft](https://github.com/martinpacesa/BindCraft)
- **实现入口**　[查看源代码](https://github.com/martinpacesa/BindCraft)

上游作者仓库

## 下载

- [项目源码 ZIP](https://github.com/martinpacesa/BindCraft/archive/7713aa0d0d351e4117a8befeb8541f3a8ebd3368.zip)　公开项目的源码快照。

## 可选调用接口

- **BindCraft MCP**　实现连接 BindCraft 的设计及评估步骤。后端使用 PyRosetta，其学术非商业及商业授权条件分别适用。 [接口源码](https://github.com/MacromNex/bindcraft_mcp/blob/acedaa2b8369bacf4db3b63954e154229725df94/scripts/run_bindcraft.py) · [适配器下载](https://github.com/MacromNex/bindcraft_mcp/archive/acedaa2b8369bacf4db3b63954e154229725df94.zip)
