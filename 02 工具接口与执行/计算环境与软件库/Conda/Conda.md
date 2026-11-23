# Conda

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

为依赖版本不同的科学工具分别管理运行环境，解析依赖并安装对应平台的软件包。

## 输入、输出与 LLM 参与

- **输入**　软件名、版本约束、渠道、操作系统与已有环境，或环境定义文件。
- **输出**　已解析的依赖清单以及可供工具运行的环境。
- **LLM 参与**　不需要 LLM。

## 结果解读

复现时应保留环境中实际解析出的版本。Conda 解决的是软件依赖，GPU 驱动等系统条件另行管理。

## 在六篇研究中的用法

- **ProteinMCP**（服务运行基础设施）　隔离不同工具的软件依赖。

## 原始来源与 GitHub

- **原始文献或官方出处**　[conda developers, conda（软件引用，见 CITATION.cff）](<https://github.com/conda/conda/blob/main/CITATION.cff>)
- **GitHub 仓库**　[conda/conda](<https://github.com/conda/conda>)
- **归属说明**　软件项目。

## 下载与访问

- [Miniforge 安装器](<https://github.com/conda-forge/miniforge/releases>)　conda-forge 提供的跨平台 Conda 发行版。
- [仓库源码 ZIP · conda/conda](<https://github.com/conda/conda/archive/76f8c394128e7be608a01bef4c995580da2f7811.zip>)　该仓库的固定快照。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
