# Claude Sonnet 4

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

理解文本与证据、按给定规则给出判断。BioDesignBench 的补充材料将 Claude Sonnet 4 列入评委池。

## 输入、输出与 LLM 参与

- **输入**　任务说明、候选回答或行动轨迹，以及提供给评委的评分标准。
- **输出**　自然语言判断或结构化评分，随后由基准按评委规则汇总。
- **LLM 参与**　这是通用 LLM 本身。它在该用途下执行评审，不负责测量分子结构或实验数值。

## 结果解读

论文中的这一评委版本应与受测智能体 Claude Sonnet 4.5 区分。Anthropic 的 Claude API 记录其标识于 2026 年 6 月退役。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 跨模型评审团](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Anthropic (2025), Claude 4 System Card（含 Claude Sonnet 4）](<https://www-cdn.anthropic.com/6d8a8055020700718b0c49369f60816ba2a7c285/Claude%204%20System%20Card.pdf>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　商业模型。P6 评委用 Claude Sonnet 4，决策模型另用 Sonnet 4.5。

## 下载与访问

厂商未公开该模型的可下载权重。

- [官方模型可用性记录](<https://platform.claude.com/docs/en/about-claude/model-deprecations>)　核对原模型 ID 和退役记录。
