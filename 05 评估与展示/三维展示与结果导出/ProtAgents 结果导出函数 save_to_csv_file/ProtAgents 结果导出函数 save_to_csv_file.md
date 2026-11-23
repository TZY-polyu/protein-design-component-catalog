# ProtAgents 结果导出函数 save_to_csv_file

[评估与展示](../../README.md) / 三维展示与结果导出

## 用途

保存群聊汇总的序列、结构和物理计算结果以便复查。格式错误曾由 Critic 识别。

## 输入、输出与 LLM 参与

- **输入**　结果 JSON 字典及输出文件名。
- **输出**　按蛋白与属性组织的 CSV 文件。
- **LLM 参与**　否，写文件是常规代码。JSON 准备和纠错由代理参与。

## 结果解读

该函数负责把对话中汇总的结构化结果落盘。输入 JSON 的字段和格式出错时，群聊可先纠正再调用。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 I–IV 结果保存。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　将字典导出 CSV 的具体函数由 ProtAgents 提供。CSV 是通用格式。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
