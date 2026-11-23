# BioDesignBench 任务规范（DesignTask）

[工具接口与执行](../../README.md) / 工作流与执行管理

## 用途

Pydantic 校验字段，基准再从任务标识确定分类。

## 输入、输出与 LLM 参与

- **输入**　原始任务 JSON，含描述、约束、元数据和评价字段。
- **输出**　按类型校验的任务记录，供生成提示及评分读取。
- **LLM 参与**　否（数据校验）

## 结果解读

Pydantic 校验数据结构。通过校验表示字段符合任务格式，真实标签和评价标准还由基准维护。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为评测准备／数据结构。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **Pydantic 的原始出处**　[Pydantic, Pydantic Validation（官方软件文档）](<https://docs.pydantic.dev/latest/>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　作者定义 DesignTask。Pydantic 为其依赖。

## 下载与访问

- [下载作者补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　包含任务结构和类型校验的方法说明。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Pydantic](../../%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/Pydantic/Pydantic.md)
