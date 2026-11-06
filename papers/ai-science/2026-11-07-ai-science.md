# AI & Economics of Science Papers — 2026-11-07

## 1. LLMs and the Organization of Scientific Work [Econ of Science]

**Authors:** Stefano Bianchini, Georgiana-Ioana Coroama
**Date:** November 2, 2026
**Source:** https://arxiv.org/abs/2611.02996
**Summary:** Analyzing CRediT contribution statements from roughly 120,000 PLOS ONE articles published 2018–2025, the authors test how ChatGPT's late-2022 release changed the way scientific teams divide labor. They find overall task participation has dropped below its pre-ChatGPT trend, especially in conceptualization, execution, and writing, while individual researchers have grown more specialized and overlap less with coauthors. This reorganization toward narrower, more autonomous roles shows up almost entirely in newly formed teams, since teams with a shared collaboration history show much more inertia and resist restructuring around the new tool.

## 2. Can Large Language Models Review the Scientific Literature? A Test Against a 102-Article Benchmark [AI for Science]

**Authors:** Abdullah Al Kalbani, David M. Schultz, Alexandra K. Anderson-Frey, Zhonghua Zheng, Catherine McGuire
**Date:** November 3, 2026
**Source:** https://arxiv.org/abs/2611.05459
**Summary:** The authors benchmark six AI tools against a published, expert-written literature review of 102 articles on the Spanish plume weather pattern, testing each tool's ability to find, interpret, synthesize, and extend the literature. Search coverage varied widely and improved substantially once tools had institutional library access, but even the best tools misclassified a large share of borderline articles and their syntheses sometimes contained unsupported claims or quotation errors despite being largely accurate. No single tool excelled at every stage, leading the authors to conclude AI can speed up discovery and interpretation but still needs expert oversight for evaluating evidence and synthesizing research.

## 3. Replicability, Reproducibility, and Robustness in Political and Social Science Research with Large Language Models [AI for Science]

**Authors:** Joan C. Timoneda, Sebastián Vallejo Vera
**Date:** November 4, 2026
**Source:** https://arxiv.org/abs/2611.06639
**Summary:** This chapter tackles the reproducibility problem created by using LLMs as research tools, since their probabilistic outputs vary across models, versions, and runs in ways that can flip the sign of downstream regression results. The authors separate replicability, reproducibility, and robustness conceptually, then propose judging LLM-based measurement by the distribution of results rather than requiring identical outputs, backed by a standardized prompting protocol and an error-structure analysis to diagnose where and how models disagree. Their proposed fix, a stacked ensemble of open-weight models, improves precision in gold-label correction methods without sacrificing the validity those corrections were designed to protect.

## 4. MapHub: Daily Relevance Heatmaps of New arXiv Preprints for a Research Community [AI for Science]

**Authors:** Kaili Cao, Camille Avestruz, Feige Wang
**Date:** November 4, 2026
**Source:** https://arxiv.org/abs/2611.07174
**Summary:** MapHub uses an LLM to score every new arXiv preprint each day against individual researcher "portfolios," then displays the results as a heatmap showing whose work in a research community each new paper is likely to touch. In blind evaluations, papers in MapHub's top 10% by score captured about 70% of raters' own top picks, versus roughly a third for a simple text-matching baseline, and the tool flags a handful of highly relevant astro-ph papers for each participant every few days. Built to run on a standard Claude subscription and released openly, it offers a low-cost way for research communities to triage the growing daily flow of preprints.

## 5. Enhancing Knowledge Entity Relation Extraction in Abstracts and Full-text Content of Academic Articles Using Large Language Models [AI for Science]

**Authors:** Yingyi Zhang, Chengzhi Zhang
**Date:** November 2, 2026 (v2; first posted October 30, 2026)
**Source:** https://arxiv.org/abs/2610.41552
**Summary:** The authors compare several LLM-based strategies for pulling structured knowledge-entity relations out of academic papers, including prompting closed-source models, fine-tuning open-source models, and hybrid setups that use LLMs to boost smaller pretrained language models. On two hand-annotated NLP-domain datasets covering abstracts and full text, a LoRA-adapted T5 model performed best overall, and smaller models improved noticeably when given LLM-generated entity descriptions, though which strategy helped most depended on the type of extraction error being fixed. The results point toward combining complementary strategies, rather than relying on any single approach, to get the most reliable automated extraction of research content at scale.
