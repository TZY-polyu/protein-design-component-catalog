# Pydantic

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

根据 Python 类型声明校验传入的数据，便于在评测系统中统一任务结构、发现缺项并安全读取字段。

## 输入、输出与 LLM 参与

- **输入**　任务 JSON 或 Python 字典，以及项目定义的字段类型和约束。
- **输出**　校验通过的模型对象及可序列化数据，或指明字段位置和原因的校验错误。
- **LLM 参与**　无需 LLM，规则由数据模型定义。

## 结果解读

BioDesignBench 的 DesignTask 描述任务内容，Pydantic 提供通用校验能力。通过校验只表明数据满足所声明的结构。

## 在六篇研究中的用法

使用此来源的研究组件包括 [BioDesignBench 任务规范（DesignTask）](../../%E5%B7%A5%E4%BD%9C%E6%B5%81%E4%B8%8E%E6%89%A7%E8%A1%8C%E7%AE%A1%E7%90%86/BioDesignBench%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E8%8C%83%EF%BC%88DesignTask%EF%BC%89/BioDesignBench%20%E4%BB%BB%E5%8A%A1%E8%A7%84%E8%8C%83%EF%BC%88DesignTask%EF%BC%89.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Pydantic, Pydantic Validation（官方软件文档）](<https://docs.pydantic.dev/latest/>)
- **GitHub 仓库**　[pydantic/pydantic](<https://github.com/pydantic/pydantic>)
- **归属说明**　库本体为官方仓库。DesignTask 为 P6 项目定义的数据模型。

## 下载与访问

- [Python 发布包](<https://pypi.org/project/pydantic/#files>)　PyPI 中提供源码发行包和 wheel。
- [仓库源码 ZIP · pydantic/pydantic](<https://github.com/pydantic/pydantic/archive/1aaef01805ae0bc436954a4e863cc0b64a827193.zip>)　该仓库的固定快照。
