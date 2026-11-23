# LigandMPNN

在蛋白逆折叠时把邻近非蛋白原子纳入环境表示，以评估序列与给定蛋白结构及分子上下文是否相容。

## 输入与输出

- **输入**　蛋白骨架坐标与可用的邻近小分子、金属等原子环境。评分时可另给候选序列。
- **输出**　结构条件下的序列候选、残基概率或序列评分，具体取决于任务模式。

## 接入条件

- **LLM 参与**　属于专用图神经网络，不要求通用 LLM。
- **运行条件**　作者发布的 LigandMPNN 权重和相应 PyTorch 环境。

与只描述蛋白骨架的模型相比，这一方法能使用周围原子环境。计算相容性仍需与针对用途的实验性质分开解释。

## 原始来源与公开实现

Dauparas et al. (2025), Atomic context-conditioned protein sequence design using LigandMPNN

[论文或原始出版物](https://doi.org/10.1038/s41592-025-02626-1)

- **GitHub 仓库**　[dauparas/LigandMPNN](https://github.com/dauparas/LigandMPNN)
- **实现入口**　[查看源代码](https://github.com/dauparas/LigandMPNN/blob/26ec57ac976ade5379920dbd43c7f97a91cf82de/model_utils.py)

作者仓库。该项工作于 2023 年先发布预印本。

## 下载

- [下载实现源码（ZIP）](https://github.com/dauparas/LigandMPNN/archive/26ec57ac976ade5379920dbd43c7f97a91cf82de.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [作者提供的模型参数下载清单](https://github.com/dauparas/LigandMPNN/blob/main/get_model_params.sh)　官方文件列出各检查点的来源，权重独立于源码。

## 可选调用接口

- **LigandMPNN MCP**　从本地安装的 LigandMPNN 加载推理及评分入口，权重需按上游项目说明准备。 [接口源码](https://github.com/MacromNex/ligandmpnn_mcp/blob/772a389ed01a9421ba11c6207be2dd0a55e8f510/scripts/lib/repo_interface.py) · [适配器下载](https://github.com/MacromNex/ligandmpnn_mcp/archive/772a389ed01a9421ba11c6207be2dd0a55e8f510.zip)
