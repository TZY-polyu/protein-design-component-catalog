# 3Dmol.js / py3Dmol

[评估与展示](../../README.md) / 三维展示与结果导出

## 用途

把蛋白质三维坐标绘成可旋转的分子视图。3Dmol.js 用于网页，py3Dmol 将同一渲染器嵌入 Python 笔记本。

## 输入、输出与 LLM 参与

- **输入**　PDB 或其他受支持格式的原子坐标，以及希望突出显示的链、残基和着色样式。
- **输出**　浏览器或笔记本中可交互的三维视图，也可以导出结果图。
- **LLM 参与**　渲染使用分子坐标和绘图指令，无需通用或蛋白语言模型。

## 结果解读

颜色与表面表示由显示设置决定。图像可帮助检查结构，不能代替结构质量或结合能的定量评估。

## 在六篇研究中的用法

- **ProtAgents**（结果展示）　展示 Chroma 与 OmegaFold 生成的结构，结合属性图供人工比较。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Rego & Koes (2015), 3Dmol.js: molecular visualization with WebGL](<https://doi.org/10.1093/bioinformatics/btu829>)
- **GitHub 仓库**　[3dmol/3Dmol.js](<https://github.com/3dmol/3Dmol.js>)
- **归属说明**　同一上游仓库包含 py3Dmol Python 接口。

## 下载与访问

- [py3Dmol 安装包](<https://pypi.org/project/py3Dmol/#files>)　Python 封装的发布文件。JavaScript 渲染器见上游仓库。
- [仓库源码 ZIP · 3dmol/3Dmol.js](<https://github.com/3dmol/3Dmol.js/archive/ab1b8e3bd7621f931c037a8214776c728e39a1a5.zip>)　该仓库的固定快照。
