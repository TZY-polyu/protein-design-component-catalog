# PyMOL（开源版）

把三维分子坐标呈现为可旋转的结构图，可突出链、残基或界面并导出插图。

## 输入与输出

- **输入**　分子坐标文件（如 PDB、mmCIF）、待显示的对象或选区及显示设置。
- **输出**　交互式结构视图、会话文件、静态图像，或由选区计算的几何量。

## 接入条件

- **LLM 参与**　渲染与几何测量无需通用 LLM。
- **运行条件**　桌面交互需要图形环境。源代码构建和预编译商业发行版的安装方式各异。

结构图展示的是载入的坐标及用户选择的表示方式，颜色和视觉接触本身不能证明分子实际结合。

## 原始来源与公开实现

DeLano (2002), PyMOL: An Open-Source Molecular Graphics Tool.

[官方来源说明](https://www.ccp4.ac.uk/ccp4-legacy/newsletters/newsletter40/11_pymol.pdf)

- **GitHub 仓库**　[schrodinger/pymol-open-source](https://github.com/schrodinger/pymol-open-source)
- **实现入口**　[查看源代码](https://github.com/schrodinger/pymol-open-source)

Schrödinger 维护的 PyMOL Open-Source Edition 源码。

## 下载

- [下载源码快照（ZIP）](https://github.com/schrodinger/pymol-open-source/archive/ea0283d105d17fb0b56bb24e7d7f8c618407f1c2.zip)　该链接固定到仓库中的一个提交。
