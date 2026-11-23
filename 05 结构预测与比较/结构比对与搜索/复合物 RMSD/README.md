# 复合物 RMSD

用原子坐标的均方根偏差比较两个复合物模型，量化对应原子在三维空间中的平均偏移。

## 输入与输出

- **输入**　两份结构坐标、链与原子的对应关系，以及采用的对齐规则。
- **输出**　以 Å 等长度单位表示的一个 RMSD 数值，通常越小表示所选原子越接近。

## 接入条件

- **LLM 参与**　数值计算无需通用 LLM。
- **运行条件**　使用所列参考实现需 Python、MDAnalysis，另需代表相同原子且次序相匹配的两组坐标。

结果取决于链映射、参与计算的原子范围和是否先做刚性叠合。不同范围得到的 RMSD 不能直接比较。

## 原始来源与公开实现

全复合物 RMSD 是坐标偏差的通用度量，未见单一首创论文。Kabsch（1976），A solution for the best rotation to relate two sets of vectors，给出了最优刚性旋转的一种经典方法。

[论文或原始出版物](https://doi.org/10.1107/S0567739476001873)

- **GitHub 仓库**　[MDAnalysis/mdanalysis](https://github.com/MDAnalysis/mdanalysis)
- **实现入口**　[查看源代码](https://github.com/MDAnalysis/mdanalysis/blob/develop/package/MDAnalysis/analysis/rms.py)

MDAnalysis 的 rmsd 和 RMSD 类提供可运行的公开参考实现，链与原子需预先建立对应关系。

## 下载

- [MDAnalysis 安装包](https://pypi.org/project/MDAnalysis/#files)　包含坐标叠合及 RMSD 计算。
- [下载项目源码（ZIP）](https://github.com/MDAnalysis/mdanalysis/archive/HEAD.zip)
