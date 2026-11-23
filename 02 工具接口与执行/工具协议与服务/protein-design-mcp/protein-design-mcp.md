# protein-design-mcp

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

把 BioDesignBench 使用的生成、预测或分析操作暴露为具有名称和参数约束的 MCP 接口。

## 输入、输出与 LLM 参与

- **输入**　指定的工具名与结构化参数。具体工具可接收序列、结构文件或任务标识。
- **输出**　按工具返回计算产物、指标、错误或任务状态，供上层智能体记录和判断。
- **LLM 参与**　通信与分派本身无需 LLM。运行时可由通用 LLM 选工具，底层模型因工具而异。

## 结果解读

原文与同期补充材料统计口径不同。对照论文实验应参考当时的工具清单与代码快照。

## 在六篇研究中的用法

- **BioDesignBench**（运行时接口）　主文报告17项。同版补充表S1列16个原子接口、3个复合接口，共19个。通过 stdio 传送 JSON-RPC，工具以 JSON Schema 描述。

使用此来源的研究组件包括 [BioDesignBench 参考智能体循环](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/BioDesignBench%20%E5%8F%82%E8%80%83%E6%99%BA%E8%83%BD%E4%BD%93%E5%BE%AA%E7%8E%AF/BioDesignBench%20%E5%8F%82%E8%80%83%E6%99%BA%E8%83%BD%E4%BD%93%E5%BE%AA%E7%8E%AF.md)、[BioDesignBench 非引导工具模式](../../%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E9%9D%9E%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F/BioDesignBench%20%E9%9D%9E%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F.md)、[BioDesignBench 引导工具模式](../../%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F/BioDesignBench%20%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F.md)、[BioDesignBench 隔离执行环境](../../%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E9%9A%94%E7%A6%BB%E6%89%A7%E8%A1%8C%E7%8E%AF%E5%A2%83/BioDesignBench%20%E9%9A%94%E7%A6%BB%E6%89%A7%E8%A1%8C%E7%8E%AF%E5%A2%83.md)、[BioDesignBench 设计功能映射](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench%20%E8%AE%BE%E8%AE%A1%E5%8A%9F%E8%83%BD%E6%98%A0%E5%B0%84/BioDesignBench%20%E8%AE%BE%E8%AE%A1%E5%8A%9F%E8%83%BD%E6%98%A0%E5%B0%84.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp>)
- **归属说明**　作者独立 MCP 封装仓库。主分支已重构，论文中的工具接口与数目按所给 v1 原文。

## 下载与访问

- [论文时期的代码快照](<https://api.github.com/repos/jasonkim8652/protein-design-mcp/zipball/7a45f13d5c7667513f4b3cfc47e472f3209b1be1>)　固定提交的 ZIP。与默认分支分开。
- [仓库源码 ZIP · jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp/archive/e9e1c89fedf335aad03a2564b93682dc4748494d.zip>)　该仓库的固定快照。

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [MCP](../MCP/MCP.md)
