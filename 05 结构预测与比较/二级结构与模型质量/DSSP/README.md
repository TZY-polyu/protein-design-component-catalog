# DSSP

从三维结构中的主链几何和氢键模式，为残基指派螺旋、折叠或其他二级结构类别。

## 输入与输出

- **输入**　含有主链原子坐标的蛋白结构文件，常见格式为 PDB 或 mmCIF。
- **输出**　按链和残基编号排列的二级结构代码，并可包含溶剂可及性等衍生量。

## 接入条件

- **LLM 参与**　规则和几何计算无需通用 LLM。
- **运行条件**　需要已安装的 mkdssp 程序或相应的 Python 绑定，以及包含主链原子坐标的结构文件。部分发行版还需配置化学组分字典。

不同研究可保留完整类别或合并为三态。比较二级结构比例时应确认两端采用了相同映射。

## 原始来源与公开实现

Kabsch & Sander (1983), Dictionary of protein secondary structure: pattern recognition of hydrogen-bonded and geometrical features

[论文或原始出版物](https://doi.org/10.1002/bip.360221211)

- **GitHub 仓库**　[PDB-REDO/dssp](https://github.com/PDB-REDO/dssp)
- **实现入口**　[查看源代码](https://github.com/PDB-REDO/dssp)

PDB-REDO 维护的 DSSP 实现，命令行主程序为 mkdssp。

## 下载

- [DSSP 官方软件发布](https://github.com/PDB-REDO/dssp/releases)　原方法维护项目发布的版本和安装资源。
- [项目源码 ZIP](https://github.com/PDB-REDO/dssp/archive/a8bd82c3178a3bc78b2c630e13a3dc9578ae2e62.zip)　公开项目的源码快照。
