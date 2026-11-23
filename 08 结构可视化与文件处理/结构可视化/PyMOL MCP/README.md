# PyMOL MCP

将本机 PyMOL 的显示、选区和测量操作提供给 MCP 客户端，供脚本或交互式助手控制分子视图。

## 输入与输出

- **输入**　PyMOL 可识别的结构文件或已加载的对象，配合选择表达式、表示方式、颜色或测量请求。
- **输出**　PyMOL 会话中更新的分子视图，以及命令的状态或测量文本。有导出请求时由 PyMOL 写出图片。

## 接入条件

- **LLM 参与**　基础命令解析、视图控制和测量均无需 LLM。自然语言会话可以由外部模型生成控制命令。
- **运行条件**　Python 3.10 或更高版本、MCP Python 包、本机 PyMOL 与同仓库配套插件。连接器代码采用 MIT 许可，PyMOL 安装版本的许可另计。

结构坐标和几何测量由 PyMOL 处理。MCP 服务负责解析命令并与本机 PyMOL 插件通信。

## 原始来源与公开实现

Vishnu Rajan Tejus 发布的 PyMOL MCP 软件。未查到该连接器的独立原始论文。

- **GitHub 仓库**　[vrtejus/pymol-mcp](https://github.com/vrtejus/pymol-mcp)
- **实现入口**　[查看源代码](https://github.com/vrtejus/pymol-mcp/blob/d54eeaf4d59d939caec33fc91c9ebb755aae1572/pymol_mcp_server.py)

连接器作者仓库，包含服务进程和 PyMOL 端插件。

## 下载

- [固定版本源码 ZIP](https://github.com/vrtejus/pymol-mcp/archive/d54eeaf4d59d939caec33fc91c9ebb755aae1572.zip)　该快照包含组件实现及配套项目文件。
