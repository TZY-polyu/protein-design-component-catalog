# PyMOL MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

让客户端调用 PyMOL 的分子视图操作与结构渲染。

## 输入、输出与 LLM 参与

- **输入**　已加载或指定的分子结构、选区以及所需的展示方式。
- **输出**　更新后的三维视图，或导出的渲染图像。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

图像呈现输入坐标与所选视图。不同配色、朝向或选区会改变展示重点。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [vrtejus/pymol-mcp](<https://github.com/vrtejus/pymol-mcp>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[vrtejus/pymol-mcp](<https://github.com/vrtejus/pymol-mcp>)（接口实现）。
- **PyMOL 的原始出处**　[DeLano (2002), PyMOL: An Open-Source Molecular Graphics Tool.](<https://legacy.ccp4.ac.uk/newsletters/newsletter40.pdf>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/vrtejus/pymol-mcp/archive/d54eeaf4d59d939caec33fc91c9ebb755aae1572.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [PyMOL](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E4%B8%89%E7%BB%B4%E5%B1%95%E7%A4%BA%E4%B8%8E%E7%BB%93%E6%9E%9C%E5%AF%BC%E5%87%BA/PyMOL/PyMOL.md)
