# k 近邻回归（KNN）

在特征空间中寻找与查询样本接近的训练样本，根据这些邻居的已知数值标签作出回归预测。

## 输入与输出

- **输入**　带有数值标签的训练样本特征、待预测样本的同类特征，以及近邻距离定义。
- **输出**　每个样本的预测数值。部分实现也可返回近邻的索引和距离。

## 接入条件

- **LLM 参与**　近邻搜索与回归无需 LLM。上游特征可以由蛋白语言模型产生。
- **运行条件**　scikit-learn、数值特征和带数值标签的训练样本。

指标尤其依赖特征缩放和样本间距离是否有意义。换用另一套嵌入表示后，最近邻往往也会改变。

**最小运行核验**　scikit-learn 1.9.0 使用 4 个已标注点训练 2 近邻回归器，在查询点 3 处返回 4。

## 原始来源与公开实现

Cover (1968), Estimation by the Nearest Neighbor Rule（近邻回归早期方法论文）

[官方来源说明](https://isl.stanford.edu/~cover/papers/transIT/0050cove.pdf)

- **GitHub 仓库**　[scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn)
- **实现入口**　[查看源代码](https://github.com/scikit-learn/scikit-learn/blob/21626d67d47889da8d19f3dd2a819a0cf527f27f/sklearn/neighbors/_regression.py)

给出 scikit-learn 的公开实现。经典近邻回归没有唯一的软件原仓库。

## 下载

- [下载实现源码（ZIP）](https://github.com/scikit-learn/scikit-learn/archive/21626d67d47889da8d19f3dd2a819a0cf527f27f.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [scikit-learn 回归器文档](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)　可查看模型输入、返回值与距离度量。
- [scikit-learn 发布包](https://pypi.org/project/scikit-learn/#files)　支持的平台可下载二进制发行包。
