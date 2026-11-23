# ProteinAtlas MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

从 Human Protein Atlas 获取特定基因或蛋白的人体组织表达及定位资料。

## 输入、输出与 LLM 参与

- **输入**　基因或蛋白标识，以及感兴趣的组织或注释类别。
- **输出**　关联条目中的表达、定位、组织或病理注释等资料。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

表达和定位取决于样本、检测方法和证据等级。条目适合用来补充研究对象的背景。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [Augmented-Nature/ProteinAtlas-MCP-Server](<https://github.com/Augmented-Nature/ProteinAtlas-MCP-Server>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[Augmented-Nature/ProteinAtlas-MCP-Server](<https://github.com/Augmented-Nature/ProteinAtlas-MCP-Server>)（接口实现）。
- **Human Protein Atlas 的原始出处**　[Uhlén et al. (2005), A human protein atlas for normal and cancer tissues based on antibody proteomics](<https://doi.org/10.1074/mcp.M500279-MCP200>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/Augmented-Nature/ProteinAtlas-MCP-Server/archive/830ae3674e9c7e448abb98b910f858cae2d82e2e.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[Human Protein Atlas](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/Human%20Protein%20Atlas/Human%20Protein%20Atlas.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
