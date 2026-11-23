# TM-score（结构相似性评分）

以长度归一化的距离评分汇总两个结构在空间叠合后的匹配程度，常用于结构相似性和折叠质量评估。

## 输入与输出

- **输入**　两个表示同一组参考残基的结构坐标。独立程序默认按残基编号建立对应，参考结构决定默认归一化长度。
- **输出**　相对于所选参考结构的 TM-score 和叠合后的结构偏差等摘要。

## 接入条件

- **LLM 参与**　无需 LLM，按几何距离和参考长度计算。
- **运行条件**　可使用作者提供的平台程序，也可用 C++ 编译器构建源码。

当残基编号或链对应有变化时，应先核对对应关系。长度归一化的选择会改变分数。

## 原始来源与公开实现

Zhang & Skolnick (2004). Scoring function for automated assessment of protein structure template quality.

[论文或原始出版物](https://doi.org/10.1002/prot.20264)

- **GitHub 仓库**　[pylelab/USalign](https://github.com/pylelab/USalign)
- **实现入口**　[查看源代码](https://github.com/pylelab/USalign/blob/master/TMscore.cpp)

作者官网发布独立的 C++ 程序。US-align 团队仓库也提供 TMscore.cpp 及对应头文件。

## 下载

- [作者发布的独立 C++ 源码](https://seq2fun.dcmb.med.umich.edu/TM-score/TMscore.cpp)　原作者提供的可编译单文件版本。
- [程序和可执行文件](https://seq2fun.dcmb.med.umich.edu/TM-score/)　提供多平台程序、说明和版本信息。
- [下载本次索引的源码快照（ZIP）](https://github.com/pylelab/USalign/archive/23f14ffcf8647f2dc1c0e01043db3a7f3a661c28.zip)
