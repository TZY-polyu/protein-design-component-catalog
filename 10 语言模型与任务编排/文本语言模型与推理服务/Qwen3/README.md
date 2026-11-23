# Qwen3

用公开权重进行文本生成和对话推理。支持工具调用的宿主还可以把模型生成的请求交给相应工具执行。

## 输入与输出

- **输入**　系统提示、用户目标、对话上下文和可用工具的文字或结构化描述。
- **输出**　模型生成的文本或符合宿主接口的工具调用请求。

## 接入条件

- **LLM 参与**　组件本身是通用 LLM。工具执行由宿主及外部程序承担。
- **运行条件**　本地运行需要相匹配的推理库、分词器和权重，以及足以容纳所选模型的内存或显存。

Qwen3 有多个模型规模及架构。下方以公开稠密版本作下载示例，工具调用格式和资源开销随权重与推理框架而变化。

## 原始来源与公开实现

Qwen Team (2025), Qwen3 Technical Report

[论文或原始出版物](https://arxiv.org/abs/2505.09388)

- **GitHub 仓库**　[QwenLM/Qwen3](https://github.com/QwenLM/Qwen3)
- **实现入口**　[查看源代码](https://github.com/huggingface/transformers/tree/main/src/transformers/models/qwen3)

Qwen 团队仓库提供发布说明。可运行的稠密模型实现位于 Hugging Face Transformers 的 qwen3 包。

## 下载

- [下载源码快照（ZIP）](https://github.com/QwenLM/Qwen3/archive/7a2f61ffc7a20d47efcd2bf97f6f2bf52729042e.zip)　该链接固定到仓库中的一个提交。
- [Qwen3-32B 权重与分词器（示例）](https://huggingface.co/Qwen/Qwen3-32B/tree/main)　Qwen 团队发布的稠密模型。
- [Transformers 发行包](https://pypi.org/project/transformers/#files)　选择支持 Qwen3 的版本。
