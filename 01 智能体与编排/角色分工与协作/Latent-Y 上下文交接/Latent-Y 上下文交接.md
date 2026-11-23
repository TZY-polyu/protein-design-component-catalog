# Latent-Y 上下文交接

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

限制长任务中的上下文负担，让不同代理分别分析。未公开具体存储或压缩算法。

## 输入、输出与 LLM 参与

- **输入**　主代理的子任务、已掌握材料与分析范围。
- **输出**　子代理任务上下文、回传的结论。
- **LLM 参与**　协同，LLM 消费和产生内容。封装机制未详述。

## 结果解读

子智能体只接收相关的任务背景，再将结论返回主智能体。作者未说明底层存储格式和压缩算法。

## 在六篇研究中的用法

该组件记录于 **Latent-Y**，对应环节为在线推理／编排。

## 原始来源与 GitHub

- **该研究中的定义**　[Latent Labs Team (2026), Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　本系统的交接机制见 §3.1。长任务上下文工程参考资料仅提供背景。 论文自建平台及智能体。官方通过 Latent Labs Platform 提供访问，未公开模型或智能体源码仓库。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [官方产品与访问申请](<https://www.latentlabs.com/latent-y/>)　服务访问需满足平台条件。
- [研究论文 PDF](<https://arxiv.org/pdf/2603.29727v2>)

## 关联组件

[Latent-Y](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
