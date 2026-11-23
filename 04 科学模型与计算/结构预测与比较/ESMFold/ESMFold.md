# ESMFold

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

将蛋白语言模型的序列表示交给折叠模块，由氨基酸序列推断三维构象。

## 输入、输出与 LLM 参与

- **输入**　一个蛋白质的氨基酸序列，使用兼容的 ESMFold 与序列编码权重。
- **输出**　预测原子坐标及残基或整体结构置信度，可导出结构文件。
- **LLM 参与**　使用 ESM-2 蛋白语言模型和结构预测模块，无需通用 LLM。

## 结果解读

它可直接从序列表征折叠。预测置信度评估模型自身的结构判断，实验折叠状态仍需要独立证据。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　从蛋白语言模型表征预测结构。
- **BioDesignBench**（运行时／结构预测）　提供依托蛋白语言模型的结构预测结果。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model](<https://doi.org/10.1126/science.ade2574>)
- **GitHub 仓库**　[Biohub/esm-archive](<https://github.com/Biohub/esm-archive>)
- **归属说明**　该论文提出 ESMFold，并报告底层 ESM-2。两者共用官方代码归档。

## 下载与访问

- [ESMFold v1 官方结构模块权重](<https://dl.fbaipublicfiles.com/fair-esm/models/esmfold_3B_v1.pt>)　上游模型目录提供的 v1 检查点，配套 ESM-2 权重见同一目录。
- [ESMFold v1 模型页](<https://huggingface.co/biohub/esmfold_v1>)　托管模型的说明及文件入口。
- [仓库源码 ZIP · Biohub/esm-archive](<https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip>)　该仓库的固定快照。

## 关联组件

[design_binder](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_binder/design_binder.md) · [ESM-2](../../%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ESM-2/ESM-2.md) · [ESMFold MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ESMFold%20MCP/ESMFold%20MCP.md) · [predict_structure](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/predict_structure/predict_structure.md) · [validate_design](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/validate_design/validate_design.md)
