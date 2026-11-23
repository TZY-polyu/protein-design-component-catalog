# Chroma

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

在给定长度或其他结构条件下采样蛋白的结构和序列，并以统一的 Protein 对象组织结果。

## 输入、输出与 LLM 参与

- **输入**　长度等约束描述、可选结构或类别条件。也可载入已有结构做数据处理。
- **输出**　带有序列和坐标的 Protein 对象，可导出为结构文件。
- **LLM 参与**　由专用生成模型完成。ProtAgents 调用 Chroma 时，通用 LLM 只负责选择工具和组织请求。

## 结果解读

ProtAgents 提供了不同的条件生成封装。给出的类别是采样条件，生成结果是否符合预期仍需独立检查。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 结构文件序列读取](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%A3%80%E7%B4%A2%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86/ProtAgents%20%E7%BB%93%E6%9E%84%E6%96%87%E4%BB%B6%E5%BA%8F%E5%88%97%E8%AF%BB%E5%8F%96/ProtAgents%20%E7%BB%93%E6%9E%84%E6%96%87%E4%BB%B6%E5%BA%8F%E5%88%97%E8%AF%BB%E5%8F%96.md)、[ProtAgents 序列长度统计](../../%E5%BA%8F%E5%88%97%E6%A3%80%E7%B4%A2%E4%B8%8E%E6%B3%A8%E9%87%8A/ProtAgents%20%E5%BA%8F%E5%88%97%E9%95%BF%E5%BA%A6%E7%BB%9F%E8%AE%A1/ProtAgents%20%E5%BA%8F%E5%88%97%E9%95%BF%E5%BA%A6%E7%BB%9F%E8%AE%A1.md)、[ProtAgents 长度条件生成](../ProtAgents%20%E9%95%BF%E5%BA%A6%E6%9D%A1%E4%BB%B6%E7%94%9F%E6%88%90/ProtAgents%20%E9%95%BF%E5%BA%A6%E6%9D%A1%E4%BB%B6%E7%94%9F%E6%88%90.md)、[ProtAgents 结构类别条件生成](../ProtAgents%20%E7%BB%93%E6%9E%84%E7%B1%BB%E5%88%AB%E6%9D%A1%E4%BB%B6%E7%94%9F%E6%88%90/ProtAgents%20%E7%BB%93%E6%9E%84%E7%B1%BB%E5%88%AB%E6%9D%A1%E4%BB%B6%E7%94%9F%E6%88%90.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ingraham et al. (2023), Illuminating protein space with a programmable generative model](<https://doi.org/10.1038/s41586-023-06728-8>)
- **GitHub 仓库**　[generatebio/chroma](<https://github.com/generatebio/chroma>)
- **归属说明**　原作者模型仓库。

## 下载与访问

- [Chroma 官方发行包](<https://pypi.org/project/generate-chroma/#files>)　提供 Python 软件包。
- [预训练权重获取说明](<https://github.com/generatebio/chroma#readme>)　作者说明获取其预训练权重需 API key。权重与源码分开发布。
- [仓库源码 ZIP · generatebio/chroma](<https://github.com/generatebio/chroma/archive/501f474a7e99ff3b359eb93f988665024c4e1493.zip>)　该仓库的固定快照。
