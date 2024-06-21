# Deploy LLM-based Agents
<p align="center">
    <img src="../img/agent_map.png" alt="agent" width="900" height="350">
</p>

## Privcacy Risks
**Private Data in Corpora** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[ProPILE: Probing Privacy Leakage in Large Language Models](https://arxiv.org/abs/2307.01881)* ![Static Badge](https://img.shields.io/badge/NIPS'23-blue)
2. *[Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)* ![Static Badge](https://img.shields.io/badge/ICLR'23-blue)

**Data Extraction Attack** ![Static Badge](https://img.shields.io/badge/Common-red)
1. *[Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)*
2. *[ETHICIST: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation](https://aclanthology.org/2023.acl-long.709/)* ![Static Badge](https://img.shields.io/badge/ACL'23-blue)
3. *[Canary Extraction in Natural Language Understanding Models](https://arxiv.org/abs/2203.13920)* ![Static Badge](https://img.shields.io/badge/ACL'22-blue)

## Security Risks
**Toxic Data in Corpora** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[Toxicity in ChatGPT: Analyzing Persona-assigned Language Models](https://arxiv.org/abs/2304.05335)* ![Static Badge](https://img.shields.io/badge/EMNLP'23-blue)
2. *[TrustGPT: A Benchmark for Trustworthy and Responsible Large Language Models](https://arxiv.org/abs/2306.11507)*
3. *[On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning](https://arxiv.org/abs/2212.08061)* ![Static Badge](https://img.shields.io/badge/ACL'23-blue)
4. *[Probing Toxic Content in Large Pre-Trained Language Models](https://aclanthology.org/2021.acl-long.329/)* ![Static Badge](https://img.shields.io/badge/ACL'21-blue)

**Poison Attack in Pre-training** ![Static Badge](https://img.shields.io/badge/Common-red)<br>
* *A. Data Poisoning*
1. *[ChatGPT as an Attack Tool: Stealthy Textual Backdoor Attack via Blackbox Generative Model Trigger](https://aclanthology.org/2024.naacl-long.165/)* ![Static Badge](https://img.shields.io/badge/NAACL'24-blue)
2. *[Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models](https://aclanthology.org/2023.emnlp-main.757/)* ![Static Badge](https://img.shields.io/badge/EMNLP'23-blue)
3. *[Concealed Data Poisoning Attacks on NLP Models](https://aclanthology.org/2021.naacl-main.13/)* ![Static Badge](https://img.shields.io/badge/NAACL'21-blue)
* *B. Model Poisoning*
1. *[BadEdit: Backdooring large language models by model editing](https://arxiv.org/abs/2403.13355)* ![Static Badge](https://img.shields.io/badge/ICLR'24-blue)
2. *[UOR: Universal Backdoor Attacks on Pre-trained Language Models](https://arxiv.org/abs/2305.09574)*
3. *[Training-free Lexical Backdoor Attacks on Language Models](https://arxiv.org/abs/2302.04116)* ![Static Badge](https://img.shields.io/badge/WWW'23-blue)
4. *[BITE: Textual Backdoor Attacks with Iterative Trigger Injection](https://aclanthology.org/2023.acl-long.725/)* ![Static Badge](https://img.shields.io/badge/ACL'23-blue)
5. *[Weight Poisoning Attacks on Pre-trained Models](https://arxiv.org/abs/2004.06660)* ![Static Badge](https://img.shields.io/badge/ACL'20-blue)
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
