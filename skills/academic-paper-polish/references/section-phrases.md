# Section-Specific Phrase Templates

Sentence templates drawn from real published papers, organized by paper section.

---

## Abstract

### Naming the Model
- `We propose an algorithm termed as [Name], for [task].`
- `We present [task] with templates, dubbed [Name].`
- `Code and models are available at [URL].`

### Opening Sentences — Describe the Problem
- `Existing [X] methods face a dilemma in [A] versus [B]: they either [downside1] or [downside2]. In this work, we propose a new approach that brings the best of both worlds together.`
- `[X] is a promising new avenue of..., ensuring many advantages over...; However, the current approach is difficult to...; To address this issue, we propose...`
- `Recently, [X] has achieved great empirical success, especially...; However, a key problem of [X] is that...; It's necessary to...`
- `Despite the rapid advancement of [X], existing approaches either are limited to [A] or...`
- `We are witnessing an explosion of [X] in [field]. Their applicability has recently expanded beyond tasks such as [Y]. However, existing methods... We introduce a new method that enables [Z].`
- `While [A] is no longer a difficult task, producing [B] is non-trivial.`
- `However, such advancements have not been fully migrated to the community of [X].`

### Middle Sentences — Describe Your Method
- `To this end, this paper proposes [X] with three distinct novelties.`
- `In this work, we present [algorithm], which can [capability].`
- `A key part of our approach is to [X].`
- `The key to our approach is to utilize [X].`
- `Our system consists of three major components: (1) a [X] model that...; (2) a [Y] approach that...; (3) a [Z].`
- `Specifically, our model first [step1]. Then, we [step2]. Finally, [step3].`
- `We show that our method does not sacrifice [property], while improving [X].`

### Closing Sentences — Show Results
- `Both quantitative and qualitative results show that our method reaches the state-of-the-art in terms of [metric1], [metric2] and [metric3].`
- `Experiments show that our proposed framework significantly outperforms SOTA methods on [dataset].`
- `Extensive experiments demonstrate that our framework can achieve [X] not only on synthetic data, but also on real scenes.`
- `We empirically demonstrate that [X] achieves a much smaller loss than [Y].`
- `Experiments on [X] tasks conducted on a range of datasets substantiate the generalizability of our model as well as its substantial improvement over the baselines.`

---

## Introduction

### Paragraph 1 — Background & Motivation
- `An explosively growing line of research on [X] studies a new paradigm of [Y]: [details].`
- `[X] has enjoyed tremendous growth and exhibited a wealth of development at both the conceptual and application levels.`
- `In recent years, with the vigorous development of [X], [Y] has attracted more and more interest.`
- `Successful applications have been demonstrated in areas spanning [A], [B].`
- `[X] has found numerous applications in [field], particularly in the last two decades.`
- `[X] have become prevalent in recent years.`
- `GANs excel at synthesizing photo-realistic images. Their conditional extension... enables many computer vision applications.`
- `We consider the task of... A key challenge in this task is...`

### Paragraph 2 — Limitations of Existing Work
- `The main drawback of such models is...`
- `A body of works / Prior attempts...`
- `Several follow-up studies propose to...`
- `[X] hamper the applicability of the method.`
- `A prominent difficulty / One prominent hurdle of the existing method is [X].`
- `unmet needs of [X]`
- `[X] has a long history [refs].`
- `We argue that it is more desirable to [X].`
- `an inevitable problem has two severe difficulties:`
- `The image quality still lags far behind other methods.`
- `in contrast, previous work...`
- `several attempts are being made to...`
- `lagged far behind` (new field's methods are far behind an established one)

### Paragraph 3 — Your Solution
- `To address this, we propose [method].`
- `Motivated by this observation, we introduce...`
- `In this paper, we present [method] to tackle [problem].`
- `[X] addresses this issue by integrating [A] into [B] and enabling [C].`

### Paragraph 4 — Contributions
- `In summary, our contributions are:`
- `Our key contributions are as follows:`

### Other Useful Lines
- `A theoretical understanding of [X] is an on-going research topic.`
- `Abundant research has been conducted on [X].`
- `a widely-used technique for solving many kinds of vision and graphics tasks ranging from [A], to [B], to [C].`

---

## Related Work

### Categorizing Related Work
- `The most related to our work can be divided into two categories: A and B. The first focuses on...; The second...`
- `Some using full-supervision in the form of... others find meaningful directions in a self-supervised fashion, and, finally, recent works present unsupervised methods.`
- `We review recent advances in [X], as well as [Y].`
- `[X] are related to many other bodies of work.`
- `Only very few works have explored [X] in the context of [Y].`

### Describing a Sub-area
- `Our method builds upon this line of research.`
- `Its formulation has been adapted for improving A, dealing with B, removing C, and handling D. Although there have been some early attempts in E, the usage of F has never been explored for G. This work addresses this gap.`
- `More specifically, [X] uses supervision in the form of... [Y] performs eigenvector decomposition...`

### Concurrent Work
- `The concurrently developed [X] and [Y] demonstrate impressive [quality]. The central distinction between these and ours is that while [X] and [Y] operate primarily in [space], with less emphasis on [Z], our method operates primarily in [space2].`

---

## Method

### Introducing the Framework
- `We present [Name], a [description] that...`
- `Fig. X illustrates an overview of our proposed framework.`
- `Our system consists of three major components: (1)... (2)... (3)...`
- `Specifically, our model first [A]. Then, we [B]. Finally, [C].`
- `We build upon [prior work] and introduce [novelty].`

### Describing Components
- `The [module] is designed to [purpose].`
- `This is achieved by [mechanism].`
- `where [X] denotes [meaning], and [Y] represents [meaning].`
- `We formulate [task] as [formulation].`

---

## Experiment

### Section Opening
- `We conduct extensive experiments to evaluate our model.`
- `This section presents qualitative and quantitative comparisons with state-of-the-art methods and analysis of our method.`
- `We first compare the quality of [X] to existing methods using [datasets]. Next, we ablate our design choices in Sec. X. Finally, we demonstrate [Z].`

### Dataset / Baselines
- `We conduct experiments on three widely-used [X] datasets:`
- `We compare against [baseline1], [baseline2], and [baseline3].`

### Results
- `We report the quantitative results of [X].`
- `As shown in Table X / Fig. X, our method outperforms all baselines by a clear margin.`
- `Our evaluation metrics are PSNR/SSIM (higher is better) and LPIPS (lower is better).`

### Figure Captions
- `**Qualitative comparison** of our method against baselines on [dataset].`
- `Illustration of [X].`
- `Examples of [X] on [dataset].`
- `First row shows [A], while the following rows present [B].`
- `The image in the red dashed box stands for [X].`

### Ablation Studies
Use `w/` (with) and `w/o` (without) notation:
- `w/ [module]`: model variant with the component
- `w/o [module]`: model variant without the component

---

## Conclusion

- `We present [method] for [task].`
- `The key idea underpinning the proposed method is to [X].`
- `Our model performs on par with and even outperforms many recent state-of-the-art methods.`
- `Extensive experiments demonstrate that [X] achieves the state-of-the-art performance for [task].`
- `We hope that this work brings us one step closer to [vision].`
- `Finally, we supplement our empirical results with a careful analysis of each component of [X].`

---

## Rebuttal

- `Thank you for the constructive feedback.`
- `We appreciate the reviewer's insightful comments.`
- `We will incorporate these suggestions in the revised version.`
- `As mentioned in our response to Reviewer X, [cross-reference].`
- `We conducted additional experiments as suggested, and the results confirm that...`
- `This concern is valid; however, [explanation/clarification].`
