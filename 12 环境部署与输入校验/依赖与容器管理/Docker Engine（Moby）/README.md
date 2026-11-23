# Docker Engine（Moby）

将程序、库和运行环境打包成镜像，并以容器运行，使不同科学工具能够隔离依赖。

## 输入与输出

- **输入**　容器镜像或构建配置、程序输入、所需文件及运行资源。
- **输出**　容器中的进程、标准输出、日志，以及挂载目录中的计算产物。

## 接入条件

- **LLM 参与**　容器引擎无需 LLM。
- **运行条件**　引擎需要兼容的 Linux 运行环境及相应权限。macOS、Windows 可通过提供 Linux 虚拟机的环境运行 Linux 容器。

Moby 提供 Docker Engine 的核心实现。Docker Desktop 的图形产品与许可单独管理。

## 原始来源与公开实现

Docker 由 Solomon Hykes 与 dotCloud 团队于 2013 年公开演示。未见 Docker Engine 单独的方法论文，官方项目与发布历史可追溯其来源。

[官方来源说明](https://www.docker.com/blog/docker-nine-years-young/)

- **GitHub 仓库**　[moby/moby](https://github.com/moby/moby)
- **实现入口**　[查看源代码](https://github.com/moby/moby)

Moby 为 Docker Engine 的开源上游，提供守护进程等引擎组件。

## 下载

- [Docker 官方安装入口](https://docs.docker.com/get-docker/)　提供桌面和服务器运行方式的正式入口。
- [项目源码 ZIP](https://github.com/moby/moby/archive/8b0c45e42959ea5322cfb33bfb97a40ed64d4a07.zip)　公开项目的源码快照。
