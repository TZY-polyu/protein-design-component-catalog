# AMBER MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

让上层程序提交 AMBER 分子模拟或轨迹分析作业。

## 输入、输出与 LLM 参与

- **输入**　分子坐标、选用的模型与体系描述。分析既有运行时还可输入已生成的轨迹。
- **输出**　按作业返回随时间的构象轨迹、能量或结构统计。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

每个时间点对应模拟中的一个构象。比较轨迹统计时需明确体系和受力模型。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供分子动力学计算。
- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/amber_mcp](<https://github.com/MacromNex/amber_mcp>)（接口实现）。
- **AMBER 的原始出处**　[Weiner & Kollman (1981), AMBER: Assisted model building with energy refinement. A general program for modeling molecules and their interactions](<https://doi.org/10.1002/jcc.540020311>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/amber_mcp/archive/f1fceb75263a5b48bc26c57da7e396b4d5392661.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[AMBER](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/AMBER/AMBER.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
