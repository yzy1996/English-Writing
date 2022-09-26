# Abstract



## 开头句

> 你为什么要提出这个方法？一般说过去的方法存在什么问题



通常采用如下方式

- 介绍背景，阐述问题，然后我们提出了一个新方法。
- 什么方法对TaskA有效，我们想应用到TaskB。
- （开门见山）我们提出了一个新方法，为什么要提出呢？




| xx问题正面临一个困境，要么<质量好>，要么<可编辑性强>，我们提出的方法正好能同时实现。 |
| :----------------------------------------------------------- |
| **Existing** 3D-aware facial generation methods **face a dilemma** in quality **versus** editability: they either generate editable results in low resolution, or high quality ones with no editing flexibility. |
| In this work, we propose a new approach that **brings the best of both worlds together**. |



| 先说xx是最近一个大红大热的方向，简要写一下它的原理，它的好处；然而，现有方法还存在一些问题；为了解决它，我们提出了… |
| :------------------------------------------------------------ |
| xx **is a promisingnew avenue of** …, xx **ensure many advantages over** …; **However, the current approach is dufficult to** …; **To address this issue, we propose** … |
| Recently, xx **has achieved great empirical success**, especially …; **However, a key problem** of xx is that …; **It's necessary to** … |



| 某技术或者领域在实现TaskA上已经做得很好了，但TaskB还不能很好解决 |
| :------------------------------------------------------------ |
| **While** generating realistic images **is no longer a difficult task**, producing the corresponding 3D structure such that they can be rendered from different views **is non-trivial**. |
| Neural Radiance Fields (NeRF) **have recently demonstrated** photo- realistic results **for the task of** novel view synthesis. In this paper, we propose to **apply** novel view synthesis **to** the robot relocalization problem: [details] |



| 第一句直接说我们的名称，做了什么                             |
| :------------------------------------------------------------ |
| **We present a method for** learning a generative 3D model based on nerf, trained solely from data with only single views of each object. |



## 中间句

> 描述你的方法

| 前面描述存在什么问题，在这里我们希望解决他                   |
| :----------------------------------------------------------- |
| To this end （为了这个目的）, this paper proposes xx with three distinct novelties. |



| 直接说我们提出了什么算法，它有什么用；它的核心是什么  |
| :---------------------------------------------------- |
| In this work, we present/ xxx algorithm, which can xx |
| A key part of our approach is to xx                   |
| The key to our approach is to utilize xx              |



| 拆分成一个个部分的写法                                       |
| :----------------------------------------------------------- |
| Our system consists of three major components: (1) a xx model that...; (2) a xx approach that...; (3) a xx |
| Specifically, our model/system first adapts. Then, we Finally, |



| 补充一句，我们的方法没有牺牲之前好的性质，反正增加了什么     |
| :----------------------------------------------------------- |
| we show that our method does not sacrifice the, improving the xx |



## 结尾句

> 描述你的实验结果多好多好，有点卖弄 (show off) 的意味在里面。

| 夸就完事了                                                   |
| :----------------------------------------------------------- |
| Both **quantitative** and **qualitative** results show that our method **reaches the state-of-the-art** in terms of photorealism, faithfulness and efficiency. |
| We show **promising result** on xx                           |
| **Quantitative and qualitative evaluation** on both controlled and in-the-wild databases demonstrate the superiority of DR-GAN **over the state of the art**. |
| **Experiments show that** our proposed framework **significantly outperforms SOTA methods** on xx dataset |
| **In contrast to existing works** on neural 3D scene representation learning, this paper approaches the problem from a new perspective |
| **Extensive experiments demonstrate that** our framework can achieve ideal editing results not only on synthetic data, but also on realscenes captured by users. |
| **We empirically demonstrate that** xx achieve a much smaller loss than xx. |



## 直接的例子

### 融合式

While NeRF has shown great success for neural reconstruction and rendering, its limited MLP capacity and long per-scene optimization times make it challenging to model large-scale indoor scenes. In contrast, classical 3D reconstruction methods can handle large-scale scenes but do not produce realistic renderings. We propose NeRFusion, a method that combines the advantages of NeRF and TSDF-based fusion techniques to achieve efficient large-scale reconstruction and photo-realistic rendering.

> 先说一个**新技术**很成功，但依旧存在一些问题；(in contrast) **传统方法**可以解决这些问题，但也有一些问题；因此提出一个新方法，融合两种，实现了xxx 
