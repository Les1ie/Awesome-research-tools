---
title: "深度学习"
date: 2024-07-01T14:47:04+08:00
draft: false
weight: 103
summary: 深度学习相关工具
---

### 通用

- [pytorch-lightning](https://www.pytorchlightning.ai/)：更为高级的 Pytorch 编程接口，能编写出更高质量、更简洁的 PyTorch 代码。

### 日志

- [TensorBoard](https://www.tensorflow.org/tensorboard)：TensorBoard 集成的日志可视化工具，也可以单独安装并搭配 PyTorch 使用。与 PyTorch-Lightning、Ultralytics 等均有集成。基于 Python。
- [Comet](https://www.comet.ml/site/)：日志可视化工具，可用于训练到生产全过程的管理、可视化和优化。基于 Python。对于一些不方便开放 Tensorbard 端口的服务器可以尝试这个工具，将日志同步到 Comet 账号上，实现外网实时访问和分享。
- [ClearML](https://www.clear.ml/)：开源的日志可视化工具，便于分享，更适合团队使用。基于 Python。

### 优化

- [Optuna](https://optuna.org)：超参数优化框架，用于自动化超参数搜索，不依赖于具体使用的深度学习框架。
- [Ax](https://ax.dev/)：基于 Pytorch 的超参数搜索框架，可简单绘制超参数分析。

### NLP

- [transformers](https://huggingface.co/docs/transformers/index)：Hugging Face 出品，可直接调用预训练的 Transformers、BERT 等模型，包含了 NLP 相关的完整 Pipeline（数据集与处理、模型搭建与优化、训练与评估），基于 PyTorch。
- [SentenceTransformers](https://www.sbert.net)：Python 库，可以直接获得句子级嵌入，基于 PyTorch。
- [fairseq](https://github.com/pytorch/fairseq)：PyTorch 团队开发的 seq2seq 库，实现了较多主流模型，可以用于机器翻译、摘要等任务训练。

### GNN

- [DGL](https://www.dgl.ai/)：深度图神经网络库，支持异构图，支持 TensorFlow 和 PyTorch，实现了 GCN、GAT 等经典模型以及一些新论文的模型，自带部分经典图数据集（如 Karate Club dataset 等，使用时自动下载）。拥有中文用户指南。
- [pytorch_geometric](https://www.pyg.org)、[tf_geometric](https://github.com/CrawlScript/tf_geometric)：相同风格的深度图神经网络库，支持异构图，分别支持 PyTorch 和 TensorFlow，实现了GCN、GAT 等经典模型以及一些新论文的模型，自带部分经典图数据集（如 Karate Club dataset 等，使用时自动下载）。
- [PyGCL](https://github.com/GraphCL/PyGCL)：图对比学习框架
- [Neo4J](https://neo4j.com/)：图数据库，一个数据库实例就是一张大图，社区免费版只支持单个数据库实例。支持异构点和边，高效实现了各种经典的图算法（遍历、迭代、生成、查找、计算等），同时也支持经典的图机器学习算法（需安装 GDS 拓展包），拥有配套的可视化工具（Web端和客户端）。可用于存储大量的图数据、进行基础计算与分析、优化模型 IO。

### CV

- [Ultralytics](https://ultralytics.com/)：YOLOv8 的开发团队与论文作者，可直接调用预训练的 YOLOv5、YOLOv8 等模型，包含了 CV 相关的完整 Pipeline（数据集与处理、模型搭建与优化、训练与评估），基于 PyTorch。
- [Open MMLab](https://openmmlab.com/codebase)：开放 CV 团队/社区，提供了通用的训练框架、模型、接口、工具箱，涉及 CV 研究中的 FewShot（少样本）、Flow（光流）、3D 等等领域。
