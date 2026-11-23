# AutoGen

为多个智能体建立会话，管理消息路由、角色和工具执行。

## 输入与输出

- **输入**　角色配置、消息历史、工具函数及可选模型客户端。
- **输出**　按会话规则形成的交互记录、工具调用和任务结果。

## 接入条件

- **LLM 参与**　消息路由和执行器可以独立运行。需要生成式决策或自然语言回复的智能体需配置 LLM。
- **运行条件**　安装与调用代码匹配的 AutoGen 包。若启用模型驱动的智能体，需另配兼容的模型客户端和后端。

框架不同代际的 API 与包名有差异，使用时需选择与应用代码兼容的发行版。

## 原始来源与公开实现

Wu et al. (2023), AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation

[论文或原始出版物](https://arxiv.org/abs/2308.08155)

- **GitHub 仓库**　[microsoft/autogen](https://github.com/microsoft/autogen)
- **实现入口**　[查看源代码](https://github.com/microsoft/autogen)

微软 AutoGen 官方项目。

## 下载

- [官方发布版本](https://github.com/microsoft/autogen/releases)　提供版本记录及源码。
- [项目源码 ZIP](https://github.com/microsoft/autogen/archive/8390985108cb1e3881f5f7297765758d8ad2540c.zip)　公开项目的源码快照。
