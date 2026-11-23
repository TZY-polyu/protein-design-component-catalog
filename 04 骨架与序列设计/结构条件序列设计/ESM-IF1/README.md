# ESM-IF1

根据给定蛋白骨架评估序列和该结构的相容程度，也可以给出符合几何上下文的候选序列。

## 输入与输出

- **输入**　蛋白骨架原子坐标。执行序列评分时额外提供候选氨基酸序列。
- **输出**　结构条件下的序列分数、序列候选或骨架编码表示。

## 接入条件

- **LLM 参与**　属于专用结构条件模型，无需通用 LLM。
- **运行条件**　ESM-IF1 检查点、逆折叠模块及其图神经网络依赖。

这是从骨架到序列的逆折叠问题。候选序列的评分不能直接说明其实际折叠、功能或活性。

## 原始来源与公开实现

Hsu et al. (2022), Learning inverse folding from millions of predicted structures

[论文或原始出版物](https://proceedings.mlr.press/v162/hsu22a.html)

- **GitHub 仓库**　[Biohub/esm-archive](https://github.com/Biohub/esm-archive)
- **实现入口**　[查看源代码](https://github.com/Biohub/esm-archive/blob/2b369911bb5b4b0dda914521b9475cad1656b2ac/esm/inverse_folding/gvp_transformer.py)

ESM 团队在共用仓库中发布逆折叠模型的实现及权重入口。

## 下载

- [下载实现源码（ZIP）](https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [ESM-IF1 官方权重](https://dl.fbaipublicfiles.com/fair-esm/models/esm_if1_gvp4_t16_142M_UR50.pt)　原作者在 ESM 归档 README 中列出的检查点。

## 可选调用接口

- **ESM MCP**　提供表征提取和序列评分的不同入口。功能取决于选择的 ESM 成员及其可下载的权重。 [接口源码](https://github.com/MacromNex/esm_mcp/blob/0a3b1c8b36c0e0e9954c753347a9678db5fba4af/src/server.py) · [适配器下载](https://github.com/MacromNex/esm_mcp/archive/0a3b1c8b36c0e0e9954c753347a9678db5fba4af.zip)
