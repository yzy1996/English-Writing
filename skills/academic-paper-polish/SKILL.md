---
name: academic-paper-polish
description: Polish and improve English writing for academic/research papers, especially in CS and ML fields. Use this skill whenever the user asks to improve, revise, or polish academic writing; wants sentence templates or phrase suggestions for paper sections (abstract, introduction, related work, method, experiment, conclusion, rebuttal); needs better vocabulary or synonyms for paper writing; asks how to phrase results, describe methods, or present findings academically; wants help writing any part of a research paper. Also activate when the user pastes a paragraph and asks to "make it better", "make it more academic", or similar in a research context.
version: 1.0.0
---

# Academic Paper Polish

Help the user write and polish English for academic research papers, with a focus on CS/ML fields. The repository at the working directory contains curated vocabulary, phrase banks, and section templates drawn from real published papers.

## Workflow

When the user provides text to polish or asks for writing help:

1. **Identify the section** — determine which part of the paper (Abstract, Introduction, Related Work, Method, Experiment, Conclusion, Rebuttal) or ask if unclear
2. **Diagnose the issues** — look for: vague vocabulary, weak transitions, informal tone, lack of precision, repetitive sentence starters, missing evidence claims
3. **Apply improvements** using vocabulary and phrase banks in the reference files
4. **Provide 2–3 alternatives** so the user can choose the best fit; explain the nuance between options

## Section-Specific Guidance

Read `references/section-phrases.md` for ready-to-use sentence templates organized by paper section.

### Abstract (3-part structure)
- **Opening**: describe the problem/gap existing methods face — "Existing approaches face a dilemma...", "Despite the rapid advancement of..."
- **Middle**: describe your method and key innovations — "In this work, we present...", "A key part of our approach is..."
- **Closing**: show results — "Extensive experiments demonstrate that our framework significantly outperforms SOTA methods on..."

### Introduction (4-paragraph structure)
1. Background & motivation — "An explosively growing line of research...", "has enjoyed tremendous growth..."
2. Limitations of existing work — "The main drawback...", "prior attempts hamper...", "an inevitable problem..."
3. Your solution — "To address this, we propose...", "Motivated by this, we introduce..."
4. Contributions — "In summary, our contributions are:" followed by bullet points

### Related Work
- Group by sub-category, not chronologically
- "The most related works can be divided into... The first focuses on... The second..."
- Handle concurrent work: "The concurrently developed X. The central distinction between these and ours is that..."
- "Our method builds upon this line of research"

### Method
- Introduce the full framework first, then individual components
- "Our system consists of three major components: (1)... (2)... (3)..."
- For math notation: "where X denotes...", "we formulate this as..."
- "Specifically, our model first adapts... Then, we... Finally,..."

### Experiment
- Standard structure: Dataset → Baselines → Metrics → Quantitative Results → Qualitative Results → Ablations
- Use `w/` and `w/o` for ablation notation (with / without)
- Figure captions: bold the key phrase, e.g. "**Qualitative comparison** of our method against baselines."
- "We conduct extensive experiments to evaluate our model."

### Conclusion
- Sentence 1: "We present [method] for [task]."
- Sentence 2: "The key idea underpinning the proposed method is to..."
- Sentence 3: "Extensive experiments demonstrate that our method achieves state-of-the-art performance."
- Sentence 4: Future impact — "We hope this work brings us one step closer to..."

## Vocabulary & Phrases

Read `references/vocabulary.md` for curated vocabulary organized by use case:
- **Positive evaluation** (abstract/good concepts): unprecedented, phenomenal, intriguing, seminal, indispensable...
- **Positive evaluation** (concrete methods): ameliorate, synergistic, complementary, maturity...
- **Negative evaluation** (critiquing baselines): hamper, hinder, deficiency, deteriorate, inferior, vulnerable...
- **Difficulty vocabulary**: elusive, tackle, address, a remedy to...
- **Transitional connectors**: notably, in contrast, as a remedy, in tandem, meanwhile...
- **Quantity expressions**: a myriad of, plethora of, a wide range of...
- **Useful phrases**: off-the-shelf, on par with, in stark contrast to, take an orthogonal direction...
- **Domain-specific terms**: leverage, streamline, harness, empirically, agnostic, hallucinate (amodal)...

## Abbreviations & Latin Terms

| Abbreviation | Meaning |
|---|---|
| e.g. | for example |
| i.e. | that is / in other words |
| w.r.t. | with regard to |
| a.k.a. | also known as |
| etc. | and so forth |

Latin terms (*italicize*): *per se*, *de facto*, *vice versa*, *post hoc*, *ad-hoc*

## AI-Assisted Polishing

Read `references/ai-polish.md` for ready-to-paste prompts for ChatGPT/Claude polishing, including:
- The **Nature (2024)** recommended template
- System presets for consistent academic style
- Dimension-specific polishing: precision, conciseness, coherence, academic tone, formality

## Key Writing Principles

- **Academic tone**: prefer "generate" over "produce", "analyze" over "look at", "demonstrate" over "show"
- **Precision**: avoid vague claims; add specifics ("improves by 3.2 PSNR", "reduces training time by 40%")
- **Variety**: avoid repeating the same sentence opener; rotate transitions (notably / in contrast / more specifically / furthermore)
- **Evidence-backed claims**: support assertions with "experiments demonstrate...", "as shown in Fig. X..."
- **Active vs. passive**: use active voice for your contributions ("We propose..."), passive for results ("The model is trained on...")
- **Avoid these weak phrases**: "it can be seen that", "in order to", "due to the fact that" → replace with direct alternatives
