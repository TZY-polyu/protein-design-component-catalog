# Gemini 2.5 Pro

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

在 BioDesignBench 中承担自然语言决策，并出现在跨模型评审所用的模型名单中。

## 输入、输出与 LLM 参与

- **输入**　作为智能体时读取任务与工具结果。作为评审时读取待评答复、证据及评分要求。
- **输出**　前一种用法给出下一步操作或最终答复，后一种用法给出指定评分项的判断。
- **LLM 参与**　它本身是通用 LLM。

## 结果解读

同一模型在决策与评审两种角色中接收的材料、承担的任务不同，比较结果时需要保留角色信息。

## 在六篇研究中的用法

- **BioDesignBench**（运行时决策／模型比较）　在引导和非引导两种模式下作决策，记录候选与工具轨迹。

使用此来源的研究组件包括 [BioDesignBench 跨模型评审团](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Gemini Team (2025), Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, Long Context, and Next Generation Agentic Capabilities](<https://arxiv.org/abs/2507.06261>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　专有模型。未公开模型源码仓库。

## 下载与访问

未核实由 Google 公开提供的 Gemini 2.5 Pro 本体权重。

- [Google 官方模型与 API 目录](<https://ai.google.dev/gemini-api/docs/models>)　托管模型入口，型号可用性受平台和账户条件影响。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)
