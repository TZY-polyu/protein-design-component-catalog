# scikit-learn

提供统一的特征预处理、监督学习、模型选择和性能评估接口，便于比较科学数据上的多个回归器。

## 输入与输出

- **输入**　训练特征矩阵、标签以及估计器设置。预测时输入与训练定义一致的特征。
- **输出**　已拟合的估计器、预测数组、交叉验证结果或评价指标。

## 接入条件

- **LLM 参与**　软件库及传统回归器无需 LLM，特征可由外部模型预先生成。
- **运行条件**　Python、NumPy 和 SciPy。监督学习还需要具有一致特征定义的已标注样本。

回归器返回的分数单位取决于训练标签。交叉验证要保持相关样本间的数据划分一致。

**最小运行核验**　scikit-learn 1.9.0 使用 4 个已标注点训练 2 近邻回归器，在查询点 3 处返回 4。

## 原始来源与公开实现

Pedregosa et al. (2011), Scikit-learn: Machine Learning in Python

[论文或原始出版物](https://www.jmlr.org/papers/v12/pedregosa11a.html)

- **GitHub 仓库**　[scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn)
- **实现入口**　[查看源代码](https://github.com/scikit-learn/scikit-learn)

scikit-learn 官方软件库及估计器实现。

## 下载

- [下载源码快照（ZIP）](https://github.com/scikit-learn/scikit-learn/archive/21626d67d47889da8d19f3dd2a819a0cf527f27f.zip)　该链接固定到仓库中的一个提交。
- [scikit-learn 发行文件](https://pypi.org/project/scikit-learn/#files)　选择适配本地 Python 和平台的二进制包或源码包。
