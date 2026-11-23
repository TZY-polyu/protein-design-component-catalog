# ESM-IF1

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

根据给定蛋白骨架评估序列和该结构的相容程度，也可以给出符合几何上下文的候选序列。

## 输入、输出与 LLM 参与

- **输入**　蛋白骨架原子坐标。执行序列评分时额外提供候选氨基酸序列。
- **输出**　结构条件下的序列分数、序列候选或骨架编码表示。
- **LLM 参与**　属于专用结构条件模型，无需通用 LLM。

## 结果解读

这是从骨架到序列的逆折叠问题。候选序列的评分不能直接说明其实际折叠、功能或活性。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。未见单列案例评测，接口按功能归纳）　提供逆折叠能力。图1将其与 ESM 并列。
- **BioDesignBench**（正文列举／注册状态未证实）　正文举例的几何条件逆折叠模型。补充表S1与A.2未将 ESM-IF 列为已注册后端。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Hsu et al. (2022), Learning inverse folding from millions of predicted structures](<https://proceedings.mlr.press/v162/hsu22a.html>)
- **GitHub 仓库**　[facebookresearch/esm](<https://github.com/facebookresearch/esm>)
- **归属说明**　Meta 官方 ESM 共用仓库，单列逆折叠模型原论文。

## 下载与访问

- [ESM-IF1 官方权重](<https://dl.fbaipublicfiles.com/fair-esm/models/esm_if1_gvp4_t16_142M_UR50.pt>)　原作者在 ESM 归档 README 中列出的检查点。
- [仓库源码 ZIP · facebookresearch/esm](<https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip>)　该仓库的固定快照。

## 关联组件

[ESM](../../%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ESM/ESM.md)
