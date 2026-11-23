# Docker

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

将程序、库和运行环境打包成镜像，并以容器运行，使不同科学工具能够隔离依赖。

## 输入、输出与 LLM 参与

- **输入**　容器镜像或构建配置、程序输入、所需文件及运行资源。
- **输出**　容器中的进程、标准输出、日志，以及挂载目录中的计算产物。
- **LLM 参与**　容器引擎无需 LLM。

## 结果解读

Moby 是引擎的开源基础。Docker Desktop、Docker Engine 和研究项目自己的工具镜像是三种不同的下载对象。

## 在六篇研究中的用法

- **ProteinMCP**（服务运行基础设施）　为高负载工具提供一次性运行环境。

使用此来源的研究组件包括 [AutoBinder 计算资源编排](../../%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/AutoBinder%20%E8%AE%A1%E7%AE%97%E8%B5%84%E6%BA%90%E7%BC%96%E6%8E%92/AutoBinder%20%E8%AE%A1%E7%AE%97%E8%B5%84%E6%BA%90%E7%BC%96%E6%8E%92.md)、[BioDesignBench 隔离执行环境](../../%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E9%9A%94%E7%A6%BB%E6%89%A7%E8%A1%8C%E7%8E%AF%E5%A2%83/BioDesignBench%20%E9%9A%94%E7%A6%BB%E6%89%A7%E8%A1%8C%E7%8E%AF%E5%A2%83.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Solomon Hykes / dotCloud (2013)，Docker 软件首次公开演示（无单一方法论文）](<https://www.docker.com/blog/docker-nine-years-young/>)
- **GitHub 仓库**　[moby/moby](<https://github.com/moby/moby>)
- **归属说明**　Docker 官方回顾。Moby 是 Docker Engine 的开源基础。

## 下载与访问

- [Docker 官方安装入口](<https://docs.docker.com/get-docker/>)　提供桌面和服务器运行方式的正式入口。
- [仓库源码 ZIP · moby/moby](<https://github.com/moby/moby/archive/8b0c45e42959ea5322cfb33bfb97a40ed64d4a07.zip>)　该仓库的固定快照。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
