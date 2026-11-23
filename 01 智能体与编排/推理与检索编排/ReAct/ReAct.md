# ReAct

[智能体与编排](../../README.md) / 推理与检索编排

## 用途

让智能体交替进行推理、选择行动、读取环境反馈，再决定下一次行动或回答。

## 输入、输出与 LLM 参与

- **输入**　任务说明、可用动作集合，以及到当前为止的交互和观察记录。
- **输出**　下一项行动或最终答案。运行过程中可形成包含行动与反馈的轨迹。
- **LLM 参与**　论文中的 ReAct 以语言模型作推理和行动决策，外部工具按各自实现执行。

## 结果解读

BioDesignBench 参考了这种交互范式。作者仓库演示原方法，具体基准的运行循环由基准项目另行实现。

## 在六篇研究中的用法

使用此来源的研究组件包括 [Latent-Y 主智能体](../../%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/Latent-Y%20%E4%B8%BB%E6%99%BA%E8%83%BD%E4%BD%93/Latent-Y%20%E4%B8%BB%E6%99%BA%E8%83%BD%E4%BD%93.md)、[BioDesignBench 参考智能体循环](../../%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/BioDesignBench%20%E5%8F%82%E8%80%83%E6%99%BA%E8%83%BD%E4%BD%93%E5%BE%AA%E7%8E%AF/BioDesignBench%20%E5%8F%82%E8%80%83%E6%99%BA%E8%83%BD%E4%BD%93%E5%BE%AA%E7%8E%AF.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Yao et al. (ICLR 2023), ReAct: Synergizing Reasoning and Acting in Language Models](<https://arxiv.org/abs/2210.03629>)
- **GitHub 仓库**　[ysymyth/ReAct](<https://github.com/ysymyth/ReAct>)
- **归属说明**　原方法仓库。论文参考其推理范式，未证明复用该代码。

## 下载与访问

- [仓库源码 ZIP · ysymyth/ReAct](<https://github.com/ysymyth/ReAct/archive/6bdb3a1fd38b8188fc7ba4102969fe483df8fdc9.zip>)　该仓库的固定快照。
