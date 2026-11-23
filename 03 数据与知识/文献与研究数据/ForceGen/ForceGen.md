# ForceGen

[数据与知识](../../README.md) / 文献与研究数据

## 用途

建立蛋白材料机械展开响应和氨基酸序列之间的联系。ProtAgents 引用了该工作产生的力学模拟训练数据。

## 输入、输出与 LLM 参与

- **输入**　原始生成任务接收目标力学响应或力–位移曲线。作为数据来源时使用对应的序列与模拟响应记录。
- **输出**　原始模型产生候选蛋白序列。其数据在 ProtAgents 中用作监督样本。
- **LLM 参与**　原始方法使用专用蛋白语言表示和扩散模型。读取其训练数据无需 LLM。

## 结果解读

来源关系是区分这两项研究的关键。ForceGen 提供的力学数据用于训练另一个模型 ProteinForceGPT。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinForceGPT 训练数据组合](../ProteinForceGPT%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E7%BB%84%E5%90%88/ProteinForceGPT%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E7%BB%84%E5%90%88.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Ni, Kaplan & Buehler (2024), ForceGen: End-to-end de novo protein generation based on nonlinear mechanical unfolding responses using a language diffusion model](<https://doi.org/10.1126/sciadv.adl4000>)
- **GitHub 仓库**　[lamm-mit/ProteinMechanicsDiffusionDesign](<https://github.com/lamm-mit/ProteinMechanicsDiffusionDesign>)
- **归属说明**　ProtAgents 引用该工作的分子力学微调数据。

## 下载与访问

- [ForceGen 作者发布的模型页](<https://huggingface.co/lamm-mit/ProteinMechanicsDiffusionDesign>)　作者 GitHub 指定的训练好模型发布入口。
- [仓库源码 ZIP · lamm-mit/ProteinMechanicsDiffusionDesign](<https://github.com/lamm-mit/ProteinMechanicsDiffusionDesign/archive/e826480fc23cb5e7ba13319e933bdcda954042af.zip>)　该仓库的固定快照。
