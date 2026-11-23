# AutoBinder 计算资源编排

[工具接口与执行](../../README.md) / 工作流与执行管理

## 用途

用优先队列和动态负载均衡分配资源，并处理异常、自动重试与资源回收。

## 输入、输出与 LLM 参与

- **输入**　待执行任务、任务优先级、节点状态。
- **输出**　容器调度、计算资源分配及任务结果。
- **LLM 参与**　未报告需要 LLM。论文描述为资源调度机制。

## 结果解读

此层负责资源分配、重试和回收。成功分配资源只表示任务具备执行条件，不能用来评价科学结果。

## 在六篇研究中的用法

该组件记录于 **AutoBinder Agent**，对应环节为系统架构。

## 原始来源与 GitHub

- **该研究中的定义**　[Ge et al. (2026), AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019>)
- **Docker 的原始出处**　[Solomon Hykes / dotCloud (2013)，Docker 软件首次公开演示（无单一方法论文）](<https://www.docker.com/blog/docker-nine-years-young/>)
- **GitHub 仓库**　未确认此组件的独立官方仓库。
- **归属说明**　调度和恢复层见本文。Docker 是外部容器项目，GPU/NPU 为硬件通类。

## 下载与访问

作者未公开可核实的独立软件包或完整项目源码。

- [研究论文 PDF](<https://arxiv.org/pdf/2602.00019v1>)

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [Docker](../../%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/Docker/Docker.md)
