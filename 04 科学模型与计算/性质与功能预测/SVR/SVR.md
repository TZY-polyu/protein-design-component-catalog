# SVR

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

在设定误差容忍范围的条件下拟合连续响应，可结合核函数学习蛋白表征与适应度之间的非线性关系。

## 输入、输出与 LLM 参与

- **输入**　已知标签的训练特征矩阵、连续目标值，以及拟合后需要预测的新样本。
- **输出**　支持向量回归模型与每个样本的连续预测值。
- **LLM 参与**　SVR 本身无需 LLM。训练特征可来自蛋白语言模型或普通编码。

## 结果解读

预测值的尺度继承自训练标签。核、特征标准化以及验证方式均会影响跨数据集表现。

## 在六篇研究中的用法

- **ProteinMCP**（案例1监督回归头）　用支持向量回归拟合表征与适应度的关系。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Drucker et al. (1996), Support Vector Regression Machines](<https://proceedings.neurips.cc/paper/1996/hash/d38901788c533e8286cb6400b40b386d-Abstract.html>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　支持向量回归的早期专文。研究未指明所用回归头的软件仓库。

## 下载与访问

- [参考实现与接口](<https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html>)　公开的核 SVR 软件实现，论文实际选择的实现依其披露。
- [可下载实现](<https://pypi.org/project/scikit-learn/#files>)　scikit-learn 发行文件。

## 关联组件

[ProtTrans](../../%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ProtTrans/ProtTrans.md)
