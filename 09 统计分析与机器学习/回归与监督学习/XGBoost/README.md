# XGBoost

通过逐轮叠加决策树拟合连续标签，可在蛋白序列表征上训练适应度回归模型。

## 输入与输出

- **输入**　按样本排列的特征矩阵、训练标签和学习目标。预测时需要具有相同列定义的新样本。
- **输出**　训练得到的树集成模型与每个样本的连续预测值，也可导出函数支持的特征重要性摘要。

## 接入条件

- **LLM 参与**　树模型的训练和推断无需 LLM，输入特征可以来自专用蛋白语言模型。
- **运行条件**　支持的平台可用预编译发行包。回归任务需有监督训练标签，预测时应沿用训练时的特征编码。

分数的含义由训练标签决定。特征重要性刻画模型使用特征的方式，不能直接解释为生物学因果关系。

## 原始来源与公开实现

Chen & Guestrin (2016), XGBoost: A Scalable Tree Boosting System

[论文或原始出版物](https://doi.org/10.1145/2939672.2939785)

- **GitHub 仓库**　[dmlc/xgboost](https://github.com/dmlc/xgboost)
- **实现入口**　[查看源代码](https://github.com/dmlc/xgboost)

DMLC 的 XGBoost 项目仓库，提供 C++ 核心及 Python 等接口。

## 下载

- [XGBoost Python 发行文件](https://pypi.org/project/xgboost/#files)　按机器环境选取官方 PyPI 构建。
- [下载本次索引的源码快照（ZIP）](https://github.com/dmlc/xgboost/archive/e0e4564aea606e688b6db58d6a9235ac19748dcb.zip)
