# LLM-as-a-Judge

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

依据评分规准，让语言模型评阅另一模型的回答，支持单答打分或两答比较。

## 输入、输出与 LLM 参与

- **输入**　问题、待评回答、评分维度和评审提示。部分任务还提供参考答案。
- **输出**　单项分数、回答优劣或平局判定，以及可选择保留的评审解释。
- **LLM 参与**　需要通用 LLM 担任评委。记录、汇总和统计评分可以由常规代码完成。

## 结果解读

评审结果受评委、提示、答案位置等因素影响。BioDesignBench 把这一思路用于评估智能体输出。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 跨模型评审团](../BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Zheng et al. (2023), Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena](<https://arxiv.org/abs/2306.05685>)
- **GitHub 仓库**　[lm-sys/FastChat](<https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge>)
- **归属说明**　P6 参考该评审方法。实际打分代码在 BioDesignBench。

## 下载与访问

- [原研究的人工评审数据](<https://huggingface.co/datasets/lmsys/mt_bench_human_judgments>)　可下载 MT-Bench 的人工标注，用于分析模型评审与人类判断的一致性。
- [仓库源码 ZIP · lm-sys/FastChat](<https://github.com/lm-sys/FastChat/archive/587d5cfa1609a43d192cedb8441cac3c17db105d.zip>)　该仓库的固定快照。
