# <p align=center>`Rebuttal` </p>

> Rebuttal 的核心：感谢 → 直接回答 → 提供证据 → 承诺修改。语气要礼貌但自信，不要道歉式回复。



## 通用开头

| 感谢审稿人                                                   |
| :----------------------------------------------------------- |
| We thank the reviewer for the thoughtful and constructive feedback. |
| We appreciate the reviewer's time and detailed comments.     |
| We are grateful for the insightful suggestions, which help strengthen our work. |
| We thank all reviewers for their valuable comments. We address each concern below. |



## 针对常见问题的回复模板

### 「创新性不足 / Novelty」

| 回复策略                                                     |
| :----------------------------------------------------------- |
| We respectfully disagree with this assessment. Our key contribution is not simply combining A and B, but rather [specific novelty]. |
| While [prior work] addresses a related problem, our work differs in three fundamental ways: (1) ... (2) ... (3) ... |
| The novelty of our work lies in [X], which, to the best of our knowledge, has not been explored before. |
| We would like to clarify that [prior work] focuses on [different setting], whereas our method targets [our setting]. These are fundamentally different problems. |



### 「实验不够充分 / Insufficient Experiments」

| 回复策略                                                     |
| :----------------------------------------------------------- |
| We conducted the requested experiments and report the results below. Our method still achieves state-of-the-art performance: [results]. |
| Due to space constraints, we could not include all experiments in the main paper. We have added them to the supplementary material / revised paper. |
| We agree that comparison with [baseline] would be valuable. We ran the experiments and the results show that our method outperforms [baseline] by [margin] on [metric]. |
| We will include these additional experiments in the revised version. |



### 「与 baseline 对比缺失 / Missing Baselines」

| 回复策略                                                     |
| :----------------------------------------------------------- |
| We appreciate this suggestion. We have added comparison with [baseline] in Table X. Our method outperforms it by [X] on [metric]. |
| [Baseline] is not directly applicable to our setting because [reason]. Instead, we adapted it by [adaptation] for a fair comparison, and results show our method still outperforms it. |
| We note that [baseline] requires [additional supervision / data / compute] that our method does not, making direct comparison unfair. Nevertheless, our method achieves comparable / superior performance. |



### 「写作不清晰 / Unclear Writing」

| 回复策略                                                     |
| :----------------------------------------------------------- |
| We apologize for the confusion. To clarify: [clear explanation]. We have revised Sec. X to make this more explicit. |
| Thank you for pointing this out. We have rewritten the paragraph in Sec. X for clarity. |
| We will add a more detailed explanation of [X] in the revised version, including [specific addition]. |
| Fig. X in the supplementary material provides a visual illustration that may help clarify this point. |



### 「需要消融实验 / Missing Ablations」

| 回复策略                                                     |
| :----------------------------------------------------------- |
| We conducted the requested ablation. Removing [component] leads to a drop of [X] in [metric], confirming its importance (see Table X). |
| We have added an ablation study on [component] in the revised paper. The results validate our design choices. |



### 「礼貌反驳 / Polite Disagreement」

| 当你认为审稿人误解了你的工作                                 |
| :----------------------------------------------------------- |
| We respectfully disagree with this point. [clear explanation of why]. |
| We believe there may be a misunderstanding. Our method does not [what reviewer said]; instead, it [what it actually does]. |
| With respect, we note that [prior work cited by reviewer] addresses a different problem: [difference]. |
| We would like to point out that [reviewer's concern] is actually addressed in Sec. X / Eq. X / Fig. X of the original submission. |



### 「时间/计算开销问题 / Efficiency Concern」

| 回复策略                                                     |
| :----------------------------------------------------------- |
| We report the runtime comparison in Table X. Our method runs at [X] ms per [unit], which is comparable to / faster than [baseline]. |
| The additional [X] ms overhead is negligible compared to the overall pipeline and is a worthwhile trade-off given the [Y]% improvement in [metric]. |



## 承诺修改的表达

| 用于结尾，承诺在正式版本中修改                               |
| :----------------------------------------------------------- |
| We will incorporate the above clarifications in the revised paper. |
| We will add [X] to Sec. X / the appendix in the revised version. |
| These experiments / discussions will be included in the camera-ready version. |
| We will revise the paper to make [X] clearer, and highlight [Y] more prominently. |



## 跨审稿人引用

| 当多个审稿人提出同一问题时                                   |
| :----------------------------------------------------------- |
| As also noted by Reviewer X, [common concern]. We address this as follows: ... |
| Please refer to our response to Reviewer X for details on this point. |



## 结尾

| 结束语                                                       |
| :----------------------------------------------------------- |
| We hope our response addresses the reviewer's concerns. We are happy to provide further clarification if needed. |
| We believe these revisions significantly strengthen the paper and hope the reviewer will reconsider their assessment. |
| Thank you again for the constructive feedback, which has improved the quality of our work. |
