# MAESD 决策专家（DE）

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

检查是否符合用户意图，并在非支配候选中按偏好选择。文中式1附近另把验证算子归于 PSE。

## 输入、输出与 LLM 参与

- **输入**　原始功能要求、结构域组合、筛选结果和用户偏好。
- **输出**　组合一致性判断及符合优先级的最终候选。
- **LLM 参与**　承担语义决策。论文未单列该角色的 LLM 调用。

## 结果解读

最终选择受用户的目标优先级影响。原文对其中一项一致性检查的角色归属有两种写法。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时角色。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　MAESD 定义的角色。

## 下载与访问

- [下载 decision.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/decision.py>)　公开框架中用于选择候选的模块。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
