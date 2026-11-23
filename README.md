# 蛋白质设计相关组件整理

本资料库收录 317 份中文组件说明，覆盖六篇研究中的 232 条使用记录和 57 个配套工具接口。同一模型在不同研究中的用法合并在同一页。一个工具有独立的方法和 MCP 封装时，两页分别给出来源、下载内容和彼此的链接。

## 按分类查找

| 分类 | 组件说明 | 包含内容 |
| --- | ---: | --- |
| [智能体与编排](01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/README.md) | 48 | 研究系统、语言模型、任务规划、角色分工与反馈 |
| [工具接口与执行](02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/README.md) | 94 | 工具协议、运行环境，以及可按名称查找的 57 个 MCP 接口 |
| [数据与知识](03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/README.md) | 39 | 序列与结构数据库、文献、训练资料和任务数据 |
| [科学模型与计算](04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/README.md) | 82 | 序列建模、结构预测、分子力学模拟及性质计算 |
| [评估与展示](05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/README.md) | 54 | 质量指标、智能体评分、统计方法、实验仪器与结果展示 |

## 直接查看

[ProteinMPNN](04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/ProteinMPNN/ProteinMPNN.md) · [ProteinMPNN MCP](02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ProteinMPNN%20MCP/ProteinMPNN%20MCP.md) · [AlphaFold2](04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [UniProt](03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/UniProt/UniProt.md) · [MCP](02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/MCP/MCP.md) · [BioDesignBench](05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)

## 阅读与下载

- **来源**　每页标出组件自身的原始论文、技术报告或作者发布页。若组件是某个研究新定义的角色或接口，单独注明该研究的定义及底层方法。
- **LLM**　通用 LLM 处理自然语言、规划或评审；蛋白语言模型（pLM）学习蛋白序列等专门表示。工具页还说明它自身的计算是否用模型，以及上层智能体怎样调用它。
- **下载**　源码 ZIP、模型权重、数据库文件和论文附件各自标明。仓库快照对应链接所示的提交。部分工具只能在线使用或须申请许可；仪器、实验方法和未公开的内部组件会说明可取得的资料。
- **接口数量**　ProteinMCP 的同期作者目录包含 24 个自研服务和 14 个社区服务。BioDesignBench 正文报告 17 个工具；同版补充表 S1 和注册代码逐项列出 19 个，其中 16 个原子接口、3 个复合接口。本目录以逐项清单收录。

## 六篇研究

- [ProtAgents](01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)　[ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- [AutoBinder Agent](01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)　[AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design](<https://arxiv.org/abs/2602.00019v1>)
- [MAESD](01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)　[MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- [ProteinMCP](01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- [Latent-Y](01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)　[Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design](<https://arxiv.org/abs/2603.29727v2>)
- [BioDesignBench](05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)
