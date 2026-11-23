# CUDA

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

为 NVIDIA GPU 上的加速计算提供编译器、运行时和基础库，供深度学习框架或科学程序使用。

## 输入、输出与 LLM 参与

- **输入**　支持 CUDA 的 GPU、兼容驱动、软件程序或由框架提交的张量与计算任务。
- **输出**　GPU 运算结果，或由编译工具生成的可执行程序和库。
- **LLM 参与**　计算平台本身无需 LLM。

## 结果解读

同一研究中的不同软件可能要求不同的 CUDA 工具包或运行时版本，下载时应区分工具包与显卡驱动。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录／计算层）　为结构与序列模型提供加速计算。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Nickolls et al. (2008), Scalable Parallel Programming with CUDA](<https://research.nvidia.com/publication/2008-03_scalable-parallel-programming-cuda>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　完整工具包由 NVIDIA 分发。不以示例仓库代替工具包。

## 下载与访问

- [NVIDIA CUDA Toolkit 下载](<https://developer.nvidia.com/cuda-downloads>)　按操作系统、架构和发行方式选择官方工具包。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [PyTorch](../PyTorch/PyTorch.md)
