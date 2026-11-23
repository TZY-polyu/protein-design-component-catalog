# Protein-Sol

根据序列的理化及组成特征估计蛋白质相对溶解倾向，供不同序列作计算比较。

## 输入与输出

- **输入**　蛋白氨基酸序列。输入需满足该工具支持的序列字符与格式。
- **输出**　序列级预测溶解性分数，以及部分输入特征相对于参考群体的偏差。

## 接入条件

- **LLM 参与**　通过序列特征与统计模型预测，无需通用 LLM。
- **运行条件**　类 Unix 环境、Shell 和 Perl。该序列模型所需的脚本与配套参数随 ZIP 发布。

分数来自参考表达数据上的模型预测。实际溶解度还与实验体系、条件有关，分数没有实验浓度单位。

**最小运行核验**　运行作者示例的两条蛋白序列，重新计算得到 scaled-sol 0.336（P00547）、0.548（P61626），与包内参考输出一致。

## 原始来源与公开实现

Hebditch et al. (2017), Protein–Sol: a web tool for predicting protein solubility from sequence

[论文或原始出版物](https://doi.org/10.1093/bioinformatics/btx345)

- **GitHub 仓库**　未找到该实现的官方 GitHub 镜像。
- **实现入口**　[查看源代码](https://www.protein-sol.manchester.ac.uk/cgi-bin/utilities/download_sequence_code.php)

曼彻斯特大学研究团队在项目主页发布本地脚本。目前核实到的原始代码托管位置为作者网站。

## 下载

- [官方 Shell／Perl 源码 ZIP](https://www.protein-sol.manchester.ac.uk/cgi-bin/utilities/download_sequence_code.php)　Protein-Sol 序列溶解性预测离线包，附运行说明。
- [官方软件说明](https://www.protein-sol.manchester.ac.uk/software)　下载页第一项为序列溶解性预测程序。

## 可选调用接口

- **Protein-Sol MCP**　通过 Perl 在本地运行 Protein-Sol 序列溶解性分析。Manchester 作者网站也分发独立源码包。 [接口源码](https://github.com/MacromNex/protein_sol_mcp/blob/0457dd7fc77a35f48602d88ad17e51fc742b1be4/scripts/lib/protein_sol.py) · [适配器下载](https://github.com/MacromNex/protein_sol_mcp/archive/0457dd7fc77a35f48602d88ad17e51fc742b1be4.zip)
