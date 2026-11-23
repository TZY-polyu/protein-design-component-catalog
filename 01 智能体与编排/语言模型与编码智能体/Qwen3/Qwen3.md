# Qwen3

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

为对话式智能体理解指令、选择工具和整理结果提供语言推理后端。AutoBinder 将 Qwen3 列为可选后端。

## 输入、输出与 LLM 参与

- **输入**　系统提示、用户目标、对话上下文和可用工具的文字或结构化描述。
- **输出**　模型生成的文本或符合宿主接口的工具调用请求。
- **LLM 参与**　组件本身是通用 LLM。工具执行由宿主及外部程序承担。

## 结果解读

Qwen3 是模型家族，具体参数规模和发布变体影响可用能力。论文模型标签与权重下载的版本应分别记录。

## 在六篇研究中的用法

- **AutoBinder Agent**（已描述的后端选项）　为智能体提供本地推理。图1标出 32B/80B，正文说明通过本地 vLLM 提供服务。未按版本报告成绩。

使用此来源的研究组件包括 [AutoBinder 任务规划层](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/AutoBinder%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E5%B1%82/AutoBinder%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E5%88%92%E5%B1%82.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Qwen Team (2025), Qwen3 Technical Report](<https://arxiv.org/abs/2505.09388>)
- **GitHub 仓库**　[QwenLM/Qwen3](<https://github.com/QwenLM/Qwen3>)
- **归属说明**　家族技术报告。

## 下载与访问

- [Qwen3-32B 模型文件](<https://huggingface.co/Qwen/Qwen3-32B/tree/main>)　Qwen 官方权重目录，为家族中一个明确命名的版本。
- [仓库源码 ZIP · QwenLM/Qwen3](<https://github.com/QwenLM/Qwen3/archive/7a2f61ffc7a20d47efcd2bf97f6f2bf52729042e.zip>)　该仓库的固定快照。

## 关联组件

[AutoBinder Agent](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [vLLM](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/vLLM/vLLM.md)
