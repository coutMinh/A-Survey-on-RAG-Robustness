# A Survey on RAG Robustness [![Awesome](https://awesome.re/badge.svg)](https://github.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#license) ![](https://img.shields.io/badge/PRs-Welcome-red)

> This repository collects papers on the **robustness of Retrieval-Augmented Generation (RAG)** systems.

Welcome to recommend missing papers through **Issues** or **Pull Requests**.

---

## News

- **2026-08**: Paper accepted to **Findings of EMNLP 2026**.
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

### Other Surveys

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2409.10102)] Trustworthiness in Retrieval-Augmented Generation Systems: A Survey. — Yujia Zhou, Yan Liu, Xiaoxi Li, Jiajie Jin, Hongjin Qian, Zheng Liu, Chaozhuo Li, Zhicheng Dou, Tsung-Yi Ho, and Philip S. Yu. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2502.06872)] Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey. — Bo Ni, Zheyuan Liu, Leyao Wang, Yongjia Lei, Yuying Zhao, Xueqi Cheng, Qingkai Zeng, Luna Dong, Yinglong Xia, Krishnaram Kenthapadi, Ryan Rossi, Franck Dernoncourt, Md Mehrab Tanjim, Nesreen Ahmed, Xiaorui Liu, Wenqi Fan, Erik Blasch, Yu Wang, Meng Jiang, and Tyler Derr. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/PCDS65695.2025.00037)] Retrieval-Augmented Generation: A Survey of Security Challenges and Countermeasures. — Chao Wang, Haonan Li, Weijian Song, and Yiyang Lin. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/AITest66680.2025.00015)] Surveying the RAG Attack Surface and Defenses: Protecting Sensitive Company Data. — Lynn Vonderhaar, Daniel Machado, and Omar Ochoa. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2409.03274)] Recent Advances in Attack and Defense Approaches of Large Language Models. — Jing Cui, Yishi Xu, Zhewei Huang, Shuchang Zhou, Jianbin Jiao, and Junge Zhang. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2501.09136)] Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG. — Aditi Singh, Abul Ehtesham, Saket Kumar, Tala Talaei Khoei, and Athanasios V. Vasilakos. `2026`

### Attack Taxonomy

#### Privacy Attacks

* [[<ins>arxiv</ins>](https://doi.org/10.5220/0013108300003899)] Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation. — Maya Anderson, Guy Amit, and Abigail Goldsteen. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3696410.3714771)] Mask-Based Membership Inference Attacks for Retrieval-Augmented Generation. — Mingrui Liu, Sixiao Zhang, and Cheng Long. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/ICASSP49660.2025.10889013)] Generating Is Believing: Membership Inference Attacks Against Retrieval-Augmented Generation. — Yuying Li, Gaoyang Liu, Chen Wang, and Yang Yang. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1007/s11432-024-4441-4)] RAG-Leaks: Difficulty-Calibrated Membership Inference Attacks on Retrieval-Augmented Generation. — Guangshuo Wang, Jiajun He, Hao Li, Min Zhang, and Dengguo Feng. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2411.14110)] Feedback-Guided Extraction of Knowledge Base from Retrieval-Augmented LLM Applications. — Changyue Jiang, Xudong Pan, Geng Hong, Chenfu Bao, Yang Chen, and Min Yang. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/search?term=Follow%20My%20Instruction%20and%20Spill%20the%20Beans)] Follow My Instruction and Spill the Beans: Scalable Data Extraction from Retrieval-Augmented Generation Systems. — Zhenting Qi, Hanlin Zhang, Eric P. Xing, Sham M. Kakade, and Himabindu Lakkaraju. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.findings-acl.267/)] The Good and the Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG). — Shenglai Zeng, Jiankun Zhang, Pengfei He, Yue Xing, Yiding Liu, Han Xu, Jie Ren, Shuaiqiang Wang, Dawei Yin, Yi Chang, and Jiliang Tang. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2507.23229)] Fine-Grained Privacy Extraction from Retrieval-Augmented Generation Systems via Knowledge Asymmetry Exploitation. — Yufei Chen, Yao Wang, Haibin Zhang, and Tao Gu. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2411.01705)] Data Extraction Attacks in Retrieval-Augmented Generation via Backdoors. — Yuefeng Peng, Junda Wang, Hong Yu, and Amir Houmansadr. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2408.04870)] ConfusedPilot: Confused Deputy Risks in RAG-Based LLMs. — Ayush RoyChowdhury, Mulong Luo, Prateek Sahu, Sarbartha Banerjee, and Mohit Tiwari. `2024`

#### Accuracy Attacks

* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-emnlp.1291/)] The RAG Paradox: A Black-Box Attack Exploiting Unintentional Vulnerabilities in Retrieval-Augmented Generation Systems. — Chanwoo Choi, Jinsoo Kim, Sukmin Cho, Soyeong Jeong, and Buru Chang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.10008)] RIPRAG: Hack a Black-Box Retrieval-Augmented Generation Question-Answering System with Reinforcement Learning. — Meng Xi, Sihan Lv, Yechen Jin, Guanjie Cheng, Naibo Wang, Ying Li, and Jianwei Yin. `2026`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.11548)] One Shot Dominance: Knowledge Poisoning Attack on Retrieval-Augmented Generation Systems. — Zhiyuan Chang, Mingyang Li, Xiaojun Jia, Junjie Wang, Yuekai Huang, Ziyou Jiang, Yang Liu, and Qing Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2410.06628)] Does Vec2Text Pose a New Corpus Poisoning Threat? — Shengyao Zhuang, Bevan Koopman, and Guido Zuccon. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2502.01386)] Topic-FlipRAG: Topic-Orientated Adversarial Opinion Manipulation Attacks to Retrieval-Augmented Generation Models. — Yuyang Gong, Zhuo Chen, Jiawei Liu, Miaokun Chen, Fengchang Yu, Wei Lu, Xiaofeng Wang, and Xiaozhong Liu. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.19864)] CPA-RAG: Covert Poisoning Attacks on Retrieval-Augmented Generation in Large Language Models. — Chunyang Li, Junwei Zhang, Anda Cheng, Zhuo Ma, Xinghua Li, and Jianfeng Ma. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.findings-emnlp.161/)] Typos that Broke the RAG's Back: Genetic Attack on RAG Pipeline by Simulating Documents in the Wild via Low-Level Perturbations. — Sukmin Cho, Soyeong Jeong, Jeongyeon Seo, Taeho Hwang, and Jong C. Park. `2024`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-acl.717/)] The Silent Saboteur: Imperceptible Adversarial Attacks Against Black-Box Retrieval-Augmented Generation Systems. — Hongru Song, Yu-An Liu, Ruqing Zhang, Jiafeng Guo, Jianming Lv, Maarten de Rijke, and Xueqi Cheng. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.13842)] ADMIT: Few-Shot Knowledge Poisoning Attacks on RAG-Based Fact Checking. — Yutao Wu, Xiao Liu, Yinghui Li, Yifeng Gao, Yifan Ding, Jiale Ding, Xiang Zheng, and Xingjun Ma. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2407.13757)] Black-Box Opinion Manipulation Attacks to Retrieval-Augmented Generation of Large Language Models. — Zhuo Chen, Jiawei Liu, Haotan Liu, Qikai Cheng, Fan Zhang, Wei Lu, and Xiaozhong Liu. `2024`
* [[<ins>arxiv</ins>](https://doi.org/10.1007/978-3-031-88717-8_18)] Poison-RAG: Adversarial Data Poisoning Attacks on Retrieval-Augmented Generation in Recommender Systems. — Fatemeh Nazary, Yashar Deldjoo, and Tommaso Di Noia. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2402.07867)] PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models. — Wei Zou, Runpeng Geng, Binghui Wang, and Jinyuan Jia. `2024`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-acl.222/)] Corpus Poisoning via Approximate Greedy Gradient Descent. — Jinyan Su, Preslav Nakov, and Claire Cardie. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.06579)] PoisonCraft: Practical Poisoning of Retrieval-Augmented Generation for Large Language Models. — Yangguang Shao, Xinjie Lin, Haozheng Luo, Chengshang Hou, Gang Xiong, Jiahao Yu, and Junzheng Shi. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.00586)] Eyes-on-Me: Scalable RAG Poisoning Through Transferable Attention-Steering Attractors. — Yen-Shan Chen, Sian-Yao Huang, Cheng-Lin Yang, and Yun-Nung Chen. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.03110)] Token-Level Precise Attack on RAG: Searching for the Best Alternatives to Mislead Generation. — Zizhong Li, Haopeng Zhang, and Jiawei Zhang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2506.06151)] Joint-GCG: Unified Gradient-Based Poisoning Attacks on Retrieval-Augmented Generation Systems. — Haowei Wang, Rupeng Zhang, Junjie Wang, Mingyang Li, Yuekai Huang, Dandan Wang, and Qing Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2504.21680)] Hoist with His Own Petard: Inducing Guardrails to Facilitate Denial-of-Service Attacks on Retrieval-Augmented Generation of LLMs. — Pan Suo, Yu-Ming Shang, San-Chuan Guo, and Xi Zhang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2409.17275)] On the Vulnerability of Applying Retrieval-Augmented Generation Within Knowledge-Intensive Application Domains. — Xun Xian, Ganghua Wang, Xuan Bi, Jayanth Srinivasa, Ashish Kundu, Charles Fleming, Mingyi Hong, and Jie Ding. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2410.02163)] Adversarial Decoding: Generating Readable Documents for Adversarial Objectives. — Collin Zhang, Tingwei Zhang, and Vitaly Shmatikov. `2026`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2405.20485)] Phantom: General Backdoor Attacks on Retrieval Augmented Language Generation. — Harsh Chaudhari, Giorgio Severi, John Abascal, Anshuman Suri, Matthew Jagielski, Christopher A. Choquette-Choo, Milad Nasr, Cristina Nita-Rotaru, and Alina Oprea. `2026`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-main.801/)] AIP: Subverting Retrieval-Augmented Generation via Adversarial Instructional Prompt. — Saket Sanjeev Chaturvedi, Gaurav Bagwe, Lan Emily Zhang, and Xiaoyong Yuan. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3726302.3730058)] PR-Attack: Coordinated Prompt-RAG Attacks on Retrieval-Augmented Generation in Large Language Models via Bilevel Optimization. — Yang Jiao, Xiaodong Wang, and Kai Yang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2405.13401)] TrojanRAG: Retrieval-Augmented Generation Can Be Backdoor Driver in Large Language Models. — Pengzhou Cheng, Yidong Ding, Tianjie Ju, Zongru Wu, Wei Du, Ping Yi, Zhuosheng Zhang, and Gongshen Liu. `2024`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=S1Bv3068Xt)] Can We Trust Embodied Agents? Exploring Backdoor Attacks Against Embodied LLM-Based Decision-Making Systems. — Ruochen Jiao, Shaoyuan Xie, Justin Yue, Takami Sato, Lixu Wang, Yixuan Wang, Qi Alfred Chen, and Qi Zhu. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=Y841BRW9rY)] AgentPoison: Red-Teaming LLM Agents via Poisoning Memory or Knowledge Bases. — Zhaorun Chen, Zhen Xiang, Chaowei Xiao, Dawn Song, and Bo Li. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2503.16248)] Real AI Agents with Fake Memories: Fatal Context Manipulation Attacks on Web3 Agents. — Atharv Singh Patlan, Peiyao Sheng, S. Ashwin Hebbar, Prateek Mittal, and Pramod Viswanath. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3689932.3694764)] Neural Exec: Learning (and Learning from) Execution Triggers for Prompt Injection Attacks. — Dario Pasquini, Martin Strohmeier, and Carmela Troncoso. `2024`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-ijcnlp.66/)] Illusions of Relevance: Arbitrary Content Injection Attacks Deceive Retrievers, Rerankers, and LLM Judges. — Manveer Singh Tamber and Jimmy Lin. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.emnlp-main.96/)] Glue Pizza and Eat Rocks—Exploiting Vulnerabilities in Retrieval-Augmented Generative Models. — Zhen Tan, Chengshuai Zhao, Raha Moraffah, Yifan Li, Song Wang, Jundong Li, Tianlong Chen, and Huan Liu. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.18652)] UniC-RAG: Universal Knowledge Corruption Attacks to Retrieval-Augmented Generation. — Runpeng Geng, Yanting Wang, Ying Chen, and Jinyuan Jia. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2503.21315)] Tricking Retrievers with Influential Tokens: An Efficient Black-Box Corpus Poisoning Attack. — Cheng Wang, Yiwei Wang, Yujun Cai, and Bryan Hooi. `2025`

#### Fairness Attacks

* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-main.804/)] Your RAG Is Unfair: Exposing Fairness Vulnerabilities in Retrieval-Augmented Generation via Backdoor Attacks. — Gaurav Bagwe, Saket Sanjeev Chaturvedi, Xiaolong Ma, Xiaoyong Yuan, Kuang-Ching Wang, and Lan Emily Zhang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2506.11415)] Bias Amplification in RAG: Poisoning Knowledge Retrieval to Steer LLMs. — Linlin Wang, Tianqing Zhu, Laiqiao Qin, Longxiang Gao, and Wanlei Zhou. `2025`

---

### Defense Taxonomy

#### Retrieval-Stage Defenses

##### Robust Retrieval

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2503.05037)] Collapse of Dense Retrievers: Short, Early, and Literal Biases Outranking Factual Evidence. — Mohsen Fayyaz, Ali Modarressi, Hinrich Schuetze, and Nanyun Peng. `2025`
* [[<ins>arxiv</ins>](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2024/EECS-2024-84.html)] Advancing Robust and Aligned Measures of Semantic Similarity in Large Language Models. — Samarth Goel. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2412.12632)] What External Knowledge Is Preferred by LLMs? Characterizing and Exploring Chain of Evidence in Imperfect Context for Multi-Hop QA. — Zhiyuan Chang, Mingyang Li, Xiaojun Jia, Junjie Wang, Yuekai Huang, Qing Wang, Yihao Huang, and Yang Liu. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.20768)] RAGRank: Using PageRank to Counter Poisoning in CTI LLM Pipelines. — Austin Jia, Avaneesh Ramesh, Zain Shamsi, Daniel Zhang, and Alex Liu. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.09710)] SeCon-RAG: A Two-Stage Semantic Filtering and Conflict-Free Framework for Trustworthy RAG. — Xiaonan Si, Meilin Zhu, Simeng Qin, Lijia Yu, Lijun Zhang, Shuaitong Liu, Xinfeng Li, Ranjie Duan, Yang Liu, and Xiaojun Jia. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/OPTIM-ACEMP62776.2025.11075247)] Disrupting Large Language Models with Hidden Prompt Injection Attacks Embedded in HTML Pages. — Ionuț-Vlăduț Dinu, Gabriel-Mihail Danciu, Raul Cristian Vintilă, and Titus-Constantin Bălan. `2025`
* [[<ins>arxiv</ins>](https://ieeexplore.ieee.org/search/searchresult.jsp?queryText=DeRAG%20Decentralized%20Multi-Source%20RAG%20System)] DeRAG: Decentralized Multi-Source RAG System with Optimized Pyth Network. — Junwei Yu and Hiroyuki Sato. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.06823)] Exposing Citation Vulnerabilities in Generative Engines. — Riku Mochizuki, Shusuke Komatsu, Souta Noguchi, and Kazuto Ataka. `2026`

##### Robust Training for Retrievers

* [[<ins>arxiv</ins>](https://aclanthology.org/2021.naacl-main.466/)] RocketQA: An Optimized Training Approach to Dense Passage Retrieval for Open-Domain Question Answering. — Yingqi Qu, Yuchen Ding, Jing Liu, Kai Liu, Ruiyang Ren, Wayne Xin Zhao, Daxiang Dong, Hua Wu, and Haifeng Wang. `2021`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.16967)] Hard Negatives, Hard Lessons: Revisiting Training Data Quality for Robust Information Retrieval with LLMs. — Nandan Thakur, Crystina Zhang, Xueguang Ma, and Jimmy Lin. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2306.10348)] Typo-Robust Representation Learning for Dense Retrieval. — Panuthep Tasawong, Wuttikorn Ponwitayarat, Peerat Limkonchotiwat, Can Udomcharoenchaikit, Ekapol Chuangsuwanich, and Sarana Nutanong. `2023`

#### Reranking-Stage Defenses

* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-main.1132/)] GRADA: Graph-Based Reranking Against Adversarial Documents Attack. — Jingjie Zheng, Aryo Pradipta Gema, Giwon Hong, Xuanli He, Pasquale Minervini, Youcheng Sun, and Qiongkai Xu. `2025`

#### Generation-Stage Defenses

##### Proactive Defenses: Filtering

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2501.00879)] TrustRAG: Enhancing Robustness and Trustworthiness in Retrieval-Augmented Generation. — Huichi Zhou, Kin-Hei Lee, Zhonghao Zhan, Yue Chen, Zhenhao Li, Zhaoyang Wang, Hamed Haddadi, and Emine Yilmaz. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2511.01268)] Rescuing the Unpoisoned: Efficient Defense Against Knowledge Corruption Attacks on RAG Systems. — Minseok Kim, Hankook Lee, and Hyungjoon Koo. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.25025)] Secure Retrieval-Augmented Generation Against Poisoning Attacks. — Zirui Cheng, Jikai Sun, Anjun Gao, Yueyang Quan, Zhuqing Liu, Xiaohua Hu, and Minghong Fang. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/search?term=ReliabilityRAG)] ReliabilityRAG: Effective and Provably Robust Defense for RAG-Based Web Search. — Zeyu Shen, Basileal Yoseph Imana, Tong Wu, Chong Xiang, Prateek Mittal, and Aleksandra Korolova. `2026`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2506.04390)] Through the Stealth Lens: Rethinking Attacks and Defenses in RAG. — Sarthak Choudhary, Nils Palumbo, Ashish Hooda, Krishnamurthy Dj Dvijotham, and Somesh Jha. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-acl.1263/)] Safeguarding RAG Pipelines with GMTP: A Gradient-Based Masked Token Probability Method for Poisoned Document Detection. — San Kim, Jonghwi Kim, Yejin Jeon, and Gary Geunbae Lee. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-main.1738/)] Retrieval-Augmented Generation with Estimation of Source Reliability. — Jeongyeon Hwang, Junyoung Park, Hyejin Park, Dongwoo Kim, Sangdon Park, and Jungseul Ok. `2025`

##### Proactive Defenses: Detection

* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-emnlp.698/)] RevPRAG: Revealing Poisoning Attacks in Retrieval-Augmented Generation Through LLM Activation Analysis. — Xue Tan, Hao Luan, Mingyu Luo, Xiaoyan Sun, Ping Chen, and Jun Dai. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2510.14005)] PIShield: Detecting Prompt Injection Attacks via Intrinsic LLM Features. — Wei Zou, Yupei Liu, Yanting Wang, Ying Chen, Neil Gong, and Jinyuan Jia. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1109/SaTML64287.2025.00011)] Get My Drift? Catching LLM Task Drift with Activation Deltas. — Sahar Abdelnabi, Aideen Fay, Giovanni Cherubin, Ahmed Salem, Mario Fritz, and Andrew Paverd. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.findings-naacl.159/)] Why So Gullible? Enhancing the Robustness of Retrieval-Augmented Models Against Counterfactual Noise. — Giwon Hong, Jeonghwan Kim, Junmo Kang, Sung-Hyon Myaeng, and Joyce Jiyoung Whang. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2507.15219)] PromptArmor: Simple Yet Effective Prompt Injection Defenses. — Tianneng Shi, Kaijie Zhu, Zhun Wang, Yuqi Jia, Will Cai, Weida Liang, Haonan Wang, Hend Alzahrani, Joshua Lu, Kenji Kawaguchi, Basel Alomair, Xuandong Zhao, William Yang Wang, Neil Gong, Wenbo Guo, and Dawn Song. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2308.14132)] Detecting Language Model Attacks with Perplexity. — Gabriel Alon and Michael Kamfonas. `2023`

##### Passive Defenses: Robust Reasoning and Generation

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2405.15556)] Certifiably Robust RAG Against Retrieval Corruption. — Chong Xiang, Tong Wu, Zexuan Zhong, David Wagner, Danqi Chen, and Prateek Mittal. `2026`
* [[<ins>arxiv</ins>](https://openreview.net/search?term=Retrieval%20Is%20Not%20Enough%20Enhancing%20RAG)] Retrieval Is Not Enough: Enhancing RAG Through Test-Time Critique and Optimization. — Jiaqi Wei, Hao Zhou, Xiang Zhang, Di Zhang, Zijie Qiu, Noah Wei, Jinzhe Li, Wanli Ouyang, and Siqi Sun. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.acl-long.1476/)] Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models. — Fei Wang, Xingchen Wan, Ruoxi Sun, Jiefeng Chen, and Sercan O. Arik. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.17118)] After Retrieval, Before Generation: Enhancing the Trustworthiness of Large Language Models in Retrieval-Augmented Generation. — Xinbang Dai, Huikang Hu, Yuncheng Hua, Jiaqi Li, Yongrui Chen, Rihui Jin, Nan Hu, and Guilin Qi. `2026`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2507.01281)] Rethinking All Evidence: Enhancing Trustworthy Retrieval-Augmented Generation via Conflict-Driven Summarization. — Juan Chen, Baolong Bi, Wei Zhang, Jingyan Sui, Xiaofei Zhu, Yuanzhuo Wang, Lingrui Mei, and Shenghua Liu. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1016/j.neucom.2025.132139)] ICR: A Framework for Resolving Knowledge Conflicts in Retrieval-Augmented Generation. — Yunxuan Xiong, Yuntao Chen, and Hai Zhang. `2026`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.findings-acl.188/)] Making RALM Robust to Irrelevant Contexts via Layer Knowledge-Guided Attention. — Weijie Shi, Hao Chen, Jiaming Li, Yao Zhao, Yazhong Zhang, Qijin Chen, Jipeng Zhang, Ruiyuan Zhang, Jia Zhu, Jiajie Xu, and Xiaofang Zhou. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2504.09593)] ControlNet: A Firewall for RAG-Based LLM Systems. — Hongwei Yao, Haoran Shi, Yidou Chen, Yixin Jiang, Cong Wang, and Zhan Qin. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.15753)] Scalable Defense Against In-the-Wild Jailbreaking Attacks with Safety Context Retrieval. — Taiye Chen, Zeming Wei, Ang Li, and Yisen Wang. `2025`

##### Passive Defenses: Robust Training for Generators

* [[<ins>arxiv</ins>](https://openreview.net/forum?id=ZS4m74kZpH)] Making Retrieval-Augmented Language Models Robust to Irrelevant Context. — Ori Yoran, Tomer Wolfson, Ori Ram, and Jonathan Berant. `2024`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.acl-long.540/)] Enhancing Noise Robustness of Retrieval-Augmented Language Models with Adaptive Adversarial Training. — Feiteng Fang, Yuelin Bai, Shiwen Ni, Min Yang, Xiaojun Chen, and Ruifeng Xu. `2024`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3726302.3730078)] Robust Fine-Tuning for Retrieval-Augmented Generation Against Retrieval Defects. — Yiteng Tu, Weihang Su, Yujia Zhou, Yiqun Liu, and Qingyao Ai. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.acl-long.261/)] RPO: Retrieval Preference Optimization for Robust Retrieval-Augmented Generation. — Shi-Qi Yan, Quan Liu, and Zhen-Hua Ling. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/search?term=To%20Trust%20or%20Not%20to%20Trust)] To Trust or Not to Trust? Enhancing Large Language Models' Situated Faithfulness to External Contexts. — Yukun Huang, Sanxing Chen, Hongyi Cai, and Bhuwan Dhingra. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=4at3O4z8dB)] InstructRAG: Instructing Retrieval-Augmented Generation via Self-Synthesized Rationales. — Zhepei Wei, Wei-Lin Chen, and Yu Meng. `2025`

#### Traceback / Attribution Defenses

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2509.13772)] Who Taught the Lie? Responsibility Attribution for Poisoned Knowledge in Retrieval-Augmented Generation. — Baolei Zhang, Haoran Xin, Yuxi Chen, Zhuqing Liu, Biao Yi, Tong Li, Lihai Nie, Zheli Liu, and Minghong Fang. `2025`
* [[<ins>arxiv</ins>](https://doi.org/10.1145/3696410.3714756)] Traceback of Poisoning Attacks to Retrieval-Augmented Generation. — Baolei Zhang, Haoran Xin, Minghong Fang, Zhuqing Liu, Biao Yi, Tong Li, and Zheli Liu. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=RSrB03W6XK)] ContextCite: Attributing Model Generation to Context. — Benjamin Cohen-Wang, Harshay Shah, Kristian Georgiev, and Aleksander Madry. `2024`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2506.04202)] TracLLM: A Generic Framework for Attributing Long-Context LLMs. — Yanting Wang, Wei Zou, Runpeng Geng, and Jinyuan Jia. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.03793)] AttnTrace: Contextual Attribution of Prompt Injection and Knowledge Corruption. — Yanting Wang, Runpeng Geng, Ying Chen, and Jinyuan Jia. `2026`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2410.03537)] WARD: Provable RAG Dataset Inference via LLM Watermarks. — Nikola Jovanović, Robin Staab, Maximilian Baader, and Martin Vechev. `2025`

---

### Benchmarking and Evaluation

* [[<ins>arxiv</ins>](https://aclanthology.org/2025.acl-long.230/)] SafeRAG: Benchmarking Security in Retrieval-Augmented Generation of Large Language Model. — Xun Liang, Simin Niu, Zhiyu Li, Sensen Zhang, Hanyu Wang, Feiyu Xiong, Zhaoxin Fan, Bo Tang, Jihao Zhao, Jiawei Yang, Shichao Song, and Mengwei Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.18543)] Benchmarking Poisoning Attacks Against Retrieval-Augmented Generation. — Baolei Zhang, Haoran Xin, Jiatong Li, Dongzhe Zhang, Minghong Fang, Zhuqing Liu, Lihai Nie, and Zheli Liu. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.12574)] PoisonArena: Uncovering Competing Poisoning Attacks in Retrieval-Augmented Generation. — Liuji Chen, Xiaofang Yang, Yuanzhuo Lu, Jinghao Zhang, Xin Sun, Qiang Liu, Shu Wu, Jing Dong, and Liang Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2512.01335)] EmoRAG: Evaluating RAG Robustness to Symbolic Perturbations. — Xinyun Zhou, Xinfeng Li, Yinan Peng, Ming Xu, Xuanwang Zhang, Miao Yu, Yidong Wang, Xiaojun Jia, Kun Wang, Qingsong Wen, Xiaofeng Wang, and Wei Dong. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.acl-short.16/)] KnowShiftQA: How Robust Are RAG Systems When Textbook Knowledge Shifts in K-12 Education? — Tianshi Zheng, Weihan Li, Jiaxin Bai, Weiqi Wang, and Yangqiu Song. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2603.19281)] URAG: A Benchmark for Uncertainty Quantification in Retrieval-Augmented Large Language Models. — Vinh Nguyen, Cuong Dang, Jiahao Zhang, Hoa Tran, Minh Tran, Trinh Chau, Thai Le, Lu Cheng, and Suhang Wang. `2026`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.coling-main.669/)] Does RAG Introduce Unfairness in LLMs? Evaluating Fairness in Retrieval-Augmented Generation Systems. — Xuyang Wu, Shuowei Li, Hsin-Tai Wu, Zhiqiang Tao, and Yi Fang. `2025`

---

### Explainability for RAG Robustness

#### Attribution Explanations

* [[<ins>arxiv</ins>](https://openreview.net/forum?id=RSrB03W6XK)] ContextCite: Attributing Model Generation to Context. — Benjamin Cohen-Wang, Harshay Shah, Kristian Georgiev, and Aleksander Madry. `2024`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.acl-long.337/)] Blinded by Generated Contexts: How Language Models Merge Generated and Retrieved Contexts When Knowledge Conflicts? — Hexiang Tan, Fei Sun, Wanli Yang, Yuanzhuo Wang, Qi Cao, and Xueqi Cheng. `2024`

#### Mechanistic Explanations

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2410.16090)] Analysing the Residual Stream of Language Models Under Knowledge Conflicts. — Yu Zhao, Xiaotang Du, Giwon Hong, Aryo Pradipta Gema, Alessio Devoto, Hongru Wang, Xuanli He, Kam-Fai Wong, and Pasquale Minervini. `2025`

#### Structural Explanations

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2412.12632)] What External Knowledge Is Preferred by LLMs? Characterizing and Exploring Chain of Evidence in Imperfect Context for Multi-Hop QA. — Zhiyuan Chang, Mingyang Li, Xiaojun Jia, Junjie Wang, Yuekai Huang, Qing Wang, Yihao Huang, and Yang Liu. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.acl-long.337/)] Blinded by Generated Contexts: How Language Models Merge Generated and Retrieved Contexts When Knowledge Conflicts? — Hexiang Tan, Fei Sun, Wanli Yang, Yuanzhuo Wang, Qi Cao, and Xueqi Cheng. `2024`

#### System-Level Explanations

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.14215)] Information Retrieval Induced Safety Degradation in AI Agents. — Cheng Yu, Benedikt Stroebl, Diyi Yang, and Orestis Papakyriakopoulos. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/search?term=Safety%20Devolution%20in%20AI%20Agents)] Safety Devolution in AI Agents. — Cheng Yu and Orestis Papakyriakopoulos. `2025`

---

### Emerging RAG Architectures and Applications

#### GraphRAG

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2501.14050)] GraphRAG Under Fire. — Jiacheng Liang, Yuhui Wang, Changjiang Li, Rongyi Zhu, Tanqiu Jiang, Neil Zhenqiang Gong, and Ting Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2507.08862)] RAG Safety: Exploring Knowledge Poisoning Attacks to Retrieval-Augmented Generation. — Tianzhe Zhao, Jiaoyan Chen, Yanchi Ru, Haiping Zhu, Nan Hu, Jun Liu, and Qika Lin. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.04276)] A Few Words Can Distort Graphs: Knowledge Poisoning Attacks on Graph-Based Retrieval-Augmented Generation of Large Language Models. — Jiayi Wen, Tianxin Chen, Zhirun Zheng, and Cheng Huang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2508.17222)] Exposing Privacy Risks in Graph Retrieval-Augmented Generation. — Jiale Liu, Jiahao Zhang, and Suhang Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2601.14662)] Query-Efficient Agentic Graph Extraction Attacks on GraphRAG Systems. — Shuhua Yang, Jiahao Zhang, Yilong Wang, Dongwon Lee, and Suhang Wang. `2026`

#### Multimodal RAG

* [[<ins>arxiv</ins>](https://arxiv.org/abs/2505.23828)] Spa-VLM: Stealthy Poisoning Attacks on RAG-Based VLM. — Lei Yu, Yechao Zhang, Ziqi Zhou, Yang Wu, Wei Wan, Minghui Li, Shengshan Hu, Xiaobing Pei, and Jing Wang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2502.17832)] MM-PoisonRAG: Disrupting Multimodal RAG with Local and Global Poisoning Attacks. — Hyeonjeong Ha, Qiusi Zhan, Jeonghwan Kim, Dimitrios Bralios, Saikrishna Sanniboina, Nanyun Peng, Kai-Wei Chang, Daniel Kang, and Heng Ji. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2601.17644)] Do Multimodal RAG Systems Leak Data? A Comprehensive Evaluation of Membership Inference and Image Caption Retrieval Attacks. — Ali Al-Lawati and Suhang Wang. `2026`

#### Agentic and Tool-Augmented RAG

* [[<ins>arxiv</ins>](https://openreview.net/forum?id=Y841BRW9rY)] AgentPoison: Red-Teaming LLM Agents via Poisoning Memory or Knowledge Bases. — Zhaorun Chen, Zhen Xiang, Chaowei Xiao, Dawn Song, and Bo Li. `2024`
* [[<ins>arxiv</ins>](https://openreview.net/search?term=Memory%20Injection%20Attacks%20on%20LLM%20Agents)] Memory Injection Attacks on LLM Agents via Query-Only Interaction. — Shen Dong, Shaochen Xu, Pengfei He, Yige Li, Jiliang Tang, Tianming Liu, Hui Liu, and Zhen Xiang. `2025`
* [[<ins>arxiv</ins>](https://arxiv.org/abs/2504.19793)] Prompt Injection Attack to Tool Selection in LLM Agents. — Jiawen Shi, Zenghui Yuan, Guiyao Tie, Pan Zhou, Neil Zhenqiang Gong, and Lichao Sun. `2025`
* [[<ins>arxiv</ins>](https://aclanthology.org/2024.findings-acl.624/)] InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents. — Qiusi Zhan, Zhixiang Liang, Zifan Ying, and Daniel Kang. `2024`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=bKf6TiJ8L4)] AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents. — Edoardo Debenedetti, Jie Zhang, Mislav Balunovic, Luca Beurer-Kellner, Marc Fischer, and Florian Tramèr. `2024`
* [[<ins>arxiv</ins>](https://aclanthology.org/2025.emnlp-demos.55/)] The Dangers of Indirect Prompt Injection Attacks on LLM-Based Autonomous Web Navigation Agents: A Demonstration. — Sam Johnson, Viet Pham, and Thai Le. `2025`
* [[<ins>arxiv</ins>](https://openreview.net/forum?id=S1Bv3068Xt)] Can We Trust Embodied Agents? Exploring Backdoor Attacks Against Embodied LLM-Based Decision-Making Systems. — Ruochen Jiao, Shaoyuan Xie, Justin Yue, Takami Sato, Lixu Wang, Yixuan Wang, Qi Alfred Chen, and Qi Zhu. `2025`

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
