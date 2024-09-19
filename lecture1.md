# Bioinformatics in action
## Course Logistics
### 学习与参考资料
PPT+bioinformatics tutorial

## Introduction_steps of bioinformatics

### 0. Question
#### Science 125 questions_top5
1. What Is the Universe Made Of?
**2. What Is the Biological Basis of Consciousness?**
**3. Why Do Humans Have So Few Genes?**
**4. To What Extent Are Genetic Variation and Personal Health Linked?**
5. Can the Laws of Physics Be Unified?
三个关于生命科学的问题

### 1.Information
images and sequences
#### Type of NGS (Next Generation Sequencing)
1. DNA-seq
2. RNA-seq
3. Epigenetics
– DNAase
– Methylation
– Histone modifications: ChIP-seq
4. Interaction
– Protein-DNA : ChIP-seq
– Protein-RNA: CLIP-seq
– DNA-RNA: Grid-seq

### 2.Analysis
Sequencing Method + Bioinformatics Tool
Interpreting the Data

### 3.Modeling
#### Model
如regression model，neural network model
**定义：**模型是在算法的基础上通过对数据进行训练后生成的数学表示，通常用来表示现实世界的某种现象或模式。
**本质：**模型是一种*结果*，通过算法处理数据后得到的。在机器学习中，模型通过使用算法从训练数据中学习和抽象出规律，并用于预测或决策。
*特点：*
模型是算法作用于特定数据后生成的实例，因此不同的数据集会生成不同的模型。
模型通常是静态的，在被训练或构建之后，它可以用于做预测或分类任务。
模型需要通过测试、调整和评估，来确保它在未见过的数据上能够有效地工作。
#### computational algorithm
**定义：**算法是解决问题的一组明确的、可执行的指令或步骤。它规定了如何从输入数据到输出结果的计算过程。
**本质：**算法是一种*方法或过程*，用来解决某个问题或执行某项任务。它是一种抽象的、固定的计算规则，强调的是如何处理数据。
*特点：*
通常是通用的，可以应用于不同的数据集。
具有固定的步骤，可以是简单的排序算法（如快速排序），也可以是复杂的机器学习算法（如梯度下降）。
直接作用于数据，目的是完成某个任务或达到某个目标。
如Number Sorting Algorithm，Dynamic Programming Algorithm

## Getting Started
### Document your work – Github & Markdown
### Backup your work
### Use Bioinformatics1 Tutorial
### Set up
vim,docker


# Study Plan
## how
in-class learning 1.5h each week
after-class study >5h each week

## 目标：
- 学习生物信息学的基础知识
- 掌握常用的生物信息学工具
- 熟悉 Python 和 R 编程的基础
- 能够独立进行基本的生物数据分析

## 总时长：4个月

---

### 生物信息学基础 & 编程基础

**1. 生物信息学基础概念**
- 学习生物信息学的基本定义与历史背景
- 了解生物数据的类型：基因组、转录组、蛋白质组等
- 学习常见数据库（如：NCBI、Ensembl、UniProt、PDB）及其用途

**2. Linux 基础**
- 学习 Linux 系统的基础命令（ls, cd, mkdir, rm, etc.）
- 了解如何在 Linux 环境下操作文件与目录
- 学习文件编辑器（nano 或 vim）的基本用法

**3. Python 编程基础**
- 学习 Python 语法基础：变量、数据类型、条件语句、循环
- 学习如何使用列表、字典、集合等数据结构
- 安装 Jupyter Notebook，练习在其中编写代码



---

### 生物数据处理 & Python 进阶

**1. Python 数据处理**
- 学习 Python 中常用的生物信息学库：BioPython
- 学习使用 Pandas 处理数据表格（如表达矩阵、基因注释文件）
- 学习如何使用 Matplotlib 绘制简单的图表

**2. 基因组学基础**
- 学习 DNA、RNA、蛋白质的基本结构与功能
- 了解基因组学、转录组学及其研究意义
- 学习 FASTA、FASTQ 文件格式及其应用

**3. R 语言基础**
- 安装 R 和 RStudio
- 学习 R 的基本语法及数据处理（向量、数据框）
- 学习 ggplot2 进行数据可视化



---

### 高通量数据分析 & 数据库工具

**1. 高通量数据分析**
- 了解高通量测序技术（NGS）：RNA-seq, ChIP-seq, ATAC-seq
- 学习如何解析 FASTQ 文件，了解基本的数据处理流程
- 了解常用的比对工具：Bowtie, BWA, STAR

**2. 生物信息学数据库工具**
- 探索 UCSC Genome Browser 和 Ensembl 的使用
- 学习如何从数据库中提取相关信息（如基因结构、变异数据）
- 学习如何使用 BLAST 进行序列比对

**3. 实践任务**
- 下载 RNA-seq 数据，使用工具进行数据清洗和比对
- 使用 BLAST 比对两段 DNA 序列

---
### 高级分析 & 实战项目

**1. 差异表达分析**
- 学习 RNA-seq 数据分析流程
- 学习如何使用 DESeq2 或 edgeR 进行差异基因表达分析
- 掌握 p 值、校正值、fold change 等统计概念

**2. 蛋白质组学与功能注释**
- 了解蛋白质组学基础及常用工具（如：InterPro、Pfam）
- 掌握基因本体（Gene Ontology, GO）及其在功能注释中的应用
- 学习使用 KEGG 进行代谢通路分析

**3. 实战项目**
- 完成一个 RNA-seq 数据分析的项目，从原始数据到结果解释
- 总结项目报告，包含数据处理流程、分析结果和可视化图表
