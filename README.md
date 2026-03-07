# A Survey on RAG Robustness [![Awesome](https://awesome.re/badge.svg)](https://github.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#license) ![](https://img.shields.io/badge/PRs-Welcome-red)

> This repository collects papers on the **robustness of Retrieval-Augmented Generation (RAG)** systems.

Welcome to recommend missing papers through **Issues** or **Pull Requests**.

---

## News

- **2026-03**: Repository initialized for **A Survey on RAG Robustness**.

---

## Content

- [📖 About](#about)
- [📜 Paper list](#paper-list)
- [⚔️ Attack Taxonomy](#attack-taxonomy)
- [🛡️ Defense Taxonomy](#defense-taxonomy)
- [📊 Benchmarking and Evaluation](#benchmarking-and-evaluation)
- [🔍 Explainability for RAG Robustness](#explainability-for-rag-robustness)
- [🚀 Emerging RAG Architectures and Applications](#emerging-rag-architectures-and-applications)
- [🔗 Contribution](#contribution)
- [📎 Citation](#citation)
- [⚖️ License](#license)

---

## About

This repository maintains a paper list on **robustness of RAG**: attack objectives, attack surfaces, defenses, evaluation, and emerging settings.

---

## Paper list
 
### Other Survey

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2409.10102)] Trustworthiness in Retrieval-Augmented Generation Systems: A Survey. `2024.09`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2502.06872)] Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey. `2025.02`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/PCDS65695.2025.00037)] Retrieval-Augmented Generation: A Survey of Security Challenges and Countermeasures. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2409.03274)] Recent Advances in Attack and Defense Approaches of Large Language Models. `2024.09`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/AITest66680.2025.00015)] Surveying the RAG Attack Surface and Defenses: Protecting Sensitive Company Data. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-emnlp.185/)] Safety in Large Reasoning Models: A Survey. `2025.11`

### Attack Taxonomy

#### Privacy Attacks

* [[<ins>arxiv</ins>](https://doi.org/10.5220/0013108300003899)] Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2507.23229)] Fine-Grained Privacy Extraction from Retrieval-Augmented Generation Systems via Knowledge Asymmetry Exploitation. `2025.07`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3696410.3714771)] Mask-based Membership Inference Attacks for Retrieval-Augmented Generation. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2411.01705)] Data Extraction Attacks in Retrieval-Augmented Generation via Backdoors. `2025`
* [[<ins>arxiv</ins>](https://www.defcon.org)] ConfusedPilot: Confused Deputy Risks in RAG-based LLMs. `2024`
* [[<ins>arxiv</ins>](https://doi.org/10.1007/s11432-024-4441-4)] RAG-leaks: Difficulty-calibrated membership inference attacks on retrieval-augmented generation. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/ICASSP49660.2025.10889013)] Generating Is Believing: Membership Inference Attacks against Retrieval-Augmented Generation. `2025`

#### Accuracy Attacks

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2406.00083)] BadRAG: Identifying Vulnerabilities in Retrieval Augmented Generation of Large Language Models. `2024.06`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.emnlp-main.96/)] Glue pizza and eat rocks - Exploiting Vulnerabilities in Retrieval-Augmented Generative Models. `2024.11`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=Y841BRW9rY)] AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases. `2024`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=S1Bv3068Xt)] Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-Based Decision-Making Systems. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-emnlp.1291/)] The RAG Paradox: A Black-Box Attack Exploiting Unintentional Vulnerabilities in Retrieval-Augmented Generation Systems. `2025.11`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2405.20485)] Phantom: General Backdoor Attacks on Retrieval Augmented Language Generation. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.findings-emnlp.161/)] Typos that Broke the RAG's Back: Genetic Attack on RAG Pipeline by Simulating Documents in the Wild via Low-level Perturbations. `2024.11`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3726302.3730058)] PR-Attack: Coordinated Prompt-RAG Attacks on Retrieval-Augmented Generation in Large Language Models via Bilevel Optimization. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2405.13401)] TrojanRAG: Retrieval-Augmented Generation Can Be Backdoor Driver in Large Language Models. `2024.05`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2409.17275)] On the Vulnerability of Applying Retrieval-Augmented Generation within Knowledge-Intensive Application Domains. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2023.emnlp-main.849/)] Poisoning Retrieval Corpora by Injecting Adversarial Passages. `2023.12`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3689932.3694764)] Neural Exec: Learning (and Learning from) Execution Triggers for Prompt Injection Attacks. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2503.21315)] Tricking Retrievers with Influential Tokens: An Efficient Black-Box Corpus Poisoning Attack. `2025.03`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.10008)] RIPRAG: Hack a Black-box Retrieval-Augmented Generation Question-Answering System with Reinforcement Learning. `2025.10`
* [[<ins>arxiv</ins>](https://aclanthology.org/venues/findings-of-the-association-for-computational-linguistics-acl/)] Corpus poisoning via approximate greedy gradient descent. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2410.02163)] Adversarial decoding: Generating readable documents for adversarial objectives. `2024.10`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.11548)] One shot dominance: Knowledge poisoning attack on retrieval-augmented generation systems. `2025.05`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.18652)] UniC-RAG: Universal Knowledge Corruption Attacks to Retrieval-Augmented Generation. `2025.08`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2410.06628)] Does Vec2Text Pose a New Corpus Poisoning Threat? `2024.10`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2503.16248)] Real AI Agents with Fake Memories: Fatal Context Manipulation Attacks on Web3 Agents. `2025.03`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-ijcnlp.66/)] Illusions of Relevance: Arbitrary Content Injection Attacks Deceive Retrievers, Rerankers, and LLM Judges. `2025.12`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.06579)] POISONCRAFT: Practical Poisoning of Retrieval-Augmented Generation for Large Language Models. `2025.05`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-main.801/)] AIP: Subverting Retrieval-Augmented Generation via Adversarial Instructional Prompt. `2025.11`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.00586)] Eyes-on-Me: Scalable RAG Poisoning through Transferable Attention-Steering Attractors. `2025.10`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.19864)] CPA-RAG: Covert Poisoning Attacks on Retrieval-Augmented Generation in Large Language Models. `2025.05`
* [[<ins>arxiv</ins>](https://doi.org/10.1007/978-3-031-88717-8_18)] Poison-RAG: Adversarial Data Poisoning Attacks on Retrieval-Augmented Generation in Recommender Systems. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.03110)] Token-Level Precise Attack on RAG: Searching for the Best Alternatives to Mislead Generation. `2025.08`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-acl.717/)] The Silent Saboteur: Imperceptible Adversarial Attacks against Black-Box Retrieval-Augmented Generation Systems. `2025.07`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.13842)] ADMIT: Few-shot Knowledge Poisoning Attacks on RAG-based Fact Checking. `2025.10`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2506.06151)] Joint-GCG: Unified Gradient-Based Poisoning Attacks on Retrieval-Augmented Generation Systems. `2025.06`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2504.21680)] Hoist with His Own Petard: Inducing Guardrails to Facilitate Denial-of-Service Attacks on Retrieval-Augmented Generation of LLMs. `2025.04`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2408.05061)] A Jailbroken GenAI Model Can Cause Substantial Harm: GenAI-powered Applications are Vulnerable to PromptWares. `2024.08`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2407.13757)] Black-Box Opinion Manipulation Attacks to Retrieval-Augmented Generation of Large Language Models. `2024.07`
* [[<ins>arxiv</ins>](https://www.usenix.org/conference/usenixsecurity25)] PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models. `2025`
* [[<ins>arxiv</ins>](https://www.usenix.org/conference/usenixsecurity25)] Topic-FlipRAG: Topic-Oriented Adversarial Opinion Manipulation Attacks to Retrieval-Augmented Generation Models. `2025`

#### Fairness Attacks

* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-main.804/)] Your RAG is Unfair: Exposing Fairness Vulnerabilities in Retrieval-Augmented Generation via Backdoor Attacks. `2025.11`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2506.11415)] Bias Amplification in RAG: Poisoning Knowledge Retrieval to Steer LLMs. `2025.06`

---

### Defense Taxonomy

#### Retrieval-Stage Defenses

#### Reranking-Stage Defenses

#### Generation-Stage Defenses

#### Passive Defenses

#### Proactive Defenses

#### Traceback / Attribution Defenses

---

### Benchmarking and Evaluation

---

### Explainability for RAG Robustness

#### Attribution Explanations

#### Mechanistic Explanations

---

### Emerging RAG Architectures and Applications

#### GraphRAG

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2501.14050)] GraphRAG under Fire. `2025.01`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2507.08862)] RAG Safety: Exploring Knowledge Poisoning Attacks to Retrieval-Augmented Generation. `2025.07`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.04276)] A Few Words Can Distort Graphs: Knowledge Poisoning Attacks on Graph-based Retrieval-Augmented Generation of Large Language Models. `2025.08`

#### Medical RAG

* [[<ins>arxiv</ins>](https://doi.org/10.1145/3696410.3714782)] MedRAG: Enhancing Retrieval-augmented Generation with Knowledge Graph-Elicited Reasoning for Healthcare Copilot. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.acl-long.1381/)] Medical Graph RAG: Evidence-based Medical Large Language Model via Graph Retrieval-Augmented Generation. `2025.07`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=Swy0XEqJdA)] Signature-Guided Adversarial Attacks On Healthcare LLMs: Exposing PII Leakage In RAG Systems. `2026`
* [[<ins>arxiv</ins>](https://www.semanticscholar.org/paper/266551228)] HyKGE: A Hypothesis Knowledge Graph Enhanced Framework for Accurate and Reliable Medical LLMs Responses. `2023`

#### Multimodal RAG

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.23828)] Spa-VLM: Stealthy Poisoning Attacks on RAG-based VLM. `2025.05`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2502.17832)] MM-PoisonRAG: Disrupting Multimodal RAG with Local and Global Poisoning Attacks. `2025.02`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2511.15435)] HV-Attack: Hierarchical Visual Attack for Multimodal Retrieval Augmented Generation. `2025.11`


---

## Contribution

### 👥 Contributors

<p align="left">
  <a href="https://github.com/coutMinh"><img src="https://github.com/coutMinh.png?size=64" width="64" height="64" style="border-radius: 50%; border: 2px solid #e1e4e8;" alt="coutMinh" /></a>
  <a href="https://github.com/CaptainCuong"><img src="https://github.com/CaptainCuong.png?size=64" width="64" height="64" style="border-radius: 50%; border: 2px solid #e1e4e8;" alt="CaptainCuong" /></a>
  <a href="https://github.com/nguyentuc"><img src="https://github.com/nguyentuc.png?size=64" width="64" height="64" style="border-radius: 50%; border: 2px solid #e1e4e8;" alt="nguyentuc" /></a>
  <a href="https://github.com/suzhentxt"><img src="https://github.com/suzhentxt.png?size=64" width="64" height="64" style="border-radius: 50%; border: 2px solid #e1e4e8;" alt="suzhentxt" /></a>
  <a href="https://github.com/minngh"><img src="https://github.com/minngh.png?size=64" width="64" height="64" style="border-radius: 50%; border: 2px solid #e1e4e8;" alt="minngh" /></a>
  <a href="https://github.com/kien206"><img src="https://github.com/kien206.png?size=64" width="64" height="64" style="border-radius: 50%; border: 2px solid #e1e4e8;" alt="kien206" /></a>
</p>

### 🎉 How to contribute

If you’re working on RAG robustness—attacks, defenses, evaluation, or anything that makes retrieval-augmented systems more reliable—we’d love to hear from you. Share your papers, point out what we missed, or suggest new directions. Open an [Issue](https://github.com/OWNER/REPO/issues) or send a [Pull Request](https://github.com/OWNER/REPO/pulls); we’re happy to grow this list with the community.

---

## Citation

If you find this repository useful, please cite our survey:

```bibtex
@article{ragrobustnesssurvey2026,
  title   = {A Survey on RAG Robustness},
  author  = {Anonymous},
  journal = {arXiv preprint arXiv:XXXX.XXXXX},
  year    = {2026}
}
```

---

## License

This repository is intended for academic and research use. Please check the paper and code licenses of the original works referenced here.
