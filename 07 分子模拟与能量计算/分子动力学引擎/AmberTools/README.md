# AmberTools

AMBER 家族中公开源码的分子模拟工具集，可准备分子体系、计算能量与动力学，并分析结构轨迹。

## 输入与输出

- **输入**　按功能接收分子结构、拓扑、力场参数、模拟条件或已有轨迹。
- **输出**　拓扑和坐标文件、能量与轨迹，以及对轨迹的结构统计结果。

## 接入条件

- **LLM 参与**　力场计算、数值积分和轨迹分析无需 LLM。
- **运行条件**　源码下载页面需填写表单。从源码构建需要 C、C++ 及 Fortran 编译器。

AmberTools 是独立发行包。AMBER 家族的其他产品有各自的分发条件。

## 原始来源与公开实现

Case 等（2023），AmberTools。专门描述 AmberTools 工具集的论文。

[论文或原始出版物](https://doi.org/10.1021/acs.jcim.3c01153)

- **GitHub 仓库**　未找到该实现的官方 GitHub 镜像。
- **实现入口**　[查看源代码](https://ambermd.org/GetAmber.php)

通过官方发行站取得完整源码压缩包，未核实完整套件的官方 GitHub 镜像。

## 下载

- [AmberTools 源码及二进制发行](https://ambermd.org/GetAmber.php)　Option 2 为源码，Option 1 提供预编译包。

## 可选调用接口

- **AmberTools 分子模拟 MCP**　可调用本机 AmberTools 的 tleap 和 sander。需自行安装 AmberTools。仓库的自动构建脚本另涉及 PMEMD，其发行条件需单独核对。 [接口源码](https://github.com/MacromNex/amber_mcp/blob/f1fceb75263a5b48bc26c57da7e396b4d5392661/src/tools/simulation.py) · [适配器下载](https://github.com/MacromNex/amber_mcp/archive/f1fceb75263a5b48bc26c57da7e396b4d5392661.zip)
