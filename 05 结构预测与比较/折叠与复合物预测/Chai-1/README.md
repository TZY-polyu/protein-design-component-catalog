# Chai-1

对包含蛋白质、核酸、配体等分子的体系预测复合结构，供结构比较和候选分析使用。

## 输入与输出

- **输入**　各分子实体的序列或化学描述，可提供序列比对、模板等上下文。
- **输出**　预测复合物坐标、结构置信度和模型给出的相关评分。

## 接入条件

- **LLM 参与**　使用专用分子结构模型。输入特征可能包含蛋白语言表征，无需通用对话 LLM。
- **运行条件**　初次运行需取得官方模型文件及配套资源。

模型同时输出结构及置信度信息。阅读结果时应区分整体评分、局部误差和各链的相对位置。

## 原始来源与公开实现

Chai Discovery (2024), Chai-1: Decoding the molecular interactions of life

[论文或原始出版物](https://doi.org/10.1101/2024.10.10.615955)

- **GitHub 仓库**　[chaidiscovery/chai-lab](https://github.com/chaidiscovery/chai-lab)
- **实现入口**　[查看源代码](https://github.com/chaidiscovery/chai-lab/blob/main/chai_lab/chai1.py)

开发团队官方仓库所引技术报告。

## 下载

- [Chai 官方 Python 软件包](https://pypi.org/project/chai_lab/#files)　权重由官方运行库按需下载并缓存。细节见仓库的模型权重说明。
- [项目源码 ZIP](https://github.com/chaidiscovery/chai-lab/archive/27e6055bed9e2abeb455674108aaec453a42d84e.zip)　公开项目的源码快照。

## 可选调用接口

- **Chai-1 MCP**　直接通过 chai_lab.chai1.run_inference 执行预测，要求本地 chai-lab 运行环境和模型参数。 [接口源码](https://github.com/MacromNex/chai1_mcp/blob/d4f8cb068315a347231bfd739a492605c4d6fb57/scripts/predict_basic_structure.py) · [适配器下载](https://github.com/MacromNex/chai1_mcp/archive/d4f8cb068315a347231bfd739a492605c4d6fb57.zip)
