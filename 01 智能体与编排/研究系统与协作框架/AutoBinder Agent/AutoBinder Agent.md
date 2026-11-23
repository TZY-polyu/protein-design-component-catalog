# AutoBinder Agent

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

把自然语言研究要求转成对不同科学模块的调用，并向用户解释执行状态和返回的计算结果。

## 输入、输出与 LLM 参与

- **输入**　用户任务说明、可访问的结构数据、可调用的工具服务及其描述。
- **输出**　结构化工具请求、过程消息、科学模块返回的候选与结果汇总。
- **LLM 参与**　需要通用 LLM 理解任务、规划和发起调用。各专业工具的数值计算由相应后端完成。

## 结果解读

原论文采用一组标准提示评估智能体行为。该分数衡量任务执行与解释，不能直接读作分子实验成功率。

## 在六篇研究中的用法

使用此来源的研究组件包括 [AutoBinder 任务规划层](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/AutoBinder%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E5%B1%82/AutoBinder%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E5%B1%82.md)、[AutoBinder 用户界面](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E7%94%A8%E6%88%B7%E4%B8%8E%E6%9C%8D%E5%8A%A1%E5%85%A5%E5%8F%A3/AutoBinder%20%E7%94%A8%E6%88%B7%E7%95%8C%E9%9D%A2/AutoBinder%20%E7%94%A8%E6%88%B7%E7%95%8C%E9%9D%A2.md)、[AutoBinder 统一模型适配器](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/AutoBinder%20%E7%BB%9F%E4%B8%80%E6%A8%A1%E5%9E%8B%E9%80%82%E9%85%8D%E5%99%A8/AutoBinder%20%E7%BB%9F%E4%B8%80%E6%A8%A1%E5%9E%8B%E9%80%82%E9%85%8D%E5%99%A8.md)、[AutoBinder MCP 通信层](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/AutoBinder%20MCP%20%E9%80%9A%E4%BF%A1%E5%B1%82/AutoBinder%20MCP%20%E9%80%9A%E4%BF%A1%E5%B1%82.md)、[AutoBinder 工具服务层](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/AutoBinder%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E5%B1%82/AutoBinder%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E5%B1%82.md)、[AutoBinder 计算资源编排](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/AutoBinder%20%E8%AE%A1%E7%AE%97%E8%B5%84%E6%BA%90%E7%BC%96%E6%8E%92/AutoBinder%20%E8%AE%A1%E7%AE%97%E8%B5%84%E6%BA%90%E7%BC%96%E6%8E%92.md)、[AutoBinder 候选种子库](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/AutoBinder%20%E5%80%99%E9%80%89%E7%A7%8D%E5%AD%90%E5%BA%93/AutoBinder%20%E5%80%99%E9%80%89%E7%A7%8D%E5%AD%90%E5%BA%93.md)、[AutoBinder 五类提示任务](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/AutoBinder%20%E4%BA%94%E7%B1%BB%E6%8F%90%E7%A4%BA%E4%BB%BB%E5%8A%A1/AutoBinder%20%E4%BA%94%E7%B1%BB%E6%8F%90%E7%A4%BA%E4%BB%BB%E5%8A%A1.md)、[AutoBinder 行为评分](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/AutoBinder%20%E8%A1%8C%E4%B8%BA%E8%AF%84%E5%88%86/AutoBinder%20%E8%A1%8C%E4%B8%BA%E8%AF%84%E5%88%86.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　论文及其 arXiv 页面未提供可核实的整套系统仓库。

## 下载与访问

论文未给出可核实的整套 AutoBinder Agent 官方代码下载地址。

- [下载作者论文（PDF）](<https://arxiv.org/pdf/2602.00019v1>)　含架构图、提示任务及行为评分表。
