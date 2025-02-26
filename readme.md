**Awesome Multi-Agent Security And Privacy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)**

The following is a list of curated security and privacy related papers in multi-agent security and privacy.

For more multi-agent papers with a broader focus, see [awesome multi-agent papers](https://github.com/kyegomez/awesome-multi-agent-papers)

For a comparative set of slides that go through each of these approaches, see [here](https://docs.google.com/presentation/d/1lT38avj9y1Xy0tU2aZugKAwd-xhjI2rLgKp0t5RdRdw/edit#slide=id.g33a59478659_0_68) and email andor@andor.us for access.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [Delegation](#delegation)
  - [Decentralized Authorization and Security](#decentralized-authorization-and-security)
  - [Distributed Systems and Event-Driven Architectures](#distributed-systems-and-event-driven-architectures)
  - [Functional Encryption and Delegation](#functional-encryption-and-delegation)
  - [Human-Agent Delegation and Cooperation](#human-agent-delegation-and-cooperation)
  - [Mechanism Design and Efficiency in Delegation](#mechanism-design-and-efficiency-in-delegation)
  - [Multi-Agent Systems and Task Delegation Frameworks](#multi-agent-systems-and-task-delegation-frameworks)
- [Secure and Privacy Preserving Agent Communication ](#secure-and-privacy-preserving-agent-communication)
- [Trust, Reputation, and Norm Based Security](#trust-reputation-and-norm-based-security)
- [Contribute](#contribute)

<!-- markdown-toc end -->

## Delegation

### Decentralized Authorization and Security

- **A Comprehensive Approach to User Delegation and Anonymity within Decentralized Identifiers for IoT** – Addresses challenges in authority delegation and anonymity in IoT environments, proposing a scheme that enhances data sovereignty and security. [PDF](https://pmc.ncbi.nlm.nih.gov/articles/PMC11014293/pdf/sensors-24-02215.pdf)
- **Authenticated Delegation and Authorized AI Agents** – Introduces a framework for authenticated, authorized, and auditable delegation to AI agents, enabling secure task delegation while maintaining accountability. [PDF](https://arxiv.org/pdf/2501.09674)
- **DAMFSD: A Decentralized Authorization Model with Flexible and Secure Delegation** – Proposes a model that enhances security in decentralized systems by allowing flexible delegation of authority while ensuring robust access control mechanisms. [Link](https://www.sciencedirect.com/science/article/pii/S2542660524002580)
- **Delegating Authentication to Edge: A Decentralized Authentication Architecture for Vehicular Networks** – Presents an architecture that delegates authentication tasks to edge nodes, improving scalability and security in vehicular networks. [Link](https://ieeexplore.ieee.org/abstract/document/9205261)
- **Grant Negotiation and Authorization Protocol (GNAP)** – An in-progress effort by the IETF to develop a next-generation authorization protocol, enabling fine-grained delegation for API access and identity assertions. [Link](https://oauth.net/gnap/)
- **Independently Verifiable Decentralized Role-Based Delegation** – Introduces a mechanism where credentials can be verified without relying on domain administrators, supporting efficient cross-domain delegation of authority. [PDF](https://people.cs.vt.edu/danfeng/papers/rbcdPaper.pdf)

### Distributed Systems and Event-Driven Architectures

- **A Distributed State of Mind: Event-Driven Multi-Agent Systems** – Discusses how event-driven architectures in multi-agent systems can leverage delegation and decentralized control to enhance responsiveness and scalability. [Link](https://www.infoworld.com/article/3808083/a-distributed-state-of-mind-event-driven-multi-agent-systems.html/amp/)

### Functional Encryption and Delegation

- **Delegation in Functional Encryption** – Explores mechanisms for delegating decryption capabilities within functional encryption schemes, balancing flexibility and security in access control. [Link](https://hal.science/tel-02394349/document?utm_source=chatgpt.com)

### Human-Agent Delegation and Cooperation

- **Delegation to Autonomous Agents Promotes Cooperation** – Examines how human behavior changes when decisions are delegated to AI agents in social dilemmas. Experiments reveal that groups allowing autonomous delegation exhibit higher cooperation, though mixed human–AI groups show reduced benefits. [Link](https://arxiv.org/abs/2103.07710#:~:text=understand%20experimentally%20whether%20the%20presence,less%20to%20the%20collective%20effort)

### Mechanism Design and Efficiency in Delegation

- **Delegated Pandora’s Box** – Studies costly search problems in delegation, defining the “delegation gap” as the efficiency loss when principals delegate search tasks. It identifies conditions under which this gap can be capped by a constant factor. [Link](https://arxiv.org/abs/2202.10382#:~:text=such%20problems%20and%20space%20of,binary)
- **Delegated Search Approximates Efficient Search** – Presents a theoretical model where a principal delegates a search task to an agent with misaligned incentives. The mechanism guarantees outcomes within a constant factor of the optimal solution and reveals links to prophet inequalities in optimal stopping theory. [Link](https://arxiv.org/abs/1806.06933#:~:text=,mechanisms%20with%20a%20natural%20threshold)
- **[On the Theory of Delegation](https://www.kellogg.northwestern.edu/research/math/papers/438.pdf)** – A foundational work that introduces a formal framework for understanding how principals optimally delegate tasks to agents under asymmetric information conditions.

### Multi-Agent Systems and Task Delegation Frameworks

- **A Model of Delegation for Multi-Agent Systems** – Proposes a formal logical framework for one agent to delegate tasks to another via communicative acts, clarifying how obligations and accountability are transferred. [PDF](http://arg.tech/people/chris/publications/2002/ukmas-book.pdf#:~:text=Abstract,latter%20commitments%20might%20then%20be)
- **Multi-Agent Goal Delegation** – Introduces an approach for collaborative goal achievement where agents use goal reasoning and a theory-of-mind model to decide which goals to pursue or delegate, enhancing overall team performance. [Link](https://par.nsf.gov/biblio/10352576)
- **Normative Multi-Agent Task Delegation Framework** – Describes a practical framework using autonomous agents and normative rules to handle task overload in organizations, validated through simulation to show improved on-time task completion. [Link](https://www.researchgate.net/publication/289421284_A_normative_multi-agent_framework_for_dynamic_task_assignment_and_delegation#:~:text=The%20problem%20of%20task%20overload,We%20simulate%20the)
- **Too Many Cooks: Coordinating Multi-Agent Collaboration Through Inverse Planning** – Introduces Bayesian Delegation, a decentralized learning mechanism that uses inverse planning for agents to infer others’ intentions, thereby facilitating flexible coordination in collaborative tasks. [PDF](https://www.cognitivesciencesociety.org/cogsci20/papers/0157/0157.pdf)

## Secure and Privacy Preserving Agent Communication 

- **A Survey of Privacy in Multi-agent Systems**  
  *Jose M. Such, Agustín Espinosa, and Ana García-Fornes (2013)*  
  This survey provides an overview of privacy issues in multi-agent systems—including challenges in agent communication—and discusses techniques for protecting sensitive data during inter-agent exchanges.  
  [PDF on ResearchGate](https://www.researchgate.net/publication/266289788_A_Survey_of_Privacy_in_Multi-agent_Systems)
- **Trusted AI in Multi-agent Systems: An Overview of Privacy and Security for Distributed Learning**  
  *Chuan Ma, Jun Li, Kang Wei, et al. (2022)*  
  Although focused on distributed learning, this paper examines security and privacy risks at various information exchange levels (from raw data to learned models). Many of these insights are applicable to designing secure communication protocols among agents.  
  [ArXiv](https://arxiv.org/abs/2202.09027)
- **A Privacy-Preserving and Trustable Multi-agent Learning Framework**  
  *Anudit Nagar, Cuong Tran, Ferdinando Fioretto (2021)*  
  This work presents a decentralized framework that combines differential privacy with blockchain smart contracts (via Ethereum) to secure communication and data sharing among agents in distributed learning setups. Its techniques can be adapted for secure, privacy-preserving agent communication in broader multi-agent contexts.  
  [ArXiv](https://arxiv.org/abs/2106.01242)

*Additional Note:* For further background on secure agent communication, you may also consult the FIPA standards on Agent Communication Languages (ACL) and subsequent extensions that address security and privacy—these standards provide foundational guidelines for implementing secure inter-agent protocols.

## Trust, Reputation, and Norm Based Security

- **A Survey of Trust and Reputation Systems for Multi-Agent Environments**  
  *Ramon Sabater and Carles Sierra (2005)*  
  This seminal survey reviews various trust and reputation mechanisms developed for multi-agent systems, discussing their design, implementation challenges, and applications in dynamic and decentralized settings.[paper](https://crad.ict.ac.cn/en/article/id/371)
- **Partial Identities as a Foundation for Trust and Reputation**  
  *Jose M. Such, Agustín Espinosa, Ana García-Fornes, and Carles Sierra (2011)*  
  This paper examines how using partial identities (which balance anonymity and accountability) can underpin robust trust and reputation models in multi-agent systems, providing insights into preserving privacy while enabling reliable interactions.  
  [Science Direct](https://www.sciencedirect.com/science/article/abs/pii/S0952197611001084)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
