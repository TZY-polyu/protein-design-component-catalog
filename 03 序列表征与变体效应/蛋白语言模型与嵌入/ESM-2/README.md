# ESM-2

将蛋白序列编码为上下文相关表示，用于下游回归、变体打分等任务。ESMFold 使用这一类表示支持结构预测。

## 输入与输出

- **输入**　氨基酸序列与选定规模的 ESM-2 检查点。
- **输出**　逐位置表示、氨基酸分布或汇聚后的蛋白级向量，随后可交给独立预测头。

## 接入条件

- **LLM 参与**　使用蛋白语言模型，不要求通用 LLM。
- **运行条件**　与所选模型规模匹配的 ESM-2 权重和 PyTorch。

ESM-2 的直接产物是序列表示和分布。要得到三维坐标还需结构预测模块。不同规模的权重对应不同模型。

## 原始来源与公开实现

Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model

[论文或原始出版物](https://doi.org/10.1126/science.ade2574)

- **GitHub 仓库**　[Biohub/esm-archive](https://github.com/Biohub/esm-archive)
- **实现入口**　[查看源代码](https://github.com/Biohub/esm-archive/blob/2b369911bb5b4b0dda914521b9475cad1656b2ac/esm/model/esm2.py)

ESM 团队的公开代码归档。仓库也提供 ESMFold 和 ESM-IF1 等独立模型。

## 下载

- [下载实现源码（ZIP）](https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [ESM-2 650M 模型权重](https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t33_650M_UR50D.pt)　官方目录中的 650M 检查点。
- [ESM-2 3B 模型权重](https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t36_3B_UR50D.pt)　官方目录中的 3B 检查点。

## 可选调用接口

- **ESM MCP**　提供表征提取和序列评分的不同入口。功能取决于选择的 ESM 成员及其可下载的权重。 [接口源码](https://github.com/MacromNex/esm_mcp/blob/0a3b1c8b36c0e0e9954c753347a9678db5fba4af/src/server.py) · [适配器下载](https://github.com/MacromNex/esm_mcp/archive/0a3b1c8b36c0e0e9954c753347a9678db5fba4af.zip)
- **ESM-2 表征提取接口（esmfold_mcp）**　该仓库发布的服务使用 ESM-2 计算序列嵌入。接口名含 esmfold，其实际暴露的结果为向量，不提供三维结构坐标。 [接口源码](https://github.com/MacromNex/esmfold_mcp/blob/5f26fdae0d9fc646b52acc3774a2485f10687264/scripts/protein_embeddings.py) · [适配器下载](https://github.com/MacromNex/esmfold_mcp/archive/5f26fdae0d9fc646b52acc3774a2485f10687264.zip)
