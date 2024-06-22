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
* *A. Memorized Data.* Defenders can identify PII and use data masking techniques to hide sensitive information, thereby reducing the risk of PII leakage.
* *B. Output.* Defenders can implement filtering and auditing processes to prevent sensitive information from being transmitted to other entities.
* *C. Authority Management.* Defenders can establish clear controls for private data access, setting access permissions for different roles within multi-agent systems.
* *D. Real-time Feedback.* Defenders can dynamically monitor and adjust output results to mitigate privacy risks caused by unauthorized interactions.

**Security Defense**
* *A. Input Processing.* Defenders can process prompts to detect and defeat jailbreak attacks targeting LLM-based agents.
* *B. Model Processing.* Defenders can employ adversarial training to improve the robustness of LLM-based agents against jailbreak attacks.
* *C. Agent Processing.* Defenders can establish multi-level consistency frameworks in multi-agent systems, ensuring alignment with human values. For role attacks, defenders can design robust filters to detect malicious agents based on role attributes, improving system safety. In constraining the high-level agent can prevent subordinate agents from producing harmful behaviors.
