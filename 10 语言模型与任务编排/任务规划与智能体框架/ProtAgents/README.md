# ProtAgents

以多角色对话协调文献检索和蛋白结构、力学分析。公开实现包括代理定义、已注册的工具函数和示例笔记本。

## 输入与输出

- **输入**　自然语言问题，以及所需的参考文献、蛋白序列、结构文件或结构编号。
- **输出**　工具生成的结构及数值结果、表格文件与对研究问题的文字答复。

## 接入条件

- **LLM 参与**　角色间的理解、规划和审查使用通用 LLM。数值工具及专用蛋白模型分别运行。
- **运行条件**　需要 Python、兼容版本的 AutoGen 及工具依赖。作者发布的整套示例需要 OpenAI 和 Chroma 的访问凭据。只运行其中某个科学工具时，所需权重或服务由该工具决定。

任务产生哪些文件与数值取决于实际选用的工具。模型对话记录可用于复查工具选择。

## 原始来源与公开实现

Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning

[论文或原始出版物](https://doi.org/10.1039/D4DD00013G)

- **GitHub 仓库**　[lamm-mit/ProtAgents](https://github.com/lamm-mit/ProtAgents)
- **实现入口**　[查看源代码](https://github.com/lamm-mit/ProtAgents/blob/7a73af3f746ca472a8524d1659547de7a54e65f5/agents.py)

作者发布的角色定义和工具函数。

## 下载

- [固定版本源码 ZIP](https://github.com/lamm-mit/ProtAgents/archive/7a73af3f746ca472a8524d1659547de7a54e65f5.zip)　包含上述实现及其同仓库配套文件。
