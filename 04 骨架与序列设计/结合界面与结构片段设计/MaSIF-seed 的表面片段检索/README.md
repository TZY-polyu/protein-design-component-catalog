# MaSIF-seed 的表面片段检索

比较蛋白表面局部区域的几何与化学特征，寻找可能互补的蛋白片段或种子。

## 输入与输出

- **输入**　蛋白三维表面的指定区域、学习得到的表面描述符，以及供比较的种子库。
- **输出**　候选表面匹配、相应片段与几何对应关系，可用于后续结构层面的比较。

## 接入条件

- **LLM 参与**　使用专用表面几何模型和检索算法，无需通用 LLM。
- **运行条件**　需要配套表面处理软件、训练参数和用于检索的几何片段库。

匹配结果用于比较蛋白表面之间的局部几何和化学互补性。实际结合性质仍需另行测量。

## 原始来源与公开实现

Gainza et al. (2023), De novo design of protein interactions with learned surface fingerprints

[论文或原始出版物](https://doi.org/10.1038/s41586-023-05993-x)

- **GitHub 仓库**　[LPDI-EPFL/masif_seed](https://github.com/LPDI-EPFL/masif_seed)
- **实现入口**　[查看源代码](https://github.com/LPDI-EPFL/masif_seed/blob/77153911d8252d02193a6d1d6d0539bf02c5faba/masif_seed_search/source/masif_seed_search_nn.py)

原作者的 MaSIF-seed 仓库含 masif_seed_search 实现及模型文件。

## 下载

- [下载实现源码（ZIP）](https://github.com/LPDI-EPFL/masif_seed/archive/77153911d8252d02193a6d1d6d0539bf02c5faba.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
