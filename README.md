# 从公式学懂神经网络

一份按数学依赖顺序组织的中文神经网络学习路线。目标不是只记住模型名称，而是能够看懂公式、检查张量形状、手算前向传播，并理解梯度如何训练参数。

## 当前学习进度

> 最后更新：2026-07-17

- 当前章节：**第 01 章 · 向量、矩阵与张量**
- 已完成：**1.1 标量、向量、形状与索引**
- 下一节：**1.2 向量运算与几何意义**
- 总进度：1 / 133 个小节

[打开第 01 章笔记与后续提示词](CHAPTER_01.md) · [查看完整进度](PROGRESS.md) · [查看所有章节提示词](COURSE.md)

## 使用方法

1. 在下方路线中找到下一个未完成章节。
2. 打开 [完整课程与提示词](COURSE.md)，复制对应章节的提示词。
3. 把提示词发给 Codex 或其他支持公式的 AI。
4. 每次只学习一个小节；完成练习后再说“继续”。
5. 在 [PROGRESS.md](PROGRESS.md) 中把对应复选框从 `[ ]` 改成 `[x]`。

统一教学顺序：

```text
直觉问题 → 符号表 → 假设 → 公式逐步推导 → 张量形状
→ 手算数值例子 → 算法/伪代码 → 动画或交互图
→ 常见错误 → 3 道递进练习 → 小结
```

## 完整学习路线

| 阶段 | 章节 | 状态 |
|---|---|---|
| A · 数学地基 | [01 · 向量、矩阵与张量](CHAPTER_01.md) | 🟡 进行中 |
| A · 数学地基 | [02 · 导数、偏导、梯度与链式法则](COURSE.md#chapter-02) | ⬜ 未开始 |
| A · 数学地基 | [03 · 概率、最大似然与信息论](COURSE.md#chapter-03) | ⬜ 未开始 |
| A · 数学地基 | [04 · 线性回归、逻辑回归与感知机](COURSE.md#chapter-04) | ⬜ 未开始 |
| B · 前馈核心 | [05 · 神经元、激活函数与损失函数](COURSE.md#chapter-05) | ⬜ 未开始 |
| B · 前馈核心 | [06 · MLP 与前向传播](COURSE.md#chapter-06) | ⬜ 未开始 |
| B · 前馈核心 | [07 · 计算图与反向传播 BP](COURSE.md#chapter-07) | ⬜ 未开始 |
| B · 前馈核心 | [08 · 梯度下降、优化器与学习率](COURSE.md#chapter-08) | ⬜ 未开始 |
| B · 前馈核心 | [09 · 初始化、正则化与归一化](COURSE.md#chapter-09) | ⬜ 未开始 |
| B · 前馈核心 | [10 · 残差连接与深层网络训练](COURSE.md#chapter-10) | ⬜ 未开始 |
| C · 空间与序列 | [11 · CNN：卷积、池化与感受野](COURSE.md#chapter-11) | ⬜ 未开始 |
| C · 空间与序列 | [12 · RNN 与时间展开](COURSE.md#chapter-12) | ⬜ 未开始 |
| C · 空间与序列 | [13 · BPTT 与梯度消失/爆炸](COURSE.md#chapter-13) | ⬜ 未开始 |
| C · 空间与序列 | [14 · LSTM 与 GRU](COURSE.md#chapter-14) | ⬜ 未开始 |
| D · Transformer | [15 · 注意力机制与 Q/K/V](COURSE.md#chapter-15) | ⬜ 未开始 |
| D · Transformer | [16 · 多头注意力与位置编码](COURSE.md#chapter-16) | ⬜ 未开始 |
| D · Transformer | [17 · Transformer Encoder/Decoder](COURSE.md#chapter-17) | ⬜ 未开始 |
| D · Transformer | [18 · BERT、GPT 与训练目标](COURSE.md#chapter-18) | ⬜ 未开始 |
| E · 进阶专题 | [19 · Autoencoder 与 VAE](COURSE.md#chapter-19) | ⬜ 未开始 |
| E · 进阶专题 | [20 · GAN 与 Diffusion](COURSE.md#chapter-20) | ⬜ 未开始 |
| E · 进阶专题 | [21 · 图神经网络 GNN](COURSE.md#chapter-21) | ⬜ 未开始 |
| E · 进阶专题 | [22 · 深度强化学习 DQN/PPO](COURSE.md#chapter-22) | ⬜ 未开始 |

## 图片中四类模型的位置

- **MLP**：第 06–10 章
- **RNN**：第 12–13 章
- **LSTM**：第 14 章
- **Transformer**：第 15–18 章

## 学习原则

- 新符号第一次出现时必须定义。
- 每个矩阵乘法都写出输入、参数和输出形状。
- 公式推导不省略关键等号。
- 每章至少完成一个手算例子和三道练习。
- 没有理解当前小节前，不急着进入下一个模型。
