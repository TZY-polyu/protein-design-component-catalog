# Protein Data Bank

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

长期保存并分发生物大分子的实验结构，供研究者查找已提交的坐标、实验信息与结构说明。

## 输入、输出与 LLM 参与

- **输入**　PDB 条目标识或检索条件。批量取数时还可按文件类型及归档版本选择。
- **输出**　坐标文件（如 PDBx/mmCIF）、关联元数据，以及适用条目的实验证据和验证报告。
- **LLM 参与**　数据访问、解析与下载无需通用 LLM。

## 结果解读

PDB 指整个结构档案。RCSB PDB 是提供服务的成员之一，传统 PDB 文件格式另有自己的字段规范。

## 在六篇研究中的用法

- **Latent-Y**（在线取数／基准构建）　寻找研究对象的已知结构、分析复合物，并用于基准选题。

使用此来源的研究组件包括 [ProtAgents 结构下载函数](../../%E6%A3%80%E7%B4%A2%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86/ProtAgents%20%E7%BB%93%E6%9E%84%E4%B8%8B%E8%BD%BD%E5%87%BD%E6%95%B0/ProtAgents%20%E7%BB%93%E6%9E%84%E4%B8%8B%E8%BD%BD%E5%87%BD%E6%95%B0.md)、[ProtAgents 结构文件序列读取](../../%E6%A3%80%E7%B4%A2%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86/ProtAgents%20%E7%BB%93%E6%9E%84%E6%96%87%E4%BB%B6%E5%BA%8F%E5%88%97%E8%AF%BB%E5%8F%96/ProtAgents%20%E7%BB%93%E6%9E%84%E6%96%87%E4%BB%B6%E5%BA%8F%E5%88%97%E8%AF%BB%E5%8F%96.md)、[MAESD 测试集与同源过滤](../../%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4/MAESD%20%E6%B5%8B%E8%AF%95%E9%9B%86%E4%B8%8E%E5%90%8C%E6%BA%90%E8%BF%87%E6%BB%A4.md)、[Latent-Y 文献推断基准集](../../%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/Latent-Y%20%E6%96%87%E7%8C%AE%E6%8E%A8%E6%96%AD%E5%9F%BA%E5%87%86%E9%9B%86/Latent-Y%20%E6%96%87%E7%8C%AE%E6%8E%A8%E6%96%AD%E5%9F%BA%E5%87%86%E9%9B%86.md)、[ProtAgents 序列长度统计](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E6%A3%80%E7%B4%A2%E4%B8%8E%E6%B3%A8%E9%87%8A/ProtAgents%20%E5%BA%8F%E5%88%97%E9%95%BF%E5%BA%A6%E7%BB%9F%E8%AE%A1/ProtAgents%20%E5%BA%8F%E5%88%97%E9%95%BF%E5%BA%A6%E7%BB%9F%E8%AE%A1.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Crystallography: Protein Data Bank (1971). Nature New Biology 233, 223.](<https://doi.org/10.1038/newbio233223b0>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　PDB 档案建立公告。最初的 BNL/CCDC 档案没有独立 GitHub。RCSB 平台另列。

## 下载与访问

- [wwPDB 档案下载](<https://www.wwpdb.org/ftp/pdb-ftp-sites>)　提供结构文件分发镜像与版本化档案入口。 此次连接超时，文件下载状态未确认。

## 关联组件

[BioMCP（acashmoney 结构分析服务）](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/BioMCP%EF%BC%88acashmoney%20%E7%BB%93%E6%9E%84%E5%88%86%E6%9E%90%E6%9C%8D%E5%8A%A1%EF%BC%89/BioMCP%EF%BC%88acashmoney%20%E7%BB%93%E6%9E%84%E5%88%86%E6%9E%90%E6%9C%8D%E5%8A%A1%EF%BC%89.md) · [PDB MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/PDB%20MCP/PDB%20MCP.md) · [RCSB PDB](../RCSB%20PDB/RCSB%20PDB.md)
