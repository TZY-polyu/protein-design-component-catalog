# MAESD

[智能体与编排](../../README.md) / 研究系统与协作框架

## 用途

把自然语言中的蛋白功能要求转为可检索的约束，协调候选生成、结构预测、分层筛选与偏好排序。

## 输入、输出与 LLM 参与

- **输入**　文字形式的功能需求。系统另使用本体、序列、结构域资料及可用参考结构。
- **输出**　候选氨基酸序列、相应预测结构、筛选依据和多目标排序结果。
- **LLM 参与**　通用 LLM 参与意图识别等语言任务。序列生成可使用蛋白语言模型，物理计算与排序有各自实现。

## 结果解读

系统报告的功能保守性来源于计算代理指标。原论文用结构与序列等指标验证候选。

## 在六篇研究中的用法

使用此来源的研究组件包括 [MAESD 意图识别智能体（IRA）](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89/MAESD%20%E6%84%8F%E5%9B%BE%E8%AF%86%E5%88%AB%E6%99%BA%E8%83%BD%E4%BD%93%EF%BC%88IRA%EF%BC%89.md)、[MAESD 演化循环（EL）](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/MAESD%20%E6%BC%94%E5%8C%96%E5%BE%AA%E7%8E%AF%EF%BC%88EL%EF%BC%89/MAESD%20%E6%BC%94%E5%8C%96%E5%BE%AA%E7%8E%AF%EF%BC%88EL%EF%BC%89.md)、[MAESD 序列生成智能体](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E5%BA%8F%E5%88%97%E7%94%9F%E6%88%90%E6%99%BA%E8%83%BD%E4%BD%93/MAESD%20%E5%BA%8F%E5%88%97%E7%94%9F%E6%88%90%E6%99%BA%E8%83%BD%E4%BD%93.md)、[MAESD 蛋白筛选专家（PSE）](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E8%9B%8B%E7%99%BD%E7%AD%9B%E9%80%89%E4%B8%93%E5%AE%B6%EF%BC%88PSE%EF%BC%89/MAESD%20%E8%9B%8B%E7%99%BD%E7%AD%9B%E9%80%89%E4%B8%93%E5%AE%B6%EF%BC%88PSE%EF%BC%89.md)、[MAESD 模块消融与迭代评测](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/MAESD%20%E6%A8%A1%E5%9D%97%E6%B6%88%E8%9E%8D%E4%B8%8E%E8%BF%AD%E4%BB%A3%E8%AF%84%E6%B5%8B/MAESD%20%E6%A8%A1%E5%9D%97%E6%B6%88%E8%9E%8D%E4%B8%8E%E8%BF%AD%E4%BB%A3%E8%AF%84%E6%B5%8B.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)
- **归属说明**　论文项目仓库。内部模块与指标共用。

## 下载与访问

作者仓库默认分支名为 2，README 将项目描述为模块化实现框架。默认配置使用 mock 适配器，真实科学模型和权重需要分别取得。

- [作者仓库源码快照（ZIP）](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　默认分支 2 的固定版本，含框架与后端适配源码。
- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [ACS 补充材料记录](<https://doi.org/10.1021/acs.jcim.5c02580.s001>)　对应同一份补充材料的永久记录。
