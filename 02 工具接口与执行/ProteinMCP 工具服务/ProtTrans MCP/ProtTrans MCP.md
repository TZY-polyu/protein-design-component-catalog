# ProtTrans MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

调用 ProtTrans 生成蛋白质序列表示，并将其用于适应度预测等下游分析。

## 输入、输出与 LLM 参与

- **输入**　蛋白质序列。监督任务另需与序列对应的性质标签。
- **输出**　序列或残基级向量，经下游模型处理后还可得到性质预测值。
- **LLM 参与**　底层计算包含专用蛋白语言模型。接口可接受智能体调用，也可由普通程序调用，均无需通用对话 LLM。

## 结果解读

表示向量的每个维度通常没有独立的物理单位。评价预测能力需要与任务标签对照。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/prottrans_mcp](<https://github.com/MacromNex/prottrans_mcp>)（接口实现）。
- **ProtTrans 的原始出处**　[Elnaggar et al. (2021 在线 / 2022 刊期), ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning](<https://doi.org/10.1109/TPAMI.2021.3095381>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/prottrans_mcp/archive/d946c8cb76a7ec6b47f349cc3db5aed6150d1c96.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [ProtTrans](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ProtTrans/ProtTrans.md)
