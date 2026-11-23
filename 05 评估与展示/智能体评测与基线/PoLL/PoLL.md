# PoLL

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

让多个语言模型分别评判同一模型输出，再聚合判断，降低对单一评委选择的依赖。

## 输入、输出与 LLM 参与

- **输入**　待评回答、原问题、评分标准，以及一组评委模型的独立判断。
- **输出**　各评委的判定和聚合结果，可比较模型之间的一致性与分歧。
- **LLM 参与**　评委来自通用 LLM，聚合规则可由常规程序执行。

## 结果解读

BioDesignBench 借鉴评委团原则。其评委遴选、回避及分数汇总属于该基准自己的实现。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 跨模型评审团](../BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2/BioDesignBench%20%E8%B7%A8%E6%A8%A1%E5%9E%8B%E8%AF%84%E5%AE%A1%E5%9B%A2.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Verga et al. (2024), Replacing Judges with Juries: Evaluating LLM Generations with a Panel of Diverse Models](<https://arxiv.org/abs/2404.18796>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　P6 借鉴 PoLL 原则。运行实现见 BioDesignBench 的评审模块。

## 下载与访问

未核实原研究的独立官方代码或模型权重。

- [原研究论文 PDF](<https://arxiv.org/pdf/2404.18796>)　可下载方法论文。暂未核实独立官方软件包。
