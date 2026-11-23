# 3Dmol.js / py3Dmol

把蛋白质三维坐标绘成可旋转的分子视图。3Dmol.js 用于网页，py3Dmol 将同一渲染器嵌入 Python 笔记本。

## 输入与输出

- **输入**　PDB 或其他受支持格式的原子坐标，以及希望突出显示的链、残基和着色样式。
- **输出**　浏览器或笔记本中可交互的三维视图，也可以导出结果图。

## 接入条件

- **LLM 参与**　渲染使用分子坐标和绘图指令，无需通用或蛋白语言模型。
- **运行条件**　网页版需要支持 WebGL 的浏览器和 3Dmol.js。py3Dmol 还需 Python、py3Dmol 包，以及能呈现 JavaScript 输出的笔记本前端。

颜色与表面表示由显示设置决定。图像可帮助检查结构，不能代替结构质量或结合能的定量评估。

## 原始来源与公开实现

Rego & Koes (2015), 3Dmol.js: molecular visualization with WebGL

[论文或原始出版物](https://doi.org/10.1093/bioinformatics/btu829)

- **GitHub 仓库**　[3dmol/3Dmol.js](https://github.com/3dmol/3Dmol.js)
- **实现入口**　[查看源代码](https://github.com/3dmol/3Dmol.js)

同一上游仓库维护网页渲染器和 Python 笔记本接口。

## 下载

- [py3Dmol 安装包](https://pypi.org/project/py3Dmol/#files)　Python 封装的发布文件。JavaScript 渲染器见上游仓库。
- [项目源码 ZIP](https://github.com/3dmol/3Dmol.js/archive/ab1b8e3bd7621f931c037a8214776c728e39a1a5.zip)　公开项目的源码快照。
