# Learn Diffusion

# 图像生成的基本原理学习教程

本文档原本是我的图像生成学习笔记，但是我将其写成教程形式，希望可以帮到更多人。

本教程按照专题展开。第一个专题是图像生成主线，后续专题会按照各个领域独立地展开。

欢迎任何人阅读。内容包括 VAE, NCSN, DDIM, Score-based Model, Flow Matching, VAR, PixelDiT 以及更多。

欢迎在 Issues 区为我提出建议。

阅读本教程，希望你已经掌握基本的机器学习内容，如梯度下降反向传播等等，以及基本的概率论与多元微积分知识，如期望的计算。

我们开始吧 ：）

# 前言

[前言 Introduction](Introduction.ipynb)

# 图像生成的主要方法

[第一章 Score Matching 中的 DSM 与 NCSN](Chapter1_01.ipynb)

[第二章 VAE 与 Denoising Diffusion Probabilistic Models](Chapter1_02.ipynb)

[第三章 Denoising Diffusion Implict Models](Chapter1_03.ipynb)

[第四章 Diffusion 与 Score Matching 的统一](Chapter1_04.ipynb)

[第五章 流与 Flow Matching](Chapter1_05.ipynb)

[第六章 神经网络与 Diffusion Transformers](Chapter1_06.ipynb)

[第七章 Flow Matching 配合 DiT 的实现与改进](Chapter1_07.ipynb)

[第八章 Consistency Models 与加速生成](Chapter1_08.ipynb)

[第九章 Visual Autoregressive Models](Chapter1_09.ipynb)

[第十章 回归像素空间的思考与 PixelDiT](Chapter1_10.ipynb)

# 少步生成专题

[第一章 Unified Continuous Generative Models](Chapter2_01.ipynb)

[第二章 一步生成的 Meanflow](Chapter2_02.ipynb)

[第三章 Improved Meanflow 与 Euler Meanflow](Chapter2_03.ipynb)

[第四章 渐进展开的 Shortcut Models](Chapter2_04.ipynb)

[第五章 理解少步生成与 Alphaflow](Chapter2_05.ipynb)

# 数据集蒸馏专题

[第一章 Dataset Distillation 与双层优化](Chapter3_01.ipynb)

[第二章 Gradient Matching](Chapter3_02.ipynb)

# 附录

[附录 证明与说明](Appendix.ipynb)
