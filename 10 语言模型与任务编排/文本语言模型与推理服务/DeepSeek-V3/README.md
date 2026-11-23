# DeepSeek-V3

用于自然语言理解、文本和代码生成，可作为对话程序的推理后端。

## 输入与输出

- **输入**　通过配套分词器处理的文本提示或多轮对话上下文。
- **输出**　生成的 token、文本回复，或经上层程序解析的结构化结果。

## 接入条件

- **LLM 参与**　本组件本身是通用 LLM。
- **运行条件**　需匹配的模型权重及可承载大型混合专家模型的计算资源。

V3 与之后的更新有独立检查点。确切权重可按发布版本核对。

## 原始来源与公开实现

DeepSeek-AI (2024), DeepSeek-V3 Technical Report

[论文或原始出版物](https://arxiv.org/abs/2412.19437)

- **GitHub 仓库**　[deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3)
- **实现入口**　[查看源代码](https://github.com/deepseek-ai/DeepSeek-V3)

模型官方仓库。

## 下载

- [DeepSeek-V3 官方权重文件](https://huggingface.co/deepseek-ai/DeepSeek-V3/tree/main)　模型发布方提供的配置和分片权重。
- [项目源码 ZIP](https://github.com/deepseek-ai/DeepSeek-V3/archive/9b4e9788e4a3a731f7567338ed15d3ec549ce03b.zip)　公开项目的源码快照。
