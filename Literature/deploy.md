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
1. *[FuzzLLM: A Novel and Universal Fuzzing Framework for Proactively Discovering Jailbreak Vulnerabilities in Large Language Models](https://arxiv.org/abs/2309.05274)* ![Static Badge](https://img.shields.io/badge/ICASSP'24-blue)
2. *[GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher](https://arxiv.org/abs/2308.06463)* ![Static Badge](https://img.shields.io/badge/ICLR'24-blue)
3. *[MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots](https://arxiv.org/abs/2307.08715)* ![Static Badge](https://img.shields.io/badge/NDSS'24-blue)
4. *[Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study](https://arxiv.org/abs/2305.13860)*
5. *[Role-Play with Large Language Models](https://arxiv.org/abs/2305.16367)* ![Static Badge](https://img.shields.io/badge/Nature'23-blue)
6. *["Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models](https://arxiv.org/abs/2308.03825)*
7. *[Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations](https://arxiv.org/abs/2310.06387)*
8. *[Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)*

* *B. Multi-step Jailbreak*
1. *[Divide-and-Conquer Attack: Harnessing the Power of LLM to Bypass Safety Filters of Text-to-Image Models](https://arxiv.org/abs/2312.07130)*
2. *[Multi-step Jailbreaking Privacy Attacks on ChatGPT](https://arxiv.org/abs/2304.05197)* ![Static Badge](https://img.shields.io/badge/EMNLP'23-blue)

**Adversarial Example Attack** ![Static Badge](https://img.shields.io/badge/Common-red)
1. *[Are aligned neural networks adversarially aligned?](https://arxiv.org/abs/2306.15447)* ![Static Badge](https://img.shields.io/badge/NIPS'23-blue)
2. *[Black Box Adversarial Prompting for Foundation Models](https://arxiv.org/abs/2302.04237)*
3. *[TransFool: An Adversarial Attack against Neural Machine Translation Models](https://arxiv.org/abs/2302.00944)* ![Static Badge](https://img.shields.io/badge/TMLR'23-blue)
4. *[Adversarial Demonstration Attacks on Large Language Models](https://arxiv.org/abs/2305.14950)*

## Countermeasure
**Privacy Protection**
* *A. Differential Privacy*
1. [Just Fine-tune Twice: Selective Differential Privacy for Large Language Models](https://aclanthology.org/2022.emnlp-main.425/) ![Static Badge](https://img.shields.io/badge/EMNLP'22-blue)
2. [SeqPATE: Differentially Private Text Generation via Knowledge Distillation](https://openreview.net/pdf?id=ZG5Bi1N4V0U) ![Static Badge](https://img.shields.io/badge/NIPS'22-blue)
3. [Flocks of Stochastic Parrots: Differentially Private Prompt Learning for Large Language Models](https://arxiv.org/abs/2305.15594) ![Static Badge](https://img.shields.io/badge/NIPS'24-blue)
4. [Privacy-Preserving Prompt Tuning for Large Language Model Services](https://arxiv.org/abs/2305.06212)
5. [Differentially Private Decoding in Large Language Models](https://arxiv.org/abs/2205.13621)
* *C. Alignment Tuning*
1. [Large Language Models Can Be Good Privacy Protection Learners](https://arxiv.org/abs/2310.02469)
* *D. Secure Computing*
1. [PUMA: Secure Inference of LLaMA-7B in Five Minutes](https://arxiv.org/abs/2307.12533)
2. [THE-X: Privacy-Preserving Transformer Inference with Homomorphic Encryption](https://aclanthology.org/2022.findings-acl.277/) ![Static Badge](https://img.shields.io/badge/ACL'22-blue)
3. [MPCFormer: fast, performant and private Transformer inference with MPC](https://arxiv.org/abs/2211.01452) ![Static Badge](https://img.shields.io/badge/ICLR'22-blue)

**Security Defense**
* *A. Output Detection and Processing*
1. [SneakyPrompt: Jailbreaking Text-to-image Generative Models](https://arxiv.org/abs/2305.12082) ![Static Badge](https://img.shields.io/badge/IEEE_Symposium_on_Security_and_Privacy'24-blue)
2. [Jailbreaker in Jail: Moving Target Defense for Large Language Models](https://arxiv.org/abs/2310.02417) ![Static Badge](https://img.shields.io/badge/MTD_Workshop'23-blue)
* *B. Prompt Engineering*
1. [Baseline Defenses for Adversarial Attacks Against Aligned Language Models](https://arxiv.org/abs/2309.00614)
2. [Text Adversarial Purification as Defense against Adversarial Attacks](https://arxiv.org/abs/2203.14207) ![Static Badge](https://img.shields.io/badge/ACL'23-blue)
3. [SmoothLLM: Defending Large Language Models Against Jailbreaking Attacks](https://arxiv.org/abs/2310.03684)
4. [Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations](https://arxiv.org/abs/2310.06387)

* *C. Robustness Training*
1. [Safer-Instruct: Aligning Language Models with Automated Preference Data](https://arxiv.org/abs/2311.08685) ![Static Badge](https://img.shields.io/badge/NAACL'24-blue)
2. [Principle-Driven Self-Alignment of Language Models from Scratch with Minimal Human Supervision](https://arxiv.org/abs/2305.03047) ![Static Badge](https://img.shields.io/badge/NIPS'23-blue)
3. [Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions](https://arxiv.org/abs/2309.07875) ![Static Badge](https://img.shields.io/badge/ICLR'23-blue)
4. [How Should Pre-Trained Language Models Be Fine-Tuned Towards Adversarial Robustness?](https://arxiv.org/abs/2112.11668) ![Static Badge](https://img.shields.io/badge/NIPS'21-blue)
