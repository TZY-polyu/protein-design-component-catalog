# ProGen2

对氨基酸序列建模，支持自回归生成或按模型似然比较序列，为候选生成提供序列先验。

## 输入与输出

- **输入**　序列前缀、待评分的序列，以及任务所选择的模型检查点。
- **输出**　生成的氨基酸序列，或对给定序列的残基条件概率与模型评分。

## 接入条件

- **LLM 参与**　ProGen2 本身是蛋白语言模型，可独立于通用对话 LLM 推理。
- **运行条件**　Python、PyTorch、仓库所列依赖及对应规模的 ProGen2 检查点。权重规模会影响所需内存。 作者的 Google Cloud 权重下载入口在本次核验地点返回 HTTP 403。使用前需确认运行环境可以取得参数。

序列的模型概率反映它与训练所得统计规律的相容性。功能与折叠需要其他证据判断。

## 原始来源与公开实现

Nijkamp et al. (2023), ProGen2: Exploring the boundaries of protein language models

[论文或原始出版物](https://doi.org/10.1016/j.cels.2023.10.002)

- **GitHub 仓库**　[salesforce/progen](https://github.com/salesforce/progen)
- **实现入口**　[查看源代码](https://github.com/salesforce/progen/tree/c27a419c234a0997923761e1fe7daffcebf0eaf5/progen2)

作者仓库的 progen2 子目录含模型实现与推理程序。

## 下载

- [ProGen2-small 权重](https://storage.googleapis.com/sfr-progen-research/checkpoints/progen2-small.tar.gz)　官方 151M 参数版本归档。其他规模见模型清单。
- [官方模型版本和下载表](https://github.com/salesforce/progen/tree/main/progen2)　模型规模、用途和检查点对应表。
- [固定版本源码 ZIP](https://github.com/salesforce/progen/archive/c27a419c234a0997923761e1fe7daffcebf0eaf5.zip)　包含上述实现及其同仓库配套文件。
