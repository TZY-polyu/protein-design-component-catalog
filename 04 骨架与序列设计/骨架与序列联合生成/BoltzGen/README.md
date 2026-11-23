# BoltzGen

按指定分子背景和约束进行生成式设计，产生待评估的蛋白或肽候选。

## 输入与输出

- **输入**　对象及其分子表示、候选类型与研究约束的结构化描述。
- **输出**　带有序列与坐标的候选结构，以及流程提供的指标或排序信息。

## 接入条件

- **LLM 参与**　主要计算由专用分子生成与评估模型执行，无需通用对话 LLM。
- **运行条件**　需要兼容的 GPU 环境、BoltzGen 代码，以及所选生成和评估模块的模型权重。

BoltzGen 与同名家族的 Boltz-2 解决不同问题。生成候选的结构或排名本身不能确定实验表现。

## 原始来源与公开实现

Stark et al. (2025), BoltzGen: Toward Universal Binder Design

[论文或原始出版物](https://doi.org/10.1101/2025.11.20.689494)

- **GitHub 仓库**　[HannesStark/boltzgen](https://github.com/HannesStark/boltzgen)
- **实现入口**　[查看源代码](https://github.com/HannesStark/boltzgen)

作者发布的 BoltzGen 生成软件，与 Boltz-2 的结构及亲和力预测具有不同的功能。

## 下载

- [作者发布的 BoltzGen 模型文件](https://huggingface.co/boltzgen/boltzgen-1/tree/main)　按模型卡和相应使用条件获取权重。
- [项目源码 ZIP](https://github.com/HannesStark/boltzgen/archive/6472b44e8072187e6eaa51271ae6838245206013.zip)　公开项目的源码快照。

## 可选调用接口

- **BoltzGen MCP**　封装本机 BoltzGen 命令的调用和作业状态管理。需要安装上游模型与依赖。 [接口源码](https://github.com/MacromNex/boltzgen_mcp/blob/200abd7e9d627edcca1a2e1f13d1a2ad42bebd1f/scripts/run_boltzgen.py) · [适配器下载](https://github.com/MacromNex/boltzgen_mcp/archive/200abd7e9d627edcca1a2e1f13d1a2ad42bebd1f.zip)
