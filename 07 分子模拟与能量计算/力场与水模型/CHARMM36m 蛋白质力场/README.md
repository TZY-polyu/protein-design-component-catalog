# CHARMM36m 蛋白质力场

为蛋白质分子动力学模拟提供经验力场参数，描述键合、静电和非键相互作用。

## 输入与输出

- **输入**　指定了原子类型、连接关系和坐标的体系，以及与模拟引擎相容的参数文件。
- **输出**　力场定义的势能与由模拟引擎计算的原子受力，进一步可形成模拟轨迹。

## 接入条件

- **LLM 参与**　经验函数和参数表不需要通用或蛋白语言模型。
- **运行条件**　需与所选参数兼容的模拟引擎及溶剂和辅助组分参数。

CHARMM36m 是参数化的力场，推进时间并产生轨迹的是模拟引擎。使用时需区分力场版本和引擎版本。

## 原始来源与公开实现

Huang 等 (2016 在线，2017 刊期). CHARMM36m: an improved force field for folded and intrinsically disordered proteins.

[论文或原始出版物](https://doi.org/10.1038/nmeth.4067)

- **GitHub 仓库**　[openmm/openmm](https://github.com/openmm/openmm)
- **实现入口**　[查看源代码](https://github.com/openmm/openmm/blob/master/wrappers/python/openmm/app/data/charmm36_2024.xml)

OpenMM 的 2024 CHARMM 端口含 CHARMM36m 蛋白质参数，上游由 MacKerell 实验室发布。

## 下载

- [MacKerell 实验室力场发布页](https://mackerell.umaryland.edu/charmm_ff.shtml)　原始开发团队提供参数与不同引擎适配资源。
- [OpenMM 安装包](https://pypi.org/project/OpenMM/#files)　含加载参数和计算能量的代码。请选择提供 2024 参数的版本。
- [端口开发者的版本说明](https://github.com/openmm/openmmforcefields/issues/298)　开发者确认 2024 年 7 月上游参数已采用 CHARMM36m。
- [项目源码 ZIP](https://github.com/openmm/openmm/archive/b5282630278e6c78e92691ed411543f73aabba75.zip)　公开项目的源码快照。
- [力场加载与建模代码](https://github.com/openmm/openmm/blob/master/wrappers/python/openmm/app/forcefield.py)　OpenMM 的 ForceField 类负责读取 XML 中的原子类型和力场定义并建立可计算的模型。
