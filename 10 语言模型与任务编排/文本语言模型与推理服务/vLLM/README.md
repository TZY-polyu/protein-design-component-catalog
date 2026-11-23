# vLLM

将已支持的生成模型部署成推理服务，以批处理和显存管理处理同时到达的请求。

## 输入与输出

- **输入**　模型参数和配置、提示词或聊天消息、推理请求及服务设置。
- **输出**　生成的 token 或文本响应，也可通过兼容接口以结构化格式返回。

## 接入条件

- **LLM 参与**　运行时加载并执行选定模型。vLLM 自身是推理引擎，没有独立的通用语言模型权重。
- **运行条件**　需要与所选硬件及软件栈匹配的 vLLM 构建，并另备引擎支持的模型权重和分词器。

可用上下文长度、显存需求和输出能力由引擎配置及载入的具体模型共同决定。

## 原始来源与公开实现

Kwon et al. (2023), Efficient Memory Management for Large Language Model Serving with PagedAttention

[论文或原始出版物](https://arxiv.org/abs/2309.06180)

- **GitHub 仓库**　[vllm-project/vllm](https://github.com/vllm-project/vllm)
- **实现入口**　[查看源代码](https://github.com/vllm-project/vllm)

vLLM 项目的公开实现，核心包括调度、模型执行和服务入口。

## 下载

- [vLLM 发行文件](https://pypi.org/project/vllm/#files)　发布包包含推理服务软件，模型权重应到模型开发者处另取。
- [下载本次索引的源码快照（ZIP）](https://github.com/vllm-project/vllm/archive/418af607309d819bf091229bcc3d8ca8e5ce007f.zip)
