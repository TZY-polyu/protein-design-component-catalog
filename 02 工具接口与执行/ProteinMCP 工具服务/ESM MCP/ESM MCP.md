# ESM MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

提取 ESM 蛋白语言模型学习到的序列表示，并支持这些表示在适应度建模中的使用。

## 输入、输出与 LLM 参与

- **输入**　蛋白质序列或变体集合。训练监督预测器时还需相应观测标签。
- **输出**　序列或残基层面的数值表示、模型分数，或基于这些表示拟合的性质预测。
- **LLM 参与**　底层计算包含专用蛋白语言模型。接口可接受智能体调用，也可由普通程序调用，均无需通用对话 LLM。

## 结果解读

嵌入是学习得到的特征向量。只有结合具体标签与预测器，数值才对应某项实验性质。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/esm_mcp](<https://github.com/MacromNex/esm_mcp>)（接口实现）。
- **ESM 的原始出处**　[Rives et al. (2021), Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences](<https://doi.org/10.1073/pnas.2016239118>)
- **ESM-1v 的原始出处**　[Meier et al. (2021), Language models enable zero-shot prediction of the effects of mutations on protein function](<https://doi.org/10.1101/2021.07.09.450648>)
- **ESM-2 的原始出处**　[Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model](<https://doi.org/10.1126/science.ade2574>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/esm_mcp/archive/0a3b1c8b36c0e0e9954c753347a9678db5fba4af.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ESM](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ESM/ESM.md) · [ESM-1v](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ESM-1v/ESM-1v.md) · [ESM-2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ESM-2/ESM-2.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
