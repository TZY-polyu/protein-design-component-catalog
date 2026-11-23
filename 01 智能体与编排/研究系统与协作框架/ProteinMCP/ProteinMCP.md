# ProteinMCP

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

把蛋白工程软件包装为标准服务，并由智能体管理工作流技能、上下文和工具调用，以协调不同计算任务。

## 输入、输出与 LLM 参与

- **输入**　自然语言任务或技能命令，以及相应的序列、结构、实验标签等输入资料。
- **输出**　所选工具产生的计算结果和报告。开发或管理任务还可产生新封装和服务注册状态。
- **LLM 参与**　系统的 Claude Code 使用通用 LLM 理解和编排。各服务自行执行其算法或专用模型。

## 结果解读

作者报告集成 38 个服务。目录中包括可用服务与社区封装，论文实际演示三个任务案例。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinMCP 技能解析器（Skill Parser）](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProteinMCP%20%E6%8A%80%E8%83%BD%E8%A7%A3%E6%9E%90%E5%99%A8%EF%BC%88Skill%20Parser%EF%BC%89/ProteinMCP%20%E6%8A%80%E8%83%BD%E8%A7%A3%E6%9E%90%E5%99%A8%EF%BC%88Skill%20Parser%EF%BC%89.md)、[ProteinMCP 上下文管理器](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProteinMCP%20%E4%B8%8A%E4%B8%8B%E6%96%87%E7%AE%A1%E7%90%86%E5%99%A8/ProteinMCP%20%E4%B8%8A%E4%B8%8B%E6%96%87%E7%AE%A1%E7%90%86%E5%99%A8.md)、[ProteinMCP 工具调用器](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E8%B0%83%E7%94%A8%E5%99%A8/ProteinMCP%20%E5%B7%A5%E5%85%B7%E8%B0%83%E7%94%A8%E5%99%A8.md)、[ProteinMCP 错误恢复与对话调试](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/ProteinMCP%20%E9%94%99%E8%AF%AF%E6%81%A2%E5%A4%8D%E4%B8%8E%E5%AF%B9%E8%AF%9D%E8%B0%83%E8%AF%95/ProteinMCP%20%E9%94%99%E8%AF%AF%E6%81%A2%E5%A4%8D%E4%B8%8E%E5%AF%B9%E8%AF%9D%E8%B0%83%E8%AF%95.md)、[ProteinMCP 平台功能定性对照](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/ProteinMCP%20%E5%B9%B3%E5%8F%B0%E5%8A%9F%E8%83%BD%E5%AE%9A%E6%80%A7%E5%AF%B9%E7%85%A7/ProteinMCP%20%E5%B9%B3%E5%8F%B0%E5%8A%9F%E8%83%BD%E5%AE%9A%E6%80%A7%E5%AF%B9%E7%85%A7.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)
- **归属说明**　论文项目仓库。封装与内部模块见该项目。

## 下载与访问

- [同期版本的整项目源码](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　可用于核对论文时期的目录和注册配置。
- [正式发表版本与附件](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　PMC 页面提供正式版全文、PDF、补充材料和数据声明。
- [下载期刊补充材料（DOCX）](<https://pmc.ncbi.nlm.nih.gov/articles/instance/13140703/bin/PRO-35-e70547-s001.docx>)　期刊附件，含表 S1–S3 的服务和工作流技能目录。
