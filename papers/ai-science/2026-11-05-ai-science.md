# AI & Economics of Science Papers — 2026-11-05

## 1. Beyond fabrication: Misattributed numbers in papers written by AI research agents [AI for Science]

**Authors:** Mosab Alfaqeeh, Omar Mohammed Horani, Mou'th Hourani, Hashem Alfaqeeh
**Date:** October 28, 2026
**Source:** https://arxiv.org/abs/2610.38691
**Summary:** Re-analyzing judgments from a benchmark of nine AI research agents tackling fifteen open problems, the authors manually label 256 numerical claims across 18 agent-written papers and find that most unsupported numbers aren't outright fabricated but misattributed — pulled from the agent's own files, just from the wrong experiment, metric, or run. They build a deterministic claim-to-evidence checker that certifies claims with over 90% precision against human annotators and show it produces far fewer false positives than an LLM-based verifier given the same evidence. Applied across 99 submissions, the checker exposes large differences in how traceable different agents' claims are, arguing for provenance-first auditing of AI-produced research rather than single-judge integrity verdicts.

## 2. Validating LLM-Generated Synthetic Survey Samples: A Use-Dependent Multi-Dimensional Framework for Social-Science Applications [AI for Science]

**Authors:** Enrico Angelo Raffaele D'Ecclesiis, Fulvio Castellacci, Arash Ahmadi
**Date:** October 30, 2026
**Source:** https://arxiv.org/abs/2611.00256
**Summary:** Using Eurobarometer survey data on attitudes toward AI, the authors test four large language models' ability to generate synthetic survey respondents and propose a validation framework that separates predictive accuracy from distributional and substantive validity, rather than judging synthetic data by one accuracy score. They find synthetic samples often perform weakly at predicting individual respondents yet still preserve demographic ordering, cross-country variation, and other population-level patterns researchers rely on. The results suggest LLM-generated survey data can be useful for social-science research, but only when validated against the specific empirical properties a given study needs rather than treated as a generic substitute for real respondents.

## 3. Exploring Collaborative Debating Models for the future of science [Econ of Science]

**Author:** Zeki C. Seskir
**Date:** October 30, 2026
**Source:** https://arxiv.org/abs/2611.00370
**Summary:** As AI expands how much research individuals and teams can produce, this paper proposes "Collaborative Debating Models" — topic-focused environments where researchers and AI jointly maintain an evolving, continuously revised account of a field rather than publishing discrete papers, with individual contributions tracked through ongoing attribution. It sketches how journals could evolve into such gathering places, linking participants to shared data repositories and remote lab services, and considers how different ownership arrangements over these spaces would shape research agendas. The proposal is a thought experiment rather than an implemented system, but it directly confronts how scientific publishing and credit may need to be restructured if AI substantially raises research output.

## 4. From Policing Provenance to Designing for Evidence: Testing Four Propositions on Generative AI Against Research and Institutional Policy [Science Policy]

**Author:** Samar Ansari
**Date:** October 31, 2026
**Source:** https://arxiv.org/abs/2611.01330
**Summary:** Coding 41 research sources and 55 UK-weighted university and sector policy documents, this paper tests the argument that redesigning assessment beats detecting or banning generative AI, finding that view well supported only when redesign is paired with added assurance measures rather than used alone. It shows institutions broadly value student AI-use disclosures even though many students skip the required declarations, and that detector-based policing is largely rejected across the sampled documents. The paper's extension of this logic to peer review is found plausible but barely addressed in current policy, and it closes with a nine-step decision framework for deciding, case by case, what role AI should play once the evidence a given outcome requires is specified.

## 5. Enhancing Knowledge Entity Relation Extraction in Abstracts and Full-text Content of Academic Articles Using Large Language Models [AI for Science]

**Authors:** Yingyi Zhang, Chengzhi Zhang
**Date:** October 30, 2026
**Source:** https://arxiv.org/abs/2610.41552
**Summary:** Comparing several ways of combining large and small language models to extract knowledge-entity relations from academic paper abstracts and full texts, the authors build two manually annotated NLP-domain datasets and find a LoRA-adapted T5 model performs best, while LLM-generated entity descriptions also measurably improve smaller, cheaper models. Error analysis shows different model combinations fail in different ways, and combining strategies with complementary error patterns further improves extraction accuracy over any single approach. The work matters for literature-mining and knowledge-graph tools that increasingly rely on automated processing of the scientific literature, since the choice and combination of models shapes how reliably those tools can extract usable knowledge from papers at scale.
