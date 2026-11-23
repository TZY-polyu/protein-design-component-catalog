# MAESD 云端与本地数据接口

[工具接口与执行](../../README.md) / 工作流与执行管理

## 用途

连接云端 LLM 与本地生物信息工具。结构预测使用 CPU、GPU 与存储。

## 输入、输出与 LLM 参与

- **输入**　文本请求或模块产出的坐标、分数及反馈。
- **输出**　语义结果、本地模型结果和模块间消息。
- **LLM 参与**　仅云端语言请求需通用 LLM，传输和执行接口本身无需。

## 结果解读

自然语言语义处理和领域计算各自返回不同类型的结果。标准化接口负责模块间传递所需数据。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行基础设施。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　云端与本地之间的接口是系统实现。正文未指定独立接口协议或软件包。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。
- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
