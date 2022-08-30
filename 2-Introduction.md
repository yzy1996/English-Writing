本文介绍如何写作 introduction

[toc]

> 出处忘记了:sweat_smile:

introduction重点在于说明自己的研究思路，很多人搞了半辈子的研究，到头来写文章时忘记的研究的初衷。好的套路就是把读者当成你的同行，讲清楚研究工作的来龙去脉。下面分三步说明。第一步，你发现有什么问题，这篇论文要解决什么问题？实际工作中存在什么问题。不要扯太远，尽量不要超过3句话。这第一步可能就把很多人难住了。尼玛课题都是老板定的，有个毛意义呀，不知道，就瞎扯一个。如果实在不清楚，说明占有的文献还不够，还得多读读。第二步，基于本人前期的研究基础，或者受前人的思路激发，我想出了方法来解决第一步的问题。这一步是关键。很多人的introduction根本没这些内容。完全就是一副“这玩意以前没人搞过，我用一种方法来试试”的态度。这一步为什么非常关键？因为同样的问题，如果很重要，很有意义的问题，肯定很多人想到了，为什么别人没做，而你想做？只有2种可能，我这里有研究基础，别人做不了，我能做。还有一种可能，这里面有难点，我也是受哪篇哪篇文章的激发，才想起解决方法，所以我才顺便试试，结果你看，一搞，结果挺好，所以来跟你们报告一下。这里面就需要吹吹牛逼了，可以弹压一下前人的工作，鼓吹一下自己的工作。第三步，前面牛吹了，后面当然要简单介绍一下结果，谈点意义，勾引读者往下看研究方法。论文的重点在于论，要讲清楚研究思路，而不是搞成实验报告。



## 点睛之笔

- 可以用一些疑问句来引出论文的核心

  > Our work aims to answer the following question
  >
  > Can this been done in an unsupervised manner
  
  



## 说什么问题是重要的

The main drawback of such models

现在新领域的方法远远落后于过去某一领域的技术  lagged far behind



## 说什么技术已经发展了，也是我们关注的base

Abundant research has been conducted on xx 

unmet needs of  不满足的需求

lots of nuances（细微差别） and ideas have contributed to the state-of-theart recently

a theoretical understanding of GANs is an on-going research topic

remarkable research efforts

A thread of recent research/studies

A prominent difficulty



说什么东西很好，很火热

has enjoyed tremendous growth and exhibited a wealth of development at both the conceptual and application levels

in recent years, with the vigorous development of xx yy has attracted more and more interest in both zz 



大背景介绍

> 存在什么问题，而要使用xx方法



什么技术 hamper the applicability of the method. （妨碍了他的广泛应用）



概述xx是什么，是用来干什么的



发展很久了但应用到什么领域还是新的

xx has found numerous applications in xx field, particularly in the last two decade

有潜力做什么



Successful applications have been demonstrated in areas spanning xx, xx



多提一提 in this paper, we focus on xx

in contrast, previous work ...

In this work we demonstrate that



## 说现有方法的缺点

One prominent hurdle (突出的障碍) of the existing method is xx

The image quality still lags far behind (落后) other methods

an inevitable problem 不可避免的问题

We argue that it is more desirable to xx

A body of works 一批工作



address xx and xx



里面可以用的句子

> xx has a long history [1,2,3]
>



is an important but less explored problem

## 我们解决了

To alleviate these issues, we design techniques 　

To compensate for xx 为了缓解

To overcome aforementioned limitations  we present a new

bridges the gap between xx and yy

To tackle the problem, we extend

the crux of xxx 关键点

We mitigate problem 

> 我们缓解这个问题通过什么方法：



对比类似的工作

In parallel work


in addition to achiieving more compelling and complicated xx,

we incorporate xx into our model

先笼统地说一下方法，然后具体地 specifically, 

xx circumvent a fundamental difficulty 避开了一个很难的问题



(do sth) has two severe difficulties: 

its effective integration with xx



Our experiments show that the novel method outperforms previous work, where we compare to (i)
current video generation models, which can only be trained on multiple video samples, and thus
benefit from an unfair advantage, (ii) recent image generation methods trained on a single image
sample, and (iii) the extension of these methods to video, which, does not replicate their success in
image generation. Finally, we consider the effect of different components of our method, such as the
number of patch-VAE levels, the receptive field, and updating networks only at specific layers.

To summarize, our work provides the following novelties: (1) a new patch-VAE formulation for a
single sample generation, which encourages large diversity and avoids mode collapse, (2) a novel
patch VAE-GAN method, which generates diverse and high quality samples, and (3) the first method
capable of unconditional video generation from a single video sample.



描述方法涵盖了很多方面，子问题

a widely-used technique for solving many knids of vision and graphics tasks **ranging from** view synthesis, **to** re-lighting, **to** pose and shape estimation, **to** 3D-aware image synthesis and editing.



Qualitative andquantitative results show the superiority of our approach overexisting methods in preserving identity as well as generatingrealistic high quality images.



最后一段是给自己方法的分类，按照自己平时的归纳习惯，

Our work can be classified as a category-specific 3D aware neural novel view synthesis method.

Our EigenGAN can be categorized into representation learning as well as architecture design for GANs.



what extent has thisinability of convolution persisted insidiously inside other tasks



To circumvent xx 别人的工作为了回避

counteract xx 缺点 为了抵消什么缺点

adversely affects 不利地影响



concretely/crucially/Specifically, we propose a xx model with yy.

As a result, our approach inherits xx 好处 and yy 好处, seperated from zz 不好的方法, which 具体不好的点。



## 如果是和别人工作的嫁接，组合式的论文 

xx marries (y method) with [z method]

our framework combines the benefits of xx with those of yy, enabling zz 



## 本文价值

可以是分析了多种方法，比较了好坏

例子: We analyse and investigate multiple design choices for representing neural implicit surfaces, ranging form monolithic MLP models over single-grid to multi-resolution grid representations.

The experiments in the paper would be more compelling



强调虽然本文中我们只用在了某个数据集上，但这个方法可以适用于很多领域

while this study presented in this paper focus on xx, is also applicable to other domains



## 关于简写表示

for ease of notation, we will simply write the xxx

For convenience, we follow the convention for xx by letting subscripts denote absolute yy

For clarity, we omit z from hereon forward

we dropped the vector arrows for ease of notation).

for more details, we refer readers to sb

we assume a fixed, and remove the subscript xx notation to simplify notation.

which we will call a “diffusion model” for brevity





## 结尾

In summary, our main technical contributions are 

Overall, the main contributions and benefits of our algorithm are summarized as follows:

Code and models will be provided upon acceptance



In this chapter, … Thereafter, … Then …
