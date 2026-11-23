# LLM-as-a-Judge（FastChat 评审器）

依据评分规准，让语言模型评阅另一模型的回答，支持单答打分或两答比较。

## 输入与输出

- **输入**　问题、待评回答、评分维度和评审提示。部分任务还提供参考答案。
- **输出**　单项分数、回答优劣或平局判定，以及可选择保留的评审解释。

## 接入条件

- **LLM 参与**　需要通用 LLM 担任评委。记录、汇总和统计评分可以由常规代码完成。
- **运行条件**　FastChat 脚本及受支持的评审服务和访问凭据。原版单答评分函数接受 OpenAI 或 Anthropic 型号，其他模型需要另接适配器。

公共实现负责构造评审输入、执行评分和保存判断。评分对评审模型、提示以及成对回答的排列顺序敏感。

## 原始来源与公开实现

Zheng et al. (2023), Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena

[论文或原始出版物](https://arxiv.org/abs/2306.05685)

- **GitHub 仓库**　[lm-sys/FastChat](https://github.com/lm-sys/FastChat)
- **实现入口**　[查看源代码](https://github.com/lm-sys/FastChat/blob/587d5cfa1609a43d192cedb8441cac3c17db105d/fastchat/llm_judge/gen_judgment.py)

FastChat 仓库含方法作者的评审脚本。评审模型本体需另外提供。

## 下载

- [下载实现源码（ZIP）](https://github.com/lm-sys/FastChat/archive/587d5cfa1609a43d192cedb8441cac3c17db105d.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [原研究的人工评审数据](https://huggingface.co/datasets/lmsys/mt_bench_human_judgments)　可下载 MT-Bench 的人工标注，用于分析模型评审与人类判断的一致性。
