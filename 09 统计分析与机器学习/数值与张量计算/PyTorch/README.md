# PyTorch

为科学模型提供张量运算、自动求导和模型推理运行环境，支持在 CPU 或加速设备上运行同一类模型。

## 输入与输出

- **输入**　数值张量、模型结构和参数。训练时还需要目标函数与训练数据。
- **输出**　预测张量、中间表征、训练梯度或更新后的参数。

## 接入条件

- **LLM 参与**　运行库本身无需 LLM，可执行蛋白模型、通用 LLM 或普通神经网络。
- **运行条件**　根据操作系统和计算设备选择匹配的 CPU 或加速器软件包。单纯使用张量计算无需模型权重。

PyTorch 提供运算能力。预测量的物理含义、单位与精度由其上运行的模型决定。

## 原始来源与公开实现

Paszke 等（2017），Automatic differentiation in PyTorch，早期系统论文。

[论文或原始出版物](https://openreview.net/pdf/25b8eee6c373d48b84e5e9c6e10e7cbbbce4ac73.pdf)

- **GitHub 仓库**　[pytorch/pytorch](https://github.com/pytorch/pytorch)
- **实现入口**　[查看源代码](https://github.com/pytorch/pytorch)

PyTorch 官方张量、自动微分及神经网络实现。

## 下载

- [下载源码快照（ZIP）](https://github.com/pytorch/pytorch/archive/e9fbc79d2e948b7a993f5a4cf2a0b865cffac67d.zip)　该链接固定到仓库中的一个提交。
- [官方安装包与平台选择](https://pytorch.org/get-started/locally/)　按平台、运行环境和加速后端选择。
- [完整系统论文（2019）](https://proceedings.neurips.cc/paper/2019/hash/bdbca288fee7f92f2bfa9f7012727740-Abstract.html)　PyTorch 的通用系统引用。
