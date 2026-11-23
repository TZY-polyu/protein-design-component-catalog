# V-rescale 随机速度重缩放

以随机速度重缩放调节分子动力学体系与热浴间的能量交换，用于维持指定的温度分布。

## 输入与输出

- **输入**　参考子程序接收当前动能、目标平均动能、自由度及热浴耦合时间。
- **输出**　返回一次热浴更新后的动能，供模拟引擎调整速度。

## 接入条件

- **LLM 参与**　无需 LLM，热浴算法通过数值运算执行。
- **运行条件**　参考实现需 Fortran 编译器，并由外层模拟程序提供当前体系状态。

它影响轨迹采样的热力学分布，与描述原子间势能的力场属于不同组件。

## 原始来源与公开实现

Bussi、Donadio 与 Parrinello (2007). Canonical sampling through velocity rescaling.

[论文或原始出版物](https://doi.org/10.1063/1.2408420)

- **GitHub 仓库**　[GiovanniBussi/StochasticVelocityRescaling](https://github.com/GiovanniBussi/StochasticVelocityRescaling)
- **实现入口**　[查看源代码](https://github.com/GiovanniBussi/StochasticVelocityRescaling/blob/master/resamplekin.f90)

Giovanni Bussi 发布了可嵌入模拟代码的参考子程序。

## 下载

- [Fortran 参考子程序](https://raw.githubusercontent.com/GiovanniBussi/StochasticVelocityRescaling/master/resamplekin.f90)　作者发布的动能重采样函数。
- [作者源码归档](https://github.com/GiovanniBussi/StochasticVelocityRescaling/archive/refs/heads/master.zip)　完整示例源码。
