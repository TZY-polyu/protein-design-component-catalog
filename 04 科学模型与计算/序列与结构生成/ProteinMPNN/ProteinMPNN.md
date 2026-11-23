# ProteinMPNN

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

根据蛋白质骨架周围的几何环境，估计各位置可以容纳的氨基酸，用于结构条件下的序列建模和候选比较。

## 输入、输出与 LLM 参与

- **输入**　一个或多个蛋白链的骨架原子坐标、链标识，以及需保留或评估的位置。
- **输出**　与输入骨架对应的氨基酸序列，也可得到模型对序列的对数概率或位置概率。
- **LLM 参与**　推理依赖图神经网络 ProteinMPNN，无需通用对话 LLM。

## 结果解读

序列分数反映模型与给定骨架的匹配程度。功能、结合强度和可表达性需要其他证据。

## 在六篇研究中的用法

- **AutoBinder Agent**（已整合的科学模块）　为给定骨架进行序列设计并对序列排序。
- **MAESD**（运行时推理。另作实验对照）　在后续轮次做结构条件序列设计。也独立运行作基线。
- **ProteinMCP**（架构目录、案例2图中家族名）　提供结构条件序列设计。
- **BioDesignBench**（运行时／序列设计）　在指定骨架上做逆折叠，获得候选序列。

使用此来源的研究组件包括 [MAESD 序列生成智能体](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E5%BA%8F%E5%88%97%E7%94%9F%E6%88%90%E6%99%BA%E8%83%BD%E4%BD%93/MAESD%20%E5%BA%8F%E5%88%97%E7%94%9F%E6%88%90%E6%99%BA%E8%83%BD%E4%BD%93.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Dauparas et al. (2022), Robust deep learning–based protein sequence design using ProteinMPNN](<https://doi.org/10.1126/science.add2187>)
- **GitHub 仓库**　[dauparas/ProteinMPNN](<https://github.com/dauparas/ProteinMPNN>)
- **归属说明**　序列设计模型原始论文。

## 下载与访问

- [通用模型权重目录](<https://github.com/dauparas/ProteinMPNN/tree/main/vanilla_model_weights>)　作者随代码发布的检查点，区别于单独列出的可溶蛋白模型 MPNNsol。
- [仓库源码 ZIP · dauparas/ProteinMPNN](<https://github.com/dauparas/ProteinMPNN/archive/8907e6671bfbfc92303b5f79c4b5e6ce47cdef57.zip>)　该仓库的固定快照。

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [design_binder](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_binder/design_binder.md) · [design_fold](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_fold/design_fold.md) · [design_sequence](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_sequence/design_sequence.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [MPNNsol](../MPNNsol/MPNNsol.md) · [ProteinMPNN MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ProteinMPNN%20MCP/ProteinMPNN%20MCP.md)
