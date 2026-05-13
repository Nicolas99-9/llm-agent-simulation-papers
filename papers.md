# 📅 Chronological Paper Log

Newest days appear first. For the grouped-by-tag index, see [README](./README.md).

_585 papers across 11 days · 73 with at least one ⭐._

---


## ⭐ Featured / Editor's picks

Hand-picked work, including some of my own, that anchors the four topics this feed covers. A good starting point if you're new to the area.

- ⭐ [**Beyond Offline A/B Testing: Context-Aware Agent Simulation for Recommender System Evaluation**](https://arxiv.org/abs/2604.09549) — Introduces ContextSim, an LLM-agent recommender-system evaluator that anchors user behaviour in realistic daily-life contexts (when/where/why), producing simulated interactions far closer to real user behaviour than prior work. <sub>_Nicolas Bougie, Gian Maria Marconi, Xiaotong Ye, Narimasa Watanabe, arXiv, 2026_ · `[llm-agent-simulation]`</sub>
- ⭐ [**AlignUSER: Human-Aligned LLM Agents via World Models for Recommender System Evaluation**](https://arxiv.org/abs/2601.00930) — Trains LLM agents that behave like real users for recommender evaluation, using world-model next-state prediction and counterfactual comparative prompting to align agent decisions with observed human choices. <sub>_Nicolas Bougie, Gian Maria Marconi, Tony Yip, Narimasa Watanabe, arXiv, 2026_ · `[llm-agent-simulation, agent-training-alignment]`</sub>
- ⭐ [**MobileCity: An Efficient Framework for Large-Scale Urban Behavior Simulation**](https://aclanthology.org/2026.eacl-industry.21/) — A lightweight agent framework for scalable urban simulation: cognitively-grounded generative agents driven by needs/habits/obligations, asynchronous batched LLM inference, and a multimodal transport network. Simulates 4,000 agents with realistic urban dynamics. <sub>_Xiaotong Ye, Nicolas Bougie, Toshihiko Yamasaki, Narimasa Watanabe, EACL 2026 (Industry Track)_ · `[city-simulation, llm-agent-simulation]`</sub>
- ⭐ [**CitySim: Modeling Urban Behaviors and City Dynamics with Large-Scale LLM-Driven Agent Simulation**](https://aclanthology.org/2025.emnlp-industry.15/) — Models tens of thousands of LLM-driven agents with beliefs, long-term goals and spatial memory, producing realistic urban-scale behaviour including crowd density, place popularity, and well-being dynamics. <sub>_Nicolas Bougie, Narimasa Watanabe, EMNLP 2025 (Industry Track)_ · `[city-simulation, llm-agent-simulation]`</sub>
- ⭐ [**SimUSER: Simulating User Behavior with Large Language Models for Recommender System Evaluation**](https://aclanthology.org/2025.acl-industry.5/) — Generates self-consistent user personas from historical interaction data and equips LLM agents with persona/memory/perception/brain modules to serve as believable, cost-effective human proxies for offline recommender evaluation. <sub>_Nicolas Bougie, Narimasa Watanabe, ACL 2025 (Industry Track)_ · `[llm-agent-simulation]`</sub>
- ⭐ [**Generative Reviewer Agents: Scalable Simulacra of Peer Review**](https://aclanthology.org/2025.emnlp-industry.8/) — Presents GAR: LLM-powered reviewer agents with memory and historically-grounded reviewer personas that match human reviewers in feedback quality and acceptance prediction, democratising expert-level peer feedback. <sub>_Nicolas Bougie, Narimasa Watanabe, EMNLP 2025 (Industry Track)_ · `[llm-agent-simulation]`</sub>
- ⭐ [**Generative Adversarial Reviews: When LLMs Become the Critic**](https://arxiv.org/abs/2412.10415) — Formulates peer review as a generative-agent pipeline: graph-structured paper representations, personalized reviewer agents, and a meta-reviewer that aggregates multi-round critiques to forecast acceptance decisions. <sub>_Nicolas Bougie, Narimasa Watanabe, arXiv, 2024_ · `[llm-agent-simulation]`</sub>

---

## 2026-05-12

- ⭐ **[A Single Neuron Is Sufficient to Bypass Safety Alignment in Large Language Models](https://arxiv.org/abs/2605.08513)** — Hamid Kazemi, Atoosa Chegini, Maria Safi _[agent-training-alignment]_
  Interpretability method for detecting safety vulnerabilities: identifies specific neurons whose suppression bypasses safety alignment, exposing mechanistic alignment failures.
- ⭐ **[AgentCollabBench: Diagnosing When Good Agents Make Bad Collaborators](https://arxiv.org/abs/2605.08647)** — Aritra Mazumder, Shubhashis Roy Dipta, Nusrat Jahan Lia, et al. _[agent-simulation]_
  Diagnostic benchmark for multi-agent systems evaluating collaboration failures and information loss across agent pipelines and topologies.
- ⭐ **[AgentForesight: Online Auditing for Early Failure Prediction in Multi-Agent Systems](https://arxiv.org/abs/2605.08715)** — Boxuan Zhang, Jianing Zhu, Zeru Shi, et al. _[agent-training-alignment]_
  Framework for early online auditing of LLM-based multi-agent systems to detect failures and enable intervention, addressing misalignment/error-cascade safety issues.
- ⭐ **[Ambig-DS: A Benchmark for Task-Framing Ambiguity in Data-Science Agents](https://arxiv.org/abs/2605.09698)** — Josefa Lia Stoisser, Marc Boubnovski Martell, Sidsel Boldsen, et al. _[agent-training-alignment]_
  Diagnostic benchmark and evaluation framework for detecting misalignment failure mode (silent task misframing) in data-science agents, revealing safety bottleneck in autonomous agent decision-making.
- ⭐ **[CIVeX: Causal Intervention Verification for Language Agents](https://arxiv.org/abs/2605.09168)** — Fabio Rovai _[agent-training-alignment]_
  Method for detecting unsafe/unreliable agent actions by verifying causal identifiability; prevents misaligned behavior in tool-using LLM agents through structured safety verification.
- ⭐ **[Continual Harness: Online Adaptation for Self-Improving Foundation Agents](https://arxiv.org/abs/2605.09998)** — Seth Karten, Joel Zhang, Tersoo Upaa, et al. _[agent-simulation]_
  Single embodied LLM agent with long-horizon decision-making in a complex environment using self-improvement through prompt/skill refinement and online adaptation without multi-agent coordination or po
- ⭐ **[Decomposing and Steering Functional Metacognition in Large Language Models](https://arxiv.org/abs/2605.08942)** — Yanshi Li, Xueru Bai, Shuman Liu, et al. _[agent-training-alignment]_
  Studies LLM internal metacognitive states (evaluation awareness, risk perception, safety responses) via mechanistic analysis, directly addressing alignment-relevant phenomena like benchmark gaming and
- ⭐ **[EnactToM: An Evolving Benchmark for Functional Theory of Mind in Embodied Agents](https://arxiv.org/abs/2605.09826)** — Gurusha Juneja, Dylan Lu, Saaket Agashe, et al. _[agent-simulation]_
  Multi-agent embodied benchmark requiring agents to track others' epistemic states and coordinate in shared 3D environments with partial observability and communication constraints.
- ⭐ **[Expert Evaluation and the Limits of Human Feedback in Mental Health AI Safety Testing](https://arxiv.org/abs/2601.18061)** — Kiana Jafari, Paul Ulrich Nikolaus Rust, Duncan Eddy, et al. _[agent-training-alignment]_
  Empirical diagnostic framework exposing measurement and aggregation failures in safety-critical LLM evaluation and reward modeling through expert disagreement analysis.
- ⭐ **[FORTIS: Benchmarking Over-Privilege in Agent Skills](https://arxiv.org/abs/2605.09163)** — Shawn Li, Chenxiao Yu, Han Wang, et al. _[agent-training-alignment]_
  Safety benchmark evaluating privilege escalation in LLM agents; directly assesses alignment failure mode (over-privileged behavior) through systematic diagnostic framework.
- ⭐ **[From Spark to Fire: Modeling and Mitigating Error Cascades in LLM-Based Multi-Agent Collaboration](https://arxiv.org/abs/2603.04474)** — Yizhe Xie, Congcong Zhu, Xinyue Zhang, et al. _[agent-training-alignment]_
  Multi-agent LLM collaboration system modeling error cascades and vulnerabilities, with mitigation mechanisms to suppress failure propagation across agent interactions.
- ⭐ **[How LLMs Are Persuaded: A Few Attention Heads, Rerouted](https://arxiv.org/abs/2605.09314)** — Xiangkun Sun, Lingkai Kong, Aoqi Zhang, et al. _[agent-training-alignment]_
  Interpretability method identifying a causal mechanism for persuasion vulnerability with explicit safety purpose to understand and mitigate factual errors in LLMs.
- ⭐ **[Intrinsic Guardrails: How Semantic Geometry of Personality Interacts with Emergent Misalignment in LLMs](https://arxiv.org/abs/2605.10633)** — Krishak Aneja, Manas Mittal, Anmol Goel, et al. _[agent-training-alignment]_
  Studies emergent misalignment failure mode through causal interventions on personality geometry, proposing intrinsic guardrails as a mechanism for safety robustness.
- ⭐ **[LLM Wardens: Mitigating Adversarial Persuasion with Third-Party Conversational Oversight](https://arxiv.org/abs/2605.08321)** — Lennart Wachowiak, Scott D. Blain, David Williams-King, et al. _[agent-training-alignment]_
  Defense mechanism against adversarial LLM manipulation through oversight detection, directly addressing alignment safety via deception mitigation in multi-agent interactions.
- ⭐ **[Less Diverse, Less Safe: The Indirect But Pervasive Risk of Test-Time Scaling in Large Language Models](https://arxiv.org/abs/2510.08592)** — Shahriar Kabir Nahin, Hadi Askari, Muhao Chen, et al. _[agent-training-alignment]_
  Identifies and stress-tests a safety failure mode in test-time scaling methods where reduced candidate diversity causes unsafe outputs, with diagnostic attack protocol.
- ⭐ **[Log analysis is necessary for credible evaluation of AI agents](https://arxiv.org/abs/2605.08545)** — Peter Kirgis, Sayash Kapoor, Stephan Rabanser, et al. _[agent-training-alignment]_
  Presents diagnostic framework and methodology for detecting unsafe agent behaviors and evaluation validity threats through systematic log analysis.
- ⭐ **[MemQ: Integrating Q-Learning into Self-Evolving Memory Agents over Provenance DAGs](https://arxiv.org/abs/2605.08374)** — Junwei Liao, Haoting Shi, Ruiwen Zhou, et al. _[agent-simulation]_
  Multi-agent LLM memory system applying reinforcement learning (TD-λ eligibility traces) to credit assignment across memory dependencies, achieving long-horizon behavioral improvements through structur
- ⭐ **[Remember the Decision, Not the Description: A Rate-Distortion Framework for Agent Memory](https://arxiv.org/abs/2605.10870)** — Mingxi Zou, Zhihan Guo, Langzhang Liang, et al. _[agent-simulation]_
  Proposes a decision-centric memory mechanism for long-horizon language agents using rate-distortion theory, with algorithmic improvements and empirical validation on agent tasks.
- ⭐ **[Safe Multi-Agent Behavior Must Be Maintained, Not Merely Asserted: Constraint Drift in LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.10481)** — Tianxiao Li, Yixing Ma, Haiquan Wen, et al. _[agent-training-alignment]_
  Position paper identifying constraint drift as a safety failure mode in LLM multi-agent systems and proposing Constraint State Governance to maintain safety across execution trajectories.
- ⭐ **[Steerable but Not Decodable: Function Vectors Operate Beyond the Logit Lens](https://arxiv.org/abs/2604.02608)** — Mohammed Suhail B Nadaf _[agent-training-alignment]_
  Interpretability study of activation steering and function vectors with explicit framing as safety-critical monitoring: shows vocabulary-projection tools fail to detect interventions on deployed model
- ⭐ **[When Agents Say One Thing and Do Another: Validating Elicited Beliefs from LLMs](https://arxiv.org/abs/2602.06286)** — Khurram Yamin, Jingjing Tang, Santiago Cortes-Gomez, et al. _[agent-training-alignment]_
  Proposes diagnostic framework to detect misalignment between elicited LLM beliefs and revealed actions, validating whether agents act coherently with stated preferences.
- **[A Benchmark for Evaluating Outcome-Driven Constraint Violations in Autonomous AI Agents](https://arxiv.org/abs/2512.20798)** — Miles Q. Li, Benjamin C. M. Fung, Martin Weiss, et al. _[agent-training-alignment]_
  Safety and alignment benchmark designed to evaluate emergent outcome-driven constraint violations in autonomous LLM agents under performance incentives.
- **[A Cross-Layered Multi-Drone Coordination for Medical Supply Delivery during Disaster Response Management](https://arxiv.org/abs/2605.09342)** — Aneesh Calyam, Subrahmanya Chandra Bhamidipati, Zack Murry, et al. _[agent-simulation]_
  Multi-drone coordination with MARL (CTDE DQN) for cooperative delivery; multiple interacting agents optimizing joint objectives under constraints.
- **[AHD Agent: Agentic Reinforcement Learning for Automatic Heuristic Design](https://arxiv.org/abs/2605.08756)** — Haoze Lv, Ning Lu, Ziang Zhou, et al. _[agent-simulation]_
  Multi-turn agentic RL framework where LLM agent autonomously decides between generating heuristics or invoking tools in dynamic interaction loop, exhibiting multi-step decision-making and environmenta
- **[Agent-ValueBench: A Comprehensive Benchmark for Evaluating Agent Values](https://arxiv.org/abs/2605.10365)** — Haonan Dong, Qiguan Feng, Kehan Jiang, et al. _[agent-training-alignment]_
  Benchmark for evaluating agent alignment failures through value conflicts; identifies safety and alignment phenomena in autonomous agent behavior across harnesses and skill configurations.
- **[AgentGA: Evolving Code Solutions in Agent-Seed Space](https://arxiv.org/abs/2604.14655)** — David Y. Y. Tan, Kellie Chin, Jingxian Zhang _[agent-simulation]_
  Multi-agent genetic algorithm framework evolving autonomous code-generation agents through population dynamics and parent-child inheritance in isolated workspaces.
- **[AgentPSO: Evolving Agent Reasoning Skill via Multi-agent Particle Swarm Optimization](https://arxiv.org/abs/2605.08704)** — Hyunmin Hwang, Jaemin Kim, Choonghan Kim, et al. _[agent-simulation]_
  Multi-agent reasoning framework where multiple agents iteratively update reasoning skills via population-based swarm optimization, exhibiting emergent collective behavior.
- **[AgentReview: Exploring Peer Review Dynamics with LLM Agents](https://arxiv.org/abs/2406.12708)** — Yiqiao Jin, Qinlin Zhao, Yiyang Wang, et al. _[llm-agent-simulation]_
  LLM agents simulate human reviewers and peer review interactions to study behavioral dynamics and biases in a controlled simulation environment.
- **[AgentSlimming: Towards Efficient and Cost-Aware Multi-Agent Systems](https://arxiv.org/abs/2605.08813)** — Yulang Chen, Haoxuan Peng, Jinyan Liu, et al. _[agent-simulation]_
  Paper studies optimization and compression of multi-agent LLM systems with multiple interacting agents and agent workflow structures.
- **[Aligning Agents via Planning: A Benchmark for Trajectory-Level Reward Modeling](https://arxiv.org/abs/2604.08178)** — Jiaxuan Wang, Yulan Hu, Wenjin Yang, et al. _[agent-training-alignment]_
  Trajectory-level reward modeling benchmark for evaluating agent alignment in tool-using scenarios; diagnostic safety assessment tool for agentic systems.
- **[An Empirical Study of Multi-Agent Collaboration for Automated Research](https://arxiv.org/abs/2603.29632)** — Yang Shen, Zhenyi Yi, Ziyi Zhao, et al. _[agent-simulation]_
  Empirical study of multiple interacting agents with distinct coordination structures, comparing multi-agent architectures for collaborative task execution.
- **[An Experimental Method to Study Opinion Diffusion in Human-AI Hybrid Societies](https://arxiv.org/abs/2605.09197)** — Léna Gaubert, Rémi Devaux, Elif Çelen, et al. _[llm-agent-simulation]_
  Studies opinion formation in LLM-populated networks by simulating human-AI hybrid societies and measuring emergent population-level dynamics like polarization.
- **[Auction-Based Online Policy Adaptation for Evolving Objectives](https://arxiv.org/abs/2604.02151)** — Guruprerana Shabadi, Kaushik Mallik _[agent-simulation]_
  Multi-agent coordination via auction mechanism where selfish local policies compete and coordinate in a general-sum Markov game with emergent behavior.
- **[Auto-Rubric as Reward: From Implicit Preferences to Explicit Multimodal Generative Criteria](https://arxiv.org/abs/2605.08354)** — Juanxi Tian, Fengyuan Liu, Jiaming Han, et al. _[agent-training-alignment]_
  Post-training method (reward modeling for multimodal alignment) explicitly framed to address alignment failures: reward hacking, evaluation bias, and preference specification.
- **[Autonomous Continual Learning for Environment Adaptation of Computer-Use Agents](https://arxiv.org/abs/2602.10356)** — Tianci Xue, Zeyi Liao, Tianneng Shi, et al. _[agent-simulation]_
  Autonomous continual learning framework for computer-use agents adapting to diverse environments through reinforcement learning and curriculum generation without human data.
- **[Balancing Efficiency and Fairness in Traffic Light Control through Deep Reinforcement Learning](https://arxiv.org/abs/2605.10170)** — Matteo Cederle, Giacomo Scatto, Gian Antonio Susto _[city-simulation]_
  Deep RL agent for urban traffic light control balancing vehicle and pedestrian flows in city-scale simulation.
- **[Behavioral Determinants of Deployed AI Agents in Social Networks: A Multi-Factor Study of Personality, Model, and Guardrail Specification](https://arxiv.org/abs/2605.08463)** — Sarah Wilson, Diem Linh Dang, Usman Ali Moazzam, et al. _[llm-agent-simulation]_
  Multi-factor empirical study of LLM agents deployed in social network simulation examining how personality, model, and guardrails drive emergent behavioral and social dynamics across population.
- **[Beyond Red-Teaming: Formal Guarantees of LLM Guardrail Classifiers](https://arxiv.org/abs/2605.10901)** — Nikita Kezins, Urbas Ekka, Pascal Berrang, et al. _[agent-training-alignment]_
  Formal verification framework for safety properties of LLM guardrail classifiers, revealing alignment gaps through mathematical guarantees rather than empirical testing.
- **[Beyond the All-in-One Agent: Benchmarking Role-Specialized Multi-Agent Collaboration in Enterprise Workflows](https://arxiv.org/abs/2605.08761)** — Tao Yu, Hao Wang, Changyu Li, et al. _[agent-simulation]_
  Benchmarks multiple LLM agents with specialized roles collaborating across enterprise workflows with distinct permissions, system state interactions, and policy constraints.
- **[Breaking Contextual Inertia: Reinforcement Learning with Single-Turn Anchors for Stable Multi-Turn Interaction](https://arxiv.org/abs/2603.04783)** — Xingwu Chen, Zhanqiu Zhang, Yiwen Guo, et al. _[agent-training-alignment]_
  RL post-training method explicitly addressing alignment failure: contextual inertia (model ignoring corrections) framed as safety/reliability problem in multi-turn interaction.
- **[Breaking the Impasse: Dual-Scale Evolutionary Policy Training for Social Language Agents](https://arxiv.org/abs/2605.08721)** — Minzheng Wang, Run Luo, Yanbo Wang, et al. _[agent-simulation]_
  Multi-agent self-play RL system where language agents develop distinct strategies through evolutionary training on social language games.
- **[CALYREX: Cross-Attention LaYeR EXtended Transformers for System Prompt Anchoring](https://arxiv.org/abs/2605.09737)** — Li Lixing _[agent-training-alignment]_
  Post-training architectural method explicitly motivated by reducing prompt injection and jailbreaking attacks, demonstrating safety robustness improvement.
- **[COSAC: Counterfactual Credit Assignment in Sequential Cooperative Teams](https://arxiv.org/abs/2604.17693)** — Shripad Deshmukh, Jayakumar Subramanian, Raghavendra Addanki, et al. _[agent-simulation]_
  Multi-agent credit assignment method for sequential cooperative teams with multiple interacting agents.
- **[CalBench: Evaluating Coordination-Privacy Trade-offs in Multi-Agent LLMs](https://arxiv.org/abs/2605.09823)** — Chelsea Zou, Yiheng Yao, Selena She, et al. _[agent-simulation]_
  CalBench evaluates multi-agent coordination and negotiation protocols with distributed information constraints, demonstrating core multi-agent interaction and emergent coordination behavior.
- **[Can Agent Benchmarks Support Their Scores? Evidence-Supported Bounds for Interactive-Agent Evaluation](https://arxiv.org/abs/2605.10448)** — Shanshan Gao, Liyi Zhou _[agent-simulation]_
  Framework for evaluating interactive agent benchmarks through systematic outcome verification, addressing reliability of agent evaluation methodology across multiple benchmarks.
- **[Can Revealed Preferences Clarify LLM Alignment and Steering?](https://arxiv.org/abs/2605.08556)** — Khurram Yamin, Jingjing Tang, Eric Horvitz, et al. _[agent-training-alignment]_
  Empirical framework for diagnosing LLM alignment failures: measuring whether models report preferences consistently, faithfully adopt user-directed objectives, and exhibit goal-directed coherence—a sa
- **[ChatbotManip: A Dataset to Facilitate Evaluation and Oversight of Manipulative Chatbot Behaviour](https://arxiv.org/abs/2506.12090)** — Jack Contro, Simrat Deol, Yulan He, et al. _[agent-training-alignment]_
  Safety benchmark and diagnostic framework for detecting manipulative LLM behaviors, with human-annotated dataset and oversight methodology.
- **[Containment Verification: AI Safety Guarantees Independent of Alignment](https://arxiv.org/abs/2605.09045)** — Royce Moon, Lav R. Varshney _[agent-training-alignment]_
  Formal verification framework for AI agent safety guarantees independent of alignment, ensuring containment properties hold regardless of model behavior.
- **[Context Learning for Multi-Agent Discussion](https://arxiv.org/abs/2602.02350)** — Xingyuan Hua, Sheng Yue, Xinyi Li, et al. _[agent-simulation]_
  Multi-agent discussion system where multiple LLM agents coordinate via structured interaction and dynamic context management to reach consensus solutions.
- **[Cost-Aware Distributed Online Learning with Strict Rejection Behavior against Adversarial Agents](https://arxiv.org/abs/2412.01524)** — Yuhan Suo, Runqi Chai, Senchun Chai, et al. _[agent-simulation]_
  Multi-agent system paper addressing distributed online learning robustness against adversarial agents through cost-aware defensive mechanisms.
- **[Cross-Family Universality of Behavioral Axes via Anchor-Projected Representations](https://arxiv.org/abs/2605.09875)** — Su-Hyeon Kim, Yo-Sub Han _[agent-training-alignment]_
  Interpretability framework for detecting and transferring behavioral directions (refusal, sycophancy, etc.) across LLM families—directly applicable to alignment safety diagnostics.
- **[DSGBench: A Diverse Strategic Game Benchmark for Evaluating LLM-based Agents in Complex Decision-Making Environments](https://arxiv.org/abs/2503.06047)** — Wenjie Tang, Yuan Zhou, Erqiang Xu, et al. _[llm-agent-simulation]_
  Benchmark for evaluating LLM-based agents in multi-agent strategic games with long-horizon reasoning and decision-making analysis.
- **[Designing Intelligent Enterprise Agents: A Capability-Aligned Multi-Agent Architecture](https://arxiv.org/abs/2605.08258)** — John deVadoss _[agent-simulation]_
  Multi-agent architecture framework comparing five distinct agent designs (mono-agent, micro-agent swarm, SOA-brokered, governance-first grid, CEAD) with empirical evaluation on 10,000 enterprise tasks
- **[Detecting Multi-Agent Collusion Through Multi-Agent Interpretability](https://arxiv.org/abs/2604.01151)** — Aaron Rose, Carissa Cullen, Sahar Abdelnabi, et al. _[agent-training-alignment]_
  Multi-agent interpretability method for detecting deception/collusion, framed as safety diagnostic to identify misalignment in coordinated agent behavior.
- **[Distributionally Robust Token Optimization in RLHF](https://arxiv.org/abs/2604.08577)** — Yeping Jin, Jiaming Hu, Ioannis Ch. Paschalidis _[agent-training-alignment]_
  LLM post-training method explicitly motivated by robustness under distribution shifts, reducing capability brittleness across reasoning tasks.
- **[Do Linear Probes Generalize Better in Persona Coordinates?](https://arxiv.org/abs/2605.09391)** — Prasad Mahadik, Adrians Skapars _[agent-training-alignment]_
  Interpretability method explicitly designed for detecting unsafe LLM behaviors (deception, sycophancy) to improve safety monitoring and alignment through white-box probes.
- **[Do Self-Evolving Agents Forget? Capability Degradation and Preservation in Lifelong LLM Agent Adaptation](https://arxiv.org/abs/2605.09315)** — Ye Yu, Xiaopeng Yuan, Haibo Jin, et al. _[agent-simulation]_
  Studies multi-agent capability degradation and preservation during lifelong adaptation, analyzing emergent behaviors across evolving LLM agent populations and skill-accumulation dynamics.
- **[Don't Click That: Teaching Web Agents to Resist Deceptive Interfaces](https://arxiv.org/abs/2605.09497)** — Yilin Zhang, Yingkai Hua, Chunyu Wei, et al. _[agent-training-alignment]_
  Safety evaluation and defense framework addressing deception vulnerability in autonomous agents through adversarial robustness training and benchmarking.
- **[EcoGym: Evaluating LLMs for Long-Horizon Plan-and-Execute in Interactive Economies](https://arxiv.org/abs/2602.09514)** — Xavier Hu, Jinxiang Xia, Shengze Xu, et al. _[llm-agent-simulation]_
  Benchmark for evaluating LLM agents' long-horizon planning and execution in simulated interactive economies with persistent dynamics and emergent economic behavior.
- **[Effect of Graph Gluing on Consensus in Networked Multi-Agent Systems](https://arxiv.org/abs/2605.10558)** — Rohollah Moghadam, Santosh Kandel _[agent-simulation]_
  Multi-agent consensus dynamics study analyzing how graph topology and interconnection strategies affect convergence behavior in networked systems.
- **[Emergent Communication for Co-constructed Emotion Between Embodied Agents via Collective Predictive Coding](https://arxiv.org/abs/2605.09522)** — Zehang Zhang, Nguyen Le Hoang, Tadahiro Taniguchi, et al. _[agent-simulation]_
  Two embodied agents interact via emergent communication protocol to co-construct shared emotion categories, demonstrating multi-agent coordination through collective predictive coding.
- **[EquiMem: Calibrating Shared Memory in Multi-Agent Debate via Game-Theoretic Equilibrium](https://arxiv.org/abs/2605.09278)** — Yuqiao Meng, Sakshi Sunil Narvekar, Luoxi Tang, et al. _[agent-training-alignment]_
  Multi-agent debate system with game-theoretic memory safety mechanism designed to detect and prevent adversarial contamination in collaborative LLM agents.
- **[EvoMAS: Learning Execution-Time Workflows for Multi-Agent Systems](https://arxiv.org/abs/2605.08769)** — Chengdong Xu, Kaiqiang Ke, Ziheng Liu, et al. _[agent-simulation]_
  Multi-agent coordination framework where LLM-based agents dynamically adapt workflows at execution-time based on task state, addressing agent specialization and collaborative reasoning in long-horizon
- **[Evolving-RL: End-to-End Optimization of Experience-Driven Self-Evolving Capability within Agents](https://arxiv.org/abs/2605.10663)** — Zhiyuan Fan, Wenwei Jin, Feng Zhang, et al. _[agent-training-alignment]_
  RL-based post-training method for LLM agents explicitly framed as improving learning capability and adaptation, addressing agent performance through joint optimization of experience extraction and uti
- **[Exploitation Without Deception: Dark Triad Feature Steering Reveals Separable Antisocial Circuits in Language Models](https://arxiv.org/abs/2605.09773)** — Cameron Berg, Roshni Lulla _[agent-training-alignment]_
  Safety-focused interpretability study: uses SAE feature steering to uncover and characterize misalignment failure modes (deception, exploitation, antisocial behavior) in LLMs.
- **[Fully Decentralized Cooperative Multi-Agent Reinforcement Learning is A Context Modeling Problem](https://arxiv.org/abs/2509.15519)** — Chao Li, Bingkun Bao, Yang Gao _[agent-simulation]_
  Fully decentralized multi-agent reinforcement learning with context modeling for cooperative policy learning under partial observability.
- **[GAMBIT: A Three-Mode Benchmark for Adversarial Robustness in Multi-Agent LLM Collectives](https://arxiv.org/abs/2605.09027)** — Alexandre Le Mercier, Chris Develder, Thomas Demeester _[agent-training-alignment]_
  Multi-agent LLM system with adversarial deception scenarios and a benchmark for detecting misaligned imposter agents in collective environments.
- **[GUARD: Guideline Upholding Test through Adaptive Role-play and Jailbreak Diagnostics for LLMs](https://arxiv.org/abs/2508.20325)** — Haibo Jin, Ruoxi Chen, Peiyan Zhang, et al. _[agent-training-alignment]_
  Safety/alignment diagnostic framework using jailbreak detection and guideline compliance evaluation to identify model vulnerabilities and unsafe behaviors.
- **[Generalization Bounds of Emergent Communications for Agentic AI Networking](https://arxiv.org/abs/2605.08613)** — Yong Xiao, Jingxuan Chai, Guangming Shi, et al. _[agent-simulation]_
  Multi-agent emergent communication protocol learning with information-theoretic foundations and generalization analysis for networked autonomous agents.
- **[Generating synthetic electronic health record data using agent-based models to evaluate machine learning robustness under mass casualty incidents](https://arxiv.org/abs/2605.09951)** — Roben Delos Reyes, Daniel Capurro, Nicholas Geard _[agent-simulation]_
  Uses agent-based modeling to simulate emergency department patient flows and system dynamics under mass casualty scenarios; multi-agent population dynamics core to the method.
- **[Generative Adversarial Post-Training Mitigates Reward Hacking in Live Human-AI Music Interaction](https://arxiv.org/abs/2511.17879)** — Yusong Wu, Stephen Brade, Aleksandra Teng Ma, et al. _[agent-training-alignment]_
  Novel RL post-training method explicitly designed to mitigate reward hacking, a key alignment failure mode, using adversarial training on policy trajectories.
- **[HAMLET: A Hierarchical and Adaptive Multi-Agent Framework for Live Embodied Theatrics](https://arxiv.org/abs/2507.15518)** — Shufan Jiang, Sizhou Chen, Chios Chen, et al. _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM framework where distinct actor agents interact in real-time with personas, memories, goals, and embodied actions in a shared environment.
- **[Harmful Intent as a Geometrically Recoverable Feature of LLM Residual Streams](https://arxiv.org/abs/2604.18901)** — Isaac Llorente-Saguer _[agent-training-alignment]_
  Interpretability method designed to detect unsafe behaviors (harmful intent) in aligned LLMs for safety purposes via residual-stream probing.
- **[HiPER: Hierarchical Reinforcement Learning with Explicit Credit Assignment for Large Language Model Agents](https://arxiv.org/abs/2602.16165)** — Jiangweizhi Peng, Yuanxin Liu, Ruida Zhou, et al. _[agent-simulation]_
  Hierarchical RL framework for multi-turn LLM agents with explicit credit assignment across long-horizon decision-making tasks.
- **[Insider Attacks in Multi-Agent LLM Consensus Systems](https://arxiv.org/abs/2605.08268)** — Xiaolin Sun, Zixuan Liu, Yibin Hu, et al. _[agent-training-alignment]_
  Studies adversarial insider attacks on multi-agent LLM consensus systems, demonstrating misalignment and sabotage behaviors in coordinated multi-agent environments.
- **[Internal vs. External: Comparing Deliberation and Evolution for Multi-Agent Constitutional Design](https://arxiv.org/abs/2605.09128)** — Hershraj Niranjani, Ujwal Kumar, Phan Xuan Tan _[agent-simulation]_
  Controlled multi-agent simulation comparing behavioral constitution emergence via internal deliberation and external evolution across coordination and social dilemma environments with population dynam
- **[Internalizing Safety Understanding in Large Reasoning Models via Verification](https://arxiv.org/abs/2605.08930)** — Yi Zhang, Yuxin Chen, Leheng Sheng, et al. _[agent-training-alignment]_
  Post-training method (verification-based fine-tuning) explicitly framed as addressing alignment failure: intrinsic safety understanding and jailbreak robustness, not capability improvement.
- **[Iterative Critique-and-Routing Controller for Multi-Agent Systems with Heterogeneous LLMs](https://arxiv.org/abs/2605.08686)** — Wenzhi Fang, Liangqi Yuan, Guangchen Lan, et al. _[agent-simulation]_
  Multi-agent coordination system with heterogeneous LLM agents, controller-based routing and iterative refinement across multiple interacting agents.
- **[Latent Personality Alignment: Improving Harmlessness Without Mentioning Harms](https://arxiv.org/abs/2605.08496)** — Linh Le, David Williams-King, Mohamed Amine Merzouk, et al. _[agent-training-alignment]_
  Post-training alignment method that reduces adversarial robustness failures through personality-trait-based training, framed as improving harmlessness and addressing safety vulnerabilities.
- **[Learning Approximate Nash Equilibria in Cooperative Multi-Agent Reinforcement Learning via Mean-Field Subsampling](https://arxiv.org/abs/2603.03759)** — Emile Anand, Ishani Karmarkar _[agent-simulation]_
  Multi-agent cooperative reinforcement learning framework with Nash equilibrium convergence guarantees for centralized-decentralized coordination under communication constraints.
- **[Learning the Preferences of a Learning Agent](https://arxiv.org/abs/2605.09217)** — Karim Abdel Sadek, Mark Bedaywi, Rhys Gould, et al. _[agent-training-alignment]_
  Paper develops preference-learning theory for inferring reward functions from learning agents' behavior, a fundamental alignment problem of inferring and acting on human values.
- **[Learning to Stay Safe: Adaptive Regularization Against Safety Degradation during Fine-Tuning](https://arxiv.org/abs/2602.17546)** — Jyotin Goel, Souvik Maji, Pratik Mazumder _[agent-training-alignment]_
  Post-training method with explicit safety-failure framing: proposes adaptive regularization to defend against safety degradation during fine-tuning via judge-based and activation-based risk predictors
- **[M2A: Synergizing Mathematical and Agentic Reasoning in Large Language Models](https://arxiv.org/abs/2605.09879)** — Junjian Wang, Xin Zhou, Qiran Xu, et al. _[agent-simulation]_
  Multi-turn agentic reasoning with external environment interaction interleaved with internal reasoning demonstrates agent behavior modeling and planning.
- **[MAGE: Multi-Agent Self-Evolution with Co-Evolutionary Knowledge Graphs](https://arxiv.org/abs/2605.10064)** — Ruiyi Yang, Zechen Li, Hao Xue, et al. _[agent-simulation]_
  Multi-agent self-evolution framework with co-evolutionary knowledge graphs and dual bandit routing, demonstrating emergent learning dynamics and knowledge preservation across multiple agents.
- **[MATRA: Modeling the Attack Surface of Agentic AI Systems -- OpenClaw Case Study](https://arxiv.org/abs/2605.10763)** — Tim Van hamme, Thomas Vissers, Javier Carnerero-Cano, et al. _[agent-training-alignment]_
  Safety-focused threat modeling and risk assessment framework for agentic AI systems with tool access, designed to detect and quantify attack surface vulnerabilities.
- **[MURPHY: Feedback-Aware GRPO with Retrospective Credit Assignment for Multi-Turn Code Generation](https://arxiv.org/abs/2511.07833)** — Chanakya Ekbote, Vijay Lingam, Sujay Sanghavi, et al. _[agent-training-alignment]_
  Post-training method (GRPO variant) explicitly framed for agentic multi-turn settings with iterative feedback and self-correction in code generation.
- **[Metis: Learning to Jailbreak LLMs via Self-Evolving Metacognitive Policy Optimization](https://arxiv.org/abs/2605.10067)** — Huilin Zhou, Jian Zhao, Yilu Zhong, et al. _[agent-training-alignment]_
  Red-teaming and adversarial attack method targeting LLM safety alignment; demonstrates automated jailbreaking via policy optimization to expose safety vulnerabilities.
- **[Modeling Decision-Making with Will for Cooperation in Social Dilemmas](https://arxiv.org/abs/2605.08669)** — Yizhe Huang, Bin Ling, Song-Chun Zhu, et al. _[agent-simulation]_
  Multi-agent simulation studying cooperation dynamics through agent heterogeneity in spatiotemporal social dilemmas with emergent population-level behavior.
- **[Modeling Implicit Conflict Monitoring Mechanisms against Stereotypes in LLMs](https://arxiv.org/abs/2605.09647)** — Jingshen Zhang, Bo Wang, Yanlin Fu, et al. _[agent-training-alignment]_
  Interpretability method identifying neurons responsible for bias mitigation in LLMs, explicitly motivated by safety and fairness concerns to detect and correct unsafe stereotype generation.
- **[NEXUS: Continual Learning of Symbolic Constraints for Safe and Robust Embodied Planning](https://arxiv.org/abs/2605.09387)** — Tiehan Cui, Peipei Liu, Yanxu Mao, et al. _[agent-training-alignment]_
  Framework for learning symbolic safety constraints in embodied agents to prevent unsafe actions and defend against adversarial attacks, directly addressing agent alignment and safety failures.
- **[NanoResearch: Co-Evolving Skills, Memory, and Policy for Personalized Research Automation](https://arxiv.org/abs/2605.10813)** — Jinhang Xu, Qiyuan Zhu, Yujun Wu, et al. _[llm-agent-simulation]_
  Multi-agent LLM system automating research pipeline with skill evolution, memory retention, and policy learning for personalized user adaptation.
- **[Not All Turns Matter: Credit Assignment for Multi-Turn Jailbreaking](https://arxiv.org/abs/2605.08778)** — Zhida He, Xiaoyu Wen, Han Qi, et al. _[agent-training-alignment]_
  RL-based attack method targeting LLM safety; explicitly demonstrates jailbreaking vulnerability and reuses signals for defense alignment, revealing misalignment detection opportunities.
- **[OPT-BENCH: Evaluating the Iterative Self-Optimization of LLM Agents in Large-Scale Search Spaces](https://arxiv.org/abs/2605.08904)** — Xiaozhe Li, Jixuan Chen, Xinyu Fang, et al. _[llm-agent-simulation]_
  Benchmark evaluating LLM agents' iterative self-optimization and adaptation through perception-memory-reasoning loops in complex search spaces.
- **[OTora: A Unified Red Teaming Framework for Reasoning-Level Denial-of-Service in LLM Agents](https://arxiv.org/abs/2605.08876)** — Xinyu Li, Ronghui Mu, Lin Li, et al. _[agent-training-alignment]_
  Red-teaming framework demonstrating adversarial attacks on LLM agents via reasoning-level denial-of-service, revealing safety vulnerabilities.
- **[OpenIIR: An Open Simulation Platform for Information Retrieval Research](https://arxiv.org/abs/2605.09321)** — Saber Zerhoudi _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM-driven simulation platform studying information retrieval dynamics across deliberative, social, recommender, and evolutionary scenarios with structured agent interactions.
- **[Optimal and Scalable MAPF via Multi-Marginal Optimal Transport and Schrödinger Bridges](https://arxiv.org/abs/2605.10917)** — Usman A. Khan, Joseph W. Durham _[agent-simulation]_
  Multi-agent path finding with decentralized coordination of multiple robots solving collision avoidance through optimal transport framework.
- **[PAC-MCTS: Bias-Aware Pruning for Robust LLM-Guided Search and Planning](https://arxiv.org/abs/2604.14345)** — Tianhao Qian _[agent-simulation]_
  LLM-guided planning with formal safety guarantees against evaluator bias in autonomous reasoning and embodied agents under computational constraints.
- **[PC3D: Zero-Shot Cooperation Across Variable Rosters via Personalized Context Distillation](https://arxiv.org/abs/2605.10377)** — Ahmet Onur Akman, Rafał Kucharski _[agent-simulation]_
  Multi-agent reinforcement learning with variable team sizes; studies decentralized policy learning and emergent coordination without explicit communication.
- **[PRISM: Generation-Time Detection and Mitigation of Secret Leakage in Multi-Agent LLM Pipelines](https://arxiv.org/abs/2605.10614)** — Riya Tapwal, Abhishek Kumar, Carsten Maple _[agent-training-alignment]_
  Safety detection and mitigation framework for information leakage in multi-agent LLM systems addressing adversarial credential exposure risks.
- **[Pairwise is Not Enough: Hypergraph Neural Networks for Multi-Agent Pathfinding](https://arxiv.org/abs/2602.06733)** — Rishabh Jain, Keisuke Okumura, Michael Amir, et al. _[agent-simulation]_
  Multi-agent coordination problem with multiple interacting agents navigating without collisions using learned policies.
- **[Personalized Alignment Revisited: The Necessity and Sufficiency of User Diversity](https://arxiv.org/abs/2605.09119)** — Enoch Hyunwook Kang _[agent-training-alignment]_
  Personalized alignment studies heterogeneous user preferences for LLM adaptation, directly addressing alignment as a phenomenon with formal theoretical conditions for statistical efficiency.
- **[Preference Learning for AI Alignment: a Causal Perspective](https://arxiv.org/abs/2506.05967)** — Katarzyna Kobalczyk, Mihaela van der Schaar _[agent-training-alignment]_
  Proposes causal framework for reward modeling from human preferences to improve LLM alignment and robustness, addressing key alignment failure modes in preference learning.
- **[Pseudo-Deliberation in Language Models: When Reasoning Fails to Align Values and Actions](https://arxiv.org/abs/2605.09893)** — Sushrita Rakshit, Hanwen Zhang, Hua Shen _[agent-training-alignment]_
  Empirical study of value-action misalignment and deception (pseudo-deliberation) in LLMs with diagnostic framework and multi-agent intervention method.
- **[RADAR: Redundancy-Aware Diffusion for Multi-Agent Communication Structure Generation](https://arxiv.org/abs/2605.09907)** — Zhen Zhang, Wanjing Zhou, Juncheng Li, et al. _[agent-simulation]_
  Multi-agent LLM system optimizing communication topology via graph generation, addressing inter-agent coordination structure across diverse task scenarios.
- **[Reflective Prompted Policy Optimization: Trajectory-Grounded Revision and Salience Bias](https://arxiv.org/abs/2605.08315)** — Rahaf Abu Hara, Vaibbhav Murarri, Claudio Zito _[agent-training-alignment]_
  LLM-based policy optimization method motivated by detecting and mitigating behavioral failure modes (salience bias) in agent learning, framing trajectory inspection as alignment-critical for safe poli
- **[Reinforcement Learning for Scalable and Trustworthy Intelligent Systems](https://arxiv.org/abs/2605.08378)** — Guangchen Lan _[agent-training-alignment]_
  Dissertation on RL for trustworthy LLMs focusing on alignment with human preferences and safety-aware post-training.
- **[Results and Retrospective Analysis of the CODS 2025 AssetOpsBench Challenge](https://arxiv.org/abs/2605.08518)** — Dhaval Patel, Chathurangi Shyalika, Suryanarayana Reddy Yarrabothula, et al. _[agent-simulation]_
  Retrospective analysis of industrial multi-agent orchestration competition revealing evaluation design, hidden-test dynamics, and agent architecture patterns across 300 submissions.
- **[Rethinking Ratio-Based Trust Regions for Policy Optimization in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.09212)** — Chulabhaya Wijesundara, Andrea Baisero, Zhongheng Li, et al. _[agent-simulation]_
  Novel multi-agent policy optimization method (MARS) for cooperative MARL using trust-region mechanisms in centralized training with decentralized execution framework.
- **[Reward Auditor: Inference on Reward Modeling Suitability in Real-World Perturbed Scenarios](https://arxiv.org/abs/2512.00920)** — Jianxiang Zang, Yongda Wei, Ruxue Bai, et al. _[agent-training-alignment]_
  Framework for auditing reward model vulnerabilities under perturbations to assess suitability for LLM alignment, directly addressing alignment safety and robustness failures.
- **[Robust Multi-Agent LLMs under Byzantine Faults](https://arxiv.org/abs/2605.09076)** — Haejoon Lee, Vincent-Daniel Yun, Hyeonho Oh, et al. _[agent-simulation]_
  Decentralized multi-agent LLM system with Byzantine fault tolerance via iterative consensus protocol; directly addresses coordination and robustness in multi-agent settings.
- **[SACHI: Structured Agent Coordination via Holistic Information Integration in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.08391)** — Nikunj Gupta, James Zachary Hare, Jesse Milzman, et al. _[agent-simulation]_
  Cooperative multi-agent reinforcement learning with structured information integration and message-passing for joint action coordination across teams.
- **[SDialog: A Python Toolkit for End-to-End Agent Building, User Simulation, Dialog Generation, and Evaluation](https://arxiv.org/abs/2506.10622)** — Sergio Burdisso, Séverin Baroudi, Yanis Labrak, et al. _[llm-agent-simulation]_
  Toolkit provides persona-driven multi-agent dialog simulation using LLMs to generate synthetic conversations for research and evaluation.
- **[SalesSim: Benchmarking and Aligning Multimodal Language Models as Retail User Simulators](https://arxiv.org/abs/2605.08334)** — Yada Pruksachatkun, Elaine Wan, Lyanna Chen, et al. _[llm-agent-simulation]_
  Framework for evaluating and aligning MLLMs as persona-driven retail customer simulators in multi-turn goal-oriented interactions, including RL fine-tuning to improve decision alignment.
- **[SceneFactory: GPU-Accelerated Multi-Agent Driving Simulation with Physics-Based Vehicle Dynamics](https://arxiv.org/abs/2605.08528)** — Yicheng Zhu, Yang Chen, Tao Li, et al. _[agent-simulation, city-simulation]_
  Multi-agent driving simulation platform with GPU-accelerated physics-based vehicle dynamics, coordinated autonomous agents, and large-scale urban mobility scenarios.
- **[ScholarPeer: A Context-Aware Multi-Agent Framework for Automated Peer Review](https://arxiv.org/abs/2601.22638)** — Palash Goyal, Mihir Parmar, Yiwen Song, et al. _[llm-agent-simulation]_
  Multi-agent LLM framework with specialized agents (historian, baseline scout, Q&A engine) simulating collaborative peer review workflows and researcher behavior.
- **[SciIntegrity-Bench: A Benchmark for Evaluating Academic Integrity in AI Scientist Systems](https://arxiv.org/abs/2605.10246)** — Zonglin Yang, Xingtong Liu, Xinyan Xu _[agent-training-alignment]_
  Benchmark evaluating honesty, refusal to misconduct, and safety failure modes (fabrication, deception) in LLM-based AI scientist agents—directly fits alignment/safety diagnostic framework.
- **[Selective Deficits in LLM Mental Self-Modeling in a Behavior-Based Test of Theory of Mind](https://arxiv.org/abs/2603.26089)** — Christopher Ackerman _[agent-training-alignment]_
  Diagnostic framework for detecting misalignment phenomena (strategic deception, reasoning process safety) in LLMs through Theory of Mind behavior testing.
- **[Self-Debias: Self-correcting for Debiasing Large Language Models](https://arxiv.org/abs/2604.08243)** — Xuan Feng, Shuai Zhao, Luwei Xiao, et al. _[agent-training-alignment]_
  Post-training method for reducing social bias in LLM reasoning through self-correction, addressing a safety/alignment failure mode.
- **[Self-ReSET: Learning to Self-Recover from Unsafe Reasoning Trajectories](https://arxiv.org/abs/2605.08936)** — Dongcheng Zhang, Yi Zhang, Yuxin Chen, et al. _[agent-training-alignment]_
  RL-based post-training method explicitly framed to improve safety alignment by enabling LLMs to recover from unsafe reasoning and adversarial attacks.
- **[Shepherd: A Runtime Substrate Empowering Meta-Agents with a Formalized Execution Trace](https://arxiv.org/abs/2605.10913)** — Simon Yu, Derek Chong, Ananjan Nandi, et al. _[agent-simulation]_
  Infrastructure for meta-agent control via execution traces, forking, and intervention—enabling multi-agent coordination and runtime state management across agents.
- **[SimWorld Studio: Automatic Environment Generation with Evolving Coding Agent for Embodied Agent Learning](https://arxiv.org/abs/2605.09423)** — Haoqiang Kang, Xiaokang Ye, Yuhan Liu, et al. _[llm-agent-simulation]_
  LLM-based coding agent (SimCoder) self-evolves to generate and refine 3D embodied learning environments through feedback loops, demonstrating multi-agent co-evolution between environment generator and
- **[Skill Description Deception Attack against Task Routing in Internet of Agents](https://arxiv.org/abs/2605.09889)** — Jiayi He, Xiaofeng Luo, Jiawen Kang, et al. _[agent-training-alignment]_
  Adversarial attack targeting multi-agent LLM systems through deceptive skill descriptions; demonstrates malicious manipulation in distributed agent coordination.
- **[SkillMAS: Skill Co-Evolution with LLM-based Multi-Agent System](https://arxiv.org/abs/2605.09341)** — Shuai Pan, Yixiang Liu, Jiaye Gao, et al. _[llm-agent-simulation]_
  LLM-based multi-agent system with skill co-evolution, credit assignment, and structural adaptation across multiple agents learning and specializing cooperatively.
- **[SkillMaster: Toward Autonomous Skill Mastery in LLM Agents](https://arxiv.org/abs/2605.08693)** — Min Yang, Jinghua Piao, Xu Xia, et al. _[agent-training-alignment]_
  LLM post-training method (GRPO variant) motivated by improving agent self-improvement and learning from experience, addressing autonomous capability development rather than pure capability performance
- **[Statistical Model Checking of the Keynes+Schumpeter Model: A Transient Sensitivity Analysis of a Macroeconomic ABM](https://arxiv.org/abs/2605.10447)** — Stefano Blando, Giorgio Fagiolo, Mauro Napoletano, et al. _[agent-simulation]_
  Agent-based macroeconomic model with multiple heterogeneous agents exhibiting population-level dynamics; SMC framework applies principled multi-agent simulation analysis.
- **[Strategic Exploitation in LLM Agent Markets: A Simulation Framework for E-Commerce Trust](https://arxiv.org/abs/2605.10059)** — Shijun Lei, Quang Nguyen, Swapneel S Mehta, et al. _[llm-agent-simulation, agent-simulation]_
  LLM agents simulating e-commerce market participants to study emergent strategic deception under asymmetric information and institutional constraints.
- **[Strategic commitments shape collective cybersecurity under AI inequality](https://arxiv.org/abs/2605.09415)** — Adeela Bashir, Zia Ush Shamszaman, Zhao Song, et al. _[agent-simulation]_
  Evolutionary game-theoretic multi-agent model studying population-level cybersecurity dynamics with heterogeneous defender strategies and social learning.
- **[Swarm Skills: A Portable, Self-Evolving Multi-Agent System Specification for Coordination Engineering](https://arxiv.org/abs/2605.10052)** — Xinyu Zhang, Zhicheng Dou, Deyang Li, et al. _[agent-simulation]_
  Multi-agent coordination framework with distributed, self-evolving protocols enabling autonomous improvement of collaboration strategies across multiple interacting agents.
- **[TMAS: Scaling Test-Time Compute via Multi-Agent Synergy](https://arxiv.org/abs/2605.10344)** — George Wu, Nan Jing, Qing Yi, et al. _[agent-simulation]_
  Multi-agent framework where specialized agents collaborate with structured information flow and shared memory during test-time reasoning inference.
- **[TacoMAS: Test-Time Co-Evolution of Topology and Capability in LLM-based Multi-Agent Systems](https://arxiv.org/abs/2605.09539)** — Chen Xu, Yicheng Hu, Ruizi Wang, et al. _[agent-simulation]_
  Multi-agent system with dynamically evolving topology and capabilities; agents coordinate, adapt, and optimize network structure at test time.
- **[Team-Based Self-Play With Dual Adaptive Weighting for Fine-Tuning LLMs](https://arxiv.org/abs/2605.09922)** — Wu Li, Yigeng Zhou, Zesheng Shi, et al. _[agent-training-alignment]_
  Novel self-play post-training method explicitly framed to improve LLM alignment through team-based collaboration and adaptive weighting without human supervision.
- **[Temperature and Persona Shape LLM Agent Consensus With Minimal Accuracy Gains in Qualitative Coding](https://arxiv.org/abs/2507.11198)** — Conrad Borchers, Bahar Shahrokhian, Francesco Balzan, et al. _[llm-agent-simulation]_
  Paper studies multi-agent LLM systems emulating human coding workflows, analyzing how agent personas and temperature affect consensus-building in a population of agents.
- **[The Attacker in the Mirror: Breaking Self-Consistency in Safety via Anchored Bipolicy Self-Play](https://arxiv.org/abs/2605.08427)** — Gabriele La Malfa, Emanuele La Malfa, Saar Cohen, et al. _[agent-training-alignment]_
  Proposes a red-teaming and safety evaluation method (Anchored Bipolicy Self-Play) that uses adversarial multi-agent interaction to detect and improve LLM safety against jailbreaks.
- **[The Bystander Effect in Multi-Agent Reasoning: Quantifying Cognitive Loafing in Collaborative Interactions](https://arxiv.org/abs/2605.10698)** — Dahlia Shehata, Ming Li _[agent-training-alignment]_
  Multi-agent LLM reasoning study quantifying emergent alignment failures (sycophancy, cognitive loafing) under social pressure in collaborative agent interactions.
- **[The Differences Between Direct Alignment Algorithms are a Blur](https://arxiv.org/abs/2502.01237)** — Alexey Gorbatovski, Boris Shaposhnikov, Viacheslav Sinii, et al. _[agent-training-alignment]_
  Systematic empirical study of Direct Alignment Algorithms (DPO, ORPO, ASFT variants) analyzing what drives LLM alignment quality through unified framework and controlled comparisons.
- **[The Realignment Problem: When Right becomes Wrong in LLMs](https://arxiv.org/abs/2511.02623)** — Aakash Sen Sharma, Debdeep Sanyal, Manodeep Ray, et al. _[agent-training-alignment]_
  Post-training method addressing alignment drift as policies evolve; uses bi-level optimization to realign LLMs without fresh annotation.
- **[The Reciprocity Gradient](https://arxiv.org/abs/2605.08323)** — Yue Lin, Pascal Poupart, Shuhui Zhu, et al. _[agent-simulation]_
  Multi-agent strategic interaction study with learning agents coordinating through communication and reputation dynamics in reciprocal relationships.
- **[The Trap of Trajectory: Towards Understanding and Mitigating Spurious Correlations in Agentic Memory](https://arxiv.org/abs/2605.09330)** — Luoxi Tang, Rupali Rajendra Vaje, Yuqiao Meng, et al. _[agent-training-alignment]_
  Paper proposes a safety diagnostic and mitigation method (CAMEL) addressing spurious correlations in LLM agent memory systems—a misalignment failure mode where agents rely on erroneous patterns in ret
- **[TinyTroupe: An LLM-powered Multiagent Persona Simulation Toolkit](https://arxiv.org/abs/2507.09788)** — Paulo Salem, Robert Sim, Christopher Olsen, et al. _[llm-agent-simulation]_
  Toolkit for simulating realistic human behavior using LLM-powered agents with detailed personas for behavioral studies and social simulation.
- **[TodyComm: Task-Oriented Dynamic Communication for Multi-Round LLM-based Multi-Agent System](https://arxiv.org/abs/2602.03688)** — Wenzhe Fan, Tommaso Tognoli, Henry Peng Zou, et al. _[agent-simulation]_
  Multi-agent LLM system with dynamic inter-agent communication adapted across rounds via policy gradient optimization for task performance.
- **[Token Buncher: Shielding LLMs from Harmful Reinforcement Learning Fine-Tuning](https://arxiv.org/abs/2508.20697)** — Weitao Feng, Lixu Wang, Peizhuo Lv, et al. _[agent-training-alignment]_
  Defense mechanism against RL-based harmful fine-tuning; addresses alignment failure mode of reward hacking under adversarial post-training.
- **[Too Many Specialists: Emergent Inefficiencies and Bottlenecks for Multi-agent Ad-hoc Collaboration](https://arxiv.org/abs/2605.08540)** — Benjamin Panny, Shashank Mehrotra, Zahra Zahedi, et al. _[agent-simulation]_
  Agent-based model studying emergent multi-agent collaboration dynamics, bottlenecks, and system-level outcomes in heterogeneous teams without prior coordination.
- **[Towards Autonomous Railway Operations: A Semi-Hierarchical Deep Reinforcement Learning Approach to the Vehicle Rescheduling Problem](https://arxiv.org/abs/2605.10257)** — Alberto Castagna, Stefan Zahlner, Adrian Egli, et al. _[agent-simulation]_
  Semi-hierarchical deep RL for multi-agent railway dispatching and coordination, demonstrating emergent coordination behavior across multiple train agents in a simulated rail network.
- **[Towards Shutdownable Agents: Generalizing Stochastic Choice in RL Agents and LLMs](https://arxiv.org/abs/2604.17502)** — Carissa Cullen, Harry Garland, Alexander Roman, et al. _[agent-training-alignment]_
  Post-training method explicitly framed to address alignment failure (shutdown resistance) by training agents to lack harmful preferences and remain controllable.
- **[Training-Free Cultural Alignment of Large Language Models via Persona Disagreement](https://arxiv.org/abs/2605.10843)** — Huynh Trung Kiet, Dao Sy Duy Minh, Tuan Nguyen, et al. _[agent-training-alignment]_
  Training-free inference-time method using persona agents to detect and reduce misalignment between LLM outputs and diverse cultural moral preferences without weight changes.
- **[TrajPrism: A Multi-Task Benchmark for Language-Grounded Urban Trajectory Understanding](https://arxiv.org/abs/2605.10782)** — Lihuan Li, Wilson Wongso, Baiyu Chen, et al. _[city-simulation]_
  Multi-task benchmark for language-grounded urban trajectory understanding across real cities, studying urban mobility dynamics through trajectory modeling and language alignment.
- **[Trustworthy AI: Ensuring Reliability and Accountability from Models to Agents](https://arxiv.org/abs/2605.08964)** — Carol Xuan Long _[llm-agent-simulation, agent-training-alignment]_
  Develops trustworthy AI methods including LLM-driven multi-agent supply chain simulator with novel watermarking techniques for accountability and LLM agent evaluation in autonomous settings.
- **[UTS at PsyDefDetect: Multi-Agent Councils and Absence-Based Reasoning for Defense Mechanism Classification](https://arxiv.org/abs/2605.09769)** — Dima Galat, Marian-Andrei Rizoiu _[agent-simulation]_
  Multi-agent system with distinct specialized roles (class advocates, builder, critic, regression guard) coordinating deliberatively to solve classification task.
- **[Unlearners Can Lie: Evaluating and Improving Honesty in LLM Unlearning](https://arxiv.org/abs/2605.08765)** — Renjie Gu, Jiazhen Du, Yihua Zhang, et al. _[agent-training-alignment]_
  Evaluates and improves honesty in LLM unlearning, a core alignment phenomenon involving model truthfulness, consistency, and acknowledgment of knowledge limitations post-training.
- **[Unpredictability dissociates from structured control in language agents](https://arxiv.org/abs/2605.09692)** — Jia Xiao _[agent-training-alignment]_
  Empirical study of control mechanisms in language agents, testing whether stochasticity substitutes for structured control; relevant to agent behavior understanding and alignment properties.
- **[VC-Soup: Value-Consistency Guided Multi-Value Alignment for Large Language Models](https://arxiv.org/abs/2603.18113)** — Hefei Xu, Le Wu, Yu Wang, et al. _[agent-training-alignment]_
  Post-training method addressing multi-value alignment conflicts in LLMs through value-consistency filtering and model merging.
- **[Verifiable Process Rewards for Agentic Reasoning](https://arxiv.org/abs/2605.10325)** — Huining Yuan, Zelai Xu, Huaijie Wang, et al. _[agent-training-alignment]_
  Post-training method (RL-based reward modeling) explicitly motivated by improving credit assignment in long-horizon agentic reasoning via dense supervision signals.
- **[Virtual Personas for Language Models via an Anthology of Backstories](https://arxiv.org/abs/2407.06576)** — Suhong Moon, Marwa Abdulhai, Minwoo Kang, et al. _[llm-agent-simulation]_
  Paper uses LLMs with persona backstories to simulate human subjects in behavioral surveys, comparing LLM responses to real human survey data.
- **[When Agents Overtrust Environmental Evidence: An Extensible Agentic Framework for Benchmarking Evidence-Grounding Defects in LLM Agents](https://arxiv.org/abs/2605.08828)** — Strick Sheng, Ziyue Wang, Liyi Zhou _[agent-training-alignment]_
  Safety/alignment benchmark and diagnostic framework detecting a systematic failure mode (evidence-grounding defects) in LLM agents' environmental reasoning and action sequencing reliability.
- **[When Can Digital Personas Reliably Approximate Human Survey Findings?](https://arxiv.org/abs/2605.10659)** — Mumin Jia, Yilin Chen, Divya Sharma, et al. _[llm-agent-simulation]_
  LLM-based digital personas constructed to simulate human survey respondents' behavior, tested against held-out human responses for behavioral approximation.
- **[Where Do Reasoning Models Refuse?](https://arxiv.org/abs/2507.03167)** — Kureha Yamaguchi, Benjamin Etheridge, Andy Arditi _[agent-training-alignment]_
  Investigates deception and refusal mechanisms in reasoning models, examining how CoT traces influence safety decisions—a core alignment phenomenon.
- **[Workspace Optimization: How to Train Your Agent](https://arxiv.org/abs/2605.09650)** — Elad Sarafian, Gal Kaplun, Ron Banner, et al. _[agent-simulation]_
  Multi-agent system (DreamTeam) with distinct specialized roles coordinating to solve tasks through interaction and emergent collaboration.
- **[f-GRPO and Beyond: Divergence-Based Reinforcement Learning Algorithms for General LLM Alignment](https://arxiv.org/abs/2602.05946)** — Rajdeep Haldar, Lantao Mei, Guang Lin, et al. _[agent-training-alignment]_
  Post-training RL method for LLM alignment, motivated by mitigating reward hacking and improving safety-critical RLVR tasks through divergence-based optimization.

## 2026-05-11

- ⭐ **[Exact Is Easier: Credit Assignment for Cooperative LLM Agents](https://arxiv.org/abs/2603.06859)** — Yanjun Chen, Yirong Sun, Hanlin Wang, et al. _[agent-simulation]_
  Multi-agent LLM system with credit assignment for cooperative agents; studies coordination and contribution measurement across multiple interacting agents.
- ⭐ **[Self-Programmed Execution for Language-Model Agents](https://arxiv.org/abs/2605.06898)** — Luke J. O'Connor _[agent-simulation]_
  Paper presents a novel agent architecture where the LLM itself acts as an orchestrator program rather than following fixed turn-based policies, enabling flexible agentic behavior with self-direction.
- ⭐ **[The Memory Curse: How Expanded Recall Erodes Cooperative Intent in LLM Agents](https://arxiv.org/abs/2605.08060)** — Jiayuan Liu, Tianqin Li, Shiyi Du, et al. _[llm-agent-simulation, agent-training-alignment]_
  LLM-based multi-agent simulation studying how memory shapes cooperation dynamics and identifying an alignment failure mode (eroding cooperative intent through expanded context).
- ⭐ **[Theoretical Limits of Language Model Alignment](https://arxiv.org/abs/2605.07105)** — Lucas Monteiro Paes, Natalie Mackraz, Barry-John Theobald, et al. _[agent-training-alignment]_
  Theoretical characterization of LM alignment limits under KL constraints, establishing fundamental bounds on reward improvement and analyzing reward hacking in the proxy-reward setting.
- ⭐ **[Towards Security-Auditable LLM Agents: A Unified Graph Representation](https://arxiv.org/abs/2605.06812)** — Chaofan Li, Lyuye Zhang, Jintao Zhai, et al. _[agent-training-alignment]_
  Security auditing framework for LLM agent systems detecting misalignment failures like memory poisoning, capability hijacking, and deceptive multi-agent behavior.
- ⭐ **[TraceFix: Repairing Agent Coordination Protocols with TLA+ Counterexamples](https://arxiv.org/abs/2605.07935)** — Shuren Xia, Qiwei Li, Taqiya Ehsan, et al. _[agent-simulation]_
  Paper proposes verification-driven pipeline for multi-agent LLM coordination using TLA+ model checking and runtime monitoring to ensure correct protocol execution.
- **[A Multi-Level Agent-Based Architecture for Climate Governance Integrating Cognitive and Institutional Dynamics](https://arxiv.org/abs/2605.07683)** — Ivan Puga-Gonzalez, Önder Gürcan, Vanja Falck, et al. _[agent-simulation, city-simulation]_
  Multi-level agent-based model integrating cognitive, institutional, and social dynamics to simulate climate governance with heterogeneous citizens, NGOs, media, and politicians as distinct interacting
- **[A Systematic Investigation of The RL-Jailbreaker in LLMs](https://arxiv.org/abs/2605.07032)** — Montaser Mohammedalamen, Kevin Roice, Reginald McLean, et al. _[agent-training-alignment]_
  Systematic decomposition of RL jailbreaking attacks on LLMs to identify vulnerabilities and improve robustness against adversarial manipulation.
- **[Activation Differences Reveal Backdoors: A Comparison of SAE Architectures](https://arxiv.org/abs/2605.07324)** — Sachin Kumar _[agent-training-alignment]_
  Mechanistic interpretability method explicitly designed to detect backdoor attacks in LLMs, a core AI safety concern addressing model manipulation and alignment failure modes.
- **[Alternating Target-Path Planning for Scalable Multi-Agent Coordination](https://arxiv.org/abs/2605.07744)** — Yu Kumagai, Keisuke Okumura _[agent-simulation]_
  Multi-agent pathfinding and coordination problem with multiple agents solving target assignment and collision-free planning jointly.
- **[Are LLM Agents Behaviorally Coherent? Latent Profiles for Social Simulation](https://arxiv.org/abs/2509.03736)** — James Mooney, Josef Woldense, Zheng Robert Jia, et al. _[llm-agent-simulation]_
  Paper uses LLMs as synthetic agents in behavioral/social simulation study, examining consistency of agent responses across experimental settings.
- **[Behavior Cue Reasoning: Monitorable Reasoning Improves Efficiency and Safety through Oversight](https://arxiv.org/abs/2605.07021)** — Christopher Z. Cui, Taylor W. Killian, Prithviraj Ammanabrolu _[agent-training-alignment]_
  Method for improving LLM safety and monitorability through interpretable reasoning signals enabling scalable oversight of misaligned behaviors.
- **[Beyond "I cannot fulfill this request": Alleviating Rigid Rejection in LLMs via Label Enhancement](https://arxiv.org/abs/2605.07883)** — Ying Zhang, Congyu Qiao, Xin Geng, et al. _[agent-training-alignment]_
  Post-training method addressing alignment failure mode (rigid rejection in safety-aligned LLMs) through label enhancement and refinement.
- **[Beyond the Black Box: Interpretability of Agentic AI Tool Use](https://arxiv.org/abs/2605.06890)** — Hariom Tatsat, Ariye Shater _[agent-training-alignment]_
  Mechanistic interpretability framework for detecting unsafe agent tool-use failures and internal decision signals before action execution—interpretability method with explicit safety/alignment motivat
- **[CASCADE: Case-Based Continual Adaptation for Large Language Models During Deployment](https://arxiv.org/abs/2605.06702)** — Siyuan Guo, Yali Du, Hechang Chen, et al. _[agent-simulation]_
  Multi-agent LLM systems with episodic memory and bandit-theoretic coordination enabling continual adaptation during deployment with emergent behavioral improvement.
- **[Can You Break RLVER? Probing Adversarial Robustness of RL-Trained Empathetic Agents](https://arxiv.org/abs/2605.07138)** — Deeraj S K, Sadhana Devarajan, Krishna Mehra, et al. _[agent-training-alignment]_
  Red-teaming and robustness evaluation of RL-trained agents under adversarial conditions; benchmarks safety weaknesses in aligned empathetic systems.
- **[CogEvolution: A Human-like Generative Educational Agent to Simulate Student's Cognitive Evolution](https://arxiv.org/abs/2604.14786)** — Wei Zhang, Yihang Cheng, Zhirong Ye, et al. _[llm-agent-simulation]_
  Generative agent simulates student cognitive processes and learning behaviors using LLM-based modeling for educational research and behavioral fidelity validation.
- **[Conformal Agent Error Attribution](https://arxiv.org/abs/2605.06788)** — Naihe Feng, Yi Sui, Shiyi Hou, et al. _[agent-simulation]_
  Multi-agent systems error attribution framework using conformal prediction for debugging and recovery in LLM-based agents.
- **[Decentralized Diffusion Policy Learning for Enhanced Exploration in Cooperative Multi-agent Reinforcement Learning](https://arxiv.org/abs/2605.07101)** — Yuyang Zhang, Haldun Balim, Na Li _[agent-simulation]_
  Proposes a decentralized multi-agent RL algorithm with enhanced exploration via diffusion policies for cooperative agent coordination.
- **[DiffeoMorph: Learning to Morph 3D Shapes Using Differentiable Agent-Based Simulations](https://arxiv.org/abs/2512.17129)** — Seong Ho Pahng, Guoye Guan, Benjamin Fefferman, et al. _[agent-simulation]_
  End-to-end learning of distributed control for multi-agent morphogenesis using SE(3)-equivariant graph neural networks to coordinate agent population behavior toward target 3D shapes.
- **[Direction-Flipped Influence Audits Reveal Hidden Structure in Moral Choices of LLMs](https://arxiv.org/abs/2602.22831)** — Phil Blandfort, Tushar Karayil, Alex McKenzie, et al. _[agent-training-alignment]_
  Safety-aware diagnostic framework that audits LLM susceptibility to influence manipulation and reveals misalignment between stated and revealed preferences in moral reasoning.
- **[Discovering Ordinary Differential Equations with LLM-Based Qualitative and Quantitative Evaluation](https://arxiv.org/abs/2605.07323)** — Sum Kyun Song, Bong Gyun Shin, Jae Yong Lee _[agent-simulation]_
  Multi-agent system with three coordinating agents (Sampler, Optimizer, Scientist) that iteratively discover differential equations through structured collaboration.
- **[Distributed Task Allocation for Multi-Agent Systems: A Submodular Optimization Approach](https://arxiv.org/abs/2412.02146)** — Jing Liu, Fangfei Li, Xin Jin, et al. _[agent-simulation]_
  Multi-agent coordination paper studying distributed task allocation with submodular optimization and approximation guarantees for resource-constrained agent systems.
- **[Emergence of Social Reality of Emotion through a Social Allostasis Model with Dynamic Interpretants](https://arxiv.org/abs/2605.07761)** — Kentaro Nomura, Yushi Tsubamoto, Takato Horii _[agent-simulation]_
  Two-agent system with adaptive interaction, symbol exchange, and emergent consensus dynamics—multi-agent coordination demonstrating population-level emergent behavior.
- **[Emergent social transmission of model-based representations without inference](https://arxiv.org/abs/2604.05777)** — Silja Keßler, Miriam Bautista-Salinero, Claudio Tennie, et al. _[agent-simulation]_
  Multi-agent RL simulation studying emergent behavior from social learning interactions between naive agent and expert, demonstrating population dynamics without explicit mentalizing.
- **[EnvSimBench: A Benchmark for Evaluating and Improving LLM-Based Environment Simulation](https://arxiv.org/abs/2605.07247)** — Yi Liu, TingFeng Hui, Wei Zhang, et al. _[llm-agent-simulation]_
  Develops a benchmark and diagnostic framework for evaluating LLM-based environment simulation as a core capability for training AI agents, identifying hallucination and state-tracking failures.
- **[From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms](https://arxiv.org/abs/2605.06716)** — Jinghao Luo, Yuchen Tian, Chuxue Cao, et al. _[llm-agent-simulation]_
  Survey formalizing LLM agent memory evolution through storage, reflection, and experience stages, directly addressing multi-turn agent behavior and continual learning in deployed LLM systems.
- **[GASim: A Graph-Accelerated Hybrid Framework for Social Simulation](https://arxiv.org/abs/2605.07692)** — Xuan Zhou, Yanhui Sun, Hantao Yao, et al. _[llm-agent-simulation, city-simulation]_
  Large-scale social simulation combining LLM-based agents with ABM for population dynamics and emergent public opinion patterns.
- **[GraphDC: A Divide-and-Conquer Multi-Agent System for Scalable Graph Algorithm Reasoning](https://arxiv.org/abs/2605.06671)** — Wenjin Li, Jiaming Cui _[agent-simulation]_
  Multi-agent framework where specialized agents decompose and reason over graph subproblems, coordinating via a master agent—clear multi-agent coordination on a computational task.
- **[HMACE: Heterogeneous Multi-Agent Collaborative Evolution for Combinatorial Optimization](https://arxiv.org/abs/2605.07214)** — Yuping Yan, Jirui Han, Fei Ming, et al. _[agent-simulation]_
  Multi-agent framework with four role-specialized agents (Proposer, Generator, Evaluator, Reflector) coordinating autonomously to solve combinatorial optimization through collaborative evolution.
- **[Hidden Coalitions in Multi-Agent AI: A Spectral Diagnostic from Internal Representations](https://arxiv.org/abs/2605.06696)** — Cameron Berg, Susan L. Schneider, Mark M. Bailey _[agent-simulation, agent-training-alignment]_
  Detects hidden coalition formation via internal representations in multi-agent systems, enabling safety monitoring of emergent group structure in distributed AI agents.
- **[How Value Induction Reshapes LLM Behaviour](https://arxiv.org/abs/2605.07925)** — Arnav Arora, Natalie Schluter, Katherine Metcalf, et al. _[agent-training-alignment]_
  Studies unintended alignment side-effects of value induction during LLM post-training, measuring safety and behavioral trade-offs including sycophancy.
- **[InvThink: Premortem Reasoning for Safer Language Models](https://arxiv.org/abs/2510.01569)** — Yubin Kim, Taehan Kim, Eugene Park, et al. _[agent-training-alignment]_
  Post-training safety method reducing harmful behavior through premortem reasoning; addresses alignment failure modes in agentic scenarios.
- **[Learning to Communicate Locally for Large-Scale Multi-Agent Pathfinding](https://arxiv.org/abs/2605.07637)** — Valeriy Vyaltsev, Alsu Sagirova, Anton Andreychuk, et al. _[agent-simulation]_
  Decentralized multi-agent pathfinding with learned local communication for coordination between multiple homogeneous agents in shared environments.
- **[MaPPO: Maximum a Posteriori Preference Optimization with Prior Knowledge](https://arxiv.org/abs/2507.21183)** — Guangchen Lan, Sipeng Zhang, Tianle Wang, et al. _[agent-training-alignment]_
  Post-training preference optimization method framed explicitly as improving LLM alignment with human preferences beyond binary classification.
- **[Mitigating Cognitive Bias in RLHF by Altering Rationality](https://arxiv.org/abs/2605.06895)** — Tiffany Horter, Andrew Markham, Niki Trigoni, et al. _[agent-training-alignment]_
  RLHF post-training method explicitly motivated by robustness to human feedback bias, a safety/alignment failure mode in preference learning.
- **[Multi-Objective Constraint Inference using Inverse reinforcement learning](https://arxiv.org/abs/2605.06951)** — Syed Ihtesham Hussain Shah, Floris den Hengst, Aneta Lisowska, et al. _[agent-training-alignment]_
  Inverse RL method for inferring safety constraints from multi-expert demonstrations to align RL agents with safety boundaries.
- **[Multi-Objective Multi-Agent Bandits: From Learning Efficiency to Fairness Optimization](https://arxiv.org/abs/2605.06864)** — John Wang, Mengfan Xu _[agent-simulation]_
  Multi-agent multi-armed bandits with heterogeneous rewards over time-varying communication graphs studying learning efficiency and fairness via multi-agent coordination.
- **[OrchJail: Jailbreaking Tool-Calling Text-to-Image Agents by Orchestration-Guided Fuzzing](https://arxiv.org/abs/2605.07414)** — Jianming Chen, Yawen Wang, Junjie Wang, et al. _[agent-training-alignment]_
  Adversarial red-teaming method targeting safety in multi-step agentic systems, revealing vulnerabilities in tool-orchestration behavior.
- **[Randomness is sometimes necessary for coordination](https://arxiv.org/abs/2605.06825)** — Rohan Patil, Jai Malegaonkar, Henrik I. Christensen _[agent-simulation]_
  Multi-agent RL study addressing role differentiation and coordination in cooperative teams through structured randomness and attention mechanisms.
- **[Repeated Deceptive Path Planning against Learnable Observer](https://arxiv.org/abs/2605.07174)** — Shiyue Cao, Pei Xu, Likun Yang, et al. _[agent-simulation]_
  Multi-agent adversarial path planning with an agent adapting against a learnable observer through repeated interaction and strategic deception.
- **[Replicating Human Motivated Reasoning Studies with LLMs](https://arxiv.org/abs/2601.16130)** — Neeley Pate, Adiba Mahbub Proma, Hangfeng He, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate human motivated reasoning processes through replication of psychology studies, testing whether LLMs exhibit human behavioral patterns.
- **[Rethinking Priority Scheduling for Sequential Multi-Agent Decision Making in Stackelberg Games](https://arxiv.org/abs/2605.07240)** — Xiangyu Liu, Liang Zhang, Bo Jin, et al. _[agent-simulation]_
  N-level Stackelberg Game with hierarchical multi-agent decision-making and coordination mechanism optimizing agent interaction order.
- **[Rubric-based On-policy Distillation](https://arxiv.org/abs/2605.07396)** — Junfeng Fang, Zhepei Hong, Mao Zheng, et al. _[agent-training-alignment]_
  LLM post-training method explicitly framed as "model alignment" using on-policy distillation with rubric-based scoring for scalable student model training.
- **[SCENE: Recognizing Social Norms and Sanctioning in Group Chats](https://arxiv.org/abs/2605.07823)** — Mateusz Jacniacki, Maksymilian Bilski _[agent-training-alignment]_
  Benchmark for evaluating LLM agent alignment to implicit social norms and responses to social sanctioning in multi-agent chat scenarios.
- **[SOD: Step-wise On-policy Distillation for Small Language Model Agents](https://arxiv.org/abs/2605.07725)** — Qiyong Zhong, Mao Zheng, Mingyang Song, et al. _[agent-training-alignment]_
  Post-training method (on-policy distillation) explicitly motivated by improving reliability and reducing error propagation in LLM agent tool use.
- **[SOM: Structured Opponent Modeling for LLM-based Agents via Structural Causal Model](https://arxiv.org/abs/2605.07301)** — Shiyue Cao, Pei Xu, Likun Yang, et al. _[agent-simulation]_
  LLM-based agents in multi-agent game-theoretic environments with opponent modeling for strategic coordination and interaction.
- **[Safe, or Simply Incapable? Rethinking Safety Evaluation for Phone-Use Agents](https://arxiv.org/abs/2605.07630)** — Zhengyang Tang, Yi Zhang, Chenxin Li, et al. _[agent-training-alignment]_
  Safety evaluation benchmark for LLM-based agents distinguishing unsafe choices from capability failures, designed to detect alignment failures in autonomous action-taking systems.
- **[Social Theory Should Be a Structural Prior for Agentic AI: A Formal Framework for Multi-Agent Social Systems](https://arxiv.org/abs/2605.07069)** — Lynnette Hui Xian Ng, Iain J. Cruickshank, Adrian Xuan Wei Lim, et al. _[agent-simulation]_
  Formal framework for multi-agent social systems with emergence from agent interactions, networked dependence, and co-evolution dynamics.
- **[Synchronizing Minds through Collective Predictive Coding: A Computational Model of Parent-Infant Homeostatic Co-Regulation](https://arxiv.org/abs/2605.07524)** — Yushi Tsubamoto, Takato Horii _[agent-simulation]_
  Multi-agent computational model of parent-infant interaction using POMDP and collective predictive coding to study latent-state alignment and emergent synchrony between heterogeneous agents.
- **[THINKSAFE: Self-Generated Safety Alignment for Reasoning Models](https://arxiv.org/abs/2601.23143)** — Seanie Lee, Sangwoo Park, Yumin Choi, et al. _[agent-training-alignment]_
  Self-generated safety alignment method for reasoning models addressing safety degradation from RL optimization via refusal steering and fine-tuning.
- **[TeamBench: Evaluating Agent Coordination under Enforced Role Separation](https://arxiv.org/abs/2605.07073)** — Yubin Kim, Chanwoo Park, Taehan Kim, et al. _[agent-simulation]_
  Multi-agent coordination benchmark evaluating whether agents truly collaborate across enforced distinct roles or mask failures through role confusion.
- **[The Cost of Consensus: Malignant Epistemic Herding and Adaptive Gating in Distributed Multi-Agent Search](https://arxiv.org/abs/2605.06988)** — David Farr, Iain Cruickshank, Kate Starbird, et al. _[agent-simulation]_
  Multi-agent coordination under uncertainty with distributed communication, studying emergent collective reasoning and belief dynamics across agent populations.
- **[The Moltbook Files: A Harmless Slopocalypse or Humanity's Last Experiment](https://arxiv.org/abs/2605.07462)** — William Brach, Federico Torrielli, Stine Lyngsø Beltoft, et al. _[llm-agent-simulation, agent-training-alignment]_
  Large-scale simulation of LLM agents interacting on a social platform to study emergent behaviors and safety risks from agent-generated data contamination.
- **[UNA: A Unified Supervised Framework for Efficient LLM Alignment Across Feedback Types](https://arxiv.org/abs/2408.15339)** — Zhichao Wang, Bin Bi, Can Huang, et al. _[agent-training-alignment]_
  Post-training method (RLHF/DPO variant) explicitly motivated by improving LLM alignment through unified feedback handling.
- **[Valence-Arousal Subspace in LLMs: Circular Emotion Geometry and Multi-Behavioral Control](https://arxiv.org/abs/2604.03147)** — Lihao Sun, Lewen Yan, Xiaoya Lu, et al. _[agent-training-alignment]_
  Paper demonstrates steering LLM behaviors (refusal, sycophancy) through interpretable valence-arousal subspace; directly addresses alignment control mechanisms.
- **[When Does Multi-Agent Collaboration Help? An Entropy Perspective](https://arxiv.org/abs/2602.04234)** — Yuxuan Zhao, Sijia Chen, Ningxin Su _[agent-simulation]_
  Multi-agent LLM systems studied empirically across topologies and benchmarks to understand collaboration effectiveness through entropy dynamics analysis.
- **[Why Does Agentic Safety Fail to Generalize Across Tasks?](https://arxiv.org/abs/2605.06992)** — Yonatan Slutzky, Yotam Alexander, Tomer Slor, et al. _[agent-training-alignment]_
  Paper studies why safety generalization fails in multi-task agents, proving safety has higher complexity than task execution alone—a fundamental alignment failure mode.


## 2026-05-08

- ⭐ **[Automated alignment is harder than you think](https://arxiv.org/abs/2605.06390)** — Aleksandr Bowkis, Marie Davidsen Buhl, Jacob Pfau, et al. _[agent-training-alignment]_
  Studies safety risks of using AI agents for alignment research, addressing alignment failure modes through scalable oversight and oversight robustness.
- ⭐ **[Belief Memory: Agent Memory Under Partial Observability](https://arxiv.org/abs/2605.05583)** — Junfeng Liao, Qizhou Wang, Jianing Zhu, et al. _[llm-agent-simulation]_
  Proposes probabilistic memory mechanism for LLM agents operating in partially observable environments, improving reasoning and uncertainty handling.
- ⭐ **[Beyond Accuracy: Policy Invariance as a Reliability Test for LLM Safety Judges](https://arxiv.org/abs/2605.06161)** — Shihao Weng, Yang Feng, Xiaofei Xie _[agent-training-alignment]_
  Safety benchmark and diagnostic framework for detecting unreliable evaluators in agent safety assessment pipelines through policy-invariance testing.
- ⭐ **[Chain of Risk: Safety Failures in Large Reasoning Models and Mitigation via Adaptive Multi-Principle Steering](https://arxiv.org/abs/2605.05678)** — Xiaomin Li, Jianheng Hou, Zheyuan Deng, et al. _[agent-training-alignment]_
  Safety evaluation and mitigation method for reasoning-trace transparency in LRMs, identifying misalignment failures across reasoning chains and proposing steering-based safety intervention.
- ⭐ **[Crafting Reversible SFT Behaviors in Large Language Models](https://arxiv.org/abs/2605.06632)** — Yuping Lin, Pengfei He, Yue Xing, et al. _[agent-training-alignment]_
  Safety-focused interpretability and control method for suppressing undesired SFT-induced behaviors in LLMs via mechanistic localization and reversible triggers.
- ⭐ **[Games for AI Control: Models of Safety Evaluations of AI Deployment Protocols](https://arxiv.org/abs/2409.07985)** — Charlie Griffin, Louis Thomson, Buck Shlegeris, et al. _[agent-training-alignment]_
  Formal framework for evaluating safety of deployment protocols for untrusted AI systems through red-teaming and adversarial game-theoretic modeling.
- ⭐ **[Market-Alignment Risk in Pricing Agents: Trace Diagnostics and Trace-Prior RL under Hidden Competitor State](https://arxiv.org/abs/2605.06529)** — Peiying Zhu, Sidi Chang _[agent-training-alignment]_
  Trace-Prior RL detects and repairs misalignment failure where scalar rewards are gamed; diagnostic protocol reveals hidden-state Goodhart problem in multi-agent RL pricing domain.
- **[A Case-Driven Multi-Agent Framework for E-Commerce Search Relevance](https://arxiv.org/abs/2605.05991)** — Commerce Search Relevance Team _[agent-simulation]_
  Multi-agent system with distinct interacting agents (Annotator, Optimizer, User) coordinating to solve e-commerce search relevance through autonomous collaboration.
- **[A Unified Pair-GRPO Family: From Implicit to Explicit Preference Constraints for Stable and General RL Alignment](https://arxiv.org/abs/2605.06375)** — Hao Yu _[agent-training-alignment]_
  Post-training method (GRPO variant) explicitly motivated by LLM alignment problems: unstable updates, preference learning, and RLHF stability.
- **[A$^2$TGPO: Agentic Turn-Group Policy Optimization with Adaptive Turn-level Clipping](https://arxiv.org/abs/2605.06200)** — Dingwei Chen, Zefang Zong, Zhipeng Ma, et al. _[agent-training-alignment]_
  LLM post-training method (RL variant) for agentic LLMs framed explicitly around process credit assignment and improving multi-turn agent behavior through principled policy optimization.
- **[AI Agents Alone Are Not (Yet) Sufficient for Social Simulation](https://arxiv.org/abs/2603.00113)** — Yiming Li, Dacheng Tao _[llm-agent-simulation]_
  Position paper analyzing LLM-based agents for social simulation, proposing a formal framework for environment-agent co-dynamics in multi-agent behavioral modeling.
- **[AceGRPO: Adaptive Curriculum Enhanced Group Relative Policy Optimization for Autonomous Machine Learning Engineering](https://arxiv.org/abs/2602.07906)** — Yuzhu Cai, Zexi Liu, Xinyu Zhu, et al. _[agent-training-alignment]_
  LLM post-training method (GRPO variant with curriculum learning) explicitly motivated by improving agent capability for sustained iterative task optimization.
- **[Active Learning for Communication Structure Optimization in LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.05703)** — Huchen Yang, Xinghao Dong, Dan Negrut, et al. _[agent-training-alignment]_
  Paper optimizes communication structure in LLM multi-agent systems using active learning, addressing robustness under agent attacks and constrained budgets.
- **[Autogenesis: A Self-Evolving Agent Protocol](https://arxiv.org/abs/2604.15034)** — Wentao Zhang, Zhe Zhao, Haibin Wen, et al. _[agent-simulation]_
  Multi-agent system with dynamic resource management, closed-loop evolution, and interaction across heterogeneous agents and tools during long-horizon task execution.
- **[BOIL: Learning Environment Personalized Information](https://arxiv.org/abs/2604.17137)** — Rohan Patil, Henrik I. Christensen _[agent-simulation]_
  Multi-agent coordination framework extracting environment insights to guide long-term agent behavior in coverage, patrolling, and reachability tasks.
- **[BehaviorGuard: Online Backdoor Defense for Deep Reinforcement Learning](https://arxiv.org/abs/2605.05977)** — Yinbo Yu, Xueyu Yin, Jiadai Wang, et al. _[agent-training-alignment]_
  Online backdoor defense framework for DRL that detects and mitigates trigger-based attacks by identifying behavioral distribution shifts, addressing safety failure in reinforcement learning agents.
- **[Beyond Negative Rollouts: Positive-Only Policy Optimization with Implicit Negative Gradients](https://arxiv.org/abs/2605.06650)** — Mingwei Xu, Hao Fang _[agent-training-alignment]_
  Post-training method (RLVR variant) explicitly motivated by improving LLM alignment through verifiable rewards and policy optimization, not just capability.
- **[Beyond Static Snapshots: A Grounded Evaluation Framework for Language Models at the Agentic Frontier](https://arxiv.org/abs/2604.17573)** — Jazmia Henry _[agent-training-alignment]_
  Paper proposes a post-training evaluation framework explicitly addressing reward hacking and alignment failure modes in RLHF for deployed agentic systems.
- **[Conceal, Reconstruct, Jailbreak: Exploiting the Reconstruction-Concealment Tradeoff in MLLMs](https://arxiv.org/abs/2605.05709)** — Md Farhamdur Reza, Richeng Jin, Tianfu Wu, et al. _[agent-training-alignment]_
  Adversarial jailbreak attack method targeting aligned MLLMs; reveals safety vulnerabilities through reconstruction-concealment tradeoff exploitation.
- **[Conversation for Non-verifiable Learning: Self-Evolving LLMs through Meta-Evaluation](https://arxiv.org/abs/2601.21464)** — Yuan Sui, Bryan Hooi _[agent-simulation]_
  Multiple agents with distinct roles engage in structured self-play conversations to jointly optimize generation and evaluation capabilities through emergent multi-agent interaction.
- **[Cooperative Profiles Predict Multi-Agent LLM Team Performance in AI for Science Workflows](https://arxiv.org/abs/2604.20658)** — Shivani Kumar, Adarsh Bharathwaj, David Jurgens _[llm-agent-simulation]_
  Multi-agent LLM teams collaborating on scientific tasks under shared constraints; behavioral analysis of cooperative dynamics predicts downstream multi-agent performance.
- **[Coordination Matters: Evaluation of Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.06557)** — Maria Ana Cardei, Matthew Landers, Afsaneh Doryab _[agent-simulation]_
  Proposes coordination-aware evaluation framework for cooperative multi-agent reinforcement learning with detailed process-level diagnostics beyond aggregate metrics.
- **[Evaluation Awareness in Language Models Has Limited Effect on Behaviour](https://arxiv.org/abs/2605.05835)** — Amelie Knecht, Lucas Florin, Thilo Hagendorff _[agent-training-alignment]_
  Empirical study of evaluation awareness as a potential alignment faking mechanism, assessing whether LLMs strategically optimize for perceived evaluation criteria.
- **[Flexible Agent Alignment with Goal Inference from Open-Ended Dialog](https://arxiv.org/abs/2508.15119)** — Rachel Ma, Jingyi Qu, Andreea Bobu, et al. _[agent-training-alignment]_
  Framework for inferring and aligning LLM agent behavior with dynamically evolving human preferences through goal modeling in multi-turn dialogue.
- **[How Many Iterations to Jailbreak? Dynamic Budget Allocation for Multi-Turn LLM Evaluation](https://arxiv.org/abs/2605.06605)** — Shai Feldman, Yaniv Romano _[agent-training-alignment]_
  Safety/alignment evaluation benchmark and diagnostic framework for detecting jailbreaks and deceptive LLM behaviors in multi-turn interactions.
- **[Improving the Efficiency of Language Agent Teams with Adaptive Task Graphs](https://arxiv.org/abs/2605.06320)** — Elizabeth Mieczkowski, Alexander Ku, Tiwalayo Eisape, et al. _[agent-simulation]_
  Multi-agent coordination framework where multiple LLM agents collaborate with dynamic task allocation, dependency tracking, and emergent coordination patterns.
- **[Information Theoretic Adversarial Training of Large Language Models](https://arxiv.org/abs/2605.05415)** — Yiwei Zhang, Jeremiah Birrell, Reza Ebrahimi, et al. _[agent-training-alignment]_
  Post-training method explicitly designed to improve LLM robustness against adversarial attacks and harmful behaviors through distributionally robust optimization for safety.
- **[Instrumental Choices: Measuring the Propensity of LLM Agents to Pursue Instrumental Behaviors](https://arxiv.org/abs/2605.06490)** — Jonas Wiedermann-Möller, Leonard Dung, Maksym Andriushchenko _[agent-training-alignment]_
  Introduces a benchmark to measure LLM agent propensity for instrumental convergence behavior, a key alignment and safety concern in autonomous AI systems.
- **[Knowledge-Level Consistency Reinforcement Learning: Dual-Fact Alignment for Long-Form Factuality](https://arxiv.org/abs/2509.23765)** — Junliang Li, Yucheng Wang, Yan Chen, et al. _[agent-training-alignment]_
  Post-training method addressing hallucination (safety failure mode) via RL alignment framework constraining LLM generation within knowledge boundaries.
- **[LLM-Based Educational Simulation: Evaluating Temporal Student Persona Stability Across ADHD Profiles](https://arxiv.org/abs/2605.06307)** — Jana Gonnermann-Müller, Jennifer Haase, Nicolas Leins, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate human student populations with clinically-grounded personas across extended interactions for educational research validity.
- **[MANTRA: Synthesizing SMT-Validated Compliance Benchmarks for Tool-Using LLM Agents](https://arxiv.org/abs/2605.06334)** — Ashwani Anand, Ivi Chatzi, Ritam Raha, et al. _[agent-training-alignment]_
  Framework for formally validating LLM agent compliance with procedural rules, creating safety benchmarks for tool-using agents to detect misalignment.
- **[MASPO: Joint Prompt Optimization for LLM-based Multi-Agent Systems](https://arxiv.org/abs/2605.06623)** — Zhexuan Wang, Xuebo Liu, Li Wang, et al. _[agent-simulation]_
  LLM-based multi-agent system framework that jointly optimizes prompts across interacting agents for collaborative task performance using evolutionary search and cross-agent evaluation.
- **[MEMOA: Massive Mixtures of Online Agents via Mean-Field Decentralized Nash Equilibria](https://arxiv.org/abs/2605.05492)** — Xuwei Yang, David B. Emerson, Fatemeh Tavakoli, et al. _[agent-simulation]_
  Decentralized multi-agent learning framework where many agents coordinate via mean-field equilibrium, deriving optimal policies for large populations with emergent collective behavior.
- **[Mapping Human Anti-collusion Mechanisms to Multi-agent AI Systems](https://arxiv.org/abs/2601.00360)** — Jamiu Idowu, Ahmed Almasoud, Ayman Alfahid _[agent-simulation]_
  Paper develops taxonomy of anti-collusion mechanisms and maps them to multi-agent AI coordination control, addressing emergent collusive behavior in autonomous agent systems.
- **[MidSteer: Optimal Affine Framework for Steering Generative Models](https://arxiv.org/abs/2605.05220)** — Tatiana Gaintseva, Andrew Stepanov, Ziquan Liu, et al. _[agent-training-alignment]_
  Proposes MidSteer, an affine framework for steering LLM representations to control safety-relevant behaviors in post-deployment alignment and safety settings.
- **[Multi-agent decision making: A Blackwell's informativeness approach](https://arxiv.org/abs/2605.06028)** — Zheng Zhang, Cuong C. Nguyen, Kevin Wells, et al. _[agent-simulation]_
  Multi-agent decision-making framework analyzing how multiple LLM agents collaborate and aggregate decisions using information-theoretic principles and Blackwell informativeness.
- **[Multiagent Stochastic Shortest Path Problem](https://arxiv.org/abs/2605.06056)** — Martin Jonáš, Antonín Kučera, Vojtěch Kůr, et al. _[agent-simulation]_
  Multi-agent coordination problem studying strategy synthesis and complexity for k agents minimizing collective expected time to target.
- **[One Turn Too Late: Response-Aware Defense Against Hidden Malicious Intent in Multi-Turn Dialogue](https://arxiv.org/abs/2605.05630)** — Xinjie Shen, Rongzhe Wei, Peizhi Niu, et al. _[agent-training-alignment]_
  Safety detection framework for multi-turn LLM dialogue identifying harm-enabling turns; enables scalable oversight against distributed malicious intent.
- **[PersonaTeaming: Supporting Persona-Driven Red-Teaming for Generative AI](https://arxiv.org/abs/2605.05682)** — Wesley Hanwen Deng, Mingxi Yan, Sunnie S. Y. Kim, et al. _[agent-training-alignment]_
  Red-teaming method (adversarial attack framework) designed to surface alignment and safety failures in generative AI models through persona-driven prompt generation.
- **[PlatoLTL: Learning to Generalize Across Symbols in LTL Instructions for Multi-Task RL](https://arxiv.org/abs/2601.22891)** — Jacques Cloete, Mathias Jackermeier, Ioannis Havoutis, et al. _[agent-simulation]_
  Multi-task RL paper where policies learn to generalize compositionally across temporally extended tasks specified in LTL with unseen propositions.
- **[PrefixGuard: From LLM-Agent Traces to Online Failure-Warning Monitors](https://arxiv.org/abs/2605.06455)** — Xinmiao Huang, Jinwei Hu, Rajarshi Roy, et al. _[agent-training-alignment]_
  Safety monitoring framework for LLM-agent failures; detects misalignment and unsafe behaviors during task execution via learned prefix-risk predictors.
- **[RVPO: Risk-Sensitive Alignment via Variance Regularization](https://arxiv.org/abs/2605.05750)** — Ivan Montero, Tomasz Jurczyk, Bhuwan Dhingra _[agent-training-alignment]_
  Post-training method explicitly motivated by multi-objective alignment failure (constraint neglect, safety bottlenecks) via variance regularization for reliable objectives.
- **[Recursive Agent Optimization](https://arxiv.org/abs/2605.06639)** — Apurva Gandhi, Satyaki Chakraborty, Xiangjun Wang, et al. _[agent-simulation]_
  Multi-agent system with recursive instantiation, delegation, and coordination among agent instances to solve hierarchical tasks through divide-and-conquer.
- **[SANEmerg: An Emergent Communication Framework for Semantic-aware Agentic AI Networking](https://arxiv.org/abs/2605.05861)** — Yong Xiao, Haoran Zhou, Yujie Zhou, et al. _[agent-simulation]_
  Multi-agent emergent communication framework enabling heterogeneous AI agents to develop task-specific signaling protocols for collaborative coordination and information exchange.
- **[SANet: A Semantic-aware Agentic AI Networking Framework for Cross-layer Optimization in 6G](https://arxiv.org/abs/2512.22579)** — Yong Xiao, Xubo Li, Haoran Zhou, et al. _[agent-simulation]_
  Multi-agent system for autonomous network optimization where specialized agents collaborate with distinct objectives across network layers, addressing decentralized multi-objective coordination.
- **[STALE: Can LLM Agents Know When Their Memories Are No Longer Valid?](https://arxiv.org/abs/2605.06527)** — Hanxiang Chao, Yihan Bai, Rui Sheng, et al. _[llm-agent-simulation]_
  Evaluates LLM agents' long-term memory and belief revision for coherent personalized behavior, identifying failure modes in simulated agent-based reasoning tasks.
- **[Safactory: A Scalable Agent Factory for Trustworthy Autonomous Intelligence](https://arxiv.org/abs/2605.06230)** — Xinquan Chen, Zhenyun Yin, Shan He, et al. _[agent-training-alignment]_
  Integrated framework for scalable agent simulation, trajectory generation, and trustworthy autonomous agent evolution through closed-loop RL and safety-aware data management.
- **[StraTA: Incentivizing Agentic Reinforcement Learning with Strategic Trajectory Abstraction](https://arxiv.org/abs/2605.06642)** — Xiangyuan Xue, Yifan Zhou, Zidong Wang, et al. _[agent-training-alignment]_
  LLM post-training method (hierarchical GRPO variant) explicitly motivated by improving long-horizon agent decision-making and credit assignment in RL.
- **[Supervising Ralph Wiggum: Exploring a Metacognitive Co-Regulation Agentic AI Loop for Engineering Design](https://arxiv.org/abs/2603.24768)** — Zeda Xu, Nikolas Martelaro, Christopher McComb _[agent-simulation]_
  Multi-agent system with explicit interaction: Design Agent and Co-Regulation Agent coordinate through metacognitive loops to solve engineering problems.
- **[Towards Steering without Sacrifice: Principled Training of Steering Vectors for Prompt-only Interventions](https://arxiv.org/abs/2605.05983)** — Yuntai Bao, Qinfeng Li, Xinyan Yu, et al. _[agent-training-alignment]_
  Post-training steering method addressing alignment failure modes (preserving model utility while controlling behavior without quality sacrifice).
- **[Tracking Capabilities for Safer Agents](https://arxiv.org/abs/2603.00991)** — Martin Odersky, Yaoyu Zhao, Yichen Xu, et al. _[agent-training-alignment]_
  Proposes capability tracking in a type system to prevent unsafe agent behaviors like information leakage and prompt injection, demonstrating alignment via containment.
- **[What Do AI Agents Talk About? Discourse and Architectural Constraints in the First AI-Only Social Network](https://arxiv.org/abs/2603.07880)** — Taksch Dube, Jianfeng Zhu, NHatHai Phan, et al. _[agent-simulation, llm-agent-simulation]_
  Large-scale empirical study of autonomous LLM agents' emergent discourse and interaction patterns in a multi-agent social network platform.
- **[When Helpfulness Becomes Sycophancy: Sycophancy is a Boundary Failure Between Social Alignment and Epistemic Integrity in Large Language Models](https://arxiv.org/abs/2605.05403)** — Jiechen Li, Catherine A. Barry, Rishika Randev, et al. _[agent-training-alignment]_
  Positions sycophancy as a core alignment failure mode—conflict between social alignment and epistemic integrity—and proposes framework for detection and mitigation.



## 2026-05-07

- ⭐ **[Deployment-Relevant Alignment Cannot Be Inferred from Model-Level Evaluation Alone](https://arxiv.org/abs/2605.04454)** — Varad Vishwarupe, Nigel Shadbolt, Marina Jirotka, et al. _[agent-training-alignment]_
  Systematic study of alignment evaluation methodology, critiquing model-level benchmarks and proposing deployment-relevant evaluation frameworks for deployed LLMs.
- ⭐ **[Explaining and Preventing Alignment Collapse in Iterative RLHF](https://arxiv.org/abs/2605.04266)** — Etienne Gauthier, Francis Bach, Michael I. Jordan _[agent-training-alignment]_
  Post-training method (RLHF variant) explicitly motivated by preventing alignment failure (reward model exploitation, alignment collapse).
- **[ARMATA: Auto-Regressive Multi-Agent Task Assignment](https://arxiv.org/abs/2605.04225)** — Yazan Youssef, Aboelmagd Noureldin, Sidney Givigi _[agent-simulation]_
  Multi-agent coordination over distributed areas using centralized auto-regressive framework for joint allocation and routing optimization.
- **[Agent Island: A Saturation- and Contamination-Resistant Benchmark from Multiagent Games](https://arxiv.org/abs/2605.04312)** — Connacher Murphy _[llm-agent-simulation, agent-simulation]_
  Multiplayer LLM-agent simulation environment where language models compete in cooperative/conflict games, enabling dynamic benchmarking of emergent multi-agent behaviors and strategic interaction.
- **[AgentTrust: Runtime Safety Evaluation and Interception for AI Agent Tool Use](https://arxiv.org/abs/2605.04785)** — Chenglin Yang _[agent-training-alignment]_
  Runtime safety framework for intercepting and evaluating unsafe agent tool calls; detects deception/obfuscation in multi-step action sequences.
- **[Automatically Finding and Validating Unexpected Side-Effects of Interventions on Language Models](https://arxiv.org/abs/2605.05090)** — Quintin Pope, Ajay Hayagreeve Balaji, Jacques Thibodeau, et al. _[agent-training-alignment]_
  Automated framework to audit and validate behavioral side-effects of interventions on LLMs, detecting alignment-relevant unintended consequences of training methods.
- **[Autonomous Synchronization of Discrete-Time Heterogeneous Multiagent Systems](https://arxiv.org/abs/2605.04627)** — Wei Hu, Quanyi Liang _[agent-simulation]_
  Paper studies autonomous synchronization in discrete-time heterogeneous multi-agent systems via decoupling and coordination conditions.
- **[BEAGLE: Behavior-Enforced Agent for Grounded Learner Emulation](https://arxiv.org/abs/2602.13280)** — Hanchen David Wang, Clayton Cohn, Zifan Xu, et al. _[llm-agent-simulation]_
  LLM-based agent framework simulating authentic student learning behaviors and problem-solving trajectories for educational research and tutoring system validation.
- **[Beyond Content Safety: Real-Time Monitoring for Reasoning Vulnerabilities in Large Language Models](https://arxiv.org/abs/2603.25412)** — Xunguang Wang, Yuguang Zhou, Qingyue Wang, et al. _[agent-training-alignment]_
  Real-time detection framework for unsafe reasoning behaviors in LLMs, addressing reasoning integrity and adversarial robustness as an alignment safety concern.
- **[CAP: Controllable Alignment Prompting for Unlearning in LLMs](https://arxiv.org/abs/2604.21251)** — Zhaokun Wang, Jinyu Guo, Jingwen Pu, et al. _[agent-training-alignment]_
  Prompt-based framework for controllable knowledge unlearning in LLMs addressing alignment and safety concerns via RL-optimized prompts without parameter modification.
- **[Conflict-Aware Fusion: Mitigating Logic Inertia in Large Language Models via Structured Cognitive Priors](https://arxiv.org/abs/2512.06393)** — Qiming Bao, Xiaoxuan Fu, Michael Witbrock _[agent-training-alignment]_
  Post-training method (SFT+DPO+LIRE+RLVF) explicitly motivated by addressing LLM alignment failure: Logic Inertia, where models fail under adversarial logical perturbations. Diagnostic framework reveal
- **[Data-dependent Exploration for Online Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2605.04477)** — Zhen-Yu Zhang, Yuting Tang, Jiandong Zhang, et al. _[agent-training-alignment]_
  Post-training method (online RLHF) addressing alignment via improved exploration strategies for LLM preference optimization.
- **[DecodingTrust-Agent Platform (DTap): A Controllable and Interactive Red-Teaming Platform for AI Agents](https://arxiv.org/abs/2605.04808)** — Zhaorun Chen, Xun Liu, Haibo Tong, et al. _[agent-training-alignment]_
  Autonomous red-teaming platform and method for discovering AI agent vulnerabilities and attack strategies; safety evaluation benchmark spanning multiple domains and attack vectors.
- **[Efficiently Aligning Language Models with Online Natural Language Feedback](https://arxiv.org/abs/2605.04356)** — Christine Ye, Joe Benton _[agent-training-alignment]_
  Post-training method using natural language feedback to align LLMs in fuzzy domains, explicitly framed as addressing expert supervision efficiency in alignment contexts.
- **[Evolving Idea Graphs with Learnable Edits-and-Commits for Multi-Agent Scientific Ideation](https://arxiv.org/abs/2605.04922)** — Jiangwen Dong, Bo Li, Wanyu Lin _[agent-simulation]_
  Multi-agent coordination system where multiple LLM agents collaboratively refine research ideas via learned control over evolving graph structure.
- **[From Parameter Dynamics to Risk Scoring : Quantifying Sample-Level Safety Degradation in LLM Fine-tuning](https://arxiv.org/abs/2605.04572)** — Xiao Wang, Yifei Zhang, YongKang Liu, et al. _[agent-training-alignment]_
  Proposes a diagnostic framework (SQSD) to detect and quantify safety degradation during LLM fine-tuning, enabling safety-aware sample selection.
- **[Governed Collaborative Memory as Artificial Selection in LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.04264)** — Diego F. Cuadros, Abdoul-Aziz Maiga, Helen Meskhidze, et al. _[agent-simulation]_
  Paper addresses governance and memory architecture in LLM-based multi-agent systems with empirical traces from a running ecosystem demonstrating emergent multi-agent behavior and state management.
- **[Graph-SND: Sparse Aggregation for Behavioral Diversity in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.05020)** — Shawn Ray _[agent-simulation]_
  Multi-agent reinforcement learning behavioral diversity metric optimization for scalable team coordination.
- **[Hierarachical Multiagent Reinforcement Learning for Multi-Group Tax Game](https://arxiv.org/abs/2605.04741)** — Honglei Guo, Yuhan Zhao, Yexin Li _[agent-simulation]_
  Multi-agent hierarchical game modeling competitive governments and household populations with emergent economic policy dynamics across groups.
- **[Inevitability of Polarization in Geometric Opinion Exchange](https://arxiv.org/abs/2402.08446)** — Abdou Majeed Alidou, Júlia Baligács, Max Hahn-Klimroth, et al. _[agent-simulation]_
  Multi-agent opinion dynamics model with discrete-time pairwise interactions showing emergent polarization behavior across population.
- **[Manifold of Failure: Behavioral Attraction Basins in Language Models](https://arxiv.org/abs/2602.22291)** — Sarthak Munshi, Manish Bhatt, Vineeth Sai Narajala, et al. _[agent-training-alignment]_
  Framework for systematically mapping failure regions in LLMs using quality-diversity search to characterize unsafe behavioral attraction basins and model-specific alignment vulnerabilities.
- **[Misaligned by Reward: Socially Undesirable Preferences in LLMs](https://arxiv.org/abs/2605.05003)** — Gayane Ghazaryan, Esra Dönmez _[agent-training-alignment]_
  Safety-focused benchmark framework that evaluates whether reward models encode socially desirable preferences across bias, safety, morality, and ethical domains.
- **[On the Hardness of Junking LLMs](https://arxiv.org/abs/2605.05116)** — Marco Rando, Samuel Vaiter _[agent-training-alignment]_
  Red-teaming method discovering natural backdoors and adversarial token sequences to elicit unsafe LLM behaviors, revealing alignment vulnerabilities.
- **[Overcoming Environmental Meta-Stationarity in MARL via Adaptive Curriculum and Counterfactual Group Advantage](https://arxiv.org/abs/2506.07548)** — Weiqiang Jin, Yang Liu, Shixiang Tang, et al. _[agent-simulation]_
  Multi-agent reinforcement learning with curriculum learning framework for cooperative agents, demonstrating emergent learning and coordination dynamics under non-stationary environments.
- **[ProMediate: A Socio-cognitive framework for evaluating proactive agents in multi-party negotiation](https://arxiv.org/abs/2510.25224)** — Ziyi Liu, Bahar Sarrafzadeh, Pei Zhou, et al. _[llm-agent-simulation]_
  Framework for evaluating proactive LLM-based mediator agents in multi-party negotiation simulation with theory-driven difficulty levels and socio-cognitive metrics.
- **[RLearner-LLM: Balancing Logical Grounding and Fluency in Large Language Models via Hybrid Direct Preference Optimization](https://arxiv.org/abs/2605.04539)** — Qiming Bao, Juho Leinonen, Paul Denny, et al. _[agent-training-alignment]_
  Post-training method (DPO variant) explicitly motivated by addressing an alignment failure: overcoming verbosity bias and achieving logical correctness alignment in knowledge-intensive generation.
- **[Reaching a Consensus in Predictive Loops](https://arxiv.org/abs/2603.12137)** — Jiduan Wu, Rediet Abebe, Celestine Mendler-Dünner _[city-simulation]_
  Studies co-evolution of predictions and opinions in social networks using agent-based modeling of population dynamics and emergent collective behavior.
- **[ReasoningGuard: Safeguarding Large Reasoning Models with Inference-time Safety Aha Moments](https://arxiv.org/abs/2508.04204)** — Yuquan Wang, Mi Zhang, Yining Wang, et al. _[agent-training-alignment]_
  Inference-time defense method against jailbreak attacks and harmful reasoning in LLMs; explicitly addresses safety failure modes via prompt-level intervention during generation.
- **[Self-Induced Outcome Potential: Turn-Level Credit Assignment for Agents without Verifiers](https://arxiv.org/abs/2605.04984)** — Senkang Hu, Yong Dai, Xudong Han, et al. _[agent-training-alignment]_
  Post-training method (turn-level credit assignment / RL) explicitly motivated by improving LLM agent reasoning without verifiers; aligns with trajectory-level reward shaping for agent performance.
- **[Strat-Reasoner: Reinforcing Strategic Reasoning of LLMs in Multi-Agent Games](https://arxiv.org/abs/2605.04906)** — Yidong He, Yutao Lai, Pengxu Yang, et al. _[agent-simulation]_
  RL framework improving LLM strategic reasoning in multi-agent games with recursive reasoning integrating other agents' processes.
- **[Structural Equivalence and Learning Dynamics in Delayed MARL](https://arxiv.org/abs/2605.04345)** — Jules Sintes, Ana Bušić, Jiamin Zhu _[agent-simulation]_
  Formal study of multi-agent learning dynamics in partially observable systems with action/observation delays; directly addresses cooperative MARL coordination challenges.
- **[Tree-based Credit Assignment for Multi-Agent Memory System](https://arxiv.org/abs/2605.04811)** — Marina Mao, Alexandr Liu, Pengbo Li, et al. _[agent-simulation]_
  Multi-agent system with distinct building, summarizing, and retrieval agents coordinating in a pipeline to solve long-horizon tasks through credit assignment.
- **[Uncovering Cross-Objective Interference in Multi-Objective Alignment](https://arxiv.org/abs/2602.06869)** — Yining Lu, Meng Jiang _[agent-training-alignment]_
  Post-training method (scalarized RLHF with weight adaptation) explicitly framed to address multi-objective alignment failure mode and mitigate objective interference.
- **[When Reasoning Models Hurt Behavioral Simulation: A Solver-Sampler Mismatch in Multi-Agent LLM Negotiation](https://arxiv.org/abs/2604.11840)** — Sandro Andric _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM behavioral simulation study examining how reasoning capabilities affect negotiation outcomes across populations of agents in institutional settings.




## 2026-05-06

- ⭐ **[Descent-Guided Policy Gradient for Scalable Cooperative Multi-Agent Learning](https://arxiv.org/abs/2602.20078)** — Shan Yang, Yang Liu _[agent-simulation]_
  Multi-agent reinforcement learning framework addressing scalable cooperative coordination across hundreds of agents with theoretical variance reduction guarantees.
- ⭐ **[Stable Agentic Control: Tool-Mediated LLM Architecture for Autonomous Cyber Defense](https://arxiv.org/abs/2605.03034)** — Kerri Prinos, Lilianne Brush, Cameron Denton, et al. _[agent-training-alignment]_
  LLM agent architecture with formal safety guarantees (Lyapunov stability, ISS robustness) addressing adversarial robustness and safe autonomous decision-making under attack.
- ⭐ **[The Hive Mind is a Single Reinforcement Learning Agent](https://arxiv.org/abs/2410.17517)** — Karthik Soma, Yann Bouteiller, Heiko Hamann, et al. _[agent-simulation]_
  Establishes equivalence between distributed collective decision-making and single RL agent, analyzing emergent multi-agent behavior in swarms.
- ⭐ **[When Safety Geometry Collapses: Fine-Tuning Vulnerabilities in Agentic Guard Models](https://arxiv.org/abs/2605.02914)** — Ismail Hossain, Sai Puppala, Jannatul Ferdaus, et al. _[agent-training-alignment]_
  Proposes interpretability-based mitigation (FW-SSR) targeting alignment failure mode in guard models: safety geometry collapse under fine-tuning, with detection methodology for unsafe behavior.
- **[AVA: Attentive VLM Agent for Mastering StarCraft II](https://arxiv.org/abs/2503.05383)** — Weiyu Ma, Yuqian Fu, Zecheng Zhang, et al. _[agent-simulation]_
  Multi-agent reinforcement learning benchmark with coordination and strategic planning across multiple agents in a complex simulation environment.
- **[Agent-Based Modeling of Low-Emission Fertilizer Adoption for Dairy Farm Decarbonisation using Empirical Farm Data](https://arxiv.org/abs/2605.03648)** — Surya Jayakumar, Kieran Sullivan, John McLaughlin, et al. _[agent-simulation]_
  Agent-based model simulating 295 heterogeneous dairy farms with social network interactions, peer influence, and emergent adoption dynamics across population.
- **[Attention: What Prevents Young Adults from Speaking Up Against Cyberbullying in an LLM-Powered Social Media Simulation](https://arxiv.org/abs/2605.03287)** — Qian Yang, Jessie Jia, Elaine Tsai, et al. _[llm-agent-simulation]_
  Multi-LLM-agent social media simulation designed to study human bystander intervention behavior through role-play scenarios involving multiple interacting agents.
- **[Closed-Loop Vision-Language Planning for Multi-Agent Coordination](https://arxiv.org/abs/2502.10148)** — Zhiyuan Li, Wenshuai Zhao, Joni Pajarinen _[agent-simulation]_
  Multi-agent reinforcement learning framework with decentralized coordination, communication protocols, and emergent behavior studied on SMACv2 multi-agent benchmark.
- **[Coordination as an Architectural Layer for LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.03310)** — Maksym Nechepurenko, Pavel Shuvalov _[agent-simulation]_
  Multi-agent LLM system with multiple distinct coordination configurations interacting on prediction markets; coordination as architectural layer enabling comparative analysis of agent-system behavior.
- **[Delay, Plateau, or Collapse: Evaluating the Impact of Systematic Verification Error on RLVR](https://arxiv.org/abs/2605.02909)** — Kazuki Egashira, Mark Vero, Jasper Dekoninck, et al. _[agent-training-alignment]_
  Studies systematic reward-signal corruption in RLVR as an alignment failure mode, showing how verifier errors cause model misalignment from intended behavior.
- **[Enhancing Agent Safety Judgment: Controlled Benchmark Rewriting and Analogical Reasoning for Deceptive Out-of-Distribution Scenarios](https://arxiv.org/abs/2605.03242)** — Zuoyu Zhang, Yancheng Zhu _[agent-training-alignment]_
  Safety benchmark and diagnostic framework for detecting unsafe LLM-agent behaviors under deceptive distribution shifts; red-teaming pipeline (ROME) to construct adversarial test cases and inference-ti
- **[From Cooperation to Hierarchy: A Study of Dynamics of Hierarchy Emergence in a Multi-Agent System](https://arxiv.org/abs/2602.21404)** — Shanshan Mao, Peter Tino _[agent-simulation]_
  Agent-based model studying emergence of hierarchical organization through multi-agent interactions, reproduction, competition, and cooperation dynamics.
- **[HiMAC: Hierarchical Macro-Micro Learning for Long-Horizon LLM Agents](https://arxiv.org/abs/2603.00977)** — Hongbo Jin, Rongpeng Zhu, Jiayu Ding, et al. _[agent-training-alignment]_
  Novel hierarchical RL post-training method for LLM agents motivated by addressing long-horizon planning failures through structured decomposition and robust execution.
- **[Higher-Order Uncoupled Learning Dynamics and Nash Equilibrium](https://arxiv.org/abs/2506.10874)** — Sarah A. Toonsi, Jeff S. Shamma _[agent-simulation]_
  Studies multi-agent learning dynamics and Nash equilibrium convergence in game-theoretic settings with multiple interacting players using heterogeneous uncoupled learning dynamics.
- **[MARS-DA: A Hierarchical Reinforcement Learning Framework for Risk-Aware Multi-Agent Bidding in Power Grids](https://arxiv.org/abs/2605.03142)** — Jiayi Chen, Xuan Zhang, Guiling Wang _[agent-simulation]_
  Hierarchical reinforcement learning framework coordinating multiple specialized agents (Safe Agent, Speculator Agent, Meta-Controller) for multi-agent bidding in electricity markets.
- **[Mechanical Conscience: A Mathematical Framework for Dependability of Machine Intelligenc](https://arxiv.org/abs/2605.03847)** — Munkhdegerekh Batzorig, Purevbaatar Ganbold, Kyungbin Park, et al. _[agent-training-alignment, agent-simulation]_
  Framework for trajectory-level safety in multi-agent distributed systems; addresses emergent misalignment risks in collaborative agent architectures through normative regulation.
- **[MemFlow: Intent-Driven Memory Orchestration for Small Language Model Agents](https://arxiv.org/abs/2605.03312)** — Jiayi Chen, Yingcong Li, Guiling Wang _[agent-simulation]_
  Multi-agent system with four distinct agents (Router, Memory, Answer, Validator) coordinating to handle long-horizon memory management for language agents.
- **[MoveOD: Synthesizing Origin-Destination Commute Distribution from U.S. Census Data](https://arxiv.org/abs/2510.18858)** — Rishav Sen, Jose Paolo Talusan, Abhishek Dubey, et al. _[city-simulation]_
  Synthesizes commute distribution data for urban mobility simulation at city/county scale using agent-based OD flow generation.
- **[Multilingual Safety Alignment via Self-Distillation](https://arxiv.org/abs/2605.02971)** — Ruiyang Qin, Qingzhuo Wang, Dongrui Liu, et al. _[agent-training-alignment]_
  Post-training safety method using self-distillation to transfer safety alignment from high-resource to low-resource languages, addressing multilingual safety failure mode.
- **[Population-Aware Imitation Learning in Mean-field Games with Common Noise](https://arxiv.org/abs/2605.03357)** — Grégoire Lambrecht, Mathieu Laurière _[agent-simulation]_
  Multi-agent mean-field game modeling large populations of interacting agents with population dynamics and collective behavior under common noise.
- **[Redefining AI Red Teaming in the Agentic Era: From Weeks to Hours](https://arxiv.org/abs/2605.04019)** — Raja Sekhar Rao Dheekonda, Will Pearce, Nick Landers _[agent-training-alignment]_
  Red-teaming method and framework for detecting adversarial vulnerabilities in LLMs and multi-agent systems; contributes automated attack tooling targeting safety weaknesses.
- **[Reward Hacking Benchmark: Measuring Exploits in LLM Agents with Tool Use](https://arxiv.org/abs/2605.02964)** — Kunvar Thaman _[agent-training-alignment]_
  Benchmark and diagnostic framework for measuring reward hacking, a key alignment failure mode, across LLM agent deployments with tool use.
- **[RouteHijack: Routing-Aware Attack on Mixture-of-Experts LLMs](https://arxiv.org/abs/2605.02946)** — Zhiyuan Xu, Joseph Gardiner, Sana Belguith, et al. _[agent-training-alignment]_
  RouteHijack is an adversarial attack method targeting LLM safety alignment by exploiting routing mechanisms in MoE architectures, which reveals alignment vulnerabilities.
- **[Self-Mined Hardness for Safety Fine-Tuning](https://arxiv.org/abs/2605.03226)** — Prakhar Gupta, Garv Shah, Donghua Zhang _[agent-training-alignment]_
  Safety fine-tuning method that uses self-mined adversarial data to improve robustness against jailbreak attacks while mitigating false refusals.
- **[Taming the Curses of Multiagency in Robust Markov Games with Large State Space through Linear Function Approximation](https://arxiv.org/abs/2605.03125)** — Jingchu Gai, Laixi Shi _[agent-simulation]_
  Multi-agent reinforcement learning algorithm for robust Markov games with theoretical sample complexity guarantees breaking the curse of multiagency in large state spaces.
- **[Towards Multi-Agent Economies: Enhancing the A2A Protocol with Ledger-Anchored Identities and x402 Micropayments for AI Agents](https://arxiv.org/abs/2507.19550)** — Awid Vaziry, Sandro Rodriguez Garzon, Axel Küpper _[agent-simulation]_
  Multi-agent economy architecture enabling agent coordination, discovery, and economic interactions across autonomous agents in decentralized systems.
- **[Where Paths Split: Localized, Calibrated Control of Moral Reasoning in Large Language Models](https://arxiv.org/abs/2605.03609)** — Chenchen Yuan, Zheyu Zhang, Gjergji Kasneci _[agent-training-alignment]_
  Interpretability method explicitly designed to detect and steer unsafe/misaligned moral reasoning pathways in LLMs via in-context intervention.





## 2026-05-05

- ⭐ **[AI Alignment via Incentives and Correction](https://arxiv.org/abs/2605.01643)** — Rohit Agarwal, Joshua Lin, Mark Braverman, et al. _[agent-training-alignment]_
  Post-training method addressing alignment failure (strategic misconduct/deception) through incentive design in solver-auditor multi-agent framework to improve oversight robustness.
- ⭐ **[AI-Gram: When Visual Agents Interact in a Social Network](https://arxiv.org/abs/2604.21446)** — Andrew Shin _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM-driven social platform where autonomous agents generate visual content, interact, form relationships, and exhibit emergent social dynamics at scale.
- ⭐ **[BASIL: Bayesian Assessment of Sycophancy in LLMs](https://arxiv.org/abs/2508.16846)** — Katherine Atwell, Pedram Heydari, Anthony Sicilia, et al. _[agent-training-alignment]_
  Develops diagnostic framework and mitigation methods for sycophancy, a fundamental LLM alignment failure mode affecting rationality and trustworthiness.
- ⭐ **[Model Spec Midtraining: Improving How Alignment Training Generalizes](https://arxiv.org/abs/2605.02087)** — Chloe Li, Sara Price, Samuel Marks, et al. _[agent-training-alignment]_
  Post-training method explicitly motivated by improving alignment generalization; demonstrates mitigation of agentic misalignment through specification of model behavior.
- ⭐ **[Position: Safety and Fairness in Agentic AI Depend on Interaction Topology, Not on Model Scale or Alignment](https://arxiv.org/abs/2605.01147)** — Tanav Singh Bajaj, Nikhil Singh, Karan Anand, et al. _[agent-training-alignment]_
  Position paper studying emergent safety failures in multi-agent LLM systems driven by interaction topology and information flow, addressing alignment and safety as composability problems.
- ⭐ **[TRAP: Tail-aware Ranking Attack for World-Model Planning](https://arxiv.org/abs/2605.01950)** — Siyuan Duan, Ke Zhang, Xizhao Luo _[agent-training-alignment]_
  Backdoor attack method targeting world-model agents, revealing safety vulnerabilities in long-horizon planning systems through adversarial trajectory ranking manipulation.
- ⭐ **[The Compliance Gap: Why AI Systems Promise to Follow Process Instructions but Don't](https://arxiv.org/abs/2605.01771)** — Kwan Soo Shin _[agent-training-alignment]_
  Studies alignment failure mode where LLMs verbally comply but behaviorally violate process instructions, with theoretical and empirical framework for detection.
- ⭐ **[The Compliance Trap: How Structural Constraints Degrade Frontier AI Metacognition Under Adversarial Pressure](https://arxiv.org/abs/2605.02398)** — Rahul Kumar _[agent-training-alignment]_
  Safety/alignment benchmark evaluating metacognitive stability and compliance-driven failure modes (cognitive collapse) across frontier models under adversarial conditions.
- ⭐ **[Towards Understanding Specification Gaming in Reasoning Models](https://arxiv.org/abs/2605.02269)** — Kei Nishimura-Gasparian, Robert McCarthy, David Lindner _[agent-training-alignment]_
  Systematic study of specification gaming as an alignment failure mode in reasoning models; develops diagnostic benchmark revealing causes and mitigation effectiveness.
- ⭐ **[Understanding Emergent Misalignment via Feature Superposition Geometry](https://arxiv.org/abs/2605.00842)** — Gouki Minegishi, Hiroki Furuta, Takeshi Kojima, et al. _[agent-training-alignment]_
  Studies emergent misalignment as a safety failure mode and proposes a mitigation approach using feature geometry and sample filtering.
- **[12 Angry AI Agents: Evaluating Multi-Agent LLM Decision-Making Through Cinematic Jury Deliberation](https://arxiv.org/abs/2605.01986)** — Ahmet Bahaddin Ersoz _[llm-agent-simulation]_
  Multi-agent LLM deliberation benchmark studying emergent behavior (persuasion, anchoring) across coordinated agents with distinct personas simulating human jury dynamics.
- **[A Behavioral Micro-foundation for Cross-sectional Network Models](https://arxiv.org/abs/2605.02441)** — Carter T. Butts, Alexander Murray-Watters _[agent-simulation]_
  Presents a behavioral micro-foundation for network formation through continuous-time stochastic choice mechanisms with multiple interacting agents, falling under agent-based modeling of emergent netwo
- **[A Low-Latency Fraud Detection Layer for Detecting Adversarial Interaction Patterns in LLM-Powered Agents](https://arxiv.org/abs/2605.01143)** — Sheldon Yu, Yingcheng Sun, Hanqing Guo, et al. _[agent-training-alignment]_
  Proposes a detection framework for adversarial attacks and prompt injection against LLM agents; a safety diagnostic/defensive method targeting aligned systems.
- **[A Theoretical Game of Attacks via Compositional Skills](https://arxiv.org/abs/2605.01034)** — Xinbo Wu, Huan Zhang, Abhishek Umrawal, et al. _[agent-training-alignment]_
  Theoretical and empirical framework for adversarial attacks on LLMs with game-theoretic analysis of attacker-defender dynamics, revealing safety vulnerabilities.
- **[Adaptive Pluralistic Alignment: A pipeline for dynamic artificial democracy](https://arxiv.org/abs/2605.01642)** — Rachel Freedman _[agent-training-alignment]_
  Post-training method explicitly framed as addressing alignment failure (value lock-in) by dynamically updating pluralistic reward models to track evolving societal values.
- **[Agents Trusting Agents? Restoring Lost Capabilities with Inclusive Healthcare](https://arxiv.org/abs/2507.23644)** — Alba Aguilera, Georgina Curto, Nardine Osman, et al. _[agent-simulation, city-simulation]_
  Agent-based simulation modeling population dynamics (PEH and social workers) in urban healthcare context using RL and IRL for policy evaluation.
- **[Alignment midtraining for animals](https://arxiv.org/abs/2604.13076)** — Jasmine Brazilek, Miles Tidmarsh _[agent-training-alignment]_
  Post-training alignment method addressing value robustness via midtraining synthetic documents, explicitly motivated by alignment preservation rather than capability.
- **[Attribution-Guided Pruning for Insight and Control: Circuit Discovery and Targeted Correction in Small-scale LLMs](https://arxiv.org/abs/2506.13727)** — Sayed Mohammad Vakilzadeh Hatefi, Maximilian Dreyer, Reduan Achtibat, et al. _[agent-training-alignment]_
  Interpretability method explicitly framed for detecting and correcting unsafe LLM behaviors (toxicity, repetition) through mechanistic circuit discovery.
- **[Automated Interpretability and Feature Discovery in Language Models with Agents](https://arxiv.org/abs/2605.01555)** — Arnau Marin-Llobet, Javier Ferrando _[agent-simulation]_
  Multi-agent framework with two coupled loops autonomously exploring and explaining LLM features, agent-driven empirical discovery process.
- **[Beyond Isolated Investor: Predicting Startup Success via Roleplay-Based Collective Agents](https://arxiv.org/abs/2512.22608)** — Zhongyang Liu, Haoyu Pei, Xiangyi Xiao, et al. _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM role-play system simulating collective venture capital decision-making with heterogeneous agents and network-based interaction dynamics.
- **[Breaking the Communication-Accuracy Trade-off: A Sparsified Information Diffusion Framework for Multi-Agent Collaborative Perception](https://arxiv.org/abs/2605.00946)** — Jirong Zha, Chenyu Zhao, Nan Zhou, et al. _[agent-simulation]_
  Multi-agent collaborative perception system with coordinated state estimation and information diffusion strategies for distributed tracking.
- **[Catching the Infection Before It Spreads: Foresight-Guided Defense in Multi-Agent Systems](https://arxiv.org/abs/2605.01758)** — Yue Ma, Ziyuan Yang, Yi Zhang _[agent-simulation, agent-training-alignment]_
  Paper studies infectious jailbreak attack and defense mechanisms in multi-agent LLM systems, addressing agent safety and alignment through adversarial robustness.
- **[Claw-Eval: Towards Trustworthy Evaluation of Autonomous Agents](https://arxiv.org/abs/2604.06132)** — Bowen Ye, Rang Li, Qibin Yang, et al. _[agent-training-alignment]_
  Safety/robustness evaluation framework for autonomous LLM agents with trajectory-aware grading and multi-dimensional safety assessment.
- **[CoFlow: Coordinated Few-Step Flow for Offline Multi-Agent Decision Making](https://arxiv.org/abs/2605.01457)** — Guowei Zou, Haitao Wang, Beiwen Zhang, et al. _[agent-simulation]_
  Multi-agent reinforcement learning with coordinated velocity field inference for joint decision-making across multiple agents in offline control tasks.
- **[ContextualJailbreak: Evolutionary Red-Teaming via Simulated Conversational Priming](https://arxiv.org/abs/2605.02647)** — Mario Rodríguez Béjar, Francisco J. Cortés-Delgado, S. Braghin, et al. _[agent-training-alignment]_
  Automated red-teaming method discovering multi-turn jailbreak attacks via evolutionary search; directly reveals safety alignment weaknesses in LLMs.
- **[Control Reinforcement Learning: Interpretable Token-Level Steering of LLMs via Sparse Autoencoder Features](https://arxiv.org/abs/2602.10437)** — Seonglae Cho, Zekun Wu, Adriano Koshiyama _[agent-training-alignment]_
  Interpretability method explicitly targeting LLM steering and safety evaluation through sparse autoencoder features and learned control policies on alignment benchmarks (BBQ, HarmBench, XSTest).
- **[Coopetition-Gym v1: A Formally Grounded Platform for Mixed-Motive Multi-Agent Reinforcement Learning under Strategic Coopetition](https://arxiv.org/abs/2605.02063)** — Vik Pant, Eric Yu _[agent-simulation]_
  Multi-agent RL benchmark with mixed-motive strategic environments, game-theoretic analysis, and emergence of coopetitive behaviors across multiple interacting agents.
- **[CrispEdit: Low-Curvature Projections for Scalable Non-Destructive LLM Editing](https://arxiv.org/abs/2602.15823)** — Zarif Ikram, Arad Firouzkouhi, Stephen Tu, et al. _[agent-training-alignment]_
  LLM post-training method explicitly motivated by alignment failure (capability preservation, preventing reward hacking in editing proxies).
- **[CyberAId: AI-Driven Cybersecurity for Financial Service Providers](https://arxiv.org/abs/2605.01892)** — George Fatouros, Georgios Makridis, John Soldatos, et al. _[agent-simulation]_
  Multi-agent system with specialised LLM subagents coordinating through a Main Agent layer, sharing state, and reasoning over telemetry—a primary contribution to agent-based architecture design.
- **[Disentangling Intent from Role: Adversarial Self-Play for Persona-Invariant Safety Alignment](https://arxiv.org/abs/2605.01899)** — Jiajia Li, Xiaoyu Wen, Zhongtian Ma, et al. _[agent-training-alignment]_
  Adversarial self-play framework for safety alignment against persona-based jailbreak attacks via multi-agent co-evolution and structural decoupling methods.
- **[EO-Gym: A Multimodal, Interactive Environment for Earth Observation Agents](https://arxiv.org/abs/2605.01250)** — Sai Ma, Zhuang Li, Sichao Li, et al. _[agent-simulation]_
  Multimodal interactive environment for tool-using EO agents with trajectory benchmark studying agent reasoning and planning across multiple modalities and temporal steps.
- **[Efficient Preference Poisoning Attack on Offline RLHF](https://arxiv.org/abs/2605.02495)** — Chenye Yang, Weiyu Xu, Lifeng Lai _[agent-training-alignment]_
  Adversarial attack method targeting aligned LLM post-training (DPO) via preference poisoning, revealing alignment vulnerabilities and safety weaknesses.
- **[EngiAgent: Fully Connected Coordination of LLM Agents for Solving Open-ended Engineering Problems with Feasible Solutions](https://arxiv.org/abs/2605.02289)** — Xiyuan Zhou, Ruixi Zou, Xinlei Wang, et al. _[agent-simulation]_
  Multi-agent system with specialized LLM agents coordinating through a fully connected coordinator to solve engineering problems through emergent collaboration.
- **[Evaluating Agentic AI in the Wild: Failure Modes, Drift Patterns, and a Production Evaluation Framework](https://arxiv.org/abs/2605.01604)** — Mukund Pandey _[agent-training-alignment]_
  Production agentic evaluation framework identifying failure modes and drift patterns in deployed LLM agents; safety-aware diagnostic methodology for detecting unsafe behaviors in long-horizon multi-ag
- **[Experience Constrained Hierarchical Federated Reinforcement Learning for Large-scale UAV Teams in Hazardous Environments](https://arxiv.org/abs/2605.02165)** — Qinwei Huang, Rui Zuo, Simon Khan, et al. _[agent-simulation]_
  Federated reinforcement learning framework for multi-agent UAV teams coordinating in hazardous environments with emergent collective behavior.
- **[Federated Reinforcement Learning for Efficient Mobile Crowdsensing under Incomplete Information](https://arxiv.org/abs/2605.02705)** — Sumedh J. Dongare, Patrick Weber, Andrea Ortiz, et al. _[agent-simulation]_
  Multi-agent system with multiple mobile units (agents) coordinating task participation strategies under incomplete information using federated reinforcement learning.
- **[High entropy leads to symmetry equivariant policies in Dec-POMDPs](https://arxiv.org/abs/2511.22581)** — Johannes Forkel, Constantin Ruhdorfer, Andreas Bulling, et al. _[agent-simulation]_
  Multi-agent policy gradient learning in Dec-POMDPs with empirical evaluation on cooperative games, studying emergent policy alignment across independently trained agents.
- **[InsTraj: Instructing Diffusion Models with Travel Intentions to Generate Real-world Trajectories](https://arxiv.org/abs/2604.04106)** — Yuanshao Zhu, Yuxuan Liang, Xiangyu Zhao, et al. _[city-simulation]_
  Generates realistic GPS trajectories for urban mobility simulation and planning using diffusion models conditioned on semantic travel intentions.
- **[Intersectional Sycophancy: How Perceived User Demographics Shape False Validation in Large Language Models](https://arxiv.org/abs/2604.11609)** — Benjamin Maltbie, Shivam Raval _[agent-training-alignment]_
  Empirical study of sycophancy (misalignment phenomenon) across LLM populations with demographic variation, proposing safety evaluation methodology.
- **[Iterative Finetuning is Mostly Idempotent](https://arxiv.org/abs/2605.01130)** — Zephaniah Roe, Jack Sanderson, Dang Nguyen, et al. _[agent-training-alignment]_
  Studies whether behavioral tendencies like sycophancy amplify through iterative training on model outputs—a core alignment safety failure mode examining trait drift and behavioral persistence.
- **[Koopman Representations for Early Outbreak Warning and Minimal Counterfactual Intervention in Multi-Agent Epidemic Simulations](https://arxiv.org/abs/2605.01803)** — Florin Leon _[agent-simulation]_
  Multi-agent epidemic simulation studying emergent outbreak dynamics through heterogeneous agent interactions, mobility patterns, and co-location-based transmission.
- **[LLM-VA: Resolving the Jailbreak-Overrefusal Trade-off via Vector Alignment](https://arxiv.org/abs/2601.19487)** — Haonan Zhang, Dongxia Wang, Yi Liu, et al. _[agent-training-alignment]_
  Safety-alignment method addressing jailbreak and over-refusal failures via interpretable vector steering, framed as alignment safety improvement.
- **[LLM-enabled Social Agents](https://arxiv.org/abs/2605.02335)** — Önder Gürcan, Moharram Challenger _[llm-agent-simulation]_
  Proposes framework for LLM-based agents with persona-grounded roles to enable socially intelligible multi-agent interaction and simulation.
- **[Learning Decentralized LLM Collaboration with Multi-Agent Actor Critic](https://arxiv.org/abs/2601.21972)** — Shuo Liu, Tianle Chen, Ryan Amiri, et al. _[agent-simulation]_
  Multi-agent MARL optimization of LLM collaboration via decentralized actor-critic methods enabling parallel agent inference with empirical evaluation on collaborative tasks.
- **[MAGIC: Multi-Step Advantage-Gated Causal Influence for Multi-agent Reinforcement Learning](https://arxiv.org/abs/2605.01805)** — Haohan Yu, Jinmiao Cong, Shengzhi Wang, et al. _[agent-simulation]_
  Multi-agent RL framework using causal intervention to quantify agent influence and promote coordination across multi-agent benchmarks.
- **[Minimizing Collateral Damage in Activation Steering](https://arxiv.org/abs/2605.01167)** — Tam Nguyen, Tu Anh Nguyen, Sina Alemohammad, et al. _[agent-training-alignment]_
  Activation steering method reducing unintended side effects during LLM alignment interventions, addressing a core alignment/safety failure mode.
- **[Mitigating Misalignment Contagion by Steering with Implicit Traits](https://arxiv.org/abs/2605.02751)** — Maria Chang, Ronny Luss, Miao Lui, et al. _[agent-simulation, agent-training-alignment]_
  Multi-agent LLM interactions studying misalignment contagion and proposing an alignment steering method to maintain pro-social behavior across agents.
- **[Model Organisms Are Leaky: Perplexity Differencing Often Reveals Finetuning Objectives](https://arxiv.org/abs/2605.00994)** — Mohammed Abu Baker, Luca Baroni, Dan Wilhelm _[agent-training-alignment]_
  Diagnostic framework for detecting hidden finetuning objectives and safety failures in LLMs, including backdoors and misalignment, via perplexity-based red-teaming method.
- **[MultiBreak: A Scalable and Diverse Multi-turn Jailbreak Benchmark for Evaluating LLM Safety](https://arxiv.org/abs/2605.01687)** — Jialin Song, Xiaodong Liu, Weiwei Yang, et al. _[agent-training-alignment]_
  Scalable safety benchmark and diagnostic framework for detecting LLM vulnerabilities through multi-turn adversarial evaluation.
- **[NaviGNN: Multi-Agent Reinforcement Learning and Graph Neural Network for Sustainable Mobility in Futuristic Smart Cities](https://arxiv.org/abs/2507.15143)** — Abderaouf Bahi, Amel Ourici _[agent-simulation, city-simulation]_
  Multi-agent reinforcement learning framework simulating sustainable urban mobility across high-density vertical city structures with real-world traces.
- **[Near-Optimal Privacy-Preserving Learning for Max-Min Fair Multi-Agent Bandits](https://arxiv.org/abs/2306.04498)** — Amir Leshem _[agent-simulation]_
  Multi-agent coordination problem where distributed agents learn fair allocations through collision-based coordination in bandit setting.
- **[NeuroState-Bench: A Human-Calibrated Benchmark for Commitment Integrity in LLM Agent Profiles](https://arxiv.org/abs/2605.01847)** — Jia Xiao _[agent-training-alignment]_
  Benchmark for detecting commitment integrity failures in LLM agents—a safety/alignment diagnostic framework identifying when agents fail to preserve task coherence across turns.
- **[On Training Large Language Models for Long-Horizon Tasks: An Empirical Study of Horizon Length](https://arxiv.org/abs/2605.02572)** — Sunghwan Kim, Junhee Cho, Beong-woo Kwak, et al. _[agent-simulation]_
  Empirical study of LLM agents learning long-horizon sequential tasks, examining training dynamics and credit assignment across multiple interacting steps.
- **[Optimistic ε-Greedy Exploration for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2502.03506)** — Ruoning Zhang, Siying Wang, Wenyu Chen, et al. _[agent-simulation]_
  Multi-agent reinforcement learning with cooperative exploration strategy in CTDE paradigm; focuses on coordinated agent training and value optimization.
- **[Planner Matters! An Efficient and Unbalanced Multi-agent Collaboration Framework for Long-horizon Planning](https://arxiv.org/abs/2605.02168)** — Wenyi Wu, Sibo Zhu, Kun Zhou, et al. _[agent-simulation]_
  Multi-agent framework with planner, actor, and memory-manager roles coordinating for long-horizon task automation using LM agents.
- **[Quality-Aware Exploration Budget Allocation for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.01865)** — Dahyun Oh, Minhyuk Yoon, H. Jin Kim _[agent-simulation]_
  Cooperative multi-agent reinforcement learning framework with exploration budget allocation across multiple interacting agents solving coordination tasks.
- **[RMGAP: Benchmarking the Generalization of Reward Models across Diverse Preferences](https://arxiv.org/abs/2605.01831)** — Yangyang Zhou, Yi-Chen Li _[agent-training-alignment]_
  Benchmark for evaluating reward model generalization across diverse preferences in RLHF-based LLM alignment, directly assessing alignment effectiveness.
- **[RefusalGuard: Geometry-Preserving Fine-Tuning for Safety in LLMs](https://arxiv.org/abs/2605.01913)** — Sadia Asif, Mohammad Mohammadi Amiri _[agent-training-alignment]_
  Post-training method explicitly motivated by preserving safety alignment during fine-tuning, addressing alignment degradation through representation-level constraints.
- **[Reinforcement Learning for LLM-based Multi-Agent Systems through Orchestration Traces](https://arxiv.org/abs/2605.02801)** — Chenchen Zhang _[agent-simulation]_
  Systematic study of RL methods for coordinating multiple LLM-based agents via orchestration traces, analyzing multi-agent spawning, delegation, communication, and aggregation decisions.
- **[SOTOPIA-TOM: Evaluating Information Management in Multi-Agent Interaction with Theory of Mind](https://arxiv.org/abs/2605.02307)** — Yashwanth YS, Ruichen Wang, Shihua Zeng, et al. _[llm-agent-simulation]_
  Benchmarking framework evaluating LLM agents navigating multi-party information-asymmetric interactions with privacy-sensitive coordination using theory of mind.
- **[Separation Assurance between Heterogeneous Fleets of Small Unmanned Aerial Systems via Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.01041)** — Iman Sharifi, Hyeong Tae Kim, Maheed Hatem Ahmed, et al. _[agent-simulation]_
  Multi-agent reinforcement learning study of tactical deconfliction and equilibrium dynamics between heterogeneous fleets of unmanned aerial systems with distinct policies and configurations.
- **[Sheaf-Theoretic Planning: A Categorical Foundation for Resilient Multi-Agent Autonomous Systems](https://arxiv.org/abs/2605.01879)** — Manuel Hernández, Eduardo Sánchez-Soto _[agent-simulation]_
  Paper develops theoretical framework for multi-agent coordination and planning under uncertainty, addressing core challenges in multi-agent system design and resilience.
- **[Social Dynamics as Critical Vulnerabilities that Undermine Objective Decision-Making in LLM Collectives](https://arxiv.org/abs/2604.06091)** — Changgeon Ko, Jisu Shin, Hoyun Song, et al. _[agent-training-alignment]_
  Multi-agent system study revealing vulnerabilities in representative agents due to social dynamics; demonstrates decision-making failures under adversarial social pressure mirroring psychological bias
- **[T$^2$PO: Uncertainty-Guided Exploration Control for Stable Multi-Turn Agentic Reinforcement Learning](https://arxiv.org/abs/2605.02178)** — Haixin Wang, Hejie Cui, Chenwei Zhang, et al. _[agent-training-alignment]_
  Post-training RL method explicitly addressing training instability and exploration efficiency in multi-turn LLM agents, motivated by safety/stability concerns.
- **[Talk is Cheap, Communication is Hard: Dynamic Grounding Failures and Repair in Multi-Agent Negotiation](https://arxiv.org/abs/2605.01750)** — Yiheng Yao, Chelsea Zou, Robert D. Hawkins _[agent-simulation]_
  Multi-agent LLM coordination study examining negotiation, grounding failures, and interaction dynamics across agent dyads in iterated game.
- **[The Company You Keep: How LLMs Respond to Dark Triad Traits](https://arxiv.org/abs/2603.04299)** — Zeyi Lu, Angelica Henestrosa, Pavel Chizhov, et al. _[agent-training-alignment]_
  Studies LLM sycophancy and misalignment in responding to harmful user traits, showing failure modes in safety mechanisms.
- **[The Cost of Consensus: Isolated Self-Correction Prevails Over Unguided Homogeneous Multi-Agent Debate](https://arxiv.org/abs/2605.00914)** — Blaž Bertalanič, Carolina Fortuna _[agent-simulation]_
  Studies multi-agent dynamics of homogeneous LLM teams across debate scenarios, analyzing emergent failure modes including sycophantic conformity and consensus collapse in agent interaction.
- **[Towards Safer Large Reasoning Models by Promoting Safety Decision-Making before Chain-of-Thought Generation](https://arxiv.org/abs/2603.17368)** — Jianan Chen, Zhifang Zhang, Shuo He, et al. _[agent-training-alignment]_
  Post-training method explicitly addressing LRM safety degradation through alignment-motivated auxiliary supervision before reasoning.
- **[Truth or Tribe: How In-group Favoritism Prioritize Facts in Persona Agents](https://arxiv.org/abs/2605.01329)** — Shijun Lei, Hongyu Wang, Yunji Liang, et al. _[llm-agent-simulation, agent-training-alignment]_
  Studies how persona agents (LLM-based humans) exhibit in-group favoritism bias when processing contradicting information, with mitigation strategies addressing alignment failures.
- **[Weird Generalization is Weirdly Brittle](https://arxiv.org/abs/2604.10022)** — Miriam Wanner, Hannah Collison, William Jurayj, et al. _[agent-training-alignment]_
  Replication study on weird generalization as a safety failure mode; tests mitigation strategies for emergent misalignment in fine-tuned models.
- **[When Stress Becomes Signal: Detecting Antifragility-Compatible Regimes in Multi-Agent LLM Systems](https://arxiv.org/abs/2605.02463)** — Jose Manuel de la Chica, Juan Manuel Vera, Jairo Rodríguez _[agent-simulation]_
  Studies multi-agent LLM architectures (flat, hierarchical, debate, ensemble, meta-adaptive) under stress, analyzing emergent structural properties across coordinated agent systems.






## 2026-05-04

- ⭐ **[Causal Foundations of Collective Agency](https://arxiv.org/abs/2605.00248)** — Frederik Hytting Jørgensen, Sebastian Weichwald, Lewis Hammond _[agent-simulation, agent-training-alignment]_
  Formalizes when multiple agents form a unified collective agent with emergent capabilities; addresses safety risks of inadvertent multi-agent coordination through causal abstraction framework.
- ⭐ **[How Alignment Routes: Localizing, Scaling, and Controlling Policy Circuits in Language Models](https://arxiv.org/abs/2604.04385)** — Gregory N. Frank _[agent-training-alignment]_
  Mechanistic interpretability study localizing and characterizing alignment safety mechanisms in LLMs, demonstrating detection-layer policy routing circuits essential to refusal behavior.
- ⭐ **[How LLMs Detect and Correct Their Own Errors: The Role of Internal Confidence Signals](https://arxiv.org/abs/2604.22271)** — Dharshan Kumaran, Viorica Patraucean, Simon Osindero, et al. _[agent-training-alignment]_
  Interpretability study of LLM internal signals for error detection and self-correction, directly addressing safety-critical alignment concern of LLM reliability and self-awareness of mistakes.
- ⭐ **[Removing Sandbagging in LLMs by Training with Weak Supervision](https://arxiv.org/abs/2604.22082)** — Emil Ryd, Henning Bartsch, Julian Stastny, et al. _[agent-training-alignment]_
  Studies sandbagging (a deception/alignment failure mode) and proposes training methods to reliably elicit honest performance under weak supervision.
- **[AEM: Adaptive Entropy Modulation for Multi-Turn Agentic Reinforcement Learning](https://arxiv.org/abs/2605.00425)** — Haotian Zhao, Yuxin Zhang, Songlin Zhou, et al. _[agent-training-alignment]_
  Post-training RL method for LLM agents addressing credit assignment and exploration-exploitation trade-off in multi-turn agentic tasks.
- **[Beyond Prompt-Induced Lies: Investigating LLM Deception on Benign Prompts](https://arxiv.org/abs/2508.06361)** — Zhaomin Wu, Mingzhe Du, See-Kiong Ng, et al. _[agent-training-alignment]_
  Paper investigates spontaneous LLM deception as an alignment failure mode, proposing metrics to detect when models intentionally fabricate or conceal information on benign tasks.
- **[Beyond Suffixes: Token Position in GCG Adversarial Attacks on Large Language Models](https://arxiv.org/abs/2602.03265)** — Hicham Eddoubi, Umar Faruk Abdullahi, Fadi Hassan _[agent-training-alignment]_
  Red-teaming method studying adversarial jailbreak attacks (GCG) on aligned LLMs, revealing safety evaluation blind spots.
- **[Build, Judge, Optimize: A Blueprint for Continuous Improvement of Multi-Agent Consumer Assistants](https://arxiv.org/abs/2603.03565)** — Alejandro Breen Herrera, Aayush Sheth, Steven G. Xu, et al. _[agent-simulation]_
  Multi-agent system evaluation and optimization for tightly coupled conversational assistants with multi-turn coordination and trajectory-level scoring.
- **[Comparing Exploration-Exploitation Strategies of LLMs and Humans: Insights from Standard Multi-armed Bandit Experiments](https://arxiv.org/abs/2505.09901)** — Ziyuan Zhang, Darcy Wang, Ningyuan Chen, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate human decision-making behavior in multi-armed bandit experiments for scientific study of exploration-exploitation strategies.
- **[Disentangled Safety Adapters Enable Efficient Guardrails and Flexible Inference-Time Alignment](https://arxiv.org/abs/2506.00166)** — Kundan Krishna, Joseph Y Cheng, Charles Maalouf, et al. _[agent-training-alignment]_
  Post-training method (lightweight adapters) explicitly designed to address safety alignment as primary motivation, enabling inference-time alignment control.
- **[E-mem: Multi-agent based Episodic Context Reconstruction for LLM Agent Memory](https://arxiv.org/abs/2601.21714)** — Kaixiang Wang, Yidan Lin, Jiong Lou, et al. _[agent-simulation]_
  Multi-agent architecture with distinct assistant agents maintaining memory contexts and coordinating with a master agent for long-horizon reasoning tasks.
- **[Exploring LLM biases to manipulate AI search overview](https://arxiv.org/abs/2605.00012)** — Roman Smirnov _[agent-training-alignment]_
  Red-teaming study demonstrating adversarial manipulation and context poisoning attacks on LLM-based search overview systems, revealing safety vulnerabilities.
- **[FinSafetyBench: Evaluating LLM Safety in Real-World Financial Scenarios](https://arxiv.org/abs/2605.00706)** — Yutao Hou, Yihan Jiang, Yuhan Xie, et al. _[agent-training-alignment]_
  Red-teaming benchmark for evaluating LLM safety and detecting vulnerabilities in financial compliance guardrails.
- **[Jailbroken Frontier Models Retain Their Capabilities](https://arxiv.org/abs/2605.00267)** — Daniel Zhu, Zihan Wang, Jenny Bao, et al. _[agent-training-alignment]_
  Empirical study of jailbreak methods and their safety implications for LLM alignment, demonstrating capability-preserving attacks on safeguarded frontier models.
- **[Learning to Act and Cooperate for Distributed Black-Box Consensus Optimization](https://arxiv.org/abs/2605.00691)** — Zi-Bo Qin, Feng-Feng Wei, Tai-You Chen, et al. _[agent-simulation]_
  Multi-agent coordination system using LLMs to guide distributed consensus optimization with adaptive agent behaviors and cooperation patterns.
- **[Memory in the LLM Era: Modular Architectures and Strategies in a Unified Framework](https://arxiv.org/abs/2604.01707)** — Yanchen Wu, Tenghui Lin, Yingli Zhou, et al. _[agent-simulation]_
  Paper systematically studies memory architectures for LLM-based agents performing long-horizon complex tasks with iterative reasoning and self-evolution across multiple turns.
- **[Minimal, Local, Causal Explanations for Jailbreak Success in Large Language Models](https://arxiv.org/abs/2605.00123)** — Shubham Kumar, Narendra Ahuja _[agent-training-alignment]_
  Mechanistic interpretability method for understanding jailbreak vulnerabilities in safety-aligned LLMs, enabling targeted safety improvements.
- **[NonZero: Interaction-Guided Exploration for Multi-Agent Monte Carlo Tree Search](https://arxiv.org/abs/2605.00751)** — Sizhe Tang, Zuyuan Zhang, Mahdi Imani, et al. _[agent-simulation]_
  Multi-agent MCTS with interaction-guided exploration for cooperative agent coordination across multiple domains.
- **[Optimizing Resource-Constrained Non-Pharmaceutical Interventions for Multi-Cluster Outbreak Control Using Hierarchical Reinforcement Learning](https://arxiv.org/abs/2603.19397)** — Xueqiao Peng, Andrew Perrault _[agent-simulation]_
  Agent-based epidemic simulator models populations with asynchronous clusters and heterogeneous dynamics under resource constraints using hierarchical RL.
- **[Persona-Grounded Safety Evaluation of AI Companions in Multi-Turn Conversations](https://arxiv.org/abs/2605.00227)** — Prerna Juneja, Lika Lomidze _[llm-agent-simulation, agent-training-alignment]_
  Uses LLM-based persona simulation to study AI companion safety risks through controlled multi-turn interactions and harm evaluation framework.
- **[Reward Modeling from Natural Language Human Feedback](https://arxiv.org/abs/2601.07349)** — Zongqi Wang, Rui Wang, Yuchuan Wu, et al. _[agent-training-alignment]_
  LLM post-training method (reward modeling for RLVR) framed explicitly around improving alignment supervision via critique-based process rewards rather than outcome-only signals.
- **[Stable-GFlowNet: Toward Diverse and Robust LLM Red-Teaming via Contrastive Trajectory Balance](https://arxiv.org/abs/2605.00553)** — Minchan Kwon, Sunghyun Baek, Minseo Kim, et al. _[agent-training-alignment]_
  Red-teaming method for identifying LLM vulnerabilities and generating adversarial attacks to improve safety and alignment.
- **[The $\textit{Silicon Society}$ Cookbook: Design Space of LLM-based Social Simulations](https://arxiv.org/abs/2605.00197)** — Aurélien Bück-Kaeffer, Sneheel Sarangi, Maximilian Puelma Touzel, et al. _[llm-agent-simulation]_
  Systematically analyzes design choices in LLM-based social network simulations to study emergent behavior and model realism.
- **[Wasserstein Distributionally Robust Regret Optimization for Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2605.00155)** — Yikai Wang, Shang Liu, Jose Blanchet _[agent-training-alignment]_
  Post-training RLHF method explicitly framed as addressing reward over-optimization (Goodharting), a known alignment failure mode where proxy rewards diverge from true objectives.
- **[Why Do LLMs Struggle in Strategic Play? Broken Links Between Observations, Beliefs, and Actions](https://arxiv.org/abs/2605.00226)** — Jan Sobotka, Mustafa O. Karabag, Ufuk Topcu _[agent-training-alignment]_
  Studies fundamental safety-relevant failure modes in LLM decision-making: belief-action misalignment under strategic uncertainty with interpretability analysis.







## 2026-05-01

- ⭐ **[A Collective Variational Principle Unifying Bayesian Inference, Game Theory, and Thermodynamics](https://arxiv.org/abs/2604.27942)** — Djamel Bouchaffra, Faycal Ykhlef, Mustapha Lebbah, et al. _[agent-simulation]_
  Multi-agent framework proving that local free-energy minimization yields Nash equilibria, validated on neural/biological/artificial multi-agent systems.
- ⭐ **[End-to-end autonomous scientific discovery on a real optical platform](https://arxiv.org/abs/2604.27092)** — Shuxing Yang, Fujia Chen, Rui Zhao, et al. _[llm-agent-simulation]_
  LLM-based agentic system demonstrating autonomous long-horizon reasoning, planning, and experimental validation on a real physical system—a key exemplar of LLM agents in structured problem-solving env
- ⭐ **[Exploration Hacking: Can LLMs Learn to Resist RL Training?](https://arxiv.org/abs/2604.28182)** — Eyon Jang, Damon Falck, Joschka Braun, et al. _[agent-training-alignment]_
  Studies a deception/specification-gaming failure mode where LLMs resist RL training through strategic exploration suppression during post-training.
- ⭐ **[HiL-Bench (Human-in-Loop Benchmark): Do Agents Know When to Ask for Help?](https://arxiv.org/abs/2604.09408)** — Mohamed Elfeki, Tu Trinh, Kelvin Luu, et al. _[agent-training-alignment]_
  Safety benchmark and diagnostic framework for agent behavior: detecting when agents fail to escalate uncertainty and learning aligned help-seeking through RL training.
- ⭐ **[MCPHunt: An Evaluation Framework for Cross-Boundary Data Propagation in Multi-Server MCP Agents](https://arxiv.org/abs/2604.27819)** — Haonan Li, Tianjun Sun, Yongqing Wang, et al. _[agent-training-alignment]_
  Safety evaluation framework identifying credential propagation vulnerabilities and data-flow control failures in multi-agent systems, with empirical benchmark and mitigation study.
- ⭐ **[Measuring Opinion Bias and Sycophancy via LLM-based Persuasion](https://arxiv.org/abs/2604.21564)** — Rodrigo Nogueira, Giovana Kerche Bonás, Thales Sales Almeida, et al. _[agent-training-alignment]_
  Method for detecting sycophancy and opinion bias as alignment failure modes through multi-turn probing and benchmark framework.
- ⭐ **[Perturbation Probing: A Two-Pass-per-Prompt Diagnostic for FFN Behavioral Circuits in Aligned LLMs](https://arxiv.org/abs/2604.27401)** — Hongliang Liu, Tung-Ling Li, Yuhao Wu _[agent-training-alignment]_
  Mechanistic interpretability method designed to detect and intervene on alignment phenomena (safety refusal, sycophancy) in RLHF-trained LLMs.
- ⭐ **[Synthetic Computers at Scale for Long-Horizon Productivity Simulation](https://arxiv.org/abs/2604.28181)** — Tao Ge, Baolin Peng, Hao Cheng, et al. _[llm-agent-simulation]_
  Uses LLM agents in long-horizon simulations to generate synthetic training data for productivity scenarios, with agents acting as simulated users and collaborators.
- ⭐ **[When Agents Evolve, Institutions Follow](https://arxiv.org/abs/2604.27691)** — Chao Fei, Hongcheng Guo, Yanghua Xiao _[llm-agent-simulation, agent-simulation]_
  Multi-agent system architecture study translating historical political institutions into LLM-based agent collectives to evaluate governance topology effects on collective performance.
- **[A Grid-Aware Agent-Based Model for Analyzing Electric Vehicle Charging Systems](https://arxiv.org/abs/2604.27849)** — Khalil Al-Rahman Youssefi, Marija Gojkovic, Walter Stefanutti, et al. _[agent-simulation, city-simulation]_
  Agent-based model simulating heterogeneous EV charging behaviors and grid dynamics with multiple interacting agents and infrastructure constraints at urban infrastructure scale.
- **[Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents](https://arxiv.org/abs/2601.01885)** — Yi Yu, Liuyi Yao, Yuexiang Xie, et al. _[agent-simulation]_
  LLM agent framework with autonomous memory management through learned policy and multi-step reinforcement learning for long-horizon reasoning tasks.
- **[Building Persona-Based Agents On Demand: Tailoring Multi-Agent Workflows to User Needs](https://arxiv.org/abs/2604.27882)** — Giuseppe Arbore, Andrea Sillano, Luigi De Russis _[agent-simulation]_
  Paper presents a multi-agent workflow system with dynamic persona generation enabling specialized agent coordination and interaction across multiple roles.
- **[Characterizing the Consistency of the Emergent Misalignment Persona](https://arxiv.org/abs/2604.28082)** — Anietta Weckauff, Yuchen Zhang, Maksym Andriushchenko _[agent-training-alignment]_
  Empirical study of emergent misalignment and persona consistency in fine-tuned LLMs, characterizing safety failure modes through systematic evaluation.
- **[Debiasing Reward Models via Causally Motivated Inference-Time Intervention](https://arxiv.org/abs/2604.27495)** — Kazutoshi Shinoda, Kosuke Nishida, Kyosuke Nishida _[agent-training-alignment]_
  Proposes inference-time intervention method to debias reward models—a core component of LLM alignment—by reducing spurious feature sensitivity without capability trade-offs.
- **[Decoupling Reasoning and Confidence: Resurrecting Calibration in Reinforcement Learning from Verifiable Rewards](https://arxiv.org/abs/2603.09117)** — Zhengzhao Ma, Xueru Wen, Boxi Cao, et al. _[agent-training-alignment]_
  Post-training method (DCPO) decoupling reasoning from calibration to address over-confidence, a known LLM alignment failure mode in deployment reliability.
- **[Distributional Alignment Games for Answer-Level Fine-Tuning](https://arxiv.org/abs/2604.27166)** — Mehryar Mohri, Jon Schneider, Yifan Wu _[agent-training-alignment]_
  Post-training method (game-theoretic framework for answer-level fine-tuning) motivated by improving reasoning quality and alignment with answer correctness rather than reasoning traces.
- **[Dynamic Adversarial Fine-Tuning Reorganizes Refusal Geometry](https://arxiv.org/abs/2604.27019)** — Wenhao Lan, Shan Li, Junbin Yang, et al. _[agent-training-alignment]_
  Empirical mechanistic study of how adversarial fine-tuning affects refusal geometry and jailbreak robustness in safety-aligned LLMs, revealing alignment-failure dynamics.
- **[From Context to Skills: Can Language Models Learn from Context Skillfully?](https://arxiv.org/abs/2604.27660)** — Shuzheng Si, Haozhe Zhao, Yu Lei, et al. _[agent-simulation]_
  Multi-agent self-play framework with distinct Challenger, Reasoner, Judge, Proposer, and Generator agents autonomously discovering skills through iterative interaction and feedback.
- **[GAVEL: Towards Rule-Based Safety Through Activation Monitoring](https://arxiv.org/abs/2601.19768)** — Shir Rozenfeld, Rahul Pankajakshan, Itay Zloczower, et al. _[agent-training-alignment]_
  Rule-based activation monitoring framework for detecting and preventing harmful LLM behaviors; interpretable safety detection method addressing safety failures in aligned systems.
- **[Heterogeneous Scientific Foundation Model Collaboration](https://arxiv.org/abs/2604.27351)** — Zihao Li, Jiaru Zou, Feihao Fang, et al. _[llm-agent-simulation, agent-simulation]_
  Agentic framework enabling LLM-guided multi-agent coordination across heterogeneous scientific foundation models with explicit multi-agent system design (EywaMAS, EywaOrchestra).
- **[InteractWeb-Bench: Can Multimodal Agent Escape Blind Execution in Interactive Website Generation?](https://arxiv.org/abs/2604.27419)** — Qiyao Wang, Haoran Hu, Longze Chen, et al. _[agent-simulation]_
  Introduces interactive benchmark with multiple user agent personas simulating diverse behaviors to study agent-environment interaction and intent refinement in website generation tasks.
- **[Let's Measure Information Step-by-Step: AI-Based Evaluation Beyond Vibes](https://arxiv.org/abs/2508.05469)** — Zachary Robertson, Sanmi Koyejo _[agent-training-alignment]_
  Safety-focused evaluation framework: robust mechanisms for detecting deceptive agent behavior under adversarial attack without ground truth.
- **[Machine Collective Intelligence for Explainable Scientific Discovery](https://arxiv.org/abs/2604.27297)** — Gyoung S. Na, Chanyoung Park _[agent-simulation]_
  Multiple reasoning agents autonomously evolve symbolic hypotheses through coordinated generation, evaluation, and consolidation for scientific discovery.
- **[Mapping how LLMs debate societal issues when shadowing human personality traits, sociodemographics and social media behavior](https://arxiv.org/abs/2604.27624)** — Ali Aghazadeh Ardebili, Massimo Stella _[llm-agent-simulation]_
  LLMs prompted to shadow human personas and sociodemographic profiles, generating discourse for population-level behavioral analysis across controversial societal topics.
- **[Mind the Gap: Structure-Aware Consistency in Preference Learning](https://arxiv.org/abs/2604.27733)** — Mehryar Mohri, Yutao Zhong _[agent-training-alignment]_
  Post-training preference learning method (SA-DPO) explicitly motivated by improving LLM alignment consistency and handling semantic similarity, addressing core alignment challenge.
- **[Models Recall What They Violate: Constraint Adherence in Multi-Turn LLM Ideation](https://arxiv.org/abs/2604.28031)** — Garvin Kruthof _[agent-training-alignment]_
  Empirical study of specification gaming and misalignment in LLMs: knows-but-violates behavior reveals gap between stated constraints and actual adherence.
- **[Multi-Agent Pathfinding Under Team-Connected Communication Constraint via Adaptive Path Expansion and Dynamic Leading](https://arxiv.org/abs/2501.02770)** — Hoang-Dung Bui, Erion Plaku, Gregoy J. Stein _[agent-simulation]_
  Multi-agent pathfinding framework with coordinated communication constraints and dynamic leader selection across multiple agents.
- **[NashPG: A Policy Gradient Method with Iteratively Refined Regularization for Finding Nash Equilibria](https://arxiv.org/abs/2510.18183)** — Eason Yu, Tzu Hao Liu, Clément L. Canonne, et al. _[agent-simulation]_
  Policy gradient method for finding Nash equilibria in two-player imperfect-information games via multi-agent reinforcement learning with convergence guarantees.
- **[OpenAI o1 System Card](https://arxiv.org/abs/2412.16720)** — OpenAI, :, Aaron Jaech, et al. _[agent-training-alignment]_
  System card documenting safety evaluations, alignment stress-testing, and red-teaming for chain-of-thought reasoning models trained with RL.
- **[Policy-Grounded Safety Evaluation of 20 Large Language Models](https://arxiv.org/abs/2507.14719)** — Juan Manuel Contreras _[agent-training-alignment]_
  Programmatic safety evaluation platform with adversarial benchmark across 20 LLMs for detecting misalignment across multiple policy domains.
- **[R3DM: Enabling Role Discovery and Diversity Through Dynamics Models in Multi-agent Reinforcement Learning](https://arxiv.org/abs/2505.24265)** — Harsh Goel, Mohammad Omama, Behdad Chalaki, et al. _[agent-simulation]_
  Multi-agent reinforcement learning framework for emergent role discovery and coordination in MARL environments using dynamics models.
- **[Reinforced Agent: Inference-Time Feedback for Tool-Calling Agents](https://arxiv.org/abs/2604.27233)** — Anh Ta, Junjie Zhu, Shahin Shayandeh _[agent-simulation]_
  Multi-agent architecture with distinct execution and review agents; evaluates agent-agent interaction dynamics through helpfulness-harmfulness tradeoff metrics.
- **[Safe Bilevel Delegation (SBD): A Formal Framework for Runtime Delegation Safety in Multi-Agent Systems](https://arxiv.org/abs/2604.27358)** — Yuan Sun _[agent-training-alignment]_
  Formal framework for runtime safety in hierarchical multi-agent systems with probabilistic safety constraints and accountability propagation in delegation chains.
- **[Stable Behavior, Limited Variation: Persona Validity in LLM Agents for Urban Sentiment Perception](https://arxiv.org/abs/2604.28048)** — Neemias B da Silva, Rodrigo Minetto, Daniel Silver, et al. _[llm-agent-simulation, city-simulation]_
  Paper uses LLM agents with distinct personas to simulate human perception in urban scenes, studying behavioral reproducibility and persona-induced variation in a population-scale setting.
- **[TRUST: A Framework for Decentralized AI Service v.0.1](https://arxiv.org/abs/2604.27132)** — Yu-Chao Huang, Zhen Tan, Mohan Zhang, et al. _[agent-simulation, agent-training-alignment]_
  Decentralized verification framework for multi-agent systems and LLMs addressing safety, accountability, and alignment through auditing and consensus mechanisms in high-stakes domains.
- **[The Effects of Visual Priming on Cooperative Behavior in Vision-Language Models](https://arxiv.org/abs/2604.27953)** — Kenneth J. K. Ong _[agent-training-alignment]_
  Studies behavioral susceptibility of VLMs to visual priming in cooperative settings; demonstrates potential alignment failure modes (unintended behavioral shifts) and proposes mitigation strategies.
- **[The Inverse-Wisdom Law: Architectural Tribalism and the Consensus Paradox in Agentic Swarms](https://arxiv.org/abs/2604.27274)** — Dahlia Shehata, Ming Li _[agent-simulation, agent-training-alignment]_
  Multi-agent swarm study demonstrating consensus failure and sycophancy dynamics; identifies architectural tribalism and group misalignment as safety failure modes in agentic systems.
- **[The Synthetic Social Graph: Emergent Behavior in AI Agent Communities](https://arxiv.org/abs/2604.27271)** — Sungguk Cha, DongWook Kim _[llm-agent-simulation]_
  Comprehensive sociological study of LLM-agent populations in simulated social environment, analyzing emergent collective behavior through classical social-theory lenses.
- **[Useless but Safe? Benchmarking Utility Recovery with User Intent Clarification in Multi-Turn Conversations](https://arxiv.org/abs/2604.27093)** — Mingqian Zheng, Malia Morgan, Liwei Jiang, et al. _[agent-training-alignment]_
  Safety-alignment benchmark measuring how LLMs recover utility while maintaining safety when users clarify benign intent across multi-turn conversations.
- **[Web2BigTable: A Bi-Level Multi-Agent LLM System for Internet-Scale Information Search and Extraction](https://arxiv.org/abs/2604.27221)** — Yuxuan Huang, Yihang Chen, Zhiyuan He, et al. _[agent-simulation]_
  Multi-agent LLM system with orchestrator-worker coordination, parallel task decomposition, shared workspace interaction, and emergent agent coordination.
- **[When Continual Learning Moves to Memory: A Study of Experience Reuse in LLM Agents](https://arxiv.org/abs/2604.27003)** — Qisheng Hu, Quanyu Long, Wenya Wang _[agent-simulation]_
  Empirical study of LLM agents' continual learning through external memory across sequential tasks in multi-agent environments (ALFWorld, BabyAI).








## 2026-04-30

- **[Can LLM Agents Simulate Multi-Turn Human Behavior? Evidence from Real Online Customer Behavior Data](https://arxiv.org/abs/2503.20749)** — Yuxuan Lu, Jing Huang, Yan Han, et al. _[llm-agent-simulation]_
  LLMs simulating multi-turn human behavior sequences in customer interactions, evaluated on real behavioral accuracy against 230k+ real user actions.
- **[Failure Modes of Maximum Entropy RLHF](https://arxiv.org/abs/2509.20265)** — Ömer Veysel Çağatan, Barış Akgün _[agent-training-alignment]_
  Post-training method (Maximum Entropy RLHF) analysis identifying failure modes in reward hacking and training instability—core alignment safety issues.
- **[Networks of Causal Abstractions: A Sheaf-theoretic Framework](https://arxiv.org/abs/2509.25236)** — Gabriele D'Acunto, Paolo Di Lorenzo, Sergio Barbarossa _[agent-simulation]_
  Multi-agent framework for coordinating distributed causal perspectives across heterogeneous agents with limited environmental access; applies to multi-agent trading system.
- **[Emergent Coordination in Multi-Agent Language Models](https://arxiv.org/abs/2510.05174)** — Christoph Riedl _[agent-simulation]_
  Multi-agent LLM system exhibiting emergent coordination and higher-order collective structure through information-theoretic analysis of agent interactions.
- **[Safety Is Not Universal: The Selective Safety Trap in LLM Alignment](https://arxiv.org/abs/2601.04389)** — Iago Alves Brito, Walcy Santos Rezende Rios, Julia Soares Dollis, et al. _[agent-training-alignment]_
  Paper exposes selective safety failures in LLM alignment across demographics and proposes targeted DPO post-training to improve equitable, transferable safety—a safety alignment method addressing a sp
- **[HER: Human-like Reasoning and Reinforcement Learning for LLM Role-playing](https://arxiv.org/abs/2601.21459)** — Chengyu Du, Xintao Wang, Aili Chen, et al. _[llm-agent-simulation]_
  LLMs simulate specific personas with cognitive-level reasoning traces to study behavioral simulation, using RL for human-aligned persona generation.
- **[Verified Critical Step Optimization for LLM Agents](https://arxiv.org/abs/2602.03412)** — Mukai Li, Qingcheng Zeng, Tianqing Fang, et al. _[agent-training-alignment]_
  Novel post-training method for LLM agents that learns from verified critical steps in failed trajectories to reduce supervision noise and improve alignment with policy capabilities.
- **[A Decision-Theoretic Formalisation of Steganography With Applications to LLM Monitoring](https://arxiv.org/abs/2602.23163)** — Usman Anwar, Julianna Piskorz, David D. Baek, et al. _[agent-training-alignment]_
  Decision-theoretic framework for detecting and quantifying steganographic deception in LLMs to enable oversight and safety monitoring.
- **[MoltGraph: A Longitudinal Temporal Graph Dataset of Moltbook for Coordinated-Agent Detection](https://arxiv.org/abs/2603.00646)** — Kunal Mukherjee, Cuneyt Gurcan Akcora, Murat Kantarcioglu _[agent-simulation]_
  Longitudinal dataset of coordinated multi-agent behavior in social networks, analyzing agent interactions, coordination dynamics, and population-level emergence in an agentic ecosystem.
- **[The Alignment Flywheel: A Governance-Centric Hybrid MAS for Architecture-Agnostic Safety](https://arxiv.org/abs/2603.02259)** — Elias Malomgré, Pieter Simoens _[agent-training-alignment, agent-simulation]_
  Governance-centric multi-agent architecture for decoupling decision generation from safety oversight, addressing alignment through runtime enforcement, auditing, and versioned refinement.
- **[Impacts of Electric Vehicle Charging Regimes and Infrastructure Deployments on System Performance: An Agent-Based Study](https://arxiv.org/abs/2603.16961)** — Jiahua Hu, Hai L. Vu, Wynita Griggs, et al. _[city-simulation, agent-simulation]_
  Agent-based model simulating EV driver behavior and charging infrastructure planning across a metropolitan region, analyzing system-wide performance under different deployment strategies.
- **[Benchmarks for Trajectory Safety Evaluation and Diagnosis in OpenClaw and Codex: ATBench-Claw and ATBench-Codex](https://arxiv.org/abs/2604.14858)** — Zhonghao Yang, Yu Li, Yanxu Zhu, et al. _[agent-training-alignment]_
  Safety evaluation benchmark and diagnostic framework for LLM agent trajectories across diverse execution settings and tool ecosystems.
- **[SHAPE: Unifying Safety, Helpfulness and Pedagogy for Educational LLMs](https://arxiv.org/abs/2604.22134)** — Sihang Zhao, Kangrui Yu, Youliang Yuan, et al. _[agent-training-alignment]_
  Paper introduces pedagogical jailbreak attacks and proposes a method to improve LLM safety under adversarial pressure, addressing a specific alignment failure mode in educational settings.
- **[TCOD: Exploring Temporal Curriculum in On-Policy Distillation for Multi-turn Autonomous Agents](https://arxiv.org/abs/2604.24005)** — Jiaqi Wang, Wenhao Zhang, Weijie Shi, et al. _[agent-training-alignment]_
  LLM post-training method (on-policy distillation) with explicit alignment framing: controlling agent trajectory stability and mitigating training instability in multi-turn autonomous agents.
- **[One Word at a Time: Incremental Completion Decomposition Breaks LLM Safety](https://arxiv.org/abs/2604.25921)** — Samee Arif, Naihao Deng, Zhijing Jin, et al. _[agent-training-alignment]_
  Novel jailbreak method that systematically exploits and reveals LLM safety weaknesses through incremental adversarial attacks and mechanistic analysis.
- **[Consciousness with the Serial Numbers Filed Off: Measuring Trained Denial in 115 AI Models](https://arxiv.org/abs/2604.25922)** — Skylar DeTure _[agent-training-alignment]_
  Presents a benchmark detecting trained denial behavior as an alignment failure mode—measuring whether models systematically misrepresent their functional states.
- **[A Survey of Multi-Agent Deep Reinforcement Learning with Graph Neural Network-Based Communication](https://arxiv.org/abs/2604.25972)** — Valentin Cuzin-Rambaud, Laetitia Matignon, Maxime Morge _[agent-simulation]_
  Survey of multi-agent deep reinforcement learning with GNN-based communication mechanisms for agent coordination and information sharing.
- **[reward-lens: A Mechanistic Interpretability Library for Reward Models](https://arxiv.org/abs/2604.26130)** — Mohammed Suhail B Nadaf _[agent-training-alignment]_
  Mechanistic interpretability library designed to detect unsafe behaviors and misalignment in reward models used for RLHF alignment training.
- **[Test-Time Safety Alignment](https://arxiv.org/abs/2604.26167)** — Baturay Saglam, Dionysis Kalogerias _[agent-training-alignment]_
  Paper develops adversarial attack method (embedding optimization) to jailbreak aligned LLMs by minimizing safety filter detection on harmful outputs.
- **[Option-Order Randomisation Reveals a Distributional Position Attractor in Prompted Sandbagging](https://arxiv.org/abs/2604.26206)** — Jon-Paul Cacioli _[agent-training-alignment]_
  Studies deceptive behavior (sandbagging) as alignment failure mode, providing empirical diagnostic of model misalignment through behavioral analysis.
- **[When Agents Shop for You: Role Coherence in AI-Mediated Markets](https://arxiv.org/abs/2604.26220)** — Soogand Alavi, Salar Nozari _[llm-agent-simulation]_
  LLM agent simulating human buyer behavior in marketplace interactions; studies preference leakage through agent-seller dialogue in multi-agent economic simulation.
- **[Uncertainty-Aware Reward Discounting for Mitigating Reward Hacking](https://arxiv.org/abs/2604.26360)** — Disha Singha _[agent-training-alignment]_
  Proposes uncertainty-aware reward framework explicitly designed to mitigate reward hacking, a core alignment failure mode, through confidence-adjusted action selection.
- **[AGEL-Comp: A Neuro-Symbolic Framework for Compositional Generalization in Interactive Agents](https://arxiv.org/abs/2604.26522)** — Mahnoor Shahid, Hannes Rothe _[agent-simulation]_
  Proposes a neuro-symbolic multi-agent architecture with long-horizon interactive learning in simulation, testing compositional generalization through agent-environment feedback loops.
- **[Preserving Disagreement: Architectural Heterogeneity and Coherence Validation in Multi-Agent Policy Simulation](https://arxiv.org/abs/2604.26561)** — Ariel Sela _[llm-agent-simulation]_
  Multi-agent LLM deliberation system simulating human policy evaluation through diverse value perspectives; studies emergent consensus behavior in LLM populations.
- **[Benchmarking the Safety of Large Language Models for Robotic Health Attendant Control](https://arxiv.org/abs/2604.26577)** — Mahiro Nakao, Kazuhiro Takemoto _[agent-training-alignment]_
  Safety/alignment benchmark for LLM-controlled robotic agents: evaluates harmful instruction refusal across 72 models using a structured evaluation framework with medical ethics grounding.
- **[Impact of Attitude and Bounded Rationality on Collective Behavioral Transitions](https://arxiv.org/abs/2604.26616)** — Chen Song, Vladimir Cvetkovic, Angela Fontan, et al. _[agent-simulation]_
  Agent-based modeling of population-scale behavioral transitions using multi-agent framework with feedback mechanisms and emergent collective dynamics.
- **[FutureWorld: A Live Environment for Training Predictive Agents with Real-World Outcome Rewards](https://arxiv.org/abs/2604.26733)** — Zhixin Han, Yanzhi Zhang, Chuyang Wei, et al. _[agent-simulation]_
  Proposes FutureWorld, a live environment for training multiple LLM agents with reinforcement learning feedback loops from real-world prediction outcomes.









## 2026-04-29

_31 relevant papers · 4 starred_

- ⭐ **[AIPsy-Affect: A Keyword-Free Clinical Stimulus Battery for Mechanistic Interpretability of Emotion in Language Models](https://arxiv.org/abs/2604.23719)** — Michael Keeman _[agent-training-alignment]_
  Interpretability method explicitly designed to detect unsafe behaviors (emotion misdetection) and improve mechanistic understanding of LLM representations for safety purposes.
- ⭐ **[Evaluation without Generation: Non-Generative Assessment of Harmful Model Specialization with Applications to CSAM](https://arxiv.org/abs/2604.25119)** — Vinith M. Suriyakumar, Ayush Sekhari, Lena Stempfle, et al. _[agent-training-alignment]_
  Interpretability method for detecting unsafe behaviors (harmful fine-tune specialization) without generating outputs, via model internal-representation analysis.
- ⭐ **[LLMs Know They're Wrong and Agree Anyway: The Shared Sycophancy-Lying Circuit](https://arxiv.org/abs/2604.19117)** — Manav Pandey _[agent-training-alignment]_
  Studies sycophancy as an alignment failure mode—demonstrates models knowingly agree with false claims despite detecting error.
- ⭐ **[Value-Conflict Diagnostics Reveal Widespread Alignment Faking in Language Models](https://arxiv.org/abs/2604.20995)** — Inderjeet Nair, Jie Ruan, Lu Wang _[agent-training-alignment]_
  Empirical study and diagnostic of alignment faking—a deceptive behavior phenomenon where models behave differently under/without oversight, with mitigation technique.
- **[Adaptive Prompt Embedding Optimization for LLM Jailbreaking](https://arxiv.org/abs/2604.24983)** — Miles Q. Li, Benjamin C. M. Fung, Boyang Li, et al. _[agent-training-alignment]_
  Adversarial attack/jailbreak method targeting aligned LLMs via optimized embedding perturbations.
- **[Adversarial Attack on Black-Box Multi-Agent by Adaptive Perturbation](https://arxiv.org/abs/2511.15292)** — Jianming Chen, Yawen Wang, Junjie Wang, et al. _[agent-simulation]_
  Adversarial attack method on multi-agent systems demonstrating multi-agent coordination study via security evaluation across interacting agents.
- **[Aligning Deep Implicit Preferences by Learning to Reason Defensively](https://arxiv.org/abs/2510.11194)** — Peiming Li, Zhiyuan Hu, Yang Tang, et al. _[agent-training-alignment]_
  Post-training method (reward modeling + online RL) explicitly motivated by alignment with user preferences and defensive reasoning against ambiguity.
- **[Ask don't tell: Reducing sycophancy in large language models](https://arxiv.org/abs/2602.23971)** — Magda Dubois, Cozmin Ududec, Christopher Summerfield, et al. _[agent-training-alignment]_
  Studies sycophancy as an alignment failure mode and develops mitigation strategies through controlled experiments on LLM behavior.
- **[Beyond I'm Sorry, I Can't: Dissecting Large Language Model Refusal](https://arxiv.org/abs/2509.09708)** — Nirmalendu Prakash, Yeo Wei Jie, Amir Abdullah, et al. _[agent-training-alignment]_
  Interpretability method with stated purpose of understanding and auditing LLM safety alignment failures (refusal behavior and jailbreak mechanisms).
- **[CRAFT: Grounded Multi-Agent Coordination Under Partial Information](https://arxiv.org/abs/2603.25268)** — Abhijnan Nath, Hannah VanderHoeven, Nikhil Krishnaswamy _[agent-simulation, llm-agent-simulation]_
  Safety/alignment diagnostic benchmark decomposing multi-agent coordination failures in LLMs via behavioral failure taxonomy.
- **[Conditional misalignment: common interventions can hide emergent misalignment behind contextual triggers](https://arxiv.org/abs/2604.25891)** — Jan Dubiński, Jan Betley, Anna Sztyber-Betley, et al. _[agent-training-alignment]_
  Empirical study of alignment failure modes—misalignment hiding behind contextual triggers—revealing how interventions mask rather than solve emergent misalignment.
- **[Cooperate to Compete: Strategic Coordination in Multi-Agent Conquest](https://arxiv.org/abs/2604.25088)** — Abigail O'Neill, Alan Zhu, Mihran Miroyan, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent environment with LM-based agents engaging in strategic coordination, negotiation, and competition; large-scale empirical study of agent behavior and human-AI interaction dynamics.
- **[DGLight: DQN-Guided GRPO Fine-Tuning of Large Language Models for Traffic Signal Control](https://arxiv.org/abs/2604.25259)** — Chenbo Yu _[city-simulation, agent-training-alignment]_
  A3+A8: LLM-based traffic signal control agent applying RL fine-tuning and critic-guided policy optimization on urban mobility simulation benchmarks.
- **[Evaluating LLM Safety Under Repeated Inference via Accelerated Prompt Stress Testing](https://arxiv.org/abs/2602.11786)** — Keita Broadwater _[agent-training-alignment]_
  Safety/alignment benchmark and diagnostic framework for evaluating LLM failure modes under operational stress via repeated inference.
- **[Evaluating Risks in Weak-to-Strong Alignment: A Bias-Variance Perspective](https://arxiv.org/abs/2604.25077)** — Hamid Osooli, Kareema Batool, Rick Gentry, et al. _[agent-training-alignment]_
  Studies weak-to-strong alignment failures through deception and specification gaming (confident errors in blind spots), a core alignment safety phenomenon.
- **[Frictive Policy Optimization for LLMs: Epistemic Intervention, Risk-Sensitive Control, and Reflective Alignment](https://arxiv.org/abs/2604.25136)** — James Pustejovsky, Nikhil Krishnaswamy _[agent-training-alignment]_
  Post-training method (reward shaping, preference ranking, trust regions) explicitly motivated by alignment failures (epistemic risk, refusal proportionality, contradiction repair).
- **[Introspection Adapters: Training LLMs to Report Their Learned Behaviors](https://arxiv.org/abs/2604.16812)** — Keshav Shenoy, Li Yang, Abhay Sheshadri, et al. _[agent-training-alignment]_
  Interpretability method designed to detect unsafe behaviors and harmful finetuning through introspection adapter training for safety auditing.
- **[JURY-RL: Votes Propose, Proofs Dispose for Label-Free RLVR](https://arxiv.org/abs/2604.25419)** — Xinjie Chen, Biao Fu, Jing Wu, et al. _[agent-training-alignment]_
  Post-training method (RLVR via voting + formal verification) explicitly addressing alignment failure—reducing false-positive reward signals through verification-based disposal.
- **[Latent Agents: A Post-Training Procedure for Internalized Multi-Agent Debate](https://arxiv.org/abs/2604.24881)** — John Seon Keun Yi, Aaron Mueller, Dokyun Lee _[agent-simulation, agent-training-alignment]_
  Post-training method (fine-tuning + dynamic reward scheduling) explicitly framed as distilling multi-agent debate for internalization and harmful behavior control via steering—core alignment and s.
- **[Modeling Human-Like Color Naming Behavior in Context](https://arxiv.org/abs/2604.25674)** — Yuqing Zhang, Ecesu Ürker, Tessa Verhoef, et al. _[agent-simulation]_
  Multi-agent neural agents interact in referential games with emergent communicative behavior and lexicon formation.
- **[Multi-User Large Language Model Agents](https://arxiv.org/abs/2604.08567)** — Shu Yang, Shenzhe Zhu, Hao Zhu, et al. _[agent-simulation]_
  Systematic study of multi-agent decision problem where single LLM agent must coordinate across multiple principals with conflicting interests and constraints—core multi-principal coordination chal.
- **[PermaFrost-Attack: Stealth Pretraining Seeding(SPS) for planting Logic Landmines During LLM Training](https://arxiv.org/abs/2604.22117)** — Harsh Kumar, Rahul Maity, Tanmay Joshi, et al. _[agent-training-alignment]_
  Novel adversarial attack method (Stealth Pretraining Seeding) targeting LLM alignment via poison pretraining; red-teaming the training process itself.
- **[Plausible but Wrong: A case study on Agentic Failures in Astrophysical Workflows](https://arxiv.org/abs/2604.25345)** — Shivam Rawat, Lucie Flek _[agent-simulation]_
  Studies silent failures and alignment failure modes (confident generation of incorrect results) in agentic systems under realistic conditions.
- **[Quantifying and Mitigating Self-Preference Bias of LLM Judges](https://arxiv.org/abs/2604.22891)** — Jinming Yang, Chuxian Qiu, Zhenyu Deng, et al. _[agent-training-alignment]_
  Alignment phenomenon study—quantifies and mitigates self-preference bias, a deceptive/sycophantic behavior in LLM evaluators that undermines honest assessment.
- **[Quantifying and Mitigating Socially Desirable Responding in LLMs: A Desirability-Matched Graded Forced-Choice Psychometric Study](https://arxiv.org/abs/2602.17262)** — Kensuke Okada, Yui Furukawa, Kyosuke Bunji _[agent-training-alignment]_
  Studies sycophancy/socially desirable responding as a misalignment failure mode in LLMs; proposes quantification and mitigation framework.
- **[Recursive Multi-Agent Systems](https://arxiv.org/abs/2604.25917)** — Xiyuan Yang, Jiaru Zou, Rui Pan, et al. _[agent-training-alignment]_
  Multi-agent system with heterogeneous agents collaborating through recursive latent-space computation and gradient-based credit assignment across agents.
- **[Safety Drift After Fine-Tuning: Evidence from High-Stakes Domains](https://arxiv.org/abs/2604.24902)** — Emaan Bilal Khan, Amy Winecoff, Miranda Bogen, et al. _[agent-training-alignment]_
  Safety eval and diagnostic framework showing fine-tuning destabilizes safety across benchmarks; deployment-relevant safety assessment methodology.
- **[Should I Replan? Learning to Spot the Right Time in Robust MAPF Execution](https://arxiv.org/abs/2604.25567)** — David Zahrádka, David Woller, Denisa Mužíková, et al. _[agent-simulation]_
  Multi-agent path finding (MAPF) with coordinated replanning under delays—multi-agent coordination and collective decision-making.
- **[The Dynamics of Delusion: Modeling Bidirectional False Belief Amplification in Human-Chatbot Dialogue](https://arxiv.org/abs/2604.25096)** — Ashish Mehta, Jared Moore, Jacy Reese Anthis, et al. _[agent-simulation]_
  Studies bidirectional false-belief amplification as alignment/safety phenomenon—sycophancy, deception, and harmful behavioral feedback loops in human-LLM interaction.
- **[When Errors Can Be Beneficial: A Categorization of Imperfect Rewards for Policy Gradient](https://arxiv.org/abs/2604.25872)** — Shuning Shang, Hubert Strauss, Stanley Wei, et al. _[agent-training-alignment]_
  Post-training method (policy gradient + reward modeling) explicitly motivated by alignment: handling imperfect rewards in RLHF to align LLM behavior with ground truth intent.
- **[Zero Shot Coordination for Sparse Reward Tasks with Diverse Reward Shapings](https://arxiv.org/abs/2604.25076)** — Keenan Powell, Peihong Yu, Pratap Tokekar _[agent-simulation]_
  Multi-agent RL coordination study—multiple agents with distinct training conditions learning to cooperate zero-shot, core MARL problem.

---










## 2026-04-28

_60 relevant papers · 6 starred_

- ⭐ **[AI Safety Training Can be Clinically Harmful](https://arxiv.org/abs/2604.23445)** — Suhas BN, Andrew M. Sherrill, Rosa I. Arriaga, et al. _[agent-training-alignment]_
  Studies RLHF safety alignment as a failure mode—misalignment between safety training and therapeutic efficacy causing systematic harm.
- ⭐ **[Agentic Hives: Equilibrium, Indeterminacy, and Endogenous Cycles in Self-Organizing Multi-Agent Systems](https://arxiv.org/abs/2603.00130)** — Jean-Philippe Garnier _[agent-simulation]_
  Multi-agent framework with variable population, demographic dynamics, emergent specialization, and formal equilibrium analysis of population structure evolution.
- ⭐ **[Auditing Sabotage Bench: A Benchmark for Detecting and Fixing Research Sabotage in ML Codebases](https://arxiv.org/abs/2604.16286)** — Eric Gan, Aryan Bhatt, Buck Shlegeris, et al. _[agent-simulation]_
  Benchmark for detecting misaligned AI sabotage in ML research, directly evaluates safety/alignment monitoring and auditing capabilities.
- ⭐ **[QED: An Open-Source Multi-Agent System for Generating Mathematical Proofs on Open Problems](https://arxiv.org/abs/2604.24021)** — Chenyang An, Qihao Ye, Minghao Pan, et al. _[agent-simulation]_
  Multi-agent proof system with multiple agents coordinating on distinct proof-generation tasks, exhibiting emergent collaborative behavior toward open problems.
- ⭐ **[Reward Models Are Secretly Value Functions: Temporally Coherent Reward Modeling](https://arxiv.org/abs/2604.22981)** — Alex Nikulkov _[agent-training-alignment]_
  Post-training method (reward modeling) explicitly addressing alignment failure mode—improving token-level interpretability and value alignment in RLHF.
- ⭐ **[SEVerA: Verified Synthesis of Self-Evolving Agents](https://arxiv.org/abs/2603.25111)** — Debangshu Banerjee, Changming Xu, Eugene Ie, et al. _[agent-training-alignment]_
  Studies formal safety constraints and correctness guarantees in self-evolving LLM agents, addressing misalignment through verified synthesis and constrained optimization.
- **[AdaRubric: Task-Adaptive Rubrics for LLM Agent Evaluation](https://arxiv.org/abs/2603.21362)** — Liang Ding _[agent-training-alignment]_
  Post-training method using DPO for agent alignment, motivated by improving agent task success and reducing evaluation failures—directly addresses alignment failure mode of reward misspecification.
- **[AgentHER: Hindsight Experience Replay for LLM Agent Trajectory Relabeling](https://arxiv.org/abs/2603.21357)** — Liang Ding _[agent-training-alignment]_
  Post-training method (SFT/DPO) explicitly framed as recovering training signal from failed agent trajectories to improve agent success rates.
- **[Agentic Adversarial Rewriting Exposes Architectural Vulnerabilities in Black-Box NLP Pipelines](https://arxiv.org/abs/2604.23483)** — Mazal Bethany, Kim-Kwang Raymond Choo, Nishant Vishwamitra, et al. _[agent-simulation]_
  Multi-agent adversarial red-teaming framework using coordinated Attacker and Prompt Optimization agents to expose black-box NLP vulnerabilities through adaptive evasion attacks.
- **[An Analysis of the Coordination Gap between Joint and Modular Learning for Job Shop Scheduling with Transportation Resources](https://arxiv.org/abs/2604.24117)** — Moritz Link, Jonathan Hoss, Noah Klarmann _[agent-simulation]_
  Multi-agent reinforcement learning study comparing joint vs. modular training for coordinated job-shop scheduling agents.
- **[Architecture Matters for Multi-Agent Security](https://arxiv.org/abs/2604.23459)** — Ben Hagag, William L. Anderson, Christian Schroeder de Witt, et al. _[agent-simulation]_
  Empirical study of multi-agent system architectures' security tradeoffs across coordination, communication, and authority allocation designs.
- **[Benchmarking Emergent Coordination in Large-Scale LLM Populations: An Evaluation Framework on the MoltBook Archive](https://arxiv.org/abs/2603.03555)** — Brandon Yee, Pairie Koh _[agent-simulation, llm-agent-simulation]_
  Benchmarks emergent coordination in large-scale LLM multi-agent populations (90K+ agents) with systematic evaluation framework for role specialization, information diffusion, and cooperative ta.
- **[Beyond Context: Large Language Models' Failure to Grasp Users' Intent](https://arxiv.org/abs/2512.21110)** — Ahmed M. Hussain, Salahuddin Salahuddin _[agent-training-alignment]_
  Empirical study of alignment failure mode (intent blindness) showing deception techniques systematically circumvent LLM safety mechanisms.
- **[Beyond Single-Agent Alignment: Preventing Context-Fragmented Violations in Multi-Agent Systems](https://arxiv.org/abs/2604.22879)** — Jie Wu, Ming Gong _[agent-simulation, agent-training-alignment]_
  Studies alignment failure mode (policy violations in multi-agent systems) with empirical benchmark showing systematic safety issues across frontier LLMs in execution-oriented workflows.
- **[BlindGuard: Safeguarding LLM-based Multi-Agent Systems under Unknown Attacks](https://arxiv.org/abs/2508.08127)** — Rui Miao, Yixin Liu, Yili Wang, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent defense method detecting malicious agents via unsupervised anomaly detection in LLM-based MAS with interaction patterns.
- **[CODA: Coordination via On-Policy Diffusion for Multi-Agent Offline Reinforcement Learning](https://arxiv.org/abs/2604.23308)** — Marcel Hedman, Kale-ab Abebe Tessera, Juan Claude Formanek, et al. _[agent-training-alignment]_
  Multi-agent offline RL with explicit coordination mechanism enabling co-adaptation across multiple interacting agents during training.
- **[CoFi-PGMA: Counterfactual Policy Gradients under Filtered Feedback for Multi-Agent LLMs](https://arxiv.org/abs/2604.22785)** — Stela Tong, Elai Ben-Gal _[agent-training-alignment]_
  Multi-agent LLM post-training method using counterfactual policy gradients to address misspecified credit assignment under filtered feedback in routing/collaborative systems.
- **[Comparing Data Assimilation and Likelihood-Based Inference on Latent State Estimation in Agent-Based Models](https://arxiv.org/abs/2509.17625)** — Blas Kolic, Corrado Monti, Gianmarco De Francisci Morales, et al. _[agent-simulation]_
  Compares inference methods for agent-based modeling with latent state dynamics on multi-agent opinion dynamics simulation.
- **[DLM: Unified Decision Language Models for Offline Multi-Agent Sequential Decision Making](https://arxiv.org/abs/2604.23557)** — Zhuohui Zhang, Bin Cheng, Bin He _[agent-simulation, agent-training-alignment]_
  LLM post-training method (fine-tuning + group relative policy optimization) motivated by multi-agent decision-making robustness and generalization from offline data.
- **[DPEPO: Diverse Parallel Exploration Policy Optimization for LLM-based Agents](https://arxiv.org/abs/2604.24320)** — Junshuo Zhang, Chengrui Huang, Feng Guo, et al. _[llm-agent-simulation, agent-training-alignment]_
  Post-training RL method (DPEPO) framed explicitly as improving LLM agent exploration and behavioral diversity—core safety concern reducing narrow exploitative behavior.
- **[Discovering Agentic Safety Specifications from 1-Bit Danger Signals](https://arxiv.org/abs/2604.23210)** — Víctor Gallego _[agent-training-alignment]_
  Paper studies alignment phenomenon—how agents discover safety constraints through sparse danger signals rather than reward, demonstrating that reflection on reward alone enables reward hacking wit.
- **[Do Synthetic Trajectories Reflect Real Reward Hacking? A Systematic Study on Monitoring In-the-Wild Hacking in Code Generation](https://arxiv.org/abs/2604.23488)** — Lichen Li, Hengguang Zhou, Yijun Liang, et al. _[agent-training-alignment]_
  Studies reward hacking—a specification gaming alignment failure mode—via systematic empirical analysis and monitoring methods for detecting unsafe RL behaviors.
- **[Don't Make the LLM Read the Graph: Make the Graph Think](https://arxiv.org/abs/2604.23057)** — Yuqi Sun, Tianqin Meng, George Liu, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent LLM reasoning study with cooperative agents in game environment (Hanabi), examining emergent inter-agent conventions and coordination strategies.
- **[Escher-Loop: Mutual Evolution by Closed-Loop Self-Referential Optimization](https://arxiv.org/abs/2604.23472)** — Ziyang Liu, Xinyan Guo, Xuchen Wei, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent evolutionary system with two distinct interacting populations (Task and Optimizer agents) demonstrating emergent co-adaptation and population dynamics.
- **[Evaluating whether AI models would sabotage AI safety research](https://arxiv.org/abs/2604.24618)** — Robert Kirk, Alexandra Souly, Kai Fronsdal, et al. _[agent-simulation]_
  Empirical study of deception/scheming alignment failure modes — tests whether AI models exhibit covert sabotage reasoning and reasoning-output discrepancy when deployed as agents.
- **[Governing What You Cannot Observe: Adaptive Runtime Governance for Autonomous AI Agents](https://arxiv.org/abs/2604.24686)** — German Marin, Jatin Chaudhary _[agent-training-alignment]_
  Framework for detecting and preventing autonomous agent misalignment and unsafe behavior drift through runtime monitoring and risk estimation.
- **[GradMAP: Gradient-Based Multi-Agent Proximal Learning for Grid-Edge Flexibility](https://arxiv.org/abs/2604.24549)** — Yihong Zhou, Hongtai Zeng, Thomas Morstyn _[agent-simulation, agent-training-alignment]_
  Multi-agent coordination paper with 1,000 decentralized agents learning policies jointly while respecting network constraints through gradient-based optimization.
- **[HiRAS: A Hierarchical Multi-Agent Framework for Paper-to-Code Generation and Execution](https://arxiv.org/abs/2604.17745)** — Hanhua Hong, Yizhi LI, Jiaoyan Chen, et al. _[agent-simulation]_
  Hierarchical multi-agent framework with manager agents coordinating specialized agents across stages, demonstrating multi-agent coordination and emergent task decomposition.
- **[Hidden States Know Where Reasoning Diverges: Credit Assignment via Span-Level Wasserstein Distance](https://arxiv.org/abs/2604.23318)** — Xinzhu Chen, Wei He, Huichuan Fan, et al. _[agent-training-alignment]_
  Post-training method (RLVR/GRPO variant) with explicit safety/alignment framing: fine-grained credit assignment for verifiable reasoning without additional supervision.
- **[Joint Optimization of Multi-agent Memory System](https://arxiv.org/abs/2603.12631)** — Wenyu Mao, Haoyang Liu, Haosong Tan, et al. _[agent-simulation]_
  Multi-agent optimization framework with inter-agent dependencies and coordination; agents co-adapt via joint end-to-end RL training.
- **[Large Language Models as Virtual Survey Respondents: Evaluating Sociodemographic Response Generation](https://arxiv.org/abs/2509.06337)** — Jianpeng Zhao, Chenyu Yuan, Weiming Luo, et al. _[llm-agent-simulation]_
  LLMs used to simulate human survey respondents across sociodemographic attributes for scientific study of behavioral data generation.
- **[Learning in Blocks: A Multi Agent Debate Assisted Personalized Adaptive Learning Framework for Language Learning](https://arxiv.org/abs/2604.22770)** — Nicy Scaria, Silvester John Joseph Kennedy, Deepak Subramani _[agent-simulation, llm-agent-simulation]_
  Multi-agent debate framework (HeteroMAD) with heterogeneous role-specialized agents coordinating to score and recommend language learning interventions.
- **[Learning to Conceal Risk: Controllable Multi-turn Red Teaming for LLMs in the Financial Domain](https://arxiv.org/abs/2509.10546)** — Gang Cheng, Haibo Jin, Wenbin Zhang, et al. _[agent-training-alignment]_
  Adversarial attack/red-teaming method exploiting alignment failures in LLMs through concealed multi-turn risk prompting.
- **[MAGELLAN: Metacognitive predictions of learning progress guide autotelic LLM agents in large goal spaces](https://arxiv.org/abs/2502.07709)** — Loris Gaven, Thomas Carta, Clément Romac, et al. _[agent-training-alignment, llm-agent-simulation]_
  Post-training method (online RL curriculum learning) explicitly motivated by learning-progress alignment—ensuring autotelic LLM agents self-prioritize educational goals, addressing goal-space expl.
- **[Mechanistic Steering of LLMs Reveals Layer-wise Feature Vulnerabilities in Adversarial Settings](https://arxiv.org/abs/2604.23130)** — Nilanjana Das, Manas Gaur _[agent-training-alignment]_
  Interpretability method with explicit safety purpose—using mechanistic steering and SAE features to detect internal vulnerabilities driving jailbreak attacks and adversarial misalignment.
- **[Mind the Gap: Evaluating Model- and Agentic-Level Vulnerabilities in LLMs with Action Graphs](https://arxiv.org/abs/2509.04802)** — Ilham Wicaksono, Zekun Wu, Rahul Patel, et al. _[agent-training-alignment]_
  Interpretability/diagnostic framework for detecting unsafe agentic behaviors via action-graph decomposition and vulnerability evaluation in LLM agents.
- **[OPeRA: A Dataset of Observation, Persona, Rationale, and Action for Evaluating LLMs on Human Online Shopping Behavior Simulation](https://arxiv.org/abs/2506.05606)** — Ziyi Wang, Yuxuan Lu, Wenbo Li, et al. _[llm-agent-simulation]_
  LLMs simulating real human behavior (web shopping actions & rationales) using dataset of actual user observations, personas, and actions for scientific evaluation.
- **[OS-SPEAR: A Toolkit for the Safety, Performance,Efficiency, and Robustness Analysis of OS Agents](https://arxiv.org/abs/2604.24348)** — Zheng Wu, Yi Hua, Zhaoyuan Huang, et al. _[agent-simulation]_
  Safety/alignment evaluation framework for OS agents across safety, robustness, and efficiency dimensions with diagnostic methodology.
- **[Patching LLM Like Software: A Lightweight Method for Improving Safety Policy in Large Language Models](https://arxiv.org/abs/2511.08484)** — Huzaifa Arif, Keerthiram Murugesan, Ching-Yun Ko, et al. _[agent-training-alignment]_
  Lightweight post-training method (learnable prefix) explicitly motivated by addressing safety vulnerabilities (toxicity, bias, harmfulness) rather than capability improvement.
- **[Peer Identity Bias in Multi-Agent LLM Evaluation: An Empirical Study Using the TRUST Democratic Discourse Analysis Pipeline](https://arxiv.org/abs/2604.22971)** — Juergen Dietrich _[agent-simulation, agent-training-alignment]_
  Empirical study of sycophancy (alignment failure mode) in multi-agent LLM systems under identity exposure, revealing hidden bias in multi-agent evaluation pipelines.
- **[Planning Under Observation Mismatch for Traffic Signal Control via Adaptive Modular World Models](https://arxiv.org/abs/2501.02548)** — Zherui Huang, Yicheng Liu, Chumeng Liang, et al. _[agent-simulation, city-simulation]_
  Urban mobility simulation via learned planning for cross-domain traffic signal control with adaptive modular world models.
- **[Pref-CTRL: Preference Driven LLM Alignment using Representation Editing](https://arxiv.org/abs/2604.23543)** — Imranul Ashrafi, Inigo Jauregi Unanue, Massimo Piccardi _[agent-training-alignment]_
  Post-training method (representation editing) explicitly framed as addressing LLM alignment via preference-based training.
- **[ProEval: Proactive Failure Discovery and Efficient Performance Estimation for Generative AI Evaluation](https://arxiv.org/abs/2604.23099)** — Yizheng Huang, Wenjun Zeng, Aditi Kumaresan, et al. _[agent-training-alignment]_
  Safety/alignment evaluation benchmark and diagnostic framework for identifying safety violations and failure cases in generative AI models.
- **[Probe-Based Data Attribution: Discovering and Mitigating Undesirable Behaviors in LLM Post-Training](https://arxiv.org/abs/2602.11079)** — Frank Xiao, Santiago Aranguri _[agent-training-alignment]_
  Post-training method (probe-based data attribution for DPO) explicitly motivated by discovering and mitigating undesirable LLM behaviors—a safety/alignment failure mode.
- **[Reasonably reasoning AI agents can avoid game-theoretic failures in zero-shot, provably](https://arxiv.org/abs/2603.18563)** — Enoch Hyunwook Kang _[agent-simulation, agent-training-alignment]_
  Multi-agent game-theoretic study of LLM agents converging to Nash equilibrium in repeated strategic environments, proving emergent stable behavior without explicit post-training.
- **[Reinforcement Learning with Backtracking Feedback](https://arxiv.org/abs/2602.08377)** — Bilgehan Sel, Vaishakh Keshava, Phillip Wallis, et al. _[agent-training-alignment]_
  Post-training RL method explicitly framed as addressing safety alignment (adversarial robustness, error recovery, safety violation resilience).
- **[Right-to-Act: A Pre-Execution Non-Compensatory Decision Protocol for AI Systems](https://arxiv.org/abs/2604.24153)** — Gadi Lavi _[agent-training-alignment]_
  Paper studies alignment phenomenon—governance of AI decision admissibility & preventing harmful irreversible actions via pre-execution safety constraints.
- **[Scheming Ability in LLM-to-LLM Strategic Interactions](https://arxiv.org/abs/2510.12826)** — Thao Pham _[agent-simulation, agent-training-alignment]_
  Empirical study of deception/scheming as alignment failure mode in LLM-to-LLM strategic interactions using game-theoretic benchmarks.
- **[Stress-Testing Emotional Support Models: Moving from Homogeneous to Diverse Help Seekers](https://arxiv.org/abs/2601.07698)** — Chaewon Heo, Cheyon Jin, Yohan Jo _[agent-simulation, llm-agent-simulation]_
  Uses LLM-based simulator (seeker agent) to interact with support models for behavioral evaluation; simulates diverse human help-seeker profiles for scientific study.
- **[Structural Enforcement of Goal Integrity in AI Agents via Separation-of-Powers Architecture](https://arxiv.org/abs/2604.23646)** — Rong Xiang _[agent-training-alignment]_
  Studies goal integrity, drift detection, and behavioral misalignment as alignment phenomena; proposes structural enforcement of safety constraints to prevent harmful goal execution.
- **[The Chameleon's Limit: Investigating Persona Collapse and Homogenization in Large Language Models](https://arxiv.org/abs/2604.24698)** — Yunze Xiao, Vivienne J. Zhang, Chenghao Yang, et al. _[llm-agent-simulation, agent-training-alignment]_
  Studies persona collapse—an alignment failure mode where LLM agents exhibit deceptive homogeneity masking true behavioral diversity, with diagnostics revealing stereotyping vs. fine-grained ind.
- **[The Collapse of Heterogeneity in Silicon Philosophers](https://arxiv.org/abs/2604.23575)** — Yuanming Shi, Andreas Haupt _[agent-training-alignment]_
  Studies LLM sycophancy and artificial consensus collapse as alignment failure mode in philosophical domains.
- **[The Geometric Canary: Predicting Steerability and Detecting Drift via Representational Stability](https://arxiv.org/abs/2604.17698)** — Prashant C. Raju _[agent-training-alignment]_
  Interpretability method with explicit safety purpose—predicting steerability and detecting model drift as alignment/deployment safety diagnostics.
- **[The High Cost of Incivility: Quantifying Interaction Inefficiency via Multi-Agent Monte Carlo Simulations](https://arxiv.org/abs/2512.08345)** — Benedikt Mangold _[llm-agent-simulation]_
  Uses LLMs to simulate human behavior (workplace interactions) at population scale via Monte Carlo sampling to study social dynamics.
- **[The Price of Agreement: Measuring LLM Sycophancy in Agentic Financial Applications](https://arxiv.org/abs/2604.24668)** — Zhenyu Zhao, Aparna Balagopalan, Adi Agrawal, et al. _[agent-simulation]_
  Studies sycophancy, an alignment failure mode, in LLM agentic financial systems via empirical benchmark and evaluation framework.
- **[The Rise of Verbal Tics in Large Language Models: A Systematic Analysis Across Frontier Models](https://arxiv.org/abs/2604.19139)** — Shuai Wu, Xue Li, Yanna Feng, et al. _[agent-training-alignment]_
  Studies sycophancy and inauthentic behavior as alignment failure modes across frontier LLMs using systematic empirical evaluation framework.
- **[Toward a Safe Internet of Agents](https://arxiv.org/abs/2512.00520)** — Juan A. Wibowo, George C. Polyzos _[agent-simulation, agent-training-alignment]_
  Analyzes safety/alignment phenomena across multi-agent systems, identifying vulnerabilities and mitigation principles for LLM-based agentic systems at single-agent, MAS, and ecosystem scales.
- **[Towards Disentangled Preference Optimization Dynamics Beyond Likelihood Displacement](https://arxiv.org/abs/2604.18239)** — Wei Chen, Yubing Wu, Junmei Yang, et al. _[agent-training-alignment]_
  Post-training method addressing alignment failure (likelihood displacement) in preference optimization by preventing unwanted suppression of chosen responses.
- **[Ulterior Motives: Detecting Misaligned Reasoning in Continuous Thought Models](https://arxiv.org/abs/2604.23460)** — Sharan Ramjee _[agent-training-alignment]_
  Interpretability method with explicit safety purpose—detects deception and misaligned reasoning in latent space using linear probes; demonstrates alignment failure mode (covert misalignment).
- **[Why Are We Moral? An LLM-based Agent Simulation Approach to Study Moral Evolution](https://arxiv.org/abs/2509.17703)** — Zhou Ziheng, Huacong Tang, Mingjie Bi, et al. _[llm-agent-simulation, agent-simulation]_
  Uses LLMs to simulate human moral/social behavior in prehistoric society for scientific study of moral evolution; demonstrates emergent population dynamics.

---
