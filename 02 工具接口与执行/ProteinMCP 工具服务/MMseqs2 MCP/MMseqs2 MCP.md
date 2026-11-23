# MMseqs2 MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

通过 MMseqs2 搜索相似序列、聚类或构建多序列比对。

## 输入、输出与 LLM 参与

- **输入**　查询序列、供检索或聚类的序列集合，以及任务类别。
- **输出**　同源候选及比对信息、聚类归属，或对齐后的序列集合，依任务而定。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

命中反映序列相似性。解释可能的功能关系时需结合覆盖区域和已有注释。

## 在六篇研究中的用法

- **ProteinMCP**（架构列为 MSA 工具与后端）　快速序列搜索和聚类，支持 MSA 构建。
- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/mmseqs2_mcp](<https://github.com/MacromNex/mmseqs2_mcp>)（接口实现）。
- **MMseqs2 的原始出处**　[Steinegger & Söding (2017), MMseqs2 enables sensitive protein sequence searching for the analysis of massive data sets](<https://doi.org/10.1038/nbt.3988>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/mmseqs2_mcp/archive/9cb7fb5addb27a97e03af57749b08ee3a1dab92d.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[MMseqs2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E6%A3%80%E7%B4%A2%E4%B8%8E%E6%B3%A8%E9%87%8A/MMseqs2/MMseqs2.md) · [MSA MCP](../MSA%20MCP/MSA%20MCP.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
