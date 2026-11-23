# BioDesignBench

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

在统一任务与评分规则下比较蛋白设计智能体，并通过工具调用记录研究其决策行为。

## 输入、输出与 LLM 参与

- **输入**　任务规范、候选提交、工具调用轨迹，以及部分评分所需的参照信息。
- **输出**　任务级或系统级评分、行为指标、分组比较和可展示的基准结果。
- **LLM 参与**　被测智能体通常调用通用 LLM。评分总计 100 分，其中算法评 72 分，LLM 评委评 28 分。

## 结果解读

主文与补充材料对个别后端描述不同。项目公开评估程序和分析代码，公开仓库并不包含全部逐题材料。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 参考智能体循环](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%84%E5%88%92%E4%B8%8E%E5%8F%8D%E9%A6%88%E6%9C%BA%E5%88%B6/BioDesignBench%20%E5%8F%82%E8%80%83%E6%99%BA%E8%83%BD%E4%BD%93%E5%BE%AA%E7%8E%AF/BioDesignBench%20%E5%8F%82%E8%80%83%E6%99%BA%E8%83%BD%E4%BD%93%E5%BE%AA%E7%8E%AF.md)、[BioDesignBench 非引导工具模式](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E9%9D%9E%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F/BioDesignBench%20%E9%9D%9E%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F.md)、[BioDesignBench 引导工具模式](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F/BioDesignBench%20%E5%BC%95%E5%AF%BC%E5%B7%A5%E5%85%B7%E6%A8%A1%E5%BC%8F.md)、[BioDesignBench 隔离执行环境](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E9%9A%94%E7%A6%BB%E6%89%A7%E8%A1%8C%E7%8E%AF%E5%A2%83/BioDesignBench%20%E9%9A%94%E7%A6%BB%E6%89%A7%E8%A1%8C%E7%8E%AF%E5%A2%83.md)、[BioDesignBench 设计功能映射](../BioDesignBench%20%E8%AE%BE%E8%AE%A1%E5%8A%9F%E8%83%BD%E6%98%A0%E5%B0%84/BioDesignBench%20%E8%AE%BE%E8%AE%A1%E5%8A%9F%E8%83%BD%E6%98%A0%E5%B0%84.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)
- **归属说明**　论文项目仓库。公开评测、基线和分析框架，未公开逐题任务、输出和参考答案。

## 下载与访问

作者未公开完整的逐题说明、作答记录和参考答案。

76 道题的逐题规范、完整输入、参考答案和逐题输出未公开。作者发布汇总结果及演示任务，复现实验的数据访问需向作者申请数据使用协议。

- [基准代码与资料的发布说明](<https://github.com/RomeroLab/BioDesignBench#readme>)　在项目说明中核对公开的代码和受限制的逐题材料。
- [同期评测框架源码（ZIP）](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　含评分、基线与分析代码。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。
- [公开演示与数据访问说明](<https://github.com/RomeroLab/BioDesignBench#why-the-task-data-is-not-in-this-repo>)　README 说明公开内容及逐题数据申请条件。
- [公开排行榜](<https://huggingface.co/spaces/RomeroLab-Duke/BioDesignBench-Leaderboard>)　公开汇总成绩与提交入口。
