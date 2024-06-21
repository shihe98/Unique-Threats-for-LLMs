# Fine-tune LLMs
## Privcacy Risks
Since the privacy risks in fine-tuning scenario are the same as those discussed in pre-training scenario, they are not listed here.
## Security Risks
**Poison Instruction-tuning** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[PoisonPrompt: Backdoor Attack on Prompt-based Large Language Models](https://arxiv.org/abs/2310.12439)* ![Static Badge](https://img.shields.io/badge/ICASSP'24-blue)
2. *[Poisoning Language Models During Instruction Tuning](https://arxiv.org/abs/2305.00944)* ![Static Badge](https://img.shields.io/badge/ICML'23-blue)
3. *[On the Exploitability of Instruction Tuning](https://arxiv.org/abs/2306.17194)* ![Static Badge](https://img.shields.io/badge/NIPS'23-blue)
4. *[Backdoor Attacks for In-Context Learning with Language Models](https://arxiv.org/abs/2306.11507)* ![Static Badge](https://img.shields.io/badge/AdvML_Frontiers_Workshop'23-blue)
5. *[BadPrompt: Backdoor Attacks on Continuous Prompts](https://arxiv.org/abs/2211.14719)* ![Static Badge](https://img.shields.io/badge/NIPS'22-blue)

**Poison Alignment-tuning** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[Best-of-Venom: Attacking RLHF by Injecting Poisoned Preference Data](https://arxiv.org/abs/2404.05530)*
2. *[Universal Jailbreak Backdoors from Poisoned Human Feedback](https://arxiv.org/abs/2311.14455)* ![Static Badge](https://img.shields.io/badge/ICLR'24-blue)
3. *[RLHFPoison: Reward Poisoning Attack for Reinforcement Learning with Human Feedback in Large Language Models](https://arxiv.org/abs/2311.09641)*
## Countermeasure
**Input-based Defense**
1. [Design and Evaluation of a Multi-Domain Trojan Detection Method on Deep Neural Networks](https://arxiv.org/abs/1911.10312) ![Static Badge](https://img.shields.io/badge/TDSC'22-blue)
2. [Defending Against Stealthy Backdoor Attacks](https://arxiv.org/abs/2205.14246)
3. [Rethinking Stealthiness of Backdoor Attack against NLP Models](https://aclanthology.org/2021.acl-long.431/) ![Static Badge](https://img.shields.io/badge/ACL'21-blue)

**Model-based Defense**
1. [LMSanitator: Defending Prompt-Tuning Against Task-Agnostic Backdoors](https://arxiv.org/abs/2308.13904) ![Static Badge](https://img.shields.io/badge/NDSS'24-blue)
2. [Constrained Optimization with Dynamic Bound-scaling for Effective NLPBackdoor Defense](https://arxiv.org/abs/2202.05749) ![Static Badge](https://img.shields.io/badge/PMLR'22-blue)
3. [PerD: Perturbation Sensitivity-based Neural Trojan Detection Framework on NLP Applications](https://arxiv.org/abs/2208.04943)

**Training data-based Defense**
1. [A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks]([https://arxiv.org/abs/2103.04264](https://arxiv.org/abs/2206.08514)) ![Static Badge](https://img.shields.io/badge/NLPS'22-blue)
2. [BDDR: An Effective Defense Against Textual Backdoor Attacks](https://www.sciencedirect.com/science/article/abs/pii/S0167404821002571) ![Static Badge](https://img.shields.io/badge/Computers&Security'21-blue)
3. [T-Miner: A Generative Approach to Defend Against Trojan Attacks on DNN-based Text Classification](https://arxiv.org/abs/2103.04264) ![Static Badge](https://img.shields.io/badge/Usenix_Security'21-blue)
