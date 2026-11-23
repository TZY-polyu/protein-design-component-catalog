# 岭回归（scikit-learn Ridge）

在线性回归中惩罚过大的系数，以改善高维或强相关蛋白特征下的估计稳定性。

## 输入与输出

- **输入**　样本特征矩阵、连续型标签以及正则化强度。用于推断时只需同一特征定义的新样本及拟合模型。
- **输出**　拟合系数、截距与连续预测值，例如某批序列的适应度预测。

## 接入条件

- **LLM 参与**　无需 LLM。上游可以提供序列编码或蛋白模型表征。
- **运行条件**　Python 与 scikit-learn。拟合需要带连续标签的数据，新样本必须使用和训练时一致的特征定义。

正则化会影响系数大小，特征尺度与验证集划分会影响不同模型间的性能比较。

## 原始来源与公开实现

Hoerl & Kennard (1970), Ridge Regression: Biased Estimation for Nonorthogonal Problems

[论文或原始出版物](https://doi.org/10.1080/00401706.1970.10488634)

- **GitHub 仓库**　[scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn)
- **实现入口**　[查看源代码](https://github.com/scikit-learn/scikit-learn/blob/main/sklearn/linear_model/_ridge.py)

此处为 scikit-learn 对经典岭回归的实现，方法源自 Hoerl 与 Kennard 的论文。

## 下载

- [下载源码快照（ZIP）](https://github.com/scikit-learn/scikit-learn/archive/21626d67d47889da8d19f3dd2a819a0cf527f27f.zip)　该链接固定到仓库中的一个提交。
- [参考实现发布包](https://pypi.org/project/scikit-learn/#files)　scikit-learn 提供 Ridge，可下载软件包。它是后续实现。
- [Ridge 接口文档](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html)　说明输入、输出和正则化目标。
