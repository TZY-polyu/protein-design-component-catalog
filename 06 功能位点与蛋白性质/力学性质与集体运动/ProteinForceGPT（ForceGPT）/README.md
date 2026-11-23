# ProteinForceGPT（ForceGPT）

从氨基酸序列估计蛋白在拉伸条件下的力学响应，供比较不同序列的计算力学特征。

## 输入与输出

- **输入**　氨基酸序列。模型的前向任务把序列映射为表征力学性质的模型输出。
- **输出**　前向力学预测可给出最大展开力和展开能的模型估计。

## 接入条件

- **LLM 参与**　使用 GPT 架构的专用蛋白语言模型进行推理，无需调用通用对话模型。
- **运行条件**　Python、PyTorch、Transformers 以及模型配置、分词器和公开权重。

用于拟合力学任务的数据来自模拟，结果的含义随训练数据的拉伸条件而定。

## 原始来源与公开实现

Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning

[论文或原始出版物](https://doi.org/10.1039/D4DD00013G)

- **GitHub 仓库**　[lamm-mit/ProtAgents](https://github.com/lamm-mit/ProtAgents)
- **实现入口**　[查看源代码](https://github.com/lamm-mit/ProtAgents/blob/7a73af3f746ca472a8524d1659547de7a54e65f5/ForceGPT.py)

作者的 ForceGPT.py 提供模型加载实现，agent_functions.py 含前向任务的调用函数。模型权重由同一团队单独发布。

## 下载

- [作者模型文件与权重](https://huggingface.co/lamm-mit/ProteinForceGPT/tree/main)　文件列表内可下载模型权重、配置及词表。
- [固定版本源码 ZIP](https://github.com/lamm-mit/ProtAgents/archive/7a73af3f746ca472a8524d1659547de7a54e65f5.zip)　包含上述实现及其同仓库配套文件。
