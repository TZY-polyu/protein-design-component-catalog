# ProteinMPNN

根据蛋白质骨架周围的几何环境，估计各位置可以容纳的氨基酸，用于结构条件下的序列建模和候选比较。

## 输入与输出

- **输入**　一个或多个蛋白链的骨架原子坐标、链标识，以及需保留或评估的位置。
- **输出**　与输入骨架对应的氨基酸序列，也可得到模型对序列的对数概率或位置概率。

## 接入条件

- **LLM 参与**　推理依赖图神经网络 ProteinMPNN，无需通用对话 LLM。
- **运行条件**　Python、PyTorch、作者的模型检查点，以及可解析的蛋白骨架坐标。

序列分数反映模型与给定骨架的匹配程度。功能、结合强度和可表达性需要其他证据。

## 原始来源与公开实现

Dauparas et al. (2022), Robust deep learning–based protein sequence design using ProteinMPNN

[论文或原始出版物](https://doi.org/10.1126/science.add2187)

- **GitHub 仓库**　[dauparas/ProteinMPNN](https://github.com/dauparas/ProteinMPNN)
- **实现入口**　[查看源代码](https://github.com/dauparas/ProteinMPNN/blob/8907e6671bfbfc92303b5f79c4b5e6ce47cdef57/protein_mpnn_run.py)

作者同时发布模型代码、推理入口和训练所得权重。

## 下载

- [通用模型检查点](https://github.com/dauparas/ProteinMPNN/tree/main/vanilla_model_weights)　选择与模型配置匹配的权重文件。
- [固定版本源码 ZIP](https://github.com/dauparas/ProteinMPNN/archive/8907e6671bfbfc92303b5f79c4b5e6ce47cdef57.zip)　包含上述实现及其同仓库配套文件。

## 可选调用接口

- **ProteinMPNN MCP**　调用本地 ProteinMPNN 程序和检查点，提供提交作业及文件结果接口。 [接口源码](https://github.com/MacromNex/proteinmpnn_mcp/blob/771996b9335cac17e0cbea9454c240389a0451ac/scripts/simple_design.py) · [适配器下载](https://github.com/MacromNex/proteinmpnn_mcp/archive/771996b9335cac17e0cbea9454c240389a0451ac.zip)
