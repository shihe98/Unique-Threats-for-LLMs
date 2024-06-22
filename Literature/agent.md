# Deploy LLM-based Agents
<p align="center">
    <img src="../img/agent_map.png" alt="agent" width="900" height="350">
</p>

## Privcacy Risks
**Malicious Agent** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. The agent system may memorize user interaction history, allowing malicious users to steal private information through **jailbreak and prompt injection attacks**.
2. **The multi-agent system faces more privacy risks** due to high-frequency interactions. Some agents may access sensitive data beyond their permission scope or expose sensitive information to agents who should not access it. An attacker can access private information across the system by compromising one agent.

**Agent Interaction** ![Static Badge](https://img.shields.io/badge/Unique-red)

Data transmission between agents can be stolen, leading to privacy leakage. The interactions are not transparent, so it is hard to supervise this generated information.
1. *[Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security](https://arxiv.org/abs/2401.05459)*

**Prompt Extraction Attack & Various Privacy Attacks** ![Static Badge](https://img.shields.io/badge/Common-red)

Deploying LLM-based agents faces similar privacy threats that exist in deploying LLMs scenario.
## Security Risks
**Malicious Agent** ![Static Badge](https://img.shields.io/badge/Unique-red)
1. Attackers can modify the role settings of victim agents, causing them to exhibit harmful behaviors.
2. The multi-agent system faces the threat of system-level attacks that can modify the role settings of the entire system.

**Agent Communication** ![Static Badge](https://img.shields.io/badge/Unique-red)

Malicious agents can interact harmful content with other agents, affecting their behavior in a domino effect.
1. *[Evil Geniuses: Delving into the Safety of LLM-based Agents](https://arxiv.org/abs/2311.11855)*

**Backdoor Attacks** ![Static Badge](https://img.shields.io/badge/Common-red)
1. *[Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208)*

**Prompt Engineering Attack** ![Static Badge](https://img.shields.io/badge/Common-red)

Deploying LLM-based agents faces similar security threats that exist in deploying LLMs scenario.
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
