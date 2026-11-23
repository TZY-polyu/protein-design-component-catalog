# BioDesignBench Leaderboard（排行榜前端）

展示已提交系统的汇总结果，供用户浏览不同系统的成绩与评估设置。

## 输入与输出

- **输入**　系统信息、提交材料和已计算的评估指标。
- **输出**　可在浏览器中查看的排名、分数及提交状态。

## 接入条件

- **LLM 参与**　排行榜展示与数据发布无需再次调用 LLM。分数来源可以包含模型评审。
- **运行条件**　本地运行网页需要 Python、Gradio、Plotly 及配套排行榜数据。若启用在线提交，还需配置对应后端。

公开前端用于呈现评测结果。完整正式任务和评测服务所用数据另行管理。

## 原始来源与公开实现

Kim 与 Romero（2026），Benchmarking and behavioral characterization of LLM agents for protein design。排行榜随基准发布，未见独立方法论文。

[论文或原始出版物](https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1)

- **GitHub 仓库**　[RomeroLab/BioDesignBench](https://github.com/RomeroLab/BioDesignBench)
- **实现入口**　[查看源代码](https://github.com/RomeroLab/BioDesignBench/blob/main/biodesignbench-leaderboard/app.py)

作者仓库中排行榜子目录。线上提交入口在 Hugging Face Spaces。

## 下载

- [官方在线排行榜](https://huggingface.co/spaces/RomeroLab-Duke/BioDesignBench-Leaderboard)　作者维护的 Hugging Face Space。前端代码位于基准仓库子目录。
- [项目源码 ZIP](https://github.com/RomeroLab/BioDesignBench/archive/718e452e3f73f8be423e954b6c05f3aa3f42859c.zip)　公开项目的源码快照。
