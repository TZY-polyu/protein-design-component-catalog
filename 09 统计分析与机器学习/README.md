# 统计分析与机器学习

计算相关性、进行假设检验，并在有标签的数据上训练回归模型。

[返回功能目录](../README.md)

## 统计检验与分布度量

| 组件 | 主要用途 |
| --- | --- |
| [Bonferroni 多重检验校正](%E7%BB%9F%E8%AE%A1%E6%A3%80%E9%AA%8C%E4%B8%8E%E5%88%86%E5%B8%83%E5%BA%A6%E9%87%8F/Bonferroni%20%E5%A4%9A%E9%87%8D%E6%A3%80%E9%AA%8C%E6%A0%A1%E6%AD%A3/README.md) | 在一组假设检验中控制把至少一个真零假设误判为显著的总体风险。 |
| [Pingouin](%E7%BB%9F%E8%AE%A1%E6%A3%80%E9%AA%8C%E4%B8%8E%E5%88%86%E5%B8%83%E5%BA%A6%E9%87%8F/Pingouin/README.md) | 为实验比较提供统计检验、效应量与相关分析，便于用统一的表格格式记录结果。 |
| [Spearman 秩相关（SciPy）](%E7%BB%9F%E8%AE%A1%E6%A3%80%E9%AA%8C%E4%B8%8E%E5%88%86%E5%B8%83%E5%BA%A6%E9%87%8F/Spearman%20%E7%A7%A9%E7%9B%B8%E5%85%B3%EF%BC%88SciPy%EF%BC%89/README.md) | 把成对观察转换成秩，再衡量两组排名的单调关联，可比较预测分数与实测标签的排序一致性。 |
| [Wilcoxon 配对符号秩检验（SciPy）](%E7%BB%9F%E8%AE%A1%E6%A3%80%E9%AA%8C%E4%B8%8E%E5%88%86%E5%B8%83%E5%BA%A6%E9%87%8F/Wilcoxon%20%E9%85%8D%E5%AF%B9%E7%AC%A6%E5%8F%B7%E7%A7%A9%E6%A3%80%E9%AA%8C%EF%BC%88SciPy%EF%BC%89/README.md) | 用配对差值的方向与绝对差的秩检验两条件的差异，适合对同一任务在两种运行条件下的成绩作配对分析。 |
| [香农熵（SciPy entropy）](%E7%BB%9F%E8%AE%A1%E6%A3%80%E9%AA%8C%E4%B8%8E%E5%88%86%E5%B8%83%E5%BA%A6%E9%87%8F/%E9%A6%99%E5%86%9C%E7%86%B5%EF%BC%88SciPy%20entropy%EF%BC%89/README.md) | 根据类别出现频率计算分布的不确定性。例如可把每种氨基酸的计数转换成一个组成多样性指标。 |

## 回归与监督学习

| 组件 | 主要用途 |
| --- | --- |
| [k 近邻回归（KNN）](%E5%9B%9E%E5%BD%92%E4%B8%8E%E7%9B%91%E7%9D%A3%E5%AD%A6%E4%B9%A0/k%20%E8%BF%91%E9%82%BB%E5%9B%9E%E5%BD%92%EF%BC%88KNN%EF%BC%89/README.md) | 在特征空间中寻找与查询样本接近的训练样本，根据这些邻居的已知数值标签作出回归预测。 |
| [scikit-learn](%E5%9B%9E%E5%BD%92%E4%B8%8E%E7%9B%91%E7%9D%A3%E5%AD%A6%E4%B9%A0/scikit-learn/README.md) | 提供统一的特征预处理、监督学习、模型选择和性能评估接口，便于比较科学数据上的多个回归器。 |
| [XGBoost](%E5%9B%9E%E5%BD%92%E4%B8%8E%E7%9B%91%E7%9D%A3%E5%AD%A6%E4%B9%A0/XGBoost/README.md) | 通过逐轮叠加决策树拟合连续标签，可在蛋白序列表征上训练适应度回归模型。 |
| [岭回归（scikit-learn Ridge）](%E5%9B%9E%E5%BD%92%E4%B8%8E%E7%9B%91%E7%9D%A3%E5%AD%A6%E4%B9%A0/%E5%B2%AD%E5%9B%9E%E5%BD%92%EF%BC%88scikit-learn%20Ridge%EF%BC%89/README.md) | 在线性回归中惩罚过大的系数，以改善高维或强相关蛋白特征下的估计稳定性。 |
| [支持向量回归 SVR（scikit-learn）](%E5%9B%9E%E5%BD%92%E4%B8%8E%E7%9B%91%E7%9D%A3%E5%AD%A6%E4%B9%A0/%E6%94%AF%E6%8C%81%E5%90%91%E9%87%8F%E5%9B%9E%E5%BD%92%20SVR%EF%BC%88scikit-learn%EF%BC%89/README.md) | 在设定误差容忍范围的条件下拟合连续响应，可结合核函数学习蛋白表征与适应度之间的非线性关系。 |

## 数值与张量计算

| 组件 | 主要用途 |
| --- | --- |
| [NumPy](%E6%95%B0%E5%80%BC%E4%B8%8E%E5%BC%A0%E9%87%8F%E8%AE%A1%E7%AE%97/NumPy/README.md) | 用多维数组统一表示数值数据，并提供向量化运算、矩阵计算和基础统计操作。 |
| [PyTorch](%E6%95%B0%E5%80%BC%E4%B8%8E%E5%BC%A0%E9%87%8F%E8%AE%A1%E7%AE%97/PyTorch/README.md) | 为科学模型提供张量运算、自动求导和模型推理运行环境，支持在 CPU 或加速设备上运行同一类模型。 |
| [SciPy](%E6%95%B0%E5%80%BC%E4%B8%8E%E5%BC%A0%E9%87%8F%E8%AE%A1%E7%AE%97/SciPy/README.md) | 提供统计检验、概率分布、数值优化和线性代数等科学计算函数，支撑结果汇总与统计比较。 |
