# Claude Sonnet 4.5

[智能体与编排](../../README.md) / 语言模型与编码智能体

## 用途

在智能体中解释研究者给出的任务，根据已有消息与工具返回结果选择下一步操作。BioDesignBench 将它列为受测的决策模型。

## 输入、输出与 LLM 参与

- **输入**　系统指令、用户任务、可用工具描述和本轮上下文。
- **输出**　自然语言回答或结构化工具调用请求，由外部运行器执行。
- **LLM 参与**　它本身是通用 LLM。调用后续生物信息工具时，工具可以独立计算。

## 结果解读

决策模型的成绩反映整个运行过程。单靠它给出的文字判断，不能确认蛋白质结构或实验性质。

## 在六篇研究中的用法

- **BioDesignBench**（运行时决策／模型比较）　在引导和非引导两种模式下作决策，记录候选与工具轨迹。

## 原始来源与 GitHub

- **原始文献或官方出处**　[Anthropic (2025), Introducing Claude Sonnet 4.5（官方发布，附系统卡）](<https://www.anthropic.com/news/claude-sonnet-4-5>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　专有模型。未公开模型源码仓库。

## 下载与访问

未核实公开模型权重。

- [官方模型与 API 目录](<https://platform.claude.com/docs/en/models/overview>)　服务入口，可用版本以账户和官方目录为准。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md)
