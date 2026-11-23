# ReAct

让语言模型依据任务和环境反馈选择下一项动作，使工具调用结果参与后续决策。

## 输入与输出

- **输入**　任务说明、可用动作集合，以及到当前为止的交互和观察记录。
- **输出**　下一项行动或最终答案。运行过程中可形成包含行动与反馈的轨迹。

## 接入条件

- **LLM 参与**　需要通用语言模型作决策。被调用的工具有各自的输入和执行实现。
- **运行条件**　需要可调用的模型后端和相应的工具环境。原示例使用历史服务。现代工具调用后端可使用 LangGraph 的实现。

论文作者公开了任务环境与交互示例。旧版示例依赖早期 GPT-3 服务，迁移到当前模型时，需要使用兼容的调用接口。

## 原始来源与公开实现

Yao et al. (ICLR 2023), ReAct: Synergizing Reasoning and Acting in Language Models

[论文或原始出版物](https://arxiv.org/abs/2210.03629)

- **GitHub 仓库**　[ysymyth/ReAct](https://github.com/ysymyth/ReAct)
- **实现入口**　[查看源代码](https://github.com/ysymyth/ReAct/blob/master/hotpotqa.ipynb)

第一作者仓库包含任务交互代码和可读的 notebook。另附 LangGraph 提供的独立实现。

## 下载

- [下载源码快照（ZIP）](https://github.com/ysymyth/ReAct/archive/6bdb3a1fd38b8188fc7ba4102969fe483df8fdc9.zip)　该链接固定到仓库中的一个提交。
- [LangGraph 中的公开 ReAct 实现](https://github.com/langchain-ai/langgraph/blob/main/libs/prebuilt/langgraph/prebuilt/chat_agent_executor.py)　由 LangGraph 维护的另一个实现，支持工具调用式模型。
- [LangGraph 预构建组件包](https://pypi.org/project/langgraph-prebuilt/#files)　通过发布包获取上述实现。
