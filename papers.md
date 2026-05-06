# 📅 Chronological Paper Log

Newest days appear first. For the grouped-by-tag index, see [README](./README.md).

_255 papers across 6 days · 33 with at least one ⭐._

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
