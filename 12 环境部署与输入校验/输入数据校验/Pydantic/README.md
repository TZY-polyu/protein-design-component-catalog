# Pydantic

按 Python 类型声明解析和校验输入，适合给任务参数、批量结果或配置文件建立一致的数据结构。

## 输入与输出

- **输入**　需要验证的 JSON、字典或 Python 对象，以及字段类型、约束和默认值。
- **输出**　校验通过的模型对象及可序列化数据，或指明字段位置和原因的校验错误。

## 接入条件

- **LLM 参与**　无需 LLM，规则由数据模型定义。
- **运行条件**　Python。安装包会依赖与相应版本匹配的 pydantic-core。

字段类型、默认值以及是否允许自动类型转换由数据模型决定。通过校验只表示数据满足所声明的结构。

## 原始来源与公开实现

Pydantic 团队，Pydantic Validation。官方按软件与版本发布，未核实有独立原始论文。

[官方来源说明](https://docs.pydantic.dev/latest/)

- **GitHub 仓库**　[pydantic/pydantic](https://github.com/pydantic/pydantic)
- **实现入口**　[查看源代码](https://github.com/pydantic/pydantic)

官方 Python 包源码。底层验证引擎在 pydantic-core 中维护。

## 下载

- [下载源码快照（ZIP）](https://github.com/pydantic/pydantic/archive/1aaef01805ae0bc436954a4e863cc0b64a827193.zip)　该链接固定到仓库中的一个提交。
- [Python 发布包](https://pypi.org/project/pydantic/#files)　PyPI 中提供源码发行包和 wheel。
