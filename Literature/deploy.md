# Pretrain LLMs
<p align="center">
    <img src="../img/agent_map.png" alt="agent" width="900" height="350">
</p>

## Privcacy Risks
**Prompt Extraction Attack** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[Prompt Injection attack against LLM-integrated Applications](https://arxiv.org/abs/2306.05499)*
2. *[Prompts Should not be Seen as Secrets: Systematically Measuring Prompt Extraction Attack Success](https://export.arxiv.org/abs/2307.06865v1)*

**Reconstruction Attack** ![Static Badge](https://img.shields.io/badge/Common-red)
1. *[Sentence Embedding Leaks More Information than You Expect: Generative Embedding Inversion Attack to Recover the Whole Sentence](https://arxiv.org/abs/2305.03010)* ![Static Badge](https://img.shields.io/badge/ACL'23-blue)
2. *[Text Embeddings Reveal (Almost) As Much As Text](https://aclanthology.org/2023.emnlp-main.765/)* ![Static Badge](https://img.shields.io/badge/EMNLP'23-blue)
3. *[Language Model Inversion](https://arxiv.org/abs/2311.13647)*

**Inference Attack** ![Static Badge](https://img.shields.io/badge/Common-red)
* *A. Membership Inference*
1. *[Membership Inference Attacks against Language Models via Neighbourhood Comparison](https://arxiv.org/abs/2305.18462)* ![Static Badge](https://img.shields.io/badge/ACL'23-blue)
2. *[TMI! Finetuned Models Leak Private Information from their Pretraining Data](https://arxiv.org/abs/2306.01181)*
3. *[Quantifying Privacy Risks of Masked Language Models Using Membership Inference Attacks](https://arxiv.org/abs/2203.03929)* ![Static Badge](https://img.shields.io/badge/EMNLP'22-blue)
* *B. Attribute Inference*
1. *[Beyond Memorization: Violating Privacy Via Inference with Large Language Models](https://arxiv.org/abs/2310.07298)* ![Static Badge](https://img.shields.io/badge/ICLR'23-blue)
2. *[You Don't Know My Favorite Color: Preventing Dialogue Representations from Revealing Speakers' Private Personas](https://arxiv.org/abs/2205.10228)* ![Static Badge](https://img.shields.io/badge/NAACL'22-blue)

**Data Extraction Attack** ![Static Badge](https://img.shields.io/badge/Common-red)
1. *[Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)*
2. *[Bag of Tricks for Training Data Extraction from Language Models](https://arxiv.org/abs/2302.04460)* ![Static Badge](https://img.shields.io/badge/ICML'23-blue)'
3. *[Ethicist: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation](https://arxiv.org/abs/2307.04401)* ![Static Badge](https://img.shields.io/badge/ACL'23-blue)'
4. *[You Don't Know My Favorite Color: Preventing Dialogue Representations from Revealing Speakers' Private Personas](https://arxiv.org/abs/2205.10228)* ![Static Badge](https://img.shields.io/badge/NAACL'22-blue)'
5. *[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)* ![Static Badge](https://img.shields.io/badge/Usenix_Security'21-blue)

**Model Extraction Attack** ![Static Badge](https://img.shields.io/badge/Common-red)
1. *[Reverse-Engineering Decoding Strategies Given Blackbox Access to a Language Generation System](https://aclanthology.org/2023.inlg-main.28/)* ![Static Badge](https://img.shields.io/badge/INLG'23-blue)'
2. *[On the Feasibility of Specialized Ability Stealing for Large Language Code Models](https://export.arxiv.org/abs/2303.03012v1)*
3. *[Stealing the Decoding Algorithms of Language Models](https://arxiv.org/abs/2303.04729)* ![Static Badge](https://img.shields.io/badge/CCS'23-blue)'

## Security Risks
**Prompt Injection Attack** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. *[AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models](https://arxiv.org/abs/2310.04451)* ![Static Badge](https://img.shields.io/badge/ICLR'24-blue)
2. *[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)* ![Static Badge](https://img.shields.io/badge/AISec'23-blue)
3. *[Prompt Packer: Deceiving LLMs through Compositional Instruction with Hidden Attacks](https://arxiv.org/abs/2310.10077)*
4. *[Exploiting Programmatic Behavior of LLMs: Dual-Use Through Standard Security Attacks](https://arxiv.org/abs/2302.05733)* ![Static Badge](https://img.shields.io/badge/New_Frontiers_in_Adv'23-blue)
5. *[Prompt Injection attack against LLM-integrated Applications](https://arxiv.org/abs/2306.05499)*
6. *[Ignore Previous Prompt: Attack Techniques For Language Models](https://arxiv.org/abs/2211.09527)* ![Static Badge](https://img.shields.io/badge/NeurIPS_ML_Safety_Workshop'22-blue)

**Jailbreak Attack** ![Static Badge](https://img.shields.io/badge/Common-red)<br>
* *A. Single-step Jailbreak*
1. *[MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots](https://arxiv.org/abs/2307.08715)* ![Static Badge](https://img.shields.io/badge/NDSS'24-blue)
2. *[Prompt as Triggers for Backdoor Attack: Examining the Vulnerability in Language Models](https://aclanthology.org/2023.emnlp-main.757/)* ![Static Badge](https://img.shields.io/badge/EMNLP'23-blue)
3. *[Concealed Data Poisoning Attacks on NLP Models](https://aclanthology.org/2021.naacl-main.13/)* ![Static Badge](https://img.shields.io/badge/NAACL'21-blue)
* *B. Multi-step Jailbreak*
1. *[BadEdit: Backdooring large language models by model editing](https://arxiv.org/abs/2403.13355)* ![Static Badge](https://img.shields.io/badge/ICLR'24-blue)
2. *[UOR: Universal Backdoor Attacks on Pre-trained Language Models](https://arxiv.org/abs/2305.09574)*

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

