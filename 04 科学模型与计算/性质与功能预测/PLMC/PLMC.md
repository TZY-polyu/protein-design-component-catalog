# PLMC

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

从蛋白家族的多序列比对估计位点偏好以及位点间统计耦合，用于比较序列在家族模型下的相容性。

## 输入、输出与 LLM 参与

- **输入**　同一家族的对齐序列、可选的序列权重及模型拟合所需信息。
- **输出**　位点场、残基对的耦合系数和可供后续评估的模型参数。可输出位点对耦合汇总。
- **LLM 参与**　以伪似然等统计方法拟合模型，无需通用 LLM。

## 结果解读

耦合反映比对数据中的协同变化，可能受样本数量与系统发育关系影响。论文关联的 EVmutation 将模型参数用于预测。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Hopf et al. (2017), Mutation effects predicted from sequence co-variation](<https://doi.org/10.1038/nbt.3769>)
- **GitHub 仓库**　[debbiemarkslab/plmc](<https://github.com/debbiemarkslab/plmc>)
- **归属说明**　作者指定的软件引用。PLMC 拟合序列耦合参数。EVmutation 是使用这些参数进行预测的配套方法。

## 下载与访问

- [仓库源码 ZIP · debbiemarkslab/plmc](<https://github.com/debbiemarkslab/plmc/archive/18c9e55e3bd2f14f4968be19a807b401996c929a.zip>)　该仓库的固定快照。

## 关联组件

[PLMC MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/PLMC%20MCP/PLMC%20MCP.md)
