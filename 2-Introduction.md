# Introduction

<details><summary>出处忘记了:sweat_smile:，与大家共勉。</summary>
<p>

introduction重点在于说明自己的研究思路，很多人搞了半辈子的研究，到头来写文章时忘记的研究的初衷。好的套路就是把读者当成你的同行，讲清楚研究工作的来龙去脉。下面分三步说明。第一步，你发现有什么问题，这篇论文要解决什么问题？实际工作中存在什么问题。不要扯太远，尽量不要超过3句话。这第一步可能就把很多人难住了。尼玛课题都是老板定的，有个毛意义呀，不知道，就瞎扯一个。如果实在不清楚，说明占有的文献还不够，还得多读读。第二步，基于本人前期的研究基础，或者受前人的思路激发，我想出了方法来解决第一步的问题。这一步是关键。很多人的introduction根本没这些内容。完全就是一副“这玩意以前没人搞过，我用一种方法来试试”的态度。这一步为什么非常关键？因为同样的问题，如果很重要，很有意义的问题，肯定很多人想到了，为什么别人没做，而你想做？只有2种可能，我这里有研究基础，别人做不了，我能做。还有一种可能，这里面有难点，我也是受哪篇哪篇文章的激发，才想起解决方法，所以我才顺便试试，结果你看，一搞，结果挺好，所以来跟你们报告一下。这里面就需要吹吹牛逼了，可以弹压一下前人的工作，鼓吹一下自己的工作。第三步，前面牛吹了，后面当然要简单介绍一下结果，谈点意义，勾引读者往下看研究方法。论文的重点在于论，要讲清楚研究思路，而不是搞成实验报告。

</p>
</details>


接下来展示的内容，首先是按大概三段式分，当然了一大段也可以拆成几个小段，不用拘泥于此。

然后即是每一部分重点写什么，提供了多个样例，灵活组合吧。



## 第一段

> 引出你研究工作的背景和价值



| 一个大红大热的方向（吸引了很多关注），主要思路是怎么做呢，有什么优点 |
| :----------------------------------------------------------- |
| **An explosively growing line of research on** xx **studies a new paradigm of** yy: [details of the paradigm] |
| xx **has enjoyed tremendous growth** and **exhibited a wealth of development** at both the conceptual and application levels |
| In recent years, with the **vigorous development** of xx yy **has attracted more and more interest in** both zz |
| **Successful applications** have been demonstrated in areas spanning xx, xx |
| xx has found **numerous applications** in xx field, particularly in the last two decade |
| a theoretical understanding of GANs **is an on-going research topic** |
| **Abundant research** has been conducted on xx               |
| 描述方法涵盖了很多方面，子问题<br/>a widely-used technique for solving many kinds of vision and graphics tasks **ranging from** view synthesis, **to** re-lighting, **to** pose and shape estimation, **to** 3D-aware image synthesis and editing. |



| 直接从技术名称开始，介绍它的优点｜应用价值，然后第二段再转到它的缺点 |
| :----------------------------------------------------------- |
| GANs **excel at** synthesizing photo-realistic images.  Their conditional extension, conditional GANs, allows controllable image synthesis and **enables many computer vision and graphics applications** such xxx |



| 交代你所解决的任务                  |
| :---------------------------------- |
| We consider the task of ...         |
| A key challenge in this task is ... |



## 第二段

> 阐述存在的问题（也是你要研究的），然后现有方法是怎么来做的



| 说现有方法的不好之处                                         |
| :----------------------------------------------------------- |
| The main drawback of such models                             |
| lagged far behind 现在新领域的方法远远落后于过去某一领域的技术 |
| A body of works 一批工作 / Prior attempts ..                 |
| Several follow-up studies propose to ...                     |
| 什么技术 hamper the applicability of the method. （妨碍了他的广泛应用） |
| A prominent difficulty                                       |
| unmet needs of  不满足的需求                                 |
| One prominent hurdle (突出的障碍) of the existing method is xx |
| xx has a long history [ref 1,2,3]                            |
| We argue that it is more desirable to xx                     |
| an inevitable problem 不可避免的问题 has two severe difficulties: |
| The image quality still lags far behind (落后) other methods |



| 现存方法大致可以分为几类                                     |
| :----------------------------------------------------------- |
| **Existing approaches to address this problem can be roughly divided into three categories**. **The first category** of works utilizes xx. **The second line** of works adopt xx. |
| in contrast, previous work ... /  In parallel work           |
| A thread of recent research/studies                          |



| 虽然这些方法怎么怎么样了，但还是没能好好解决                 |
| :----------------------------------------------------------- |
| While these methods compensate .. by .., this task remains challenging. |
| xx is an important but less explored problem                 |
| **This serves as a major bottleneck**, **as** multiple-view data **is hard to acquire**. |
| xx circumvent a fundamental difficulty 避开了一个很难的问题  |
| To circumvent xx 别人的工作为了回避                          |
| counteract xx 为了抵消什么缺点                               |



| 发展很久了但应用到什么领域还是新的 \| 这个问题还没有被深入研究，同时很具有研究价值 |
| :----------------------------------------------------------- |
| Despite its potential to serve as a powerful method to xx, this problem remains much less explored. |
| Despite its practical importance, up to our knowledge, we are the first to address this unexplored problem. |
| Existing approaches can not well have not been well studied  |
| To our knowledge, this is the first study in which the has not been proposed yet |





## 第三段

> 讲自己的方法；先笼统地说一下方法，然后具体地 specifically



| 承上启下引入                                                 |
| :----------------------------------------------------------- |
| To address the above problem, we propose xx                  |
| To answer this question, we conduct a comprehensive empirical study by xx |



| 我们提出了                                                   |
| :----------------------------------------------------------- |
| In this work, we propose a new approach, [Name]              |
| We propose to exploit                                        |
| concretely/crucially/Specifically… , we propose a xx model .. |
| In this work we demonstrate that                             |



| 可以用到的词汇                                               |
| :----------------------------------------------------------- |
| To alleviate these issues, we design techniques              |
| To compensate for xx 为了缓解                                |
| To overcome aforementioned limitations  we present a new     |
| bridges the gap between xx and yy                            |
| To tackle the problem, we extend                             |
| the crux of xxx 关键点                                       |
| We mitigate problem                                          |
| This model has several benefits,                             |
| in addition to achieving more compelling and complicated xx, |



## 最后一段

> 说本文价值，夸就完事了

| 本文价值，可以是分析了多种方法，比较了好坏                   |
| :----------------------------------------------------------- |
| We analyse and investigate multiple design choices for representing neural implicit surfaces, ranging form monolithic MLP models over single-grid to multi-resolution grid representations. |
| The experiments in the paper would be more compelling        |
| 强调虽然本文中我们只用在了某个数据集上，但这个方法可以适用于很多领域<br/>while this study presented in this paper focus on xx, is also applicable to other domains |
| As a result, our approach inherits xx 好处 and yy 好处, seperated from zz 不好的方法, which 具体不好的点。 |



| 在很多数据集上进行了测试                                     |
| :----------------------------------------------------------- |
| We empirically demonstrate the advantage of xx over existing approaches on a variety of xx tasks: |
| We evaluate our method on both tasks of 2D image synthesis and 3D-aware image synthesis. On a wide range of datasets including [xx data], [model name] exhibits consistent improvements over the baselines. |
| Qualitative and quantitative results show the superiority of our approach over existing methods in preserving identity as well as generating realistic high quality images. |
| We validate our approach through quantitative and qualitative results and demonstrate that our method achieves state-of-the-art results for the task of StyleGAN inversion and real image editing. |
| Our experiments show that the novel method outperforms previous work |



## 结尾

| 给出贡献列表                                                 |
| :----------------------------------------------------------- |
| In summary, our main technical contributions are             |
| Overall, the main contributions and benefits of our algorithm are summarized as follows: |
| Our proposed framework has several theoretical and practical contributions: |
| To summarize, our work provides the following novelties:     |

| 有关公开代码                                      |
| :------------------------------------------------ |
| Code and models will be provided upon acceptance. |



## 点睛之笔

| 可以用一些疑问句来引出论文的核心                             |
| :----------------------------------------------------------- |
| Our work aims to answer the following question / Can this been done in an unsupervised manner |
| **The research question we are addressing in this work is, whether** an event stream from a DVS moving around the scene is sufﬁcient to reconstruct a 3D representation of a static scene, e.g., NeRF. |
| What extent has this inability of convolution persisted insidiously inside other tasks |
| Is it possible to reconstruct the 3D shape of a single 2D image by exploiting the 3D-alike image manipulation effects produced by GANs? |
| It naturally raises a question: does a discriminator with a fixed capacity meet the demand of such a dynamic training environment? |



| 以及多提一提论文的核心        |
| :---------------------------- |
| In this paper, we focus on xx |



| 给出自己方法的定位                                           |
| :----------------------------------------------------------- |
| Our work can be classified as a category-specific 3D aware neural novel view synthesis method. |
| Our [model name] can be categorized into representation learning as well as architecture design for GANs. |





## 如果是和别人工作的嫁接，组合式的论文 

xx marries (y method) with [z method]

our framework combines the benefits of xx with those of yy, enabling zz 

we incorporate xx into our model

its effective integration with xx

| 方法不是原创的，但我拿来用到了一个新的领域                   |
| ------------------------------------------------------------ |
| Tuning the generator to accommodate a given input image (描述你的方法) is not new~\cite{}, we first introduce this approach to the field of StyleGAN-based editing. |
| (最好还要写出我不是生硬地套过来，是因地制宜的，或者效果更好，达到了我的目的) In contrast to the aforementioned work, our technique maintains the unique editing capabilities, while preserving identity accurately. |





## 有时候为了节省篇幅，会省略一些东西，就需要加以说明

for ease of notation, we will simply write the xxx

For convenience, we follow the convention for xx by letting subscripts denote absolute yy

For clarity, we omit z from hereon forward

we dropped the vector arrows for ease of notation).

for more details, we refer readers to sb

we assume a fixed, and remove the subscript xx notation to simplify notation.

which we will call a “diffusion model” for brevity



Detailed theoretical analysis will be elaborated later.



