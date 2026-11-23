# BioDesignBench 隔离执行环境

[工具接口与执行](../../README.md) / 工作流与执行管理

## 用途

每次会话使用隔离 Docker 容器。工具提供器对接 OpenAI、Anthropic、Google Gen AI SDK / Vertex AI，DeepSeek 经兼容接口访问。

## 输入、输出与 LLM 参与

- **输入**　封装的工具、任务及运行配置。
- **输出**　可复现的工具运行环境、参考智能体执行记录。
- **LLM 参与**　否（基础设施本身）

## 结果解读

每次会话在受控环境中运行，参考程序保存工具调用与产物。基准代码和领域工具包有各自的仓库。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为运行基础设施。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **Docker 的原始出处**　[Solomon Hykes / dotCloud (2013)，Docker 软件首次公开演示（无单一方法论文）](<https://www.docker.com/blog/docker-nine-years-young/>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　作者提供 agent harness 与工具镜像。Docker 为已有运行技术。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Docker](../../%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/Docker/Docker.md) · [protein-design-mcp](../../%E5%B7%A5%E5%85%B7%E5%8D%8F%E8%AE%AE%E4%B8%8E%E6%9C%8D%E5%8A%A1/protein-design-mcp/protein-design-mcp.md)
