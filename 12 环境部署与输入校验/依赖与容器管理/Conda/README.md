# Conda

为依赖版本不同的科学工具分别管理运行环境，解析依赖并安装对应平台的软件包。

## 输入与输出

- **输入**　软件名、版本约束、渠道、操作系统与已有环境，或环境定义文件。
- **输出**　已解析的依赖清单以及可供工具运行的环境。

## 接入条件

- **LLM 参与**　不需要 LLM。
- **运行条件**　需在所支持的操作系统安装 Conda 发行版，并可写入环境目录。首次获取软件包时需访问软件源或本地镜像。

复现时应保留环境中实际解析出的版本。Conda 解决的是软件依赖，GPU 驱动等系统条件另行管理。

## 原始来源与公开实现

conda developers, conda（软件引用，见 CITATION.cff）

[官方来源说明](https://github.com/conda/conda/blob/main/CITATION.cff)

- **GitHub 仓库**　[conda/conda](https://github.com/conda/conda)
- **实现入口**　[查看源代码](https://github.com/conda/conda)

Conda 官方源码。不同发行途径还可能捆绑默认渠道与软件包。

## 下载

- [Miniforge 安装器](https://github.com/conda-forge/miniforge/releases)　conda-forge 提供的跨平台 Conda 发行版。
- [项目源码 ZIP](https://github.com/conda/conda/archive/76f8c394128e7be608a01bef4c995580da2f7811.zip)　公开项目的源码快照。
