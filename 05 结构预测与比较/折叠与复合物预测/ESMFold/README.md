# ESMFold

将蛋白语言模型的序列表示交给折叠模块，由氨基酸序列推断三维构象。

## 输入与输出

- **输入**　一个蛋白质的氨基酸序列，使用兼容的 ESMFold 与序列编码权重。
- **输出**　预测原子坐标及残基或整体结构置信度，可导出结构文件。

## 接入条件

- **LLM 参与**　使用 ESM-2 蛋白语言模型和结构预测模块，无需通用 LLM。
- **运行条件**　需要 ESMFold 结构模块、对应的 ESM-2 参数和兼容的 OpenFold 依赖。

它可直接从序列表征折叠。预测置信度评估模型自身的结构判断，实验折叠状态仍需要独立证据。

## 原始来源与公开实现

Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model

[论文或原始出版物](https://doi.org/10.1126/science.ade2574)

- **GitHub 仓库**　[Biohub/esm-archive](https://github.com/Biohub/esm-archive)
- **实现入口**　[查看源代码](https://github.com/Biohub/esm-archive/blob/2b369911bb5b4b0dda914521b9475cad1656b2ac/esm/esmfold/v1/esmfold.py)

公开代码归档的 esmfold/v1 目录实现序列到三维坐标的结构模块。

## 下载

- [下载实现源码（ZIP）](https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [ESMFold v1 官方结构模块权重](https://dl.fbaipublicfiles.com/fair-esm/models/esmfold_3B_v1.pt)　上游模型目录提供的 v1 检查点，配套 ESM-2 权重见同一目录。
- [ESMFold v1 模型页](https://huggingface.co/biohub/esmfold_v1)　托管模型的说明及文件入口。
