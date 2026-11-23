# MaSIF-site

用蛋白表面的几何和理化特征，估计每处表面区域参与蛋白相互作用的倾向。

## 输入与输出

- **输入**　蛋白三维结构以及由结构生成的分子表面网格和局部特征。
- **输出**　映射回分子表面的逐点界面倾向分数，可汇总为值得关注的表面区域。

## 接入条件

- **LLM 参与**　由专用几何深度学习模型执行，无需通用 LLM。
- **运行条件**　配套表面预处理工具、MaSIF-site 推理环境和作者发布的模型参数。

高分表示具有与已知界面相似的表面特征，模型本身不指定结合伙伴，也不输出实测亲和力。

## 原始来源与公开实现

Gainza et al. (online 2019; issue 2020), Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning

[论文或原始出版物](https://doi.org/10.1038/s41592-019-0666-6)

- **GitHub 仓库**　[LPDI-EPFL/masif](https://github.com/LPDI-EPFL/masif)
- **实现入口**　[查看源代码](https://github.com/LPDI-EPFL/masif/blob/2a370518e0d0d0b0d6f153f2f10f6630ae91f149/source/masif_site/masif_site_predict.py)

MaSIF 作者在同一仓库分别提供表面位点识别、表面匹配等方法，所列源文件专属位点识别。

## 下载

- [下载实现源码（ZIP）](https://github.com/LPDI-EPFL/masif/archive/2a370518e0d0d0b0d6f153f2f10f6630ae91f149.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [MaSIF-site 预训练参数](https://github.com/LPDI-EPFL/masif/tree/2a370518e0d0d0b0d6f153f2f10f6630ae91f149/data/masif_site/nn_models/all_feat_3l/model_data)　仓库中专用于界面倾向预测的模型文件。
- [论文配套表面数据](https://zenodo.org/records/2625420)　作者公开的结构及表面网格数据。
