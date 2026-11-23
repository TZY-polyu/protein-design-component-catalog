# NetMHCpan

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

针对给定 MHC I 型分子计算肽段与该分子的预测结合或呈递倾向。

## 输入、输出与 LLM 参与

- **输入**　候选肽序列与 MHC I 型等位基因或对应分子序列。
- **输出**　各肽段的预测分数和百分位排名。部分模式提供亲和力预测。
- **LLM 参与**　由专用神经网络推理，无需通用 LLM。

## 结果解读

MHC I 与 MHC II 的预测对象和模型各异。排名应按当前预测模型与等位基因的参考分布解读。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　评估 I 类分子相关的肽结合。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Nielsen et al. (2007), NetMHCpan, a Method for Quantitative Predictions of Peptide Binding to Any HLA-A and -B Locus Protein of Known Sequence](<https://doi.org/10.1371/journal.pone.0000796>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　列方法族首篇。研究未给版本，DTU 官方以服务和软件包发布。

## 下载与访问

- [DTU 软件包申请](<https://services.healthtech.dtu.dk/software.php>)　可按 DTU 许可条件申请离线软件。
- [DTU 官方在线服务](<https://services.healthtech.dtu.dk/services/NetMHCpan-4.2/>)　此页是有版本号的访问入口，原研究所用版本未公开。

## 关联组件

[NetMHCpan MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/NetMHCpan%20MCP/NetMHCpan%20MCP.md)
