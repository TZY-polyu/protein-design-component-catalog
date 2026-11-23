# 功能位点与蛋白性质

寻找可能的口袋或相互作用界面，估计稳定性、溶解性和力学性质。

[返回功能目录](../README.md)

## 结合位点与界面识别

| 组件 | 主要用途 |
| --- | --- |
| [MaSIF-site](%E7%BB%93%E5%90%88%E4%BD%8D%E7%82%B9%E4%B8%8E%E7%95%8C%E9%9D%A2%E8%AF%86%E5%88%AB/MaSIF-site/README.md) | 用蛋白表面的几何和理化特征，估计每处表面区域参与蛋白相互作用的倾向。 |
| [P2Rank](%E7%BB%93%E5%90%88%E4%BD%8D%E7%82%B9%E4%B8%8E%E7%95%8C%E9%9D%A2%E8%AF%86%E5%88%AB/P2Rank/README.md) | 在蛋白质三维结构表面寻找可能与小分子结合的口袋，并为候选位置排序。 |

## 蛋白稳定性与溶解性

| 组件 | 主要用途 |
| --- | --- |
| [Protein-Sol](%E8%9B%8B%E7%99%BD%E7%A8%B3%E5%AE%9A%E6%80%A7%E4%B8%8E%E6%BA%B6%E8%A7%A3%E6%80%A7/Protein-Sol/README.md) | 根据序列的理化及组成特征估计蛋白质相对溶解倾向，供不同序列作计算比较。 |
| [SPIRED-Stab](%E8%9B%8B%E7%99%BD%E7%A8%B3%E5%AE%9A%E6%80%A7%E4%B8%8E%E6%BA%B6%E8%A7%A3%E6%80%A7/SPIRED-Stab/README.md) | 估计氨基酸替换引起的稳定性变化，适合对同一参考蛋白的已知变体进行计算比较。 |

## 力学性质与集体运动

| 组件 | 主要用途 |
| --- | --- |
| [ANM（各向异性网络模型）](%E5%8A%9B%E5%AD%A6%E6%80%A7%E8%B4%A8%E4%B8%8E%E9%9B%86%E4%BD%93%E8%BF%90%E5%8A%A8/ANM%EF%BC%88%E5%90%84%E5%90%91%E5%BC%82%E6%80%A7%E7%BD%91%E7%BB%9C%E6%A8%A1%E5%9E%8B%EF%BC%89/README.md) | 用空间节点与弹性联系近似蛋白结构，估计结构整体偏好沿哪些方向发生协同运动。 |
| [ProDy](%E5%8A%9B%E5%AD%A6%E6%80%A7%E8%B4%A8%E4%B8%8E%E9%9B%86%E4%BD%93%E8%BF%90%E5%8A%A8/ProDy/README.md) | 支持结构读取与动力学分析，可利用蛋白弹性网络的正常模态描述集体运动。 |
| [ProteinForceGPT（ForceGPT）](%E5%8A%9B%E5%AD%A6%E6%80%A7%E8%B4%A8%E4%B8%8E%E9%9B%86%E4%BD%93%E8%BF%90%E5%8A%A8/ProteinForceGPT%EF%BC%88ForceGPT%EF%BC%89/README.md) | 从氨基酸序列估计蛋白在拉伸条件下的力学响应，供比较不同序列的计算力学特征。 |
