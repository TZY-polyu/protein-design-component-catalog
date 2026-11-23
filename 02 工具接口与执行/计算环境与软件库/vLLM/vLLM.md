# vLLM

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

把语言模型部署为推理服务，并通过批处理和显存管理支持并发请求。AutoBinder 用它承载本地 Qwen 后端。

## 输入、输出与 LLM 参与

- **输入**　模型参数和配置、提示词或聊天消息、推理请求及服务设置。
- **输出**　生成的 token 或文本响应，也可通过兼容接口以结构化格式返回。
- **LLM 参与**　运行时加载并执行选定模型。vLLM 自身是推理引擎，没有独立的通用语言模型权重。

## 结果解读

同一个 vLLM 版本可以服务不同模型。回答质量由模型和推理设置共同决定，服务地址本身不能标识模型版本。

## 在六篇研究中的用法

使用此来源的研究组件包括 [AutoBinder 统一模型适配器](../../%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/AutoBinder%20%E7%BB%9F%E4%B8%80%E6%A8%A1%E5%9E%8B%E9%80%82%E9%85%8D%E5%99%A8/AutoBinder%20%E7%BB%9F%E4%B8%80%E6%A8%A1%E5%9E%8B%E9%80%82%E9%85%8D%E5%99%A8.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Kwon et al. (2023), Efficient Memory Management for Large Language Model Serving with PagedAttention](<https://arxiv.org/abs/2309.06180>)
- **GitHub 仓库**　[vllm-project/vllm](<https://github.com/vllm-project/vllm>)
- **归属说明**　原文提出 PagedAttention 并构建 vLLM。

## 下载与访问

- [vLLM 发行文件](<https://pypi.org/project/vllm/#files>)　发布包包含推理服务软件，模型权重应到模型开发者处另取。
- [仓库源码 ZIP · vllm-project/vllm](<https://github.com/vllm-project/vllm/archive/418af607309d819bf091229bcc3d8ca8e5ce007f.zip>)　该仓库的固定快照。
