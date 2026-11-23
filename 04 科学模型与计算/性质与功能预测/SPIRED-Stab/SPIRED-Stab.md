# SPIRED-Stab

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

从蛋白序列及其变体估计稳定性变化。该模型与 SPIRED 的单序列结构建模框架共享研究来源。

## 输入、输出与 LLM 参与

- **输入**　蛋白质参考序列及待比较变体的序列或替换信息。
- **输出**　对稳定性变化的预测，例如自由能变化或熔解温度变化的估计。
- **LLM 参与**　使用专用蛋白模型与学习到的序列表征。无需通用对话 LLM。

## 结果解读

比较不同输出前应核对指标定义、单位和差值方向。预测值本身没有替代实际稳定性测量。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供稳定性估计。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Chen et al. (2024), An end-to-end framework for the prediction of protein structure and fitness from single sequence](<https://doi.org/10.1038/s41467-024-51776-x>)
- **GitHub 仓库**　[Gonglab-THU/SPIRED-Fitness](<https://github.com/Gonglab-THU/SPIRED-Fitness>)
- **归属说明**　原论文同时提出 SPIRED-Fitness 与其派生模型 SPIRED-Stab，代码共用仓库。

## 下载与访问

- [作者发布的模型参数](<https://doi.org/10.5281/zenodo.12560925>)　作者仓库指向的模型参数存档，包含同一研究系列的模型。
- [仓库源码 ZIP · Gonglab-THU/SPIRED-Fitness](<https://github.com/Gonglab-THU/SPIRED-Fitness/archive/dae6f00fa6f5be84657560b2c9b1f8b5e22fb9e3.zip>)　该仓库的固定快照。
