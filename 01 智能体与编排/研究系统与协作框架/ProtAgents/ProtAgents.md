# ProtAgents

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

用基于 GPT-4 的多角色对话协调文献检索、结构生成、结构分析和蛋白力学性质预测。

## 输入、输出与 LLM 参与

- **输入**　自然语言问题，以及所需的参考文献、蛋白序列、结构文件或结构编号。
- **输出**　工具生成的结构及数值结果、表格文件与对研究问题的文字答复。
- **LLM 参与**　角色间的理解、规划和审查使用通用 LLM。数值工具及专用蛋白模型分别运行。

## 结果解读

论文用四组计算案例展示各角色交接任务。力学预测和计算结构应与原始实验数据分别解读。

## 在六篇研究中的用法

- **MAESD**（仅对照）　用另一项多智能体系统与 MAESD 比较结构指标、序列新颖性和运行成本。

使用此来源的研究组件包括 [ProtAgents 用户代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E7%94%A8%E6%88%B7%E4%BB%A3%E7%90%86/ProtAgents%20%E7%94%A8%E6%88%B7%E4%BB%A3%E7%90%86.md)、[ProtAgents 规划代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E8%A7%84%E5%88%92%E4%BB%A3%E7%90%86/ProtAgents%20%E8%A7%84%E5%88%92%E4%BB%A3%E7%90%86.md)、[ProtAgents 执行代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%90%86/ProtAgents%20%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%90%86.md)、[ProtAgents 审查代理](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProtAgents%20%E5%AE%A1%E6%9F%A5%E4%BB%A3%E7%90%86/ProtAgents%20%E5%AE%A1%E6%9F%A5%E4%BB%A3%E7%90%86.md)、[ProtAgents 结果导出函数 save_to_csv_file](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E4%B8%89%E7%BB%B4%E5%B1%95%E7%A4%BA%E4%B8%8E%E7%BB%93%E6%9E%9C%E5%AF%BC%E5%87%BA/ProtAgents%20%E7%BB%93%E6%9E%9C%E5%AF%BC%E5%87%BA%E5%87%BD%E6%95%B0%20save_to_csv_file/ProtAgents%20%E7%BB%93%E6%9E%9C%E5%AF%BC%E5%87%BA%E5%87%BD%E6%95%B0%20save_to_csv_file.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)

## 下载与访问

- [作者仓库源码快照（ZIP）](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　含角色定义、工具函数和实验 notebook。
- [ProteinForceGPT 模型文件](<https://huggingface.co/lamm-mit/ProteinForceGPT/tree/main>)　力学性质专用模型的上游发布页。
- [预训练数据文件](<https://huggingface.co/datasets/lamm-mit/GPTProteinPretrained/tree/main>)　作者预训练序列集。
- [项目论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[MAESD](../MAESD/MAESD.md)
