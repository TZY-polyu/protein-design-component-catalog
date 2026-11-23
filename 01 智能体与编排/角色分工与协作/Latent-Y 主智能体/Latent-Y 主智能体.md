# Latent-Y 主智能体

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

解释约束、选择工具、整合结果并判断何时结束。推理引擎可更换，未公布逐次运行的型号映射。

## 输入、输出与 LLM 参与

- **输入**　文字目标、结构化计划或论文，工具返回结果。
- **输出**　研究计划、子任务、候选清单与解释。
- **LLM 参与**　是，通用 LLM 直接推理。

## 结果解读

主智能体统筹子任务和结束条件。作者说明模型后端可以替换，未逐次标明各任务所用的通用模型。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为在线推理／编排。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **ReAct 的原始出处**　[Yao et al. (ICLR 2023), ReAct: Synergizing Reasoning and Acting in Language Models](<https://arxiv.org/abs/2210.03629>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　主系统由 Latent Labs 提出。ReAct 是其引用的推理/行动范式。每轮 LLM 型号未列。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [ReAct](../../%E6%8E%A8%E7%90%86%E4%B8%8E%E6%A3%80%E7%B4%A2%E7%BC%96%E6%8E%92/ReAct/ReAct.md)
