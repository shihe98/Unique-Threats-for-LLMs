# Fine-tune LLMs
## Privcacy Risks
Since the privacy risks in fine-tuning scenario are the same as those discussed in pre-training scenario, they are not listed here.
## Security Risks
**Poison Instruction-tuning** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[On the Exploitability of Instruction Tuning](https://arxiv.org/abs/2306.17194)* ![Static Badge](https://img.shields.io/badge/NIPS'23-blue)
2. *[Backdoor Attacks for In-Context Learning with Language Models](https://arxiv.org/abs/2306.11507)* ![Static Badge](https://img.shields.io/badge/AdvML_Frontiers_Workshop'23-blue)
3. *[BadPrompt: Backdoor Attacks on Continuous Prompts](https://arxiv.org/abs/2211.14719)* ![Static Badge](https://img.shields.io/badge/NIPS'22-blue)
4. 
5. *[On the Exploitability of Instruction Tuning](https://arxiv.org/abs/2306.17194)* ![Static Badge](https://img.shields.io/badge/NIPS'23-blue)
6. *[Probing Toxic Content in Large Pre-Trained Language Models](https://aclanthology.org/2021.acl-long.329/)* ![Static Badge](https://img.shields.io/badge/ACL'21-blue)

**Poison Alignment-tuning** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[ChatGPT as an Attack Tool: Stealthy Textual Backdoor Attack via Blackbox Generative Model Trigger](https://aclanthology.org/2024.naacl-long.165/)* ![Static Badge](https://img.shields.io/badge/NAACL'24-blue)
2. *[Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models](https://aclanthology.org/2023.emnlp-main.757/)* ![Static Badge](https://img.shields.io/badge/EMNLP'23-blue)
3. *[Concealed Data Poisoning Attacks on NLP Models](https://aclanthology.org/2021.naacl-main.13/)* ![Static Badge](https://img.shields.io/badge/NAACL'21-blue)
## Countermeasure
**Privacy Protection**
* *A. Corpora Cleaning for Private Data*
1. [Detecting Personal Information in Training Corpora: an Analysis](https://aclanthology.org/2023.trustnlp-1.18/) ![Static Badge](https://img.shields.io/badge/TRUSTNLP'23-blue)
2. [Deduplicating Training Data Mitigates Privacy Risks in Language Models](https://arxiv.org/abs/2202.06539) ![Static Badge](https://img.shields.io/badge/ICML'22-blue)
3. [Scaling Laws and Interpretability of Learning from Repeated Data](https://arxiv.org/abs/2205.10487)
* *B. Privacy Pre-training*
1. [Selective Pre-training for Private Fine-tuning](https://arxiv.org/abs/2305.13865)
3. [Large Language Models Can Be Strong Differentially Private Learners](https://arxiv.org/abs/2110.05679) ![Static Badge](https://img.shields.io/badge/ICLR'22-blue)
4. [Differentially Private Language Models for Secure Data Sharing](https://aclanthology.org/2022.emnlp-main.323/) ![Static Badge](https://img.shields.io/badge/EMNLP'22-blue)
5. [Membership Inference Attack Susceptibility of Clinical Language Models](https://arxiv.org/abs/2104.08305)

**Security Defense**
* *A. Corpora Cleaning for Toxic Data*
1. [ParaDetox: Detoxification with Parallel Data](https://aclanthology.org/2022.acl-long.469/) ![Static Badge](https://img.shields.io/badge/ACL'22-blue)
2. [Exploring Cross-lingual Text Detoxification with Large Multilingual Language Models](https://aclanthology.org/2022.acl-srw.26/) ![Static Badge](https://img.shields.io/badge/ACL'22-blue)
3. [Challenges in Detoxifying Language Models](https://aclanthology.org/2021.findings-emnlp.210/) ![Static Badge](https://img.shields.io/badge/EMNLP'21-blue)
* *B. Model-based Defense*
1. [ONION: A Simple and Effective Defense Against Textual Backdoor Attacks](https://aclanthology.org/2021.emnlp-main.752/) ![Static Badge](https://img.shields.io/badge/EMNLP'21-blue)
2. [Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks](https://arxiv.org/abs/1805.12185) ![Static Badge](https://img.shields.io/badge/RAID'19-blue)
