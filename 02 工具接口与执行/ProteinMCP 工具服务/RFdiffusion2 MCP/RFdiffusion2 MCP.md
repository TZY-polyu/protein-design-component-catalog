# RFdiffusion2 MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

调度 RFdiffusion2，根据给定的几何描述生成结构候选。

## 输入、输出与 LLM 参与

- **输入**　研究者给定的结构信息或几何约束。
- **输出**　与输入条件对应的蛋白结构候选及坐标。
- **LLM 参与**　几何生成由专用模型完成。普通程序或 LLM 智能体均可提交请求。

## 结果解读

这些坐标是生成模型给出的可行构象候选。与参考几何相符和具备生物学功能是不同层面的评价。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/rfdiffusion2_mcp](<https://github.com/MacromNex/rfdiffusion2_mcp>)（接口实现）。
- **RFdiffusion2 的原始出处**　[Ahern et al. (2025 在线 / 2026 刊期), Atom-level enzyme active site scaffolding using RFdiffusion2](<https://doi.org/10.1038/s41592-025-02975-x>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/rfdiffusion2_mcp/archive/90f3df61eeb511f0c496584c9301c58f66995dff.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [RFdiffusion2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/RFdiffusion2/RFdiffusion2.md)
