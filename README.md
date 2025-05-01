<div align="center">

<p>
  <img src="assets/cover.png" width="88%" alt="Towards AI that improves AI — the plan, execute, feedback, repair loop">
</p>

<h1>🚀 Awesome AI4AI</h1>

<p><strong><em>AI4AI Survey: From Long-Horizon Agents to Recursive Self-Improvement</em></strong><br>
<sub>Definitions, Reliable Horizons, and Open Problems · 23 authors · 7 institutions</sub></p>

<p>
  Weekly news featuring top AI-for-AI papers, releases, and blogs. <strong>Stay tuned 🔥</strong>
</p>

<p>
  <a href="assets/AI4AI-Survey.pdf"><img src="https://img.shields.io/badge/-Paper_(nice_layout)-B31B1B.svg?style=flat-square" alt="Paper, nice layout"></a>
  <a href="https://www.preprints.org/manuscript/202608.2108/v1"><img src="https://img.shields.io/badge/-Paper_on_Preprints.org-8B5CF6.svg?style=flat-square" alt="Paper on Preprints.org"></a>
  <a href="https://kaiwu5.github.io/Awesome-AI4AI/"><img src="https://img.shields.io/badge/-Project_Site-D76712.svg?style=flat-square" alt="Project Site"></a>
  <a href="https://github.com/simple-agent-lab/RSIHub"><img src="https://img.shields.io/badge/-RSIHub_Harness-24292F.svg?style=flat-square" alt="RSIHub Harness"></a>
  <a href="https://simpleagentlab.com/ai4ai/"><img src="https://img.shields.io/badge/-Blog-0A7EA4.svg?style=flat-square" alt="Blog"></a>
  <a href="https://doi.org/10.20944/preprints202608.2108.v1"><img src="https://img.shields.io/badge/DOI-10.20944%2Fpreprints202608.2108.v1-0A7EA4.svg?style=flat-square" alt="DOI"></a>
</p>

</div>

<br>

## Why This Repo

<table>
<tr>
<td width="33%" align="center">
  <strong>🔄 Refreshed rankings</strong><br>
  <sub>Citations, GitHub stars, and rankings refresh with maintainer updates.</sub>
</td>
<td width="33%" align="center">
  <strong>🗞️ Weekly update</strong><br>
  <sub>Top papers and releases, selected every week and verified against primary sources.</sub>
</td>
<td width="33%" align="center">
  <strong>🧭 Survey-grounded map</strong><br>
  <sub>From long-horizon agents to recursive self-improvement.</sub>
</td>
</tr>
</table>

<p align="center">
  <strong>Star ⭐ to save the map · Watch 👀 for weekly updates · Share 🔁 with your lab</strong>
</p>

## What's New

- 📄 **2026-08-30 — [Companion survey now online.](https://www.preprints.org/manuscript/202608.2108/v1)** Read *AI4AI Survey: From Long-Horizon Agents to Recursive Self-Improvement—Definitions, Reliable Horizons, and Open Problems*.
- 🔄 **Maintainer refresh.** Citations, GitHub stars, and recent-paper/yearly rankings are rebuilt from the catalog.
- 🚀 **2026-10-13 — Latest weekly edition published.** The living catalog and source-verified news digest are up to date.

<details open markdown="1">
<summary><b>🗂️ Explore the full collection</b></summary>

- [📅 Weekly News · Top 10](#weekly-news)
- [📈 Live Rankings](#-live-rankings)
  - [Top Ranking Papers by Average Monthly Citations](#top-ranking-papers-by-average-monthly-citations)
  - [🏆 Most-Cited Papers by Year](#-most-cited-papers-by-year)
- [🧪 Benchmarks](#-benchmarks)
- [🛠️ Harness Design](#-harness-design)
- [🧠 Model Design](#-model-design)
- [📚 How We Curate](#-how-we-curate)
- [📄 Citation](#-citation)
- [🤝 Contributing](#-contributing)

</details>

<br>

<a id="monthly-news"></a>
<a id="weekly-news"></a>

## 📅 Weekly News · Top 10

> **Updated 2026-10-13** · Weekly news picks, refreshed every Monday alongside citation rankings.
>
> **How we select:** The top stories from the trailing 30 days, scored on publisher authority, discussion volume, whether a concrete verifiable result is reported, whether it changes what agent builders do now, whether an artifact was released, and expected durability. Only primary sources are cited, and performance claims remain attributed to their publishers.

| Date · Type | News | Why it matters |
|:--|:--|:--|
| 2026‑10‑12<br><sub>Research release</sub> | [**GLM-Legal: Advancing Agentic Legal Intelligence**](https://z.ai/blog/glm-legal)<br><sub>Z.ai</sub> | Z.ai introduces a GLM-5.3-Flash-based legal specialist and describes joint optimization of model training and the agent harness. It reports a 19.2% all-pass rate on Harvey LAB, 12.5 points above its base model; beta participation is invited and AutoClaw integration is forthcoming. |
| 2026‑10‑09<br><sub>Paper</sub> | [**Proactive Agentic Orchestration**](https://arxiv.org/abs/2610.13485)<br><sub>Xueyang Feng et al. · arXiv</sub> | The authors release POrchestra, allowing sub-agents to request harness adjustments during execution, and OPOD, which distills hindsight feedback into orchestration training. Across three long-horizon benchmarks, they report average relative success gains of 9.1% over the strongest orchestration baseline and 10.0% over existing small-orchestrator training baselines. |
| 2026‑10‑08<br><sub>Paper</sub> | [**Memento 3: Model-Based Recursive Self-Improvement through Reflective Rulebooks**](https://arxiv.org/abs/2610.11794)<br><sub>Haoyu Zhao et al. · arXiv</sub> | The authors keep the LLM fixed while revising persistent natural-language world models, compiling them into code and verifying observed transitions. They report clearing all levels of 25 public ARC-AGI-3 games with mean RHAE 100.0 using 44% of the human action count. |
| 2026‑10‑07<br><sub>Model release</sub> | [**Introducing Claude Haiku 5.5**](https://www.anthropic.com/claude-haiku-5-5)<br><sub>Anthropic</sub> | Anthropic releases Haiku 5.5 for compaction, summarization and subagent work, reporting 72.4% on the OSWorld 2.1 offline subset and 39.2% on Terminal-Bench 4.0. It estimates typical task costs around 75% below Haiku 4.5 and introduces adjustable effort for the Haiku tier. |
| 2026‑10‑06<br><sub>Model release</sub> | [**Introducing Mistral Large 4**](https://mistral.ai/news/mistral-large-4/)<br><sub>Mistral</sub> | Mistral opens the public preview API for a one-trillion-parameter native multimodal flagship and reports 93.3% attack resistance on Lakera B3. The announcement promises weights by the end of October; this edition does not treat those weights as already released. |
| 2026‑10‑04<br><sub>Paper</sub> | [**Complex Agents, Shallow Tests: Demystifying and Enhancing Test Adequacy of Agent Harness in the Wild**](https://arxiv.org/abs/2610.04921)<br><sub>Yifan Xiong et al. · arXiv</sub> | The authors introduce HarnessTester, which generates tests grounded in agent-harness contracts. They report detecting 122 real-world harness bugs, including 88 previously unknown bugs and 69 confirmed by developers, alongside larger coverage and mutation-score gains than general-purpose test generators. |
| 2026‑10‑04<br><sub>Paper</sub> | [**MESH-Harness: Self-Improving Agent Harnesses via Bandit-Guided Compositional Evolution**](https://arxiv.org/abs/2610.05300)<br><sub>Zhiwei Shang et al. · arXiv</sub> | The authors combine modular harness reuse with bandit-guided compositional search while fixing model weights. Under matched candidate-evaluation budgets, they report gains of 2.00 to 7.01 points over Meta-Harness across four domains and 14.6% lower total cost including search. |
| 2026‑10‑01<br><sub>Paper</sub> | [**Safety Must Survive Self-Improvement: Why Failures Persist and How Agents Recover**](https://arxiv.org/abs/2610.01073)<br><sub>Yunbei Zhang et al. · arXiv</sub> | In a controlled authorization testbed, the authors find that stale scores preserve unsafe agents in 22 of 48 framework histories after requirements change. Full validation and validated rollback yield fully correct programs in the core study while retaining over 43% deployment savings. |
| 2026‑09‑29<br><sub>Model update</sub> | [**Introducing GPT-6.1 Sol**](https://openai.com/index/introducing-gpt-6-1-sol/)<br><sub>OpenAI</sub> | OpenAI reports a 6.4-point DeepSWE v1.1 gain over GPT-6 Sol at lower reasoning effort and cost, and seven points on OSWorld 2.0 offline at maximum effort. On Terminal-Bench Science 0.1, it reports an average cost of $5.47 per task at maximum effort versus $23.80 for Astra. |
| 2026‑09‑17<br><sub>Paper</sub> | [**SoL-Pi: Recursively Scaling Auto-Research Loops for Efficient Agent Harness**](https://arxiv.org/abs/2609.20519)<br><sub>Haozhe Liu et al. · arXiv</sub> | The authors release SoL-Pi after auto-research selects reusable mechanisms for execution, compaction, observations and delegated reading. On 51 EdgeBench tasks with two model backbones, they report performance comparable to Pi while reducing recorded token traffic by 44.7-49.0% and API cost by about one third. |

> **Want next week's news?** Watch the repository. Citation counts, rankings, and the weekly news picks are published with maintainer updates. [Browse past editions →](highlights/README.md)

## 📈 Live Rankings

> Citation counts are current through **2026-10-13** from Semantic Scholar and OpenAlex. Rankings are discovery aids, not quality scores; audit evidence remains independent of popularity. GitHub stars are snapshots from **2026-10-13**. For papers indexed as multiple versions, retain the largest title-verified count reported by the configured sources. All yearly rankings use first public appearance year; a later venue year never moves a paper into a newer cohort.

### Top Ranking Papers by Average Monthly Citations

| Paper | Venue | Date | Citations | Avg. cites/month | Code |
|:--|:--:|:--:|:--:|:--:|:--:|
| [**Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces**](https://arxiv.org/abs/2601.11868) | arXiv | <nobr>2026-01</nobr> | 570 | **63.3** | [GitHub](https://github.com/harbor-framework/terminal-bench-1) · ★ 2,600 |
| [**AlphaEvolve: A coding agent for scientific and algorithmic discovery**](https://arxiv.org/abs/2506.13131) | arXiv | <nobr>2025-06</nobr> | 1012 | **63.2** | — |
| [**Towards End-to-End Automation of AI Research**](https://doi.org/10.1038/s41586-026-10265-5) | Nature 2026 | <nobr>2026-03</nobr> | 302 | **43.1** | [GitHub](https://github.com/SakanaAI/AI-Scientist-v2) · ★ 7,318 |
| [**Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory**](https://doi.org/10.3233/faia251160) | European Conference on Artificial Intelligence (ECAI) | <nobr>2025-04</nobr> | 775 | **43.1** | [GitHub](https://github.com/mem0ai/mem0) · ★ 67,091 |
| [**Meta-Harness: End-to-End Optimization of Model Harnesses**](https://arxiv.org/abs/2603.28052) | arXiv | <nobr>2026-03</nobr> | 279 | **39.9** | [GitHub](https://github.com/stanford-iris-lab/meta-harness-tbench2-artifact) · ★ 1,233 |
| [**The Berkeley Function Calling Leaderboard (BFCL): From tool use to agentic evaluation of large language models**](https://proceedings.mlr.press/v267/patil25a.html) | Proceedings of the 42nd International Conference on Machine Learning | <nobr>2025</nobr> | 607 | **37.9** | [GitHub](https://github.com/ShishirPatil/gorilla) · ★ 13,050 |
| [**Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models**](https://arxiv.org/abs/2510.04618) | arXiv | <nobr>2025-10</nobr> | 414 | **34.5** | [GitHub](https://github.com/ace-agent/ace) · ★ 1,361 |
| [**Kimi K3: Open Frontier Intelligence**](https://arxiv.org/abs/2607.24653) | arXiv | <nobr>2026-07</nobr> | 94 | **31.3** | [GitHub](https://github.com/MoonshotAI/Kimi-K3) · ★ 8,917 |
| [**LLMs Get Lost In Multi-Turn Conversation**](https://arxiv.org/abs/2505.06120) | International Conference on Learning Representations | <nobr>2025-05</nobr> | 513 | **30.2** | [GitHub](https://github.com/microsoft/lost_in_conversation) · ★ 301 |
| [**Group-in-Group Policy Optimization for LLM Agent Training**](https://arxiv.org/abs/2505.10978) | Advances in Neural Information Processing Systems | <nobr>2025-05</nobr> | 507 | **29.8** | [GitHub](https://github.com/langfengQ/verl-agent) · ★ 2,371 |

### 🏆 Most-Cited Papers by Year

<details open markdown="1">
<summary><b>Top 12 of 2026</b> by citations</summary>

| Paper | Date | Citations | Code |
|:--|:--:|:--:|:--:|
| [**Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces**](https://arxiv.org/abs/2601.11868)<br><sub>arXiv</sub> | <nobr>2026-01</nobr> | 570 | [GitHub](https://github.com/harbor-framework/terminal-bench-1) · ★ 2,600 |
| [**Towards End-to-End Automation of AI Research**](https://doi.org/10.1038/s41586-026-10265-5)<br><sub>Nature 2026</sub> | <nobr>2026-03</nobr> | 302 | [GitHub](https://github.com/SakanaAI/AI-Scientist-v2) · ★ 7,318 |
| [**Meta-Harness: End-to-End Optimization of Model Harnesses**](https://arxiv.org/abs/2603.28052)<br><sub>arXiv</sub> | <nobr>2026-03</nobr> | 279 | [GitHub](https://github.com/stanford-iris-lab/meta-harness-tbench2-artifact) · ★ 1,233 |
| [**Kimi K3: Open Frontier Intelligence**](https://arxiv.org/abs/2607.24653)<br><sub>arXiv</sub> | <nobr>2026-07</nobr> | 94 | [GitHub](https://github.com/MoonshotAI/Kimi-K3) · ★ 8,917 |
| [**Self-Harness: Harnesses That Improve Themselves**](https://arxiv.org/abs/2606.09498)<br><sub>arXiv</sub> | <nobr>2026-06</nobr> | 84 | [GitHub](https://github.com/qzzqzzb/Self-Harness) · ★ 125 |
| [**Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering**](https://arxiv.org/abs/2604.08224)<br><sub>arXiv preprint arXiv:2604.08224</sub> | <nobr>2026-04</nobr> | 71 | — |
| [**Hindsight Credit Assignment for Long-Horizon LLM Agents**](https://arxiv.org/abs/2603.08754)<br><sub>arXiv preprint arXiv:2603.08754</sub> | <nobr>2026-03</nobr> | 59 | — |
| [**Natural-Language Agent Harnesses**](https://arxiv.org/abs/2603.25723)<br><sub>arXiv</sub> | <nobr>2026-03</nobr> | 55 | — |
| [**DeepSWE: Measuring Frontier Coding Agents on Original, Long-Horizon Engineering Tasks**](https://arxiv.org/abs/2607.07946)<br><sub>arXiv preprint arXiv:2607.07946</sub> | <nobr>2026-07</nobr> | 53 | [GitHub](https://github.com/datacurve-ai/deep-swe) · ★ 1,818 |
| [**SWE-Pruner: Self-Adaptive Context Pruning for Coding Agents**](https://arxiv.org/abs/2601.16746)<br><sub>arXiv preprint arXiv:2601.16746</sub> | <nobr>2026-01</nobr> | 53 | [GitHub](https://github.com/Ayanami1314/swe-pruner) · ★ 320 |
| [**PostTrainBench: Can LLM Agents Automate LLM Post-Training?**](https://arxiv.org/abs/2603.08640)<br><sub>arXiv</sub> | <nobr>2026-03</nobr> | 52 | [GitHub](https://github.com/aisa-group/PostTrainBench) · ★ 590 |
| [**SkillOS: Learning Skill Curation for Self-Evolving Agents**](https://arxiv.org/abs/2605.06614)<br><sub>arXiv</sub> | <nobr>2026-05</nobr> | 51 | — |

</details>

<details markdown="1">
<summary><b>Top 12 of 2025</b> by citations</summary>

| Paper | Date | Citations | Code |
|:--|:--:|:--:|:--:|
| [**A-MEM: Agentic Memory for LLM Agents**](https://arxiv.org/abs/2502.12110)<br><sub>Advances in Neural Information Processing Systems</sub> | <nobr>2025-02</nobr> | 1181 | [GitHub](https://github.com/WujiangXu/A-mem) · ★ 987 |
| [**AlphaEvolve: A coding agent for scientific and algorithmic discovery**](https://arxiv.org/abs/2506.13131)<br><sub>arXiv</sub> | <nobr>2025-06</nobr> | 1012 | — |
| [**Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory**](https://doi.org/10.3233/faia251160)<br><sub>European Conference on Artificial Intelligence (ECAI)</sub> | <nobr>2025-04</nobr> | 775 | [GitHub](https://github.com/mem0ai/mem0) · ★ 67,091 |
| [**Why Do Multi-Agent LLM Systems Fail?**](https://proceedings.neurips.cc/paper_files/paper/2025/hash/b1041e52d3be19f0a9bc491657488e4a-Abstract-Datasets_and_Benchmarks_Track.html)<br><sub>Advances in Neural Information Processing Systems</sub> | <nobr>2025-03</nobr> | 722 | [GitHub](https://github.com/multi-agent-systems-failure-taxonomy/MAST) · ★ 424 |
| [**The Berkeley Function Calling Leaderboard (BFCL): From tool use to agentic evaluation of large language models**](https://proceedings.mlr.press/v267/patil25a.html)<br><sub>Proceedings of the 42nd International Conference on Machine Learning</sub> | <nobr>2025</nobr> | 607 | [GitHub](https://github.com/ShishirPatil/gorilla) · ★ 13,050 |
| [**LLMs Get Lost In Multi-Turn Conversation**](https://arxiv.org/abs/2505.06120)<br><sub>International Conference on Learning Representations</sub> | <nobr>2025-05</nobr> | 513 | [GitHub](https://github.com/microsoft/lost_in_conversation) · ★ 301 |
| [**Group-in-Group Policy Optimization for LLM Agent Training**](https://arxiv.org/abs/2505.10978)<br><sub>Advances in Neural Information Processing Systems</sub> | <nobr>2025-05</nobr> | 507 | [GitHub](https://github.com/langfengQ/verl-agent) · ★ 2,371 |
| [**Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models**](https://arxiv.org/abs/2510.04618)<br><sub>arXiv</sub> | <nobr>2025-10</nobr> | 414 | [GitHub](https://github.com/ace-agent/ace) · ★ 1,361 |
| [**Darwin Godel Machine: Open-ended evolution of self-improving agents**](https://openreview.net/forum?id=pUpzQZTvGY)<br><sub>arXiv</sub> | <nobr>2025-05</nobr> | 346 | [GitHub](https://github.com/jennyzzt/dgm) · ★ 2,412 |
| [**PaperBench: Evaluating AI's ability to replicate AI research**](https://arxiv.org/abs/2504.01848)<br><sub>arXiv</sub> | <nobr>2025-04</nobr> | 323 | [GitHub](https://github.com/openai/frontier-evals) · ★ 1,315 |
| [**Memory in the Age of AI Agents**](https://arxiv.org/abs/2512.13564)<br><sub>arXiv preprint arXiv:2512.13564</sub> | <nobr>2025-12</nobr> | 290 | — |
| [**SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?**](https://arxiv.org/abs/2509.16941)<br><sub>arXiv</sub> | <nobr>2025-09</nobr> | 287 | [GitHub](https://github.com/scaleapi/SWE-bench_Pro-os) · ★ 542 |

</details>

<details markdown="1">
<summary><b>Top 12 of 2024</b> by citations</summary>

| Paper | Date | Citations | Code |
|:--|:--:|:--:|:--:|
| [**τ-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains**](https://arxiv.org/abs/2406.12045)<br><sub>arXiv</sub> | <nobr>2024-06</nobr> | 1430 | [GitHub](https://github.com/sierra-research/tau-bench) · ★ 1,460 |
| [**OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**](https://arxiv.org/abs/2404.07972)<br><sub>NeurIPS 2024</sub> | <nobr>2024-04</nobr> | 1312 | [GitHub](https://github.com/xlang-ai/OSWorld) · ★ 3,202 |
| [**Self-rewarding language models**](https://proceedings.mlr.press/v235/yuan24d.html)<br><sub>arXiv</sub> | <nobr>2024-01</nobr> | 756 | — |
| [**Demystifying LLM-Based Software Engineering Agents**](https://doi.org/10.1145/3715754)<br><sub>Proceedings of the ACM on Software Engineering</sub> | <nobr>2024-07</nobr> | 545 | [GitHub](https://github.com/OpenAutoCoder/Agentless) · ★ 2,124 |
| [**TravelPlanner: A Benchmark for Real-World Planning with Language Agents**](https://arxiv.org/abs/2402.01622)<br><sub>International Conference on Machine Learning</sub> | <nobr>2024-02</nobr> | 501 | [GitHub](https://github.com/OSU-NLP-Group/TravelPlanner) · ★ 555 |
| [**WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**](https://arxiv.org/abs/2401.13919)<br><sub>Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)</sub> | <nobr>2024-01</nobr> | 484 | [GitHub](https://github.com/MinorJerry/WebVoyager) · ★ 1,127 |
| [**MLE-bench: Evaluating machine learning agents on machine learning engineering**](https://arxiv.org/abs/2410.07095)<br><sub>ICLR 2025</sub> | <nobr>2024-10</nobr> | 476 | [GitHub](https://github.com/openai/mle-bench) · ★ 1,772 |
| [**AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents**](https://arxiv.org/abs/2405.14573)<br><sub>International Conference on Learning Representations</sub> | <nobr>2024-05</nobr> | 474 | [GitHub](https://github.com/google-research/android_world) · ★ 949 |
| [**Automated design of agentic systems**](https://arxiv.org/abs/2408.08435)<br><sub>ICLR 2025</sub> | <nobr>2024-08</nobr> | 413 | [GitHub](https://github.com/ShengranHu/ADAS) · ★ 1,646 |
| [**AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents**](https://arxiv.org/abs/2407.18901)<br><sub>ACL 2024</sub> | <nobr>2024-07</nob