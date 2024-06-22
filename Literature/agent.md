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

* *B. Privacy Pre-training*


**Security Defense**
* *A. Corpora Cleaning for Toxic Data*

* *B. Model-based Defense*

