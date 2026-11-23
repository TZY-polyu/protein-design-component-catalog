# Boltz-2

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

预测分子复合体系的三维结构，并对模型支持的蛋白与配体组合给出结合亲和力相关的预测。

## 输入、输出与 LLM 参与

- **输入**　分子实体和链组成，以及体系的序列或化学描述。视任务包含额外输入特征。
- **输出**　三维结构和置信度。经适用的亲和力预测头，可输出结合相关分数或预测值。
- **LLM 参与**　专用结构与亲和力网络，无需通用对话 LLM。

## 结果解读

结构置信度与亲和力预测是不同输出。BioDesignBench 报告使用 Boltz-2，出处应对应该版本。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供复合物结构预测选项。
- **BioDesignBench**（运行时／独立复评）　补充表S1确认 Boltz-2 结构预测和亲和力预测接口。正文与补充D列其为质量复核后端。补充A.5另述AF2体系。

使用此来源的研究组件包括 [BioDesignBench 结构质量独立复算](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97.md)、[BioDesignBench 三类质量指标交叉核验](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E4%B8%89%E7%B1%BB%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87%E4%BA%A4%E5%8F%89%E6%A0%B8%E9%AA%8C/BioDesignBench%20%E4%B8%89%E7%B1%BB%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87%E4%BA%A4%E5%8F%89%E6%A0%B8%E9%AA%8C.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Passaro et al. (2025), Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction](<https://doi.org/10.1101/2025.06.14.659707>)
- **GitHub 仓库**　[jwohlwend/boltz](<https://github.com/jwohlwend/boltz>)
- **归属说明**　Boltz 系列仓库。P6 正文使用 Boltz-2，引文[35]是前代 Boltz-1。

## 下载与访问

- [Boltz-2 官方模型文件](<https://huggingface.co/boltz-community/boltz-2/tree/main>)　模型开发者发布的参数文件。
- [Boltz Python 发行包](<https://pypi.org/project/boltz/#files>)　同一家族的软件包，请在复核研究时对照版本。
- [仓库源码 ZIP · jwohlwend/boltz](<https://github.com/jwohlwend/boltz/archive/b1ebfc46ecf57f5414e0d1a6f9027bbb122c53bc.zip>)　该仓库的固定快照。

## 关联组件

[Boltz MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/Boltz%20MCP/Boltz%20MCP.md) · [predict_affinity_boltz](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/predict_affinity_boltz/predict_affinity_boltz.md) · [predict_structure_boltz](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/predict_structure_boltz/predict_structure_boltz.md)
