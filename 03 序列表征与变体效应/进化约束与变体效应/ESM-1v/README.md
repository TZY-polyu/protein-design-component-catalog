# ESM-1v

用只在序列上预训练的蛋白语言模型比较不同氨基酸在同一位置上的相对相容性，为变体效应评估提供序列证据。

## 输入与输出

- **输入**　参考蛋白质序列、待比较的位置和变体序列，以及 ESM-1v 检查点。
- **输出**　残基概率或相对对数似然分数，也可输出序列表征。

## 接入条件

- **LLM 参与**　使用专用蛋白语言模型，不需要通用 LLM。
- **运行条件**　需要 PyTorch、与其兼容的 ESM 代码以及相应的 ESM-1v 检查点。运行多检查点评分时需分别取得相应参数。

分数反映预训练语料中的序列偏好，实验可以检验它对特定任务性质的解释力。该家族提供五个不同的已训练检查点。

## 原始来源与公开实现

Meier et al. (2021), Language models enable zero-shot prediction of the effects of mutations on protein function

[论文或原始出版物](https://proceedings.neurips.cc/paper/2021/hash/f51338d736f95dd42427296047067694-Abstract.html)

- **GitHub 仓库**　[Biohub/esm-archive](https://github.com/Biohub/esm-archive)
- **实现入口**　[查看源代码](https://github.com/Biohub/esm-archive)

原 ESM 项目公开代码归档，可配合 ESM-1v 检查点推理。

## 下载

- [ESM-1v 第一组权重](https://dl.fbaipublicfiles.com/fair-esm/models/esm1v_t33_650M_UR90S_1.pt)　官方目录列出的五个检查点之一。
- [完整 ESM 模型目录](https://github.com/Biohub/esm-archive#pre-trained-models)　可核对模型命名与来源。
- [项目源码 ZIP](https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip)　公开项目的源码快照。

## 可选调用接口

- **ESM MCP**　提供表征提取和序列评分的不同入口。功能取决于选择的 ESM 成员及其可下载的权重。 [接口源码](https://github.com/MacromNex/esm_mcp/blob/0a3b1c8b36c0e0e9954c753347a9678db5fba4af/src/server.py) · [适配器下载](https://github.com/MacromNex/esm_mcp/archive/0a3b1c8b36c0e0e9954c753347a9678db5fba4af.zip)
