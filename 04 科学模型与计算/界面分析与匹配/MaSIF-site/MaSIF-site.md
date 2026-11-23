# MaSIF-site

[科学模型与计算](../../README.md) / 界面分析与匹配

## 用途

用蛋白表面的几何和理化特征，估计每处表面区域参与蛋白相互作用的倾向。

## 输入、输出与 LLM 参与

- **输入**　蛋白三维结构以及由结构生成的分子表面网格和局部特征。
- **输出**　映射回分子表面的逐点界面倾向分数，可汇总为值得关注的表面区域。
- **LLM 参与**　由专用几何深度学习模型执行，无需通用 LLM。

## 结果解读

高分表示具有与已知界面相似的表面特征，模型本身不指定结合伙伴，也不输出实测亲和力。

## 在六篇研究中的用法

- **AutoBinder Agent**（已整合的科学模块）　通过几何深度学习辨认可能参与蛋白间相互作用的表面区域。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Gainza et al. (online 2019; issue 2020), Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning](<https://doi.org/10.1038/s41592-019-0666-6>)
- **GitHub 仓库**　[LPDI-EPFL/masif](<https://github.com/LPDI-EPFL/masif>)
- **归属说明**　MaSIF-site 原始方法。

## 下载与访问

- [论文配套表面数据](<https://zenodo.org/records/2625420>)　下载清单含 MaSIF-site 与 MaSIF-search 的结构及表面 PLY 文件。
- [仓库源码 ZIP · LPDI-EPFL/masif](<https://github.com/LPDI-EPFL/masif/archive/2a370518e0d0d0b0d6f153f2f10f6630ae91f149.zip>)　该仓库的固定快照。

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
