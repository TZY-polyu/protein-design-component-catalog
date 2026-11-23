# NetMHCIIpan

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

针对给定 MHC II 型分子比较肽段的预测结合或呈递倾向。

## 输入、输出与 LLM 参与

- **输入**　候选肽序列与指定的 MHC II 型等位基因或分子信息。
- **输出**　逐肽段或结合核心的评分和相对排名。具体字段随版本与模式而异。
- **LLM 参与**　依赖专用预测模型，无需通用 LLM。

## 结果解读

结果适合作为计算注释。实验中的抗原呈递与免疫反应还受到算法输入之外的因素影响。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　评估 II 类分子相关的肽结合。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Nielsen et al. (2008), Quantitative Predictions of Peptide Binding to Any HLA-DR Molecule of Known Sequence: NetMHCIIpan](<https://doi.org/10.1371/journal.pcbi.1000107>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　列方法族首篇。研究未给版本，DTU 官方以服务和软件包发布。

## 下载与访问

- [DTU 软件包申请](<https://services.healthtech.dtu.dk/software.php>)　离线包按软件、系统和许可条件申请。
- [DTU 官方在线服务](<https://services.healthtech.dtu.dk/services/NetMHCIIpan-4.3/>)　此页是有版本号的访问入口，ProteinMCP 未披露所用具体版本。

## 关联组件

[NetMHCIIpan MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/NetMHCIIpan%20MCP/NetMHCIIpan%20MCP.md)
