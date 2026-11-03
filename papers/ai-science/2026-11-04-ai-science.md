# AI & Economics of Science Papers — 2026-11-04

## 1. LLMs and the Organization of Scientific Work [Econ of Science]

**Authors:** Stefano Bianchini, Georgiana-Ioana Coroama
**Date:** November 2, 2026
**Source:** https://arxiv.org/abs/2611.02996
**Summary:** Using CRediT contribution statements from roughly 120,000 PLOS ONE articles published 2018–2025, the authors track how teams divided research tasks before and after ChatGPT's late-2022 release. They find overall task participation, especially in conceptualization, execution, and writing, fell below its prior trajectory, while individual researchers took on narrower, more specialized task portfolios with less overlap with co-authors. These shifts concentrate almost entirely in newly formed teams, since teams with a shared collaboration history show much greater inertia, suggesting LLM adoption is reorganizing scientific labor around individual autonomy rather than uniformly across all teams.

## 2. Change the Funnel, Not Who May Submit: Engineering Peer Review for the Flood [Peer Review & Publication]

**Authors:** Mikhail L. Arbuzov, Lee Mosbacker, Sisong Bei
**Date:** October 31, 2026
**Source:** https://arxiv.org/abs/2611.01076
**Summary:** Motivated by NeurIPS's 2026 submission count of over 30,000 papers and roughly 184,000 reviewer-hours spent, mostly on rejected work, the authors simulate both the submission caps conferences are adopting and an alternative staged-review funnel, calibrated against real NeurIPS re-review data showing reviewers disagree on roughly half of borderline accepts. Submission limits save little reviewing time, select no better, and disproportionately exclude new authors, whereas the staged funnel — an automated readiness filter, then reader-based ranking from brief summaries, then full review only for finalists — needs just over half of today's reviewer hours while accepting 95.5% of genuinely top-tier papers versus 74% today. The results argue that restructuring how review effort is allocated, rather than restricting who can submit, better matches peer review capacity to a still-growing submission volume.

## 3. Comparative Evaluation of LLM-Based Review Paradigms for Academic Paper Quality Assessment [Peer Review & Publication]

**Authors:** Fan Huang, Hongyu Zhou
**Date:** October 30, 2026
**Source:** https://arxiv.org/abs/2610.41391
**Summary:** Testing five ways of structuring LLM-based peer review across three input formats and three models on over 11,000 scored ICLR 2025 submissions, the authors find that rank correlation with human scores looks similar across methods but masks very different failure modes: direct absolute rating compresses nearly all predictions above the accept line, while comparative ranking methods mainly add placement rather than better ordering once recalibrated. Abstract-only input beat full-paper summarization, and which LLM was used mattered as much as which review paradigm was used, with none of the paradigms beating a simple always-reject baseline in raw accuracy on the full submission pool. Only human scores and one specific paradigm tracked eventual citation counts well, leading the authors to argue that rank correlation alone cannot certify an LLM reviewing method and that calibration, thresholds, and the chosen outcome measure all need separate validation.

## 4. Retrieve-then-Disambiguate: Scalable Reviewer Discovery [Peer Review & Publication]

**Authors:** Vicente Amado Olivo, Joe Petrecca, Wolfgang E. Kerzendorf
**Date:** October 29, 2026
**Source:** https://arxiv.org/abs/2610.40768
**Summary:** To address peer review strain from a growing pool of qualified-but-unidentified potential reviewers, the authors frame reviewer discovery as a retrieval problem, built as an open-source pipeline that finds domain-similar past publications for a submission and then resolves ambiguous author names into distinct researcher identities. Evaluated on 500 astronomy and physics papers using ORCID-linked authorship and citations as ground truth, retrieving the top 500 similar papers recovers about 68% of first authors, 60% of co-authors, and 45% of cited researchers with known ties to the query paper. The tool offers venues a scalable way to surface qualified reviewers beyond their existing contact networks, though recall still falls well short of complete coverage even at a fairly generous retrieval depth.

## 5. "PRISM" Is Not All You Need: Cross-Topic Name Collisions and Scientific Paper Retrieval [AI for Science]

**Authors:** Jingjie Ning, Xueqi Li, Yibo Kong
**Date:** November 1, 2026
**Source:** https://arxiv.org/abs/2611.01362
**Summary:** Analyzing 564,861 AI-related arXiv records, the authors show that the same catchy project name increasingly gets reused across unrelated research topics, with cross-topic name collisions growing more than fourfold since 2020–2022 while within-topic reuse barely changed, a pattern confirmed with an independent sentence encoder. This naming convergence meaningfully hurts identification: title-based retrieval misidentifies shared-name papers roughly 26 percentage points more often than it should, though adding context such as abstracts or a ranking language model recovers much of that ambiguity. The findings matter for AI research assistants and literature-search tools, which increasingly rely on names and short queries that can no longer reliably distinguish between unrelated papers sharing a popular name.
