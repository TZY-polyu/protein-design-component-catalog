# 支持向量回归 SVR（scikit-learn）

在设定误差容忍范围的条件下拟合连续响应，可结合核函数学习蛋白表征与适应度之间的非线性关系。

## 输入与输出

- **输入**　已知标签的训练特征矩阵、连续目标值，以及拟合后需要预测的新样本。
- **输出**　支持向量回归模型与每个样本的连续预测值。

## 接入条件

- **LLM 参与**　SVR 本身无需 LLM。训练特征可来自蛋白语言模型或普通编码。
- **运行条件**　Python 与 scikit-learn。需要带连续标签的训练数据，预测时必须保持特征列定义一致。

预测值的尺度继承自训练标签。核、特征标准化以及验证方式均会影响跨数据集表现。

## 原始来源与公开实现

Drucker et al. (1996), Support Vector Regression Machines

[论文或原始出版物](https://proceedings.neurips.cc/paper/1996/hash/d38901788c533e8286cb6400b40b386d-Abstract.html)

- **GitHub 仓库**　[scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn)
- **实现入口**　[查看源代码](https://github.com/scikit-learn/scikit-learn/blob/main/sklearn/svm/_classes.py)

这里收录 scikit-learn 的 SVR 类，底层使用 libsvm。论文是支持向量回归方法的来源。

## 下载

- [scikit-learn 发行包](https://pypi.org/project/scikit-learn/#files)　包含 sklearn.svm.SVR。
- [SVR 函数参考](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)　核、特征矩阵和模型属性说明。
- [下载本次索引的源码快照（ZIP）](https://github.com/scikit-learn/scikit-learn/archive/21626d67d47889da8d19f3dd2a819a0cf527f27f.zip)
