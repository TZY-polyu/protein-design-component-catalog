# DeepSeek（版本未披露）

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

作为 AutoBinder Agent 描述的语言模型后端，解释对话和返回信息，生成工作流计划或工具请求。

## 输入、输出与 LLM 参与

- **输入**　研究目标、对话上下文、可用工具及其返回结果。
- **输出**　文本回复、任务分解或调用工具所需的结构化参数。
- **LLM 参与**　属于通用 LLM 后端。

## 结果解读

原文只写 DeepSeek。模型系列中不同版本的架构、权重和 API 标识不能据此逆推出当时的具体版本。

## 在六篇研究中的用法

- **AutoBinder Agent**（已描述的后端选项）　为智能体提供推理。经 OpenAI 兼容 API 接入。论文未列出具体模型版本或单独成绩。

使用此来源的研究组件包括 [AutoBinder 任务规划层](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/AutoBinder%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E5%B1%82/AutoBinder%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E5%B1%82.md)、[BioDesignBench 跨模型评审团](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[AutoBinder 未公开所用版本，无法确定该模型的原始论文。家族早期报告为 DeepSeek-AI (2024), DeepSeek LLM: Scaling Open-Source Language Models with Longtermism。](<https://arxiv.org/abs/2401.02954>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　链接对应家族早期报告。具体模型和仓库未披露。

## 下载与访问

该论文所用检查点未披露，无法给出对应版本的精确下载。

- [DeepSeek 官方模型目录](<https://huggingface.co/deepseek-ai>)　可查看已公开的各型号权重及许可。
- [DeepSeek API 文档](<https://api-docs.deepseek.com/>)　提供服务接入信息。

## 关联组件

[AutoBinder Agent](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [OpenAI-compatible API (DeepSeek)](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/OpenAI-compatible%20API%20%28DeepSeek%29/OpenAI-compatible%20API%20%28DeepSeek%29.md)
