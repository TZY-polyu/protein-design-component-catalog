# AlphaFold 3

根据组成一个体系的分子实体预测三维结构，可在同一次预测中表示蛋白质、核酸、配体等分子。

## 输入与输出

- **输入**　参与体系的序列、化学组分描述和链信息。可附带序列比对与结构模板信息。
- **输出**　预测的原子坐标、整体及局部置信度、链间误差估计等结果文件。

## 接入条件

- **LLM 参与**　核心为专用结构预测模型，推理不需要通用对话 LLM。
- **运行条件**　需要兼容计算环境及官方模型权重。代码按 Apache 2.0 许可，标准权重受 Google 非商业使用条款限制。官方权重直链在本次核验的访问地点返回 403，下载受地区可用性影响。

输入描述的是参与建模的实体。模型给出可能的空间构象，置信度也不能替代实验测得的亲和力。

## 原始来源与公开实现

Abramson et al. (2024), Accurate structure prediction of biomolecular interactions with AlphaFold 3

[论文或原始出版物](https://doi.org/10.1038/s41586-024-07487-w)

- **GitHub 仓库**　[google-deepmind/alphafold3](https://github.com/google-deepmind/alphafold3)
- **实现入口**　[查看源代码](https://github.com/google-deepmind/alphafold3)

DeepMind 官方代码。模型参数另有获取与使用条件。

## 下载

- [官方模型参数](https://storage.googleapis.com/alphafold3/af3.bin.zst)　Google 发布的标准模型权重压缩文件，与代码分开发放。
- [模型参数使用条款](https://github.com/google-deepmind/alphafold3/blob/main/WEIGHTS_TERMS_OF_USE.md)　官方说明列明参数获取来源和用途条件。
- [项目源码 ZIP](https://github.com/google-deepmind/alphafold3/archive/5870e09dd26a1541bd622fbdfa28dd518cc56192.zip)　公开项目的源码快照。

## 可选调用接口

- **AlphaFold 3 MCP**　将结构预测任务交给本地 AlphaFold 3 运行程序。需单独依官方条款取得模型参数，并配置本地数据库和计算环境。 [接口源码](https://github.com/MacromNex/alphafold3_mcp/blob/9ed29a468276df18393fe1f823517aa5df0724ba/scripts/alphafold3_runner.py) · [适配器下载](https://github.com/MacromNex/alphafold3_mcp/archive/9ed29a468276df18393fe1f823517aa5df0724ba.zip)
