# DSSP

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

从三维结构中的主链几何和氢键模式，为残基指派螺旋、折叠或其他二级结构类别。

## 输入、输出与 LLM 参与

- **输入**　含有主链原子坐标的蛋白结构文件，常见格式为 PDB 或 mmCIF。
- **输出**　按链和残基编号排列的二级结构代码，并可包含溶剂可及性等衍生量。
- **LLM 参与**　规则和几何计算无需通用 LLM。

## 结果解读

不同研究可保留完整类别或合并为三态。比较二级结构比例时应确认两端采用了相同映射。

## 在六篇研究中的用法

- **BioDesignBench**（正文列举／注册状态未证实）　正文列举的二级结构标注方法。补充表S1未列独立 DSSP 接口。

使用此来源的研究组件包括 [ProtAgents 二级结构组成统计](../ProtAgents%20%E4%BA%8C%E7%BA%A7%E7%BB%93%E6%9E%84%E7%BB%84%E6%88%90%E7%BB%9F%E8%AE%A1/ProtAgents%20%E4%BA%8C%E7%BA%A7%E7%BB%93%E6%9E%84%E7%BB%84%E6%88%90%E7%BB%9F%E8%AE%A1.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Kabsch & Sander (1983), Dictionary of protein secondary structure: pattern recognition of hydrogen-bonded and geometrical features](<https://doi.org/10.1002/bip.360221211>)
- **GitHub 仓库**　[PDB-REDO/dssp](<https://github.com/PDB-REDO/dssp>)
- **归属说明**　维护中的 DSSP 软件仓库。论文经 Biopython 调用。

## 下载与访问

- [DSSP 官方软件发布](<https://github.com/PDB-REDO/dssp/releases>)　原方法维护项目发布的版本和安装资源。
- [仓库源码 ZIP · PDB-REDO/dssp](<https://github.com/PDB-REDO/dssp/archive/a8bd82c3178a3bc78b2c630e13a3dc9578ae2e62.zip>)　该仓库的固定快照。
