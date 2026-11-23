# predict_affinity_boltz

[工具接口与执行](../../README.md) / BioDesignBench 工具接口

## 用途

通过 Boltz-2 查询其支持的分子结合亲和力预测。

## 输入、输出与 LLM 参与

- **输入**　模型支持的分子组合以及参与计算的实体描述。
- **输出**　对该组合给出的结合相关预测值，可能同时附带结构或置信度。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

补充表 S1 确认此接口的注册名。实际数值的意义取决于后端的预测头和适用分子类型。

## 在六篇研究中的用法

- **BioDesignBench**（运行时／案例评估）　补充表S1与A.2明确将 predict_affinity_boltz 映射到 Boltz-2。正文案例只称学习式亲和力预测器，未给调用日志以核对案例身份。
- **BioDesignBench**　表 S1 原子工具，两种模式均可用。

## 原始来源与 GitHub

- **接口定义**　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)。[作者补充材料与工具表 S1](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)
- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp/tree/7a45f13d5c7667513f4b3cfc47e472f3209b1be1>)（含该接口的工具包，固定版本）。
- **Boltz-2 的原始出处**　[Passaro et al. (2025), Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction](<https://doi.org/10.1101/2025.06.14.659707>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/jasonkim8652/protein-design-mcp/archive/7a45f13d5c7667513f4b3cfc47e472f3209b1be1.zip>)　下载同期工具包，含本接口及其他已注册接口。
- [作者补充材料 PDF（工具表 S1）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Boltz-2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/Boltz-2/Boltz-2.md)
