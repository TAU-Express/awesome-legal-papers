# Awesome Legal Papers

A curated list of papers on legal NLP, legal AI, and legal-domain evaluation.

Part of the [ACE-EXP](https://github.com/TAU-Express/ace-exp) legal-AI evaluation project.

## Contents

- [Papers](#papers)
- [Contributing](#contributing)
- [License](#license)

## Papers

| Title | Year | Venue | Link | Datasets/Tasks |
|---|---|---|---|---|
| NLP for the Legal Domain: A Survey of Tasks, Datasets, Models, and Challenges | 2025 | ACM Computing Surveys | https://arxiv.org/abs/2410.21306 | — |
| A Survey on Legal Judgment Prediction: Datasets, Metrics, Models and Challenges | 2022 | arXiv 2022 (canonical LJP survey) | https://arxiv.org/abs/2204.04859 | — |
| A Comprehensive Survey on Legal Summarization | 2025 | arXiv | https://arxiv.org/abs/2501.17830 | — |
| Large Language Models Meet Legal Artificial Intelligence: A Survey | 2025 | arXiv | https://arxiv.org/abs/2509.09969 | — |
| When LLMs Meet Law: Dual-Lens Taxonomy, Technical Advances, Ethical Governance | 2025 | arXiv 2025 (Kilimajaro/LLMs_Meet_Law) | https://arxiv.org/abs/2507.07748 | — |
| Evaluation of LLMs in Legal Applications: Challenges, Methods, Future Directions | 2026 | arXiv Jan 2026 (very recent) | https://arxiv.org/abs/2601.15267 | — |
| Large Language Models in Legal Systems: A Survey | 2025 | Nature HSSC | https://www.nature.com/articles/s41599-025-05924-3 | — |
| Large Language Models in Law: A Survey | 2023 | arXiv Dec 2023 (early LLM-law survey) | https://arxiv.org/abs/2312.03718 | — |
| BigLaw Bench (Harvey) | 2024 | Harvey | https://www.harvey.ai/blog/introducing-biglaw-bench | Real billable legal work (drafting, research, due diligence, litigation) |
| BigLaw Bench: Global (Harvey) | 2024 | Harvey | https://www.harvey.ai/blog/introducing-big-law-bench-global | BLB extended to more jurisdictions |
| BigLaw Bench: Research (Harvey) | None | Harvey | https://www.harvey.ai/blog/introducing-big-law-bench-research | Hard agentic US case-law research problems |
| Legal Agent Benchmark (LAB / HLAB) (Harvey) | 2026 | Harvey | https://www.harvey.ai/blog/introducing-harveys-legal-agent-benchmark | Long-horizon legal AGENT tasks (client-matter workflows) |
| 2026 Contract Review Benchmark (LegalOn Technologies) | 2026 | LegalOn Technologies | https://www.legalontech.com/post/the-contract-review-benchmark-2026 | Provision-level contract review precision vs 11 LLMs |
| MLEB (Massive Legal Embedding Benchmark) (Isaacus) | 1936 | Isaacus | https://isaacus.com/mleb | Legal embedding/retrieval: search, zero-shot classification, QA |
| Legal RAG Bench (Isaacus) | 2026 | Isaacus | https://isaacus.com/blog/legal-rag-bench | End-to-end legal RAG w/ error decomposition (halluc/retrieval/reasoning) |
| Open Australian Legal Corpus / QA (Isaacus) | None | Isaacus | https://huggingface.co/datasets/isaacus/open-australian-legal-corpus | Corpus (229K texts, 1.4B tokens) + 2,124 synthesized QA pairs |
| Vals Legal AI Report (VLAIR) (Vals AI) | 2025 | Vals AI | https://www.vals.ai/industry-reports/vlair-2-27-25 | 7 legal tasks across vendor tools vs lawyer baseline |
| Legal Research Bench (Vals AI) | None | Vals AI | https://www.vals.ai/benchmarks/legal_research | Agentic legal research (case/web/doc retrieval -> synthesis) |
| CaseLaw v1/v2 (Vals AI (w/ Jurisage)) | None | Vals AI (w/ Jurisage) | https://www.vals.ai/benchmarks/case_law-04-11-2025 | Litigation precedent QA (family + criminal law) |
| CoCoBench (Thomson Reuters / CoCounsel) | 2025 | Thomson Reuters / CoCounsel | https://www.thomsonreuters.com/en-us/posts/innovation/why-legal-ai-needs-a-new-standard-inside-thomson-reuters-cocobench/ | Fiduciary-grade legal task completion; longitudinal tracking |
| LegalRikai (Open Benchmark) (LegalOn Technologies) | 2025 | LegalOn Technologies | https://arxiv.org/abs/2512.11297 | 4 tasks: complex Japanese corporate legal work (long-form doc editing) |
| JudgmentBench (Snorkel AI + Stanford Law) | 2026 | Snorkel AI + Stanford Law | https://arxiv.org/abs/2605.25240 | Rubric vs comparative(pairwise) judgment as eval methodology (on 30 BigLawBench tasks) |
| PRBench-Legal (Scale AI) | 2026 | Scale AI | https://scale.com/research/prbench | High-stakes professional legal reasoning; weighted rubric criteria |
| APEX (Big Law associate split) (Mercor) | 2025 | Mercor | https://arxiv.org/abs/2509.25721 | Professional-work tasks; law is one of 4 domains |
| AI IE + Contract Drafting Benchmarks (legalbenchmarks.ai (consortium)) | 2025 | legalbenchmarks.ai (consortium) | https://www.legalbenchmarks.ai/research/phase-1-research | Phase1: info extraction (6 tools); Phase2: contract drafting (14+ tools) |
| ContractIQ Bench (Luna) (Luminance) | 2025 | Luminance | https://www.luminance.com/resources/insights/the-era-of-vertical-ai-is-here-introducing-luna-crescent-luminances-proprietary-legal-intelligence-model/ | Contract provision annotations to validate Luna/Luna Crescent model |
| State of Contracts clause benchmarks (Spellbook) | 2026 | Spellbook | https://www.spellbook.legal/blog/2026-state-of-contracts-report | 270+ clause benchmarks across 13 agreement types |


## Sources & Acknowledgments

Entries in this list were seeded in part from:

- [maastrichtlawtech/awesome-legal-nlp](https://github.com/maastrichtlawtech/awesome-legal-nlp)
- [CSHaitao/Awesome-LegalAI-Resources](https://github.com/CSHaitao/Awesome-LegalAI-Resources)
- [thunlp/LegalPapers](https://github.com/thunlp/LegalPapers)
- [Jeryi-Sun/LLM-and-Law](https://github.com/Jeryi-Sun/LLM-and-Law)
- [ZhitianHou/LLMs4LegalAI](https://github.com/ZhitianHou/LLMs4LegalAI)
- [czyssrs/LLM_X_papers](https://github.com/czyssrs/LLM_X_papers)
- [Liquid-Legal-Institute/Legal-Text-Analytics](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics)
- [openlegaldata/awesome-legal-data](https://github.com/openlegaldata/awesome-legal-data)
- [hecongqing/Awesome-LLM4Law](https://github.com/hecongqing/Awesome-LLM4Law)
- [chen-friedman/awesome-legaltech](https://github.com/chen-friedman/awesome-legaltech)
- [dalinvip/Awesome-Law-NLP-Research-Work](https://github.com/dalinvip/Awesome-Law-NLP-Research-Work)

## Contributing

PRs welcome. Every entry must include a resolvable link (DOI / arXiv ID / publisher URL).

## License

This list (the curation itself) is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
