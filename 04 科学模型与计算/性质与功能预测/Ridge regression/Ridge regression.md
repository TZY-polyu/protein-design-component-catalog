# Ridge regression

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

在线性回归中惩罚过大的系数，以改善高维或强相关蛋白特征下的估计稳定性。

## 输入、输出与 LLM 参与

- **输入**　样本特征矩阵、连续型标签以及正则化强度。用于推断时只需同一特征定义的新样本及拟合模型。
- **输出**　拟合系数、截距与连续预测值，例如某批序列的适应度预测。
- **LLM 参与**　无需 LLM。上游可以提供序列编码或蛋白模型表征。

## 结果解读

正则化会影响系数大小，特征尺度与验证集划分会影响不同模型间的性能比较。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Hoerl & Kennard (1970), Ridge Regression: Biased Estimation for Nonorthogonal Problems](<https://doi.org/10.1080/00401706.1970.10488634>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　经典统计方法，原始工作无专属 GitHub。

## 下载与访问

- [参考实现发布包](<https://pypi.org/project/scikit-learn/#files>)　scikit-learn 提供 Ridge，可下载软件包。它是后续实现。
- [Ridge 接口文档](<https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html>)　说明输入、输出和正则化目标。

## 关联组件

[EV+OneHot MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/EV%2BOneHot%20MCP/EV%2BOneHot%20MCP.md)
