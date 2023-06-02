# Review-MuseGAN

MuseGAN: Multi-track Sequential Generative Adversarial Networks for Symbolic Music Generation and Accompaniment.

MuseGAN：用于符号音乐生成和伴奏的多轨序列生成对抗网络。

## Abstract

生成音乐与生成图像和视频有一些显著的区别。首先，音乐是一种时间上的艺术，需要一个时间模型。其次，音乐通常由多个乐器/轨道组成，具有自己的时间动态，但集体地它们相互依赖地随着时间展开。最后，在复调音乐中，音符通常被分组成和弦、琶音或旋律，因此引入音符的时间顺序并不自然适合。在本文中，我们提出了三个基于生成对抗网络（GANs）框架的符号多轨音乐生成模型。这三个模型在基本假设和相应的网络架构上存在差异，分别称为jamming模型、composer模型和hybrid模型。我们使用超过十万小节的摇滚音乐数据集对所提出的模型进行了训练，并将其用于生成五个轨道的钢琴卷帘：低音、鼓、吉他、钢琴和弦乐。除了主观用户研究外，我们还提出了一些轨道内和轨道间客观度量指标来评估生成结果。我们展示了我们的模型可以生成四小节连贯的音乐（即没有人类输入）。我们还将我们的模型扩展到人工智能协作音乐生成：给定一个由人类创作的特定轨道，我们可以生成四个附加轨道来伴奏。所有代码、数据集和渲染音频样本均可在 https://salu133445.github.io/musegan/ 上获得。

## Paper

### English Original Version

EN-MuseGAN Multi-track Sequential Generative Adversarial Networks for Symbolic Music Generation and Accompaniment.pdf [[Link](https://github.com/prodbyido/Review-MuseGAN/blob/main/EN-MuseGAN%20Multi-track%20Sequential%20Generative%20Adversarial%20Networks%20for%20Symbolic%20Music%20Generation%20and%20Accompaniment.pdf)]

### Simplified Chinese Translation Version

CN-MuseGAN Multi-track Sequential Generative Adversarial Networks for Symbolic Music Generation and Accompaniment.pdf [[Link](https://github.com/prodbyido/Review-MuseGAN/blob/main/CN-MuseGAN%20Multi-track%20Sequential%20Generative%20Adversarial%20Networks%20for%20Symbolic%20Music%20Generation%20and%20Accompaniment.pdf)]

## Goals
使用带有卷积神经网络的GAN生成以钢琴卷帘格式为基础的多轨流行音乐。

