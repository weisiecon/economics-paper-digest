# AI & Economics of Science Papers — 2026-11-03

## 1. Comparative Evaluation of LLM-Based Review Paradigms for Academic Paper Quality Assessment [Peer Review & Publication]

**Authors:** Fan Huang, Hongyu Zhou
**Date:** October 30, 2026
**Source:** https://arxiv.org/abs/2610.41391
**Summary:** Testing five ways of turning LLM judgments into peer-review scores across three input formats and three models on 232 stratified ICLR 2025 submissions, the authors find that direct rating and pairwise/Elo-style ranking produce similar rank correlation with human scores, but direct rating badly compresses its predictions near the accept threshold and barely flags papers reviewers scored below it. A recalibration check shows the problem is placement rather than ordering; once rescaled, direct rating beats Elo while needing only a quarter of the API calls, and reading just the abstract outperforms summarizing the full paper. Replicating across all 11,513 ICLR submissions confirms the pattern and shows none of the paradigms beat an always-reject baseline on accuracy, while human scores track citation counts better than any LLM paradigm except one variant that keeps its citation correlation after controlling for human scores.

## 2. Causal Analysis of Author Demographics in Academic Peer Review [Peer Review & Publication]

**Authors:** Uttamasha Anjally Oyshi, Gibson Nkhata, Susan Gauch
**Date:** October 29, 2026 (v2; first posted February 25, 2026)
**Source:** https://arxiv.org/abs/2603.06641
**Summary:** Working with 530 papers and using publication-venue prestige as a stand-in for review outcome, the authors move beyond correlational bias studies to estimate the causal effect of author race, gender, and country on acceptance ranking. They find statistically significant penalties for authors from minority racial groups, women, and institutions in the Global South, with the largest average treatment effect attached to Global South affiliation. The results argue that fairness interventions are needed in both human and AI-assisted review pipelines, since AI tools trained on biased historical review data could otherwise entrench the same disparities.

## 3. Letting AI Formulate the Research Question: Autonomous Research Agents [AI for Science]

**Authors:** Ko Fujimura
**Date:** October 29, 2026
**Source:** https://arxiv.org/abs/2610.39620
**Summary:** The author builds a coding-agent system that not only executes and writes up research, as prior "AI Scientist" demonstrations did, but also picks its own research question, using a second AI model to critique candidate ideas and a reviewer from a different model family to rerun the study before publication. Across 13 development runs, small changes to the one- or two-sentence prompt steering the research area produced large shifts in which questions and papers the system generated, eventually converging on applying emerging technology to societal problems. Five pre-registered, fully autonomous runs each went from question to a revised, reproducible paper on a single laptop with no human research input, and external AI reviewers judged the resulting papers at or near workshop quality.

## 4. Ignore the Writing: A Proposal for Peer Review in the Age of AI [Peer Review & Publication]

**Authors:** Vassilis Kostakos
**Date:** October 27, 2026
**Source:** https://arxiv.org/abs/2610.38062
**Summary:** Kostakos argues that generative AI has severed the old link between a polished manuscript and the research behind it, pushing peer review toward a future where AI writes papers that AI also reviews. Rather than resist that loop, he proposes redesigning submissions as a short 1,500-word brief accompanied by an unlimited, machine-checkable appendix, so human reviewers judge whether the pursuit is worthwhile while models verify the experimental record. The piece reframes human reviewing effort itself as the reward signal that should keep an AI-driven research loop pointed at worthwhile problems rather than just fluent writing.

## 5. Organizational Structure and the Research of U.S. Library and Information Science Schools [Econ of Science]

**Authors:** Jiangen He, Wen Lou
**Date:** October 26, 2026 (v2; first posted January 28, 2026)
**Source:** https://arxiv.org/abs/2601.20806
**Summary:** Using 18,048 publications from 1,602 faculty at 44 U.S. library and information science schools, the authors test whether a school's organizational home — independent, or housed with computing, education, communication, or arts and sciences — shapes what its faculty study. Clustering abstracts into 15 research themes, they find school type explains only a small share of the variation in topics and venues (2.2% and 5.3% respectively), with most variation occurring among faculty within the same school; schools paired with computing departments lean toward security, networks, and biomedical informatics topics. Over the 2013–2026 period studied, schools broadly drifted away from traditional library research without correspondingly adopting their parent discipline's venues, suggesting faculty composition matters more for a field's research direction than its administrative home.
