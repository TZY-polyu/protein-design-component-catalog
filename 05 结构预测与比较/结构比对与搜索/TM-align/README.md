# TM-align

为两种蛋白三维结构寻找残基对应和空间叠合，以 TM-score 衡量折叠层面的结构相似性。

## 输入与输出

- **输入**　两个蛋白结构的坐标与所比较的链。
- **输出**　结构对齐、残基对应关系、TM-score，以及对齐范围和 RMSD 等摘要。

## 接入条件

- **LLM 参与**　无需 LLM，通过结构比对算法求解。
- **运行条件**　本地编译需 C++ 工具链与完整仓库的头文件。输入为可解析的结构坐标。

归一化使用哪一侧结构的长度会影响报告值。相似度应和对齐长度、覆盖范围一起看。

**最小运行核验**　从作者源码编译 TM-align（20240303），对 12 个合成 Cα 坐标与其整体平移后的副本做比对。结果对齐 12 个残基，RMSD 为 0.00 Å，两种长度归一化的 TM-score 均为 1.00000。

## 原始来源与公开实现

Zhang & Skolnick (2005), TM-align: a protein structure alignment algorithm based on the TM-score

[论文或原始出版物](https://doi.org/10.1093/nar/gki524)

- **GitHub 仓库**　[pylelab/USalign](https://github.com/pylelab/USalign)
- **实现入口**　[查看源代码](https://github.com/pylelab/USalign/blob/master/TMalign.cpp)

US-align 团队仓库中包含可编译的 TM-align 前端和所需头文件。

## 下载

- [含依赖头文件的源码包](https://github.com/pylelab/USalign/archive/refs/heads/master.zip)　完整源码树包含 TMalign.cpp。
