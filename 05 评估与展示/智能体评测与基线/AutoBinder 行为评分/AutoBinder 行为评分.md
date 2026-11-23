# AutoBinder 行为评分

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

评估任务理解、选工具、执行顺序、可解释性和输出一致性。讨论指出部分指标为人工评定。

## 输入、输出与 LLM 参与

- **输入**　对提示的答复、工具选择和顺序、推理解释、重复执行的一致性。
- **输出**　五项分数及加权综合分。表II报告平均 93.86/100。
- **LLM 参与**　加权计算否。部分人工评定，未披露 LLM 裁判。

## 结果解读

综合分按作者定义的五个行为指标汇总，部分判定依靠人工评价。该分数衡量智能体执行与解释任务的表现。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为实验评估。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　本篇定义具体的五项行为指标与加权公式。表II给出分数。 论文及其 arXiv 页面未提供可核实的整套系统仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
