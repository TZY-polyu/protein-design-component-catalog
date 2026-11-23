# 分子模拟与能量计算

执行分子模拟、选择力场和积分方法，或对给定结构进行打分和弛豫。

[返回功能目录](../README.md)

## 分子动力学引擎

| 组件 | 主要用途 |
| --- | --- |
| [AmberTools](%E5%88%86%E5%AD%90%E5%8A%A8%E5%8A%9B%E5%AD%A6%E5%BC%95%E6%93%8E/AmberTools/README.md) | AMBER 家族中公开源码的分子模拟工具集，可准备分子体系、计算能量与动力学，并分析结构轨迹。 |
| [GROMACS](%E5%88%86%E5%AD%90%E5%8A%A8%E5%8A%9B%E5%AD%A6%E5%BC%95%E6%93%8E/GROMACS/README.md) | 利用分子力场推进体系的运动方程，执行能量计算或动力学模拟，并记录轨迹。 |
| [OpenMM](%E5%88%86%E5%AD%90%E5%8A%A8%E5%8A%9B%E5%AD%A6%E5%BC%95%E6%93%8E/OpenMM/README.md) | 为分子力学系统计算能量和力，支持结构能量最小化及分子动力学模拟。 |

## 力场与水模型

| 组件 | 主要用途 |
| --- | --- |
| [CHARMM36m 蛋白质力场](%E5%8A%9B%E5%9C%BA%E4%B8%8E%E6%B0%B4%E6%A8%A1%E5%9E%8B/CHARMM36m%20%E8%9B%8B%E7%99%BD%E8%B4%A8%E5%8A%9B%E5%9C%BA/README.md) | 为蛋白质分子动力学模拟提供经验力场参数，描述键合、静电和非键相互作用。 |
| [TIP3P 水模型（GROMACS 拓扑）](%E5%8A%9B%E5%9C%BA%E4%B8%8E%E6%B0%B4%E6%A8%A1%E5%9E%8B/TIP3P%20%E6%B0%B4%E6%A8%A1%E5%9E%8B%EF%BC%88GROMACS%20%E6%8B%93%E6%89%91%EF%BC%89/README.md) | 在显式溶剂模拟中，用三个相互作用位点表示一个水分子。GROMACS 可读取这份拓扑并在分子动力学计算中应用。 |

## 约束、静电与系综算法

| 组件 | 主要用途 |
| --- | --- |
| [LINCS](%E7%BA%A6%E6%9D%9F%E3%80%81%E9%9D%99%E7%94%B5%E4%B8%8E%E7%B3%BB%E7%BB%BC%E7%AE%97%E6%B3%95/LINCS/README.md) | 在分子动力学积分中校正受约束的键长，让分子几何满足拓扑文件给定的约束。 |
| [Parrinello–Rahman](%E7%BA%A6%E6%9D%9F%E3%80%81%E9%9D%99%E7%94%B5%E4%B8%8E%E7%B3%BB%E7%BB%BC%E7%AE%97%E6%B3%95/Parrinello%E2%80%93Rahman/README.md) | 在分子动力学中调节模拟盒的尺寸或形状，使体系压力随动力学演化与指定条件相联系。 |
| [PME（GROMACS 实现）](%E7%BA%A6%E6%9D%9F%E3%80%81%E9%9D%99%E7%94%B5%E4%B8%8E%E7%B3%BB%E7%BB%BC%E7%AE%97%E6%B3%95/PME%EF%BC%88GROMACS%20%E5%AE%9E%E7%8E%B0%EF%BC%89/README.md) | 在周期性边界条件下利用网格方法计算长程静电相互作用，降低直接求和的计算成本。 |
| [V-rescale 随机速度重缩放](%E7%BA%A6%E6%9D%9F%E3%80%81%E9%9D%99%E7%94%B5%E4%B8%8E%E7%B3%BB%E7%BB%BC%E7%AE%97%E6%B3%95/V-rescale%20%E9%9A%8F%E6%9C%BA%E9%80%9F%E5%BA%A6%E9%87%8D%E7%BC%A9%E6%94%BE/README.md) | 以随机速度重缩放调节分子动力学体系与热浴间的能量交换，用于维持指定的温度分布。 |

## 结构建模、能量评分与弛豫

| 组件 | 主要用途 |
| --- | --- |
| [PyRosetta](%E7%BB%93%E6%9E%84%E5%BB%BA%E6%A8%A1%E3%80%81%E8%83%BD%E9%87%8F%E8%AF%84%E5%88%86%E4%B8%8E%E5%BC%9B%E8%B1%AB/PyRosetta/README.md) | 在 Python 中读取、操作和打分 Rosetta 的结构对象，可将结构分析嵌入现有科学计算程序。 |
| [Rosetta](%E7%BB%93%E6%9E%84%E5%BB%BA%E6%A8%A1%E3%80%81%E8%83%BD%E9%87%8F%E8%AF%84%E5%88%86%E4%B8%8E%E5%BC%9B%E8%B1%AB/Rosetta/README.md) | 以能量函数和构象采样程序对蛋白质结构进行建模、松弛或打分。 |
| [Rosetta ref2015](%E7%BB%93%E6%9E%84%E5%BB%BA%E6%A8%A1%E3%80%81%E8%83%BD%E9%87%8F%E8%AF%84%E5%88%86%E4%B8%8E%E5%BC%9B%E8%B1%AB/Rosetta%20ref2015/README.md) | 用 Rosetta 的全原子能量函数对构象打分，查看不同能量项对总分的贡献，并在相同设置下比较结构。 |
