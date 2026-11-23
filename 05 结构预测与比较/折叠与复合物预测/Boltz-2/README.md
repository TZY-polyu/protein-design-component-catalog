# Boltz-2

预测分子复合体系的三维结构，并对模型支持的蛋白与配体组合给出结合亲和力相关的预测。

## 输入与输出

- **输入**　分子实体和链组成，以及体系的序列或化学描述。视任务包含额外输入特征。
- **输出**　三维结构和置信度。经适用的亲和力预测头，可输出结合相关分数或预测值。

## 接入条件

- **LLM 参与**　专用结构与亲和力网络，无需通用对话 LLM。
- **运行条件**　需要兼容的 Boltz 安装环境和相应模型权重。CPU 可运行，GPU 可加速。启用外部比对服务时需要联网。

结构置信度用于评价坐标预测。小分子与蛋白质的亲和力预测采用单独的输出及适用范围。

## 原始来源与公开实现

Passaro et al. (2025), Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction

[论文或原始出版物](https://doi.org/10.1101/2025.06.14.659707)

- **GitHub 仓库**　[jwohlwend/boltz](https://github.com/jwohlwend/boltz)
- **实现入口**　[查看源代码](https://github.com/jwohlwend/boltz)

Boltz 项目维护多个版本。此处的方法文献及模型参数对应 Boltz-2。

## 下载

- [Boltz-2 模型文件](https://huggingface.co/boltz-community/boltz-2/tree/main)　开发者公开的模型参数。
- [Boltz 软件包](https://pypi.org/project/boltz/#files)　选取与使用的模型权重兼容的版本。
- [项目源码 ZIP](https://github.com/jwohlwend/boltz/archive/b1ebfc46ecf57f5414e0d1a6f9027bbb122c53bc.zip)　公开项目的源码快照。

## 可选调用接口

- **Boltz MCP**　构造 Boltz 本地命令并从输出目录读取结果。需要安装匹配版本的 Boltz 和模型参数。 [接口源码](https://github.com/MacromNex/boltz_mcp/blob/e35c2c26ccf1140f92e8b33be987fbbf8b249bfe/scripts/structure_prediction.py) · [适配器下载](https://github.com/MacromNex/boltz_mcp/archive/e35c2c26ccf1140f92e8b33be987fbbf8b249bfe.zip)
