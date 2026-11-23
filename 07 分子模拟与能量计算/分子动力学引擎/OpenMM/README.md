# OpenMM

为分子力学系统计算能量和力，支持结构能量最小化及分子动力学模拟。

## 输入与输出

- **输入**　分子拓扑、初始坐标、选定的力场和系统定义。
- **输出**　视任务返回调整后的坐标、能量和力，或随时间记录的模拟轨迹。

## 接入条件

- **LLM 参与**　由数值计算引擎执行，无需通用 LLM。
- **运行条件**　OpenMM 安装包、和输入兼容的力场及拓扑。可选计算平台取决于软硬件环境。

能量数字依赖力场、单位、体系定义和坐标。比较不同构象时需要保持这些条件一致。

## 原始来源与公开实现

Eastman & Pande (2010), OpenMM: A Hardware Independent Framework for Molecular Simulations.

[论文或原始出版物](https://doi.org/10.1109/MCSE.2010.27)

- **GitHub 仓库**　[openmm/openmm](https://github.com/openmm/openmm)
- **实现入口**　[查看源代码](https://github.com/openmm/openmm/blob/b5282630278e6c78e92691ed411543f73aabba75/openmmapi/src/Context.cpp)

具名框架论文。Friedrichs 等（2009）另述早期 GPU 实现。

## 下载

- [下载实现源码（ZIP）](https://github.com/openmm/openmm/archive/b5282630278e6c78e92691ed411543f73aabba75.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [OpenMM 发布包](https://pypi.org/project/OpenMM/#files)　按操作系统与 Python 版本提供软件包。
