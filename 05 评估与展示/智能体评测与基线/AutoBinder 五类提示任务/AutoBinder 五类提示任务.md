# AutoBinder 五类提示任务

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

用彼此隔离的上下文考察系统能力。P4 提问模块暂不可用时如何应对。

## 输入、输出与 LLM 参与

- **输入**　分别测试工具辨识、流程规划、参数解析、错误恢复、端到端执行的研究者提示。
- **输出**　各任务的智能体答复与行为记录。
- **LLM 参与**　是。被测对象是 LLM 智能体。

## 结果解读

每类提示在独立上下文中测试一种能力。任务编号对应实验条件，所得答复可用于比较工具选择、规划和错误恢复表现。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为实验评估。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　任务集由本篇表I给出。 论文及其 arXiv 页面未提供可核实的整套系统仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
