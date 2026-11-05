# AI & Economics of Science Papers — 2026-11-06

## 1. Can Large Language Models Review the Scientific Literature? A Test Against a 102-Article Benchmark [AI for Science]

**Authors:** Abdullah Al Kalbani, David M. Schultz, Alexandra K. Anderson-Frey, Zhonghua Zheng, Catherine McGuire
**Date:** November 3, 2026
**Source:** https://arxiv.org/abs/2611.05459
**Summary:** Testing six AI tools against a published 102-article literature review on the Spanish plume weather pattern, the authors evaluate discovery, interpretation, synthesis, and future-research stages separately rather than treating "literature review" as one task. They find institutional library access roughly doubles how many relevant articles the tools can find, but even the best tools misclassify a large share of passing mentions as substantial discussion and occasionally fabricate quotes or overstate consensus in their syntheses. The study concludes LLMs can meaningfully assist literature discovery and interpretation but cannot yet substitute for expert judgment in evaluating or synthesizing evidence.

## 2. Replicability, Reproducibility, and Robustness in Political and Social Science Research with Large Language Models [AI for Science]

**Authors:** Joan C. Timoneda, Sebastián Vallejo Vera
**Date:** November 4, 2026
**Source:** https://arxiv.org/abs/2611.06639
**Summary:** This chapter tackles the problem that LLM outputs are probabilistic and version-dependent, which can quietly flip the sign of downstream regression results in social-science research that uses LLMs to code or measure variables. The authors propose judging LLM-based measurement by the stability of its output distribution rather than demanding identical answers, and introduce error-structure diagnostics plus a standardized prompting script to test within-model variation. Combining several open-weight models into a stacked ensemble improves precision while preserving validity, though gold-labeled correction samples remain the more reliable, if costlier, fix.

## 3. Enhancing Knowledge Entity Relation Extraction in Abstracts and Full-text Content of Academic Articles Using Large Language Models [AI for Science]

**Authors:** Yingyi Zhang, Chengzhi Zhang
**Date:** October 30, 2026
**Source:** https://arxiv.org/abs/2610.41552
**Summary:** Building two hand-annotated NLP-domain datasets from paper abstracts and full texts, the authors compare several ways of combining large and small language models to extract entity relations from scientific papers, including two new hybrid strategies they introduce. A LoRA-adapted T5 model performs best overall, and smaller models improve further when LLMs generate auxiliary entity descriptions for them, though which hybrid strategy wins depends on the type of error being corrected. The work is a step toward more reliable automated tools for mining structured knowledge out of the growing scientific literature.

## 4. Truly Every Author is First Author: Equal-Width Superimposition by Minimising Visual Distortion [Peer Review & Publication]

**Authors:** Peter Waldert, Benedikt Kantz, Thomas Köhler
**Date:** October 31, 2026
**Source:** https://arxiv.org/abs/2611.01331
**Summary:** Responding to a prior proposal that journals list every author as "first author" by stacking all names on top of each other on the title page, the authors point out that unequal name widths let the longest name visually dominate, undoing the intended equality. They solve this with a closed-form optimization that stretches and tracks each name's letters until all occupy an identical common width, formally minimizing total visual distortion, and provide the method as LaTeX and Typst packages with machine-checked proofs. It is a tongue-in-cheek but technically serious contribution to the recurring debate over how academic publishing assigns and displays authorship credit.

*Note: Only 4 qualifying papers were found this cycle. The arXiv harvest (econ.GN, cs.DL, cs.CY) and a budgeted supplemental search of NBER, SSRN, and Research Policy found no additional candidates clearly within the 30-day window; the window was not widened.*
