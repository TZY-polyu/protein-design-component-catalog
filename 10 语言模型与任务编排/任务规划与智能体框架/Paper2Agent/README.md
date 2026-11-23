# Paper2Agent

将论文附带的科研代码、教程与文档整理成可由智能体调用的工具，使文献方法可以交互使用。

## 输入与输出

- **输入**　研究论文、公开的代码仓库，以及可用的示例、教程或测试。
- **输出**　从文献代码提取并测试的可调用工具、其接口说明，以及能够调用工具的智能体环境。

## 接入条件

- **LLM 参与**　生成、解释与协调过程使用通用 LLM。已封装函数的科学计算依各自实现执行。
- **运行条件**　兼容的编码智能体、待处理的文献和研究代码。能否验证生成的工具还取决于原方法的依赖和数据。

工作流可验证生成工具的接口及测试情况。原方法缺少依赖、数据或可运行示例时，工具的可验证范围也会随之缩小。

## 原始来源与公开实现

Miao et al. (2025), Paper2Agent: Reimagining Research Papers As Interactive and Reliable AI Agents

[论文或原始出版物](https://arxiv.org/abs/2509.06917)

- **GitHub 仓库**　[jmiao24/Paper2Agent](https://github.com/jmiao24/Paper2Agent)
- **实现入口**　[查看源代码](https://github.com/jmiao24/Paper2Agent/blob/8c2d059165ef8cdcb70dbea76655b9c2b55b38e6/skills/paper2agent/paper2mcp/scripts/verify_mcp_server.py)

上游作者仓库

## 下载

- [下载实现源码（ZIP）](https://github.com/jmiao24/Paper2Agent/archive/8c2d059165ef8cdcb70dbea76655b9c2b55b38e6.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
