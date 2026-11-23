# PyTorch

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

为科学模型提供张量运算、自动求导和模型推理运行环境，支持在 CPU 或加速设备上运行同一类模型。

## 输入、输出与 LLM 参与

- **输入**　数值张量、模型结构和参数。训练时另有目标函数与训练数据。
- **输出**　预测张量、中间表征、训练梯度或更新后的参数。
- **LLM 参与**　运行库本身无需 LLM，可执行蛋白模型、通用 LLM 或普通神经网络。

## 结果解读

PyTorch 提供运算能力。预测量的物理含义、单位与精度由其上运行的模型决定。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录／计算层）　为结构与序列模型提供加速计算。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Paszke et al. (2019), PyTorch: An Imperative Style, High-Performance Deep Learning Library](<https://proceedings.neurips.cc/paper/2019/hash/bdbca288fee7f92f2bfa9f7012727740-Abstract.html>)
- **GitHub 仓库**　[pytorch/pytorch](<https://github.com/pytorch/pytorch>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [官方安装包选择器](<https://pytorch.org/get-started/locally/>)　按本机系统和计算平台选择对应构建。
- [仓库源码 ZIP · pytorch/pytorch](<https://github.com/pytorch/pytorch/archive/e9fbc79d2e948b7a993f5a4cf2a0b865cffac67d.zip>)　该仓库的固定快照。

## 关联组件

[CUDA](../CUDA/CUDA.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
