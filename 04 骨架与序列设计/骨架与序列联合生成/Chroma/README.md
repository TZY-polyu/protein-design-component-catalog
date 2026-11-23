# Chroma

在给定长度或其他结构条件下采样蛋白的结构和序列，并以统一的 Protein 对象组织结果。

## 输入与输出

- **输入**　长度等约束描述、可选结构或类别条件。也可载入已有结构做数据处理。
- **输出**　带有序列和坐标的 Protein 对象，可导出为结构文件。

## 接入条件

- **LLM 参与**　使用专用蛋白生成模型，采样无需通用对话 LLM。
- **运行条件**　需要 Python、PyTorch 和官方预训练权重。代码采用 Apache 2.0。学术和非营利使用者需接受单独的权重许可并取得个人令牌，商业使用需另行联系。此次未领取权重或运行该模型。

采样可以产生新的序列和坐标。所设定的生成条件不能单独证明结果具备相应的生物学性质。

## 原始来源与公开实现

Ingraham et al. (2023), Illuminating protein space with a programmable generative model

[论文或原始出版物](https://doi.org/10.1038/s41586-023-06728-8)

- **GitHub 仓库**　[generatebio/chroma](https://github.com/generatebio/chroma)
- **实现入口**　[查看源代码](https://github.com/generatebio/chroma)

原作者模型仓库。

## 下载

- [Chroma Python 发行包](https://pypi.org/project/generate-chroma/#files)　获取 Python 程序包。
- [模型权重申请入口](https://chroma-weights.generatebiomedicines.com/)　在作者的权重门户查看许可并获取个人令牌。
- [项目源码 ZIP](https://github.com/generatebio/chroma/archive/501f474a7e99ff3b359eb93f988665024c4e1493.zip)　公开项目的源码快照。
