# PLMC

从蛋白家族的多序列比对估计位点偏好以及位点间统计耦合，用于比较序列在家族模型下的相容性。

## 输入与输出

- **输入**　同一家族的对齐序列、可选的序列权重及模型拟合所需信息。
- **输出**　位点场、残基对的耦合系数和可供后续评估的模型参数。可输出位点对耦合汇总。

## 接入条件

- **LLM 参与**　以伪似然等统计方法拟合模型，无需通用 LLM。
- **运行条件**　下载仓库中的适配二进制文件，或使用 C 编译器与 make 构建。拟合需要具有足够覆盖度的多序列比对。

序列比对覆盖范围、样本数量和序列之间的亲缘关系都会影响拟合。统计耦合是序列数据中的关联。

## 原始来源与公开实现

Hopf et al. (2017), Mutation effects predicted from sequence co-variation

[论文或原始出版物](https://doi.org/10.1038/nbt.3769)

- **GitHub 仓库**　[debbiemarkslab/plmc](https://github.com/debbiemarkslab/plmc)
- **实现入口**　[查看源代码](https://github.com/debbiemarkslab/plmc/tree/18c9e55e3bd2f14f4968be19a807b401996c929a/src)

作者指定的软件引用。PLMC 拟合序列耦合参数。EVmutation 是使用这些参数进行预测的配套方法。

## 下载

- [固定版本源码 ZIP](https://github.com/debbiemarkslab/plmc/archive/18c9e55e3bd2f14f4968be19a807b401996c929a.zip)　包含上述实现及其同仓库配套文件。

## 可选调用接口

- **PLMC MCP**　在本地调用公开 PLMC 程序拟合序列共演化模型，并包含多序列比对文件格式转换。 [接口源码](https://github.com/MacromNex/plmc_mcp/blob/fa139852c1adbba646741cdc794022b96e0fa32f/src/tools/readme.py) · [适配器下载](https://github.com/MacromNex/plmc_mcp/archive/fa139852c1adbba646741cdc794022b96e0fa32f.zip)
