# KNN

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

在特征空间中选择与待评样本接近的训练样本，汇总其已知标签给出预测。ProteinMCP 的适应度示例使用近邻回归。

## 输入、输出与 LLM 参与

- **输入**　带有数值标签的训练样本特征、待预测样本的同类特征，以及近邻距离定义。
- **输出**　每个样本的预测数值。部分实现也可返回近邻的索引和距离。
- **LLM 参与**　近邻搜索与回归无需 LLM。上游特征可以由蛋白语言模型产生。

## 结果解读

指标尤其依赖特征缩放和样本间距离是否有意义。换用另一套嵌入表示后，最近邻往往也会改变。

## 在六篇研究中的用法

- **ProteinMCP**（案例1监督回归头）　比较局部近邻法与其他回归头。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Cover (1968), Estimation by the Nearest Neighbor Rule（近邻回归早期方法论文）](<https://isl.stanford.edu/~cover/papers/transIT/0050cove.pdf>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　经典方法，所用实现未指明，未确认一般 k 近邻回归唯一的首发论文。

## 下载与访问

- [scikit-learn 参考实现说明](<https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html>)　可用的近邻回归实现，ProteinMCP 中采用的具体类未披露。
- [scikit-learn 官方安装与下载](<https://scikit-learn.org/stable/install.html>)　提供包含该参考实现的软件包。

## 关联组件

[ProtTrans](../../%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ProtTrans/ProtTrans.md)
