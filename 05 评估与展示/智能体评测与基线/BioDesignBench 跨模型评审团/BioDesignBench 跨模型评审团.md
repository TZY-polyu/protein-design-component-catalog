# BioDesignBench 跨模型评审团

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

评委池为 Claude Sonnet 4、GPT-5.2、Gemini 2.5 Pro、DeepSeek（具体版本未明）。智能体用三个异族评委，人工基线可用全部四个。

## 输入、输出与 LLM 参与

- **输入**　智能体的选择、执行记录与设计依据。
- **输出**　主观分项评分及抗离群值的加权汇总。
- **LLM 参与**　是（评分阶段使用通用 LLM）

## 结果解读

依据多评委原则评价策略与解释，在被测模型家族以外选取评委，再汇总各自判断。该模块承担评分中的主观部分。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为提交后／主观评分。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **PoLL 的原始出处**　[Verga et al. (2024), Replacing Judges with Juries: Evaluating LLM Generations with a Panel of Diverse Models](<https://arxiv.org/abs/2404.18796>)
- **LLM-as-a-Judge 的原始出处**　[Zheng et al. (2023), Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena](<https://arxiv.org/abs/2306.05685>)
- **Claude Sonnet 4 的原始出处**　[Anthropic (2025), Claude 4 System Card（含 Claude Sonnet 4）](<https://www-cdn.anthropic.com/6d8a8055020700718b0c49369f60816ba2a7c285/Claude%204%20System%20Card.pdf>)
- **GPT-5.2 的原始出处**　[OpenAI (2025), Update to GPT-5 System Card: GPT-5.2（官方系统卡）](<https://openai.com/index/gpt-5-system-card-update-gpt-5-2/>)
- **Gemini 2.5 Pro 的原始出处**　[Gemini Team (2025), Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, Long Context, and Next Generation Agentic Capabilities](<https://arxiv.org/abs/2507.06261>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　本文按 PoLL 思路组织评委、限制同族自评并汇总。文献48–50为此前的模型评审与专家组方法。

## 下载与访问

- [下载 panel.py](<https://raw.githubusercontent.com/RomeroLab/BioDesignBench/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/llm_judge/panel.py>)　公开的多模型评审实现。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../BioDesignBench/BioDesignBench.md) · [Claude Sonnet 4](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Claude%20Sonnet%204/Claude%20Sonnet%204.md) · [DeepSeek（版本未披露）](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/DeepSeek%EF%BC%88%E7%89%88%E6%9C%AC%E6%9C%AA%E6%8A%AB%E9%9C%B2%EF%BC%89/DeepSeek%EF%BC%88%E7%89%88%E6%9C%AC%E6%9C%AA%E6%8A%AB%E9%9C%B2%EF%BC%89.md) · [Gemini 2.5 Pro](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/Gemini%202.5%20Pro/Gemini%202.5%20Pro.md) · [GPT-5.2](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BC%96%E7%A0%81%E6%99%BA%E8%83%BD%E4%BD%93/GPT-5.2/GPT-5.2.md) · [LLM-as-a-Judge](../LLM-as-a-Judge/LLM-as-a-Judge.md) · [PoLL](../PoLL/PoLL.md)
