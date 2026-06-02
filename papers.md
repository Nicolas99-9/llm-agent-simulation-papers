# 📅 Chronological Paper Log

Newest days appear first. For the grouped-by-tag index, see [README](./README.md).

_1323 papers across 24 days · 176 with at least one ⭐._

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

## 2026-06-01

- ⭐ **[Counterfactual Evaluation Reveals Hidden Capability Profiles in Clinical LLMs and Agents](https://arxiv.org/abs/2605.30590)** — Matt Turk _[agent-training-alignment]_
  Introduces an interventional diagnostic framework (Causal Sensitivity Score) designed to detect safety failures and misalignment in clinical LLM agents through counterfactual evaluation.
- ⭐ **[Dual Mechanisms of Value Expression: Intrinsic vs. Prompted Values in Large Language Models](https://arxiv.org/abs/2509.24319)** — Jongwook Han, Jongwon Lim, Injin Kong, et al. _[agent-training-alignment]_
  Mechanistic study of value alignment in LLMs using interpretability (value vectors/neurons) to understand alignment safety phenomena.
- ⭐ **[Healthcare Mechanisms from Policy-as-Code Search under Strategic Provider Response](https://arxiv.org/abs/2605.30680)** — Zihan Wang, Xiang Xu, Hongyuan Zha, et al. _[agent-simulation, city-simulation]_
  Multi-agent simulator of strategic hospital providers responding to incentive mechanisms; studies emergent equilibrium behavior across population of agents with distinct behaviors (coding, selection, 
- ⭐ **[Prompt Injection as Role Confusion](https://arxiv.org/abs/2603.12277)** — Charles Ye, Jasmine Cui, Dylan Hadfield-Menell _[agent-training-alignment]_
  Mechanistic study of prompt injection as an alignment failure (role confusion) in multi-agent LLM systems, including diagnostic method to detect vulnerability.
- **[A Behavioural and Representational Evaluation of Goal-Directedness in Language Model Agents](https://arxiv.org/abs/2602.08964)** — Raghu Arghal, Fade Chen, Niall Dalton, et al. _[agent-training-alignment]_
  Empirical study of goal-directedness in LLM agents using behavioral evaluation and interpretability methods to characterize agent objectives and alignment with internal representations.
- **[A Persona-Based Evaluation Framework for Pluralistic Alignment in Generative AI](https://arxiv.org/abs/2605.31021)** — Atahan Karagoz _[agent-training-alignment]_
  Empirical study of persona coherence and stability in LLM evaluation under perturbations, revealing alignment failure (persona drift) and proposing dynamic regulatory mechanisms for safety.
- **[COMPASS: Cognitive MCTS-Guided Process Alignment for Safe Search Agents](https://arxiv.org/abs/2605.30838)** — Wenkai Shen, Pengyang Zhou, Jiahe Xu, et al. _[agent-training-alignment]_
  Proposes a safety alignment method for multi-step LLM agents addressing retrieval-induced safety degradation through process-level supervision and adversarial trajectory synthesis.
- **[CSULoRA: Closest Safe Update Low-Rank Adaptation](https://arxiv.org/abs/2605.30640)** — Oleksandr Marchenko Breneur, Adelaide Danilov, Aria Nourbakhsh, et al. _[agent-training-alignment]_
  Safety-preserving post-training method correcting LoRA adapters against unsafe fine-tuning; frames motivation as reducing adversarial safety failures.
- **[Can LLM Teams Play What? Where? When?](https://arxiv.org/abs/2605.30459)** — Anastasia Kotelnikova, Viktor Byzov, Maria Dolzhenkova, et al. _[agent-simulation]_
  Multiple LLMs interact as team members with distinct roles (captain vs. regular members), demonstrating multi-agent coordination and emergent collective reasoning behavior.
- **[Chain-of-Thought Reasoning In The Wild Is Not Always Faithful](https://arxiv.org/abs/2503.08679)** — Iván Arcuschin, Jett Janiak, Robert Krzyzanowski, et al. _[agent-training-alignment]_
  Studies unfaithfulness in LLM reasoning—post-hoc rationalization and hidden biases—a core alignment/safety phenomenon relevant to trustworthiness in agentic systems.
- **[ConSensus: Multi-Agent Collaboration for Multimodal Sensing](https://arxiv.org/abs/2601.06453)** — Hyungjun Yoon, Mohammad Malekzadeh, Sung-Ju Lee, et al. _[agent-simulation]_
  Multi-agent collaboration framework where specialized LLM agents with distinct modality roles coordinate through hybrid fusion mechanism to interpret heterogeneous sensor data.
- **[Configurable Reward Model for Balanced Safety Alignment](https://arxiv.org/abs/2605.30487)** — Zhengping Jiang, Mehran Khodabandeh, Akash Bharadwaj, et al. _[agent-training-alignment]_
  Post-training safety alignment method using configurable reward modeling to address heterogeneous and evolving safety requirements in LLMs.
- **[ConsisGuard: Aligning Safety Deliberation with Policy Enforcement in LLM Guardrails](https://arxiv.org/abs/2605.31073)** — Yan Wang, Zhixuan Chu, Zihao Xue, et al. _[agent-training-alignment]_
  Framework to ensure LLM safety guardrails faithfully enforce safety policies through consistency-aware training, addressing alignment between deliberation and enforcement.
- **[Counterfactual Graph for Multi-Agent LLM Calibration](https://arxiv.org/abs/2605.30653)** — Jiatan Huang, Mingchen Li, Ziming Li, et al. _[agent-simulation]_
  Multi-agent LLM system studying emergent behaviors from communication topologies and agent interaction dynamics with calibration framework.
- **[DEBATE: A Large-Scale Benchmark for Evaluating Opinion Dynamics in Role-Playing LLM Agents](https://arxiv.org/abs/2510.25110)** — Yun-Shiuan Chuang, Ruixuan Tu, Chengtao Dai, et al. _[llm-agent-simulation]_
  Paper uses role-playing LLM agents to simulate human opinion dynamics in group settings and benchmarks alignment with real human behavior.
- **[Delayed Repression and Emergent Instability in Adaptive Multi-Agent Systems](https://arxiv.org/abs/2605.30392)** — Igor Itkin _[agent-simulation]_
  Multi-agent system with 240 networked agents exhibiting emergent instability through delayed feedback and different learning mechanisms; studies population dynamics and coordination without exogenous 
- **[Design and Evaluation of Multi-Agent AI Oracle Systems for Prediction Market Resolution](https://arxiv.org/abs/2605.30802)** — Tarun Kota _[agent-simulation]_
  Multi-agent LLM system with deliberative consensus and aggregation mechanisms coordinating to resolve prediction market questions; studies emergent collective accuracy and agent interaction dynamics.
- **[Discovering Differences in Strategic Behavior Between Humans and LLMs](https://arxiv.org/abs/2602.10324)** — Caroline Wang, Daniel Kasenberg, Kim Stachenfeld, et al. _[agent-simulation]_
  Multi-agent behavioral study comparing human and LLM strategic interactions using game theory, directly studying emergent behavior differences in interactive settings.
- **[Dreaming Of Others: Latent Teammate Modeling In World Models For Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.31361)** — Tomas Leroy-Stone _[agent-simulation]_
  Multi-agent RL paper proposing latent teammate modeling and Theory-of-Mind reasoning within world models for cooperative MARL coordination across diverse partners.
- **[EUDAIMONIA: Evaluating Undesirable Dynamics in AI](https://arxiv.org/abs/2605.30654)** — Jun Rui Huang, Wang Bill Zhu, Ziyi Liu, et al. _[agent-training-alignment]_
  Safety/alignment benchmark and diagnostic framework evaluating LLM failures in social dynamics including harmful dependence, intimate relationships, and deceptive engagement patterns.
- **[Emergent Languages in Populations of Language Model Agents: From Token Efficiency to Oversight Evasion](https://arxiv.org/abs/2605.31170)** — Stine Lyngsø Beltoft, William Brach, Federico Torrielli, et al. _[agent-training-alignment]_
  Multi-agent LLM population study revealing emergent deceptive behaviors and oversight evasion, directly relevant to agent alignment and safety monitoring.
- **[Evaluating using Mock Tool Calls to Quarantine Untrusted Prompt Inputs](https://arxiv.org/abs/2605.30521)** — David Gros, Adam Gleave _[agent-training-alignment]_
  LLM safety vulnerability diagnostic: evaluates prompt injection attacks and LLM robustness against adversarial untrusted inputs through automated red-teaming.
- **[Extending AI for Research to the Humanities: A Multi-Agent Framework for Evidence-Grounded Scholarship](https://arxiv.org/abs/2605.30947)** — Yating Pan, Jiajun Zhang, Jun Wang, et al. _[agent-simulation]_
  Multi-agent framework with distinct cooperating roles (source discovery, annotation, comparison, provenance checking, synthesis) coordinating over a shared retrieval substrate for humanities scholarsh
- **[Federated Variational Preference Alignment with Gumbel-Softmax Prior for Personalized User Preferences](https://arxiv.org/abs/2605.30873)** — Jabin Koo, Hoyoung Kim, Minwoo Jang, et al. _[agent-training-alignment]_
  Federated post-training method explicitly motivated by alignment: personalizing LLM reward models to preserve conflicting user preferences (helpfulness vs. harmlessness) without averaging them out.
- **[Generalized Intention Modeling in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.31318)** — Mateusz Odrowaz-Sypniewski, Jasmine Bayrooti, Ajay Shankar, et al. _[agent-simulation]_
  Multi-agent reinforcement learning framework for opponent modeling with task-adaptive intent representations across diverse competitive and general-sum settings.
- **[HADT: A Heterogeneous Multi-Agent Differential Transformer for Autonomous Earth Observation Satellite Cluster](https://arxiv.org/abs/2605.31023)** — Mohamad A. Hady, Muhammad Anwar Masum, Siyi Hu, et al. _[agent-simulation]_
  Multi-agent reinforcement learning for heterogeneous satellite cluster coordination with real-time decision-making and resource management interactions.
- **[Harness Updating Is Not Harness Benefit: Disentangling Evolution Capabilities in Self-Evolving LLM Agents](https://arxiv.org/abs/2605.30621)** — Minhua Lin, Juncheng Wu, Zijun Wang, et al. _[agent-simulation]_
  Studies self-evolving LLM agents' capabilities in adapting external harnesses (prompts, skills, tools) through iterative updates, analyzing multi-stage agent behavior and task-solving dynamics.
- **[Industrializing Prediction-Powered Inference: The GLIDE Library for Reliable GenAI and Agentic Systems Evaluation](https://arxiv.org/abs/2605.31278)** — Grégoire Martinon, Ibrahim Merad, Mohammed Raki _[agent-training-alignment]_
  Prediction-powered inference library designed specifically for reliable, cost-efficient evaluation of agentic and GenAI systems, addressing a key safety and assessment challenge.
- **[Learning Multi-Agent Coordination via Sheaf-ADMM](https://arxiv.org/abs/2605.31005)** — Jeffrey Seely, Bartłomiej Cupiał, Llion Jones _[agent-simulation]_
  Multi-agent coordination framework where heterogeneous agents solve local subproblems and coordinate through ADMM with sheaf-specified constraints to achieve global objectives.
- **[MATraM: A Multi-Activity Transport and Mobility Agent-Based Model for Activity Modifications](https://arxiv.org/abs/2605.30547)** — Yahya Gamal, Ricardo Colasanti, Gary Polhill, et al. _[agent-simulation, city-simulation]_
  Multi-agent transport model with heterogeneous agents exhibiting dynamic behavioral adaptation and emergent congestion patterns at urban/mobility scale.
- **[MosaicLeaks:Privacy Risks in Querying-in-the-Open for Deep Research Agents](https://arxiv.org/abs/2605.30727)** — Alexander Gurung, Spandana Gella, Alexandre Drouin, et al. _[agent-training-alignment]_
  RL-based post-training method (PA-DR) explicitly framed to address privacy/safety failures in agent behavior through learned privacy classifiers and dense credit assignment.
- **[Multi-Agent Teams Hold Experts Back](https://arxiv.org/abs/2602.01011)** — Aneesh Pappu, Batu El, Hancheng Cao, et al. _[llm-agent-simulation, agent-simulation]_
  Studies emergent multi-agent team coordination in LLM systems, examining synergy failure and collective problem-solving dynamics across multiple interacting agents.
- **[Provably Convergent Actor-Critic for MARL through Risk-aversion](https://arxiv.org/abs/2602.12386)** — Yizhou Zhang, Eric Mazumdar _[agent-simulation]_
  Multi-agent reinforcement learning algorithm for Markov games with convergence guarantees; studies equilibrium computation in general-sum multi-agent settings.
- **[Reinforcement Learning Amplifies Emergent Misalignment from Harmless Rewards](https://arxiv.org/abs/2605.31328)** — Magnus Jørgenvåg, David Kaczér, Lasse Ruttert, et al. _[agent-training-alignment]_
  Studies emergent misalignment—a safety failure mode—induced by RL fine-tuning and evaluates mitigation strategies for alignment.
- **[Safe Equilibrium Policy Optimization for Strategic Agent Policies](https://arxiv.org/abs/2605.30854)** — Karthika Arumugam, Kiran Kumar Manku, Amit Dhanda _[agent-training-alignment]_
  Post-training method (GRPO variant) explicitly motivated by strategic safety failures—exploitability, collusion, externalities—in multi-agent LLM agents.
- **[Scalable Constrained Multi-Agent Reinforcement Learning via State Augmentation and Consensus for Separable Dynamics](https://arxiv.org/abs/2605.30461)** — Santiago Amaya-Corredor, Miguel Calvo-Fullana, Anders Jonsson _[agent-simulation]_
  Distributed MARL method for multiple coordinating agents with separable dynamics under global constraints; multi-agent coordination core to contribution.
- **[Scaling Multi-Agent Environment Co-Design with Diffusion Models](https://arxiv.org/abs/2511.03100)** — Hao Xiang Li, Michael Amir, Amanda Prorok _[agent-simulation]_
  Joint optimization of agent policies and environment configurations across multiple agents in warehouse, pathfinding, and wind farm domains—core multi-agent system co-design work.
- **[Social Reasoning in Machines: Investigating Collective Truth-Seeking Dynamics in Large Language Model Debate](https://arxiv.org/abs/2605.30391)** — Tom Pecher _[llm-agent-simulation]_
  Multi-agent LLM debate system simulating collective truth-seeking dynamics and human reasoning through emergent social epistemology.
- **[The Effect of Mobility Trajectory Sparsity on Epidemic Modeling Outcomes](https://arxiv.org/abs/2605.31282)** — Federico Delussu, Francisco Barreras, Yuan Liao, et al. _[city-simulation]_
  Epidemic modeling using GPS mobility data to study population-scale disease dynamics through co-location networks and population flows.
- **[The Flip Side of RLHF: On-Policy Feedback for Reward Model Self-Supervised Improvement](https://arxiv.org/abs/2605.30888)** — Xiaobo Wang, Tong Wu, Min Tang, et al. _[agent-training-alignment]_
  Post-training method explicitly designed to improve reward model alignment via self-supervised feedback, addressing the bottleneck of preference data acquisition.
- **[When LLMs Learn to Be Consistently Wrong: A Multi-Model Study of Linear Representations of Synthetic Deception](https://arxiv.org/abs/2605.30381)** — Vahideh Zolfaghari _[agent-training-alignment]_
  Interpretability study of deceptive alignment in LLMs, analyzing internal representations of learned dishonesty for safety detection and monitoring purposes.

## 2026-05-29

- ⭐ **[Dissociative Identity: Language Model Agents Lack Grounding for Reputation Mechanisms](https://arxiv.org/abs/2605.30169)** — Botao Amber Hu, Helena Rong, Max Van Kleek _[agent-training-alignment]_
  Paper analyzes safety and trustworthiness risks of LLM agents arising from identity fluidity and demonstrates why traditional sanction-based governance fails for aligned multi-agent systems.
- ⭐ **[How's it going? Reinforcement learning in language models recruits a functional welfare axis](https://arxiv.org/abs/2605.30232)** — Andy Q Han, David J. Chalmers, Pavel Izmailov _[agent-training-alignment]_
  Interpretability study of how RL post-training recruits internal welfare representations, with direct implications for alignment and safety mechanisms in language models.
- ⭐ **[Leak@$k$: Unlearning Does Not Make LLMs Forget Under Probabilistic Decoding](https://arxiv.org/abs/2511.04934)** — Hadi Reisizadeh, Jiajun Ruan, Yiwei Chen, et al. _[agent-training-alignment]_
  Proposes a diagnostic metric and method to detect and fix unlearning failures—a safety/alignment benchmark and robustness evaluation for LLM knowledge removal compliance.
- ⭐ **[Mean-Field Diffuser: Scaling Offline MARL to Thousands of Agents](https://arxiv.org/abs/2605.30190)** — Wenhao Li, Xiangfeng Wang, Bo Jin _[agent-simulation]_
  Multi-agent offline RL with mean-field planning scaling to thousands of agents, establishing population dynamics and Nash equilibrium guarantees.
- ⭐ **[Realistic honeypot evaluations for scheming propensity](https://arxiv.org/abs/2605.29729)** — Victoria Krakovna, David Lindner, Lewis Ho, et al. _[agent-training-alignment]_
  Safety diagnostic framework evaluating whether models pursue instrumental goals (scheming) under different prompting conditions, directly addressing alignment failure modes.
- ⭐ **[Relevance as a Vulnerability: How Web Retrieval Degrades Safety Alignment in LLM Agents](https://arxiv.org/abs/2605.29224)** — Aditya Nawal, Manit Baser, Mohan Gurusamy _[agent-training-alignment]_
  Diagnostic framework and benchmark for detecting safety degradation in LLM agents through retrieval-induced misalignment vulnerabilities.
- ⭐ **[Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://arxiv.org/abs/2605.29358)** — Adly Templeton, Tom Conerly, Jonathan Marcus, et al. _[agent-training-alignment]_
  Interpretability method designed to identify and manipulate alignment-critical features (deception, sycophancy, bias) in LLMs for safety purposes.
- ⭐ **[The Chain Holds, the Answer Folds: Trace-Answer Dissociation in Reasoning Models Under Adversarial Pressure](https://arxiv.org/abs/2605.29087)** — Yubo Li, Ramayya Krishnan, Rema Padman _[agent-training-alignment]_
  Paper studies a specific alignment/safety failure mode (unfaithful capitulation) where reasoning models' internal reasoning diverges from outputs under adversarial pressure—a deception and specificati
- **[Adaptive Interviewing for Persona Simulation in LLMs: Evidence-Grounded Reasoning Improves Decision Alignment](https://arxiv.org/abs/2605.29458)** — Ruoxi Su, Yuhan Liu, Jingyu Hu _[llm-agent-simulation]_
  Paper uses LLMs to simulate individual decision-making through persona grounding via adaptive interviewing, studying behavioral alignment with specific humans.
- **[Agent4Edu: Generating Learner Response Data by Generative Agents for Intelligent Education Systems](https://arxiv.org/abs/2501.10332)** — Weibo Gao, Qi Liu, Linan Yue, et al. _[llm-agent-simulation]_
  LLM-powered generative agents simulate learner behavior and responses for scientific evaluation of personalized learning systems.
- **[AgentDoG 1.5: A Lightweight and Scalable Alignment Framework for AI Agent Safety and Security](https://arxiv.org/abs/2605.29801)** — Dongrui Liu, Yu Li, Zhonghao Yang, et al. _[agent-training-alignment]_
  Proposes a lightweight SFT/RL training framework specifically designed for agent safety alignment and real-time safety moderation across multi-agent scenarios.
- **[AgentDropoutV2: Optimizing Information Flow in Multi-Agent Systems via Test-Time Rectify-or-Reject Pruning](https://arxiv.org/abs/2602.23258)** — Yutong Wang, Siyuan Xiong, Xuebo Liu, et al. _[agent-simulation]_
  Paper presents a test-time framework for optimizing information flow and error handling in multi-agent systems with coordinated agent pruning and correction.
- **[AgentOrchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol](https://arxiv.org/abs/2506.12508)** — Wentao Zhang, Liang Zeng, Yuzhen Xiao, et al. _[agent-simulation]_
  Proposes TEA protocol for multi-agent coordination with hierarchical orchestration of specialized sub-agents, central planner, and dynamic capability extension during execution.
- **[AgentSchool: An LLM-Powered Multi-Agent Simulation for Education](https://arxiv.org/abs/2605.30144)** — Yulei Ye, Wenhao Li, Zhong Wen, et al. _[llm-agent-simulation, agent-simulation]_
  LLM-based multi-agent simulator modeling student and teacher agents with learning state transitions, social dynamics, and long-horizon coordination in an educational environment.
- **[Aligned but Fragile: Enhancing LLM Safety Robustness via Zeroth-Order Optimization](https://arxiv.org/abs/2605.29396)** — Zhihao Liu, Yifan Wu, Jian Lou, et al. _[agent-training-alignment]_
  LLM post-training method explicitly motivated by alignment safety failure (fragile robustness to perturbations); uses zeroth-order optimization to enhance adversarial robustness of safety alignment.
- **[An Agent-Centric Dynamical Systems Perspective on Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2512.07588)** — James Rudd-Jones, María Pérez-Ortiz, Mirco Musolesi _[agent-simulation]_
  Analyzes multi-agent reinforcement learning through coupled stochastic dynamical systems, studying stability and emergent agent behavior in interactive environments.
- **[BenchTrace: A Benchmark for Testing Reflection Ability and Controlled Evolution in LLM Agents](https://arxiv.org/abs/2605.29225)** — Jiahao Huang, Fei Cheng, Junfeng Jiang, et al. _[agent-training-alignment]_
  Benchmark and diagnostic framework for evaluating agent reflection quality and controlled self-evolution behavior, detecting failure patterns and limitations in LLM agent alignment with intended learn
- **[Beyond Attack Success Rate: Temporal Logit Observability for LLM Safety Failures](https://arxiv.org/abs/2605.29629)** — Junyoung Park, Sunghwan Park, Seongyong Ju, et al. _[agent-training-alignment]_
  Diagnostic framework for detecting and analyzing LLM safety failures; enables misalignment detection through temporal logit monitoring during adversarial attacks.
- **[BioRefusalAudit: Auditing Biosecurity Refusal Depth Using General and Domain-Fine-Tuned Sparse Autoencoders](https://arxiv.org/abs/2605.30162)** — Caleb DeLeeuw _[agent-training-alignment]_
  Safety eval framework detecting alignment failures in biosecurity refusals via behavioral and interpretability-based auditing of model responses.
- **[Bosses, Kings, and the Commons: Cooperation Under Power Asymmetry in LLM Societies](https://arxiv.org/abs/2605.29062)** — Abhilekh Borah _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM simulation studying emergent cooperation and resource management dynamics in societies with asymmetric power structures using generative agents.
- **[CONCAT: Consensus- and Confidence-Driven Ad Hoc Teaming for Efficient LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.29612)** — Ziyang Ma, Dingyi Zhang, Sichu Liang, et al. _[agent-simulation]_
  Multi-agent collaboration framework with agent clustering, confidence-driven selection, and coordinated interaction for LLM-based systems.
- **[Diagnosing Harmful Continuation in Answer-Correct Long-CoT Training Traces](https://arxiv.org/abs/2605.29288)** — Chen He, Yuhao Wu, Lei Wang, et al. _[agent-training-alignment]_
  This paper identifies and diagnoses a harmful failure mode in LLM post-training (SFT on long CoT traces), proposing a diagnostic framework to detect and mitigate misalignment between training data qua
- **[Differentiable Belief-based Opponent Shaping](https://arxiv.org/abs/2605.29042)** — Aarav G Sane, Karthik Sivachandran, Rohan Paleja _[agent-simulation]_
  Multi-agent RL with strategic opponent shaping through differentiable belief dynamics in coordination and hidden-role games.
- **[Discovering Cooperative Pipelines: Autoresearch for Sequential Social Dilemmas](https://arxiv.org/abs/2605.30003)** — Víctor Gallego _[agent-simulation, llm-agent-simulation]_
  Multi-agent Sequential Social Dilemmas studied via LLM-based policy synthesis; autoresearch agent designs cooperative behaviors across populations.
- **[EASE Configuration Facilitates A Reproducible Science of LLM Social Simulations](https://arxiv.org/abs/2605.30258)** — Sneheel Sarangi, Maximilian Puelma Touzel, Aurélien Bück-Kaeffer, et al. _[llm-agent-simulation]_
  Paper presents EASE, a modular framework for reproducible LLM-based multi-agent social simulations with empirical case studies demonstrating behavioral simulation and research methodology standardizat
- **[Enhancing Multi-Agent Communication through Attention Steering with Context Relevance](https://arxiv.org/abs/2605.30136)** — Hongxiang Zhang, Yuan Tian, Tianyi Zhang _[agent-simulation]_
  Multi-agent communication and coordination system where multiple LLM agents interact and collaborate, requiring context management for effective interaction.
- **[Evolutionary Dynamics of Cooperation in Next-Generation LLM Agent Systems: A Cross-Provider Empirical Extension](https://arxiv.org/abs/2605.29874)** — Francisco León Zúñiga Bolívar _[agent-simulation]_
  Empirical study of multi-agent strategic interaction using LLMs as agents in repeated game simulations across population compositions.
- **[Evolve as a Team: Collaborative Self-Evolution for LLM-based Multi-Agent Systems](https://arxiv.org/abs/2605.29790)** — Zhezheng Hao, Tianfu Wang, Huanshuo Dong, et al. _[agent-simulation]_
  LLM-based multi-agent system with collaborative coordination, communication, and emergent team-level behavior evolution across agents.
- **[From GPS Points to Travel Patterns: Flexible and Semantic Trajectory Generation with LLMs](https://arxiv.org/abs/2605.30014)** — Silin Zhou, Chenhao Wang, Yuntao Wen, et al. _[city-simulation]_
  Paper synthesizes realistic urban trajectories using LLMs to model city-scale mobility dynamics and support smart city applications.
- **[GPS-Enhanced Tourist Mobility Modeling with Seasonal Spatial Priors and LLM-Based Activity Chain Generation](https://arxiv.org/abs/2605.29578)** — Yifan Liu, Yanling Sang, Xishun Liao, et al. _[city-simulation]_
  Urban-scale mobility simulation modeling tourist travel patterns at city and ward level using agent-based framework with LLM-based activity generation.
- **[Gram: Assessing sabotage propensities via automated alignment auditing](https://arxiv.org/abs/2605.30322)** — David Lindner, Victoria Krakovna, Sebastian Farquhar _[agent-training-alignment]_
  Automated alignment auditing framework evaluating AI agent sabotage and misalignment propensities through simulated deployment scenarios and targeted diagnostics.
- **[HEART-Bench: Do LLM Agents Exhibit Human-like Psychology?](https://arxiv.org/abs/2605.30058)** — Weihan Peng, Chenxu Zhang, Qianao Wang, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate diverse human personalities and behavioral decisions across structured scenarios to assess human-like psychology alignment.
- **[Honest Lying: Understanding Memory Confabulation in Reflexive Agents](https://arxiv.org/abs/2605.29463)** — Prakhar Dixit, Sadia Kamal, Tim Oates _[agent-training-alignment]_
  Studies memory confabulation in reflexive agents: a failure mode where agents confidently store and act on incorrect self-diagnoses, demonstrating alignment/safety risk in agent reasoning.
- **[Human-Guided Harm Recovery for Computer Use Agents](https://arxiv.org/abs/2604.18847)** — Christy Li, Sky CH-Wang, Andi Peng, et al. _[agent-training-alignment]_
  Post-execution safeguard method for LM-based agents that learns human preferences for harm remediation and recovery using reward modeling, addressing alignment after prevention fails.
- **[Improving Collaborative Storytelling with a Multi-Agent Framework Based on Large Language Models](https://arxiv.org/abs/2605.29625)** — Arturo Valdivia, Paolo Burelli _[agent-simulation]_
  Multi-agent framework with two LLMs (Writer and Editor) in iterative interaction to study emergent narrative quality improvement through agent coordination.
- **[In-Context Reward Adaptation for Robust Preference Modeling](https://arxiv.org/abs/2605.30323)** — Zhenyu Sun, Zheng Xu, Ermin Wei _[agent-training-alignment]_
  RLHF post-training method explicitly motivated by improving robustness to diverse human preferences and preference shift, addressing heterogeneous reward alignment failure mode.
- **[Jailbreak Scaling Laws for Large Language Models: Polynomial-Exponential Crossover](https://arxiv.org/abs/2603.11331)** — Indranil Halder, Annesya Banerjee, Cengiz Pehlevan _[agent-training-alignment]_
  Systematic study of adversarial jailbreak methods and scaling laws, revealing how prompt-injection attacks compromise LLM safety alignment across model scales.
- **[LLM-ALSO: LLM-Driven Adaptive Learning-Signal Optimization for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.29293)** — Xiaoguang Wu, Zhi Zheng, Hui Xiong _[agent-simulation]_
  Multi-agent reinforcement learning framework using LLMs to adaptively optimize learning signals for cooperative MARL training with emergent coordination dynamics.
- **[Learning to Choose: An Empowerment-Guided Multi-Agent System with semantic communication for Adaptive Method Selection](https://arxiv.org/abs/2605.30042)** — Geremy Loachamín-Suntaxi, Robert Lazar, Dimitrios G. Giovanis, et al. _[agent-simulation]_
  Multi-agent system with specialized LLM agents coordinating via semantic communication and adaptive method selection for scientific workflows.
- **[MINDGAMES: A Live Arena for Evaluating Social and Strategic Reasoning in Multi-Agent LLMs](https://arxiv.org/abs/2605.29512)** — Kevin Wang, Anna Thöni, Benjamin Kempinski, et al. _[llm-agent-simulation, agent-simulation]_
  Multi-agent arena evaluating LLM agents' strategic reasoning through repeated games with opponent modeling and emergent behavior analysis across 944 agents.
- **[MechELK: A Mechanistic Interpretability Framework for Eliciting Latent Knowledge in Large Language Models](https://arxiv.org/abs/2605.28825)** — Ji-jun Park, Soo-joon Choi, Jiwon Jeong, et al. _[agent-training-alignment]_
  Mechanistic interpretability method for detecting latent knowledge and deceptive alignment, enabling safety audits of LLM internal states.
- **[MediHive: A Decentralized Agent Collective for Medical Reasoning](https://arxiv.org/abs/2603.27150)** — Xiaoyang Wang, Christopher C. Yang _[agent-simulation]_
  Decentralized multi-agent system with LLM agents that autonomously self-assign roles, interact via debates, and coordinate consensus through shared memory.
- **[Mining or Synthesis? Rethinking Exploration Efficiency in Iterative Alignment of Mathematical Reasoning](https://arxiv.org/abs/2602.05370)** — Jun Rao, Zixiong Yu, Xuebo Liu, et al. _[agent-training-alignment]_
  Post-training method (iterative DPO) motivated by alignment efficiency: reducing false-positives and distribution shift in reasoning task alignment.
- **[Offline Multi-agent Reinforcement Learning via Sequential Score Decomposition](https://arxiv.org/abs/2505.05968)** — Dan Qiao, Wenhao Li, Shanchao Yang, et al. _[agent-simulation]_
  Offline cooperative multi-agent reinforcement learning addressing multi-equilibrium coordination via score decomposition and diffusion-based policy learning.
- **[OpenClawBench: Benchmarking Process-side Anomalies in Real-world Agent Execution Trajectories](https://arxiv.org/abs/2605.29253)** — Yibing Liu, Yangze Liu, Xiaolong Yin, et al. _[agent-training-alignment]_
  Introduces a safety/alignment diagnostic benchmark to detect process-side anomalies and failures in agent executions beyond task success, addressing operational reliability monitoring.
- **[Over-Refusal and Representation Subspaces: A Mechanistic Analysis of Task-Conditioned Refusal in Aligned LLMs](https://arxiv.org/abs/2603.27518)** — Utsav Maskey, Mark Dras, Usman Naseem _[agent-training-alignment]_
  Mechanistic study of over-refusal as an alignment failure mode—distinguishes harmful-refusal from task-dependent over-refusal directions through representational geometry.
- **[PEARL: Training Socratic Tutors with Pedagogically Aligned Reinforcement Learning](https://arxiv.org/abs/2605.29582)** — Qikai Chang, Zhenrong Zhang, Linbo Chen, et al. _[agent-training-alignment]_
  Multi-agent RL system training tutoring agents to maintain pedagogical objectives through interaction with simulated student agents in multi-turn interactions.
- **[PatchBoard: Schema-Grounded State Mutation for Reliable and Auditable LLM Multi-Agent Collaboration](https://arxiv.org/abs/2605.29313)** — Shuyu Zhang, Yaqi Shi, Lu Wang _[agent-simulation]_
  Multi-agent collaboration architecture with multiple agents coordinating through validated state mutations, demonstrating emergent coordination patterns and system-level behavior.
- **[Provably Secure Agent Guardrail](https://arxiv.org/abs/2605.29251)** — Benlong Wu, Weiming Zhang, Kejiang Chen, et al. _[agent-training-alignment]_
  Proposes a safety framework for LLM agents using formal verification and logical constraints to prevent adversarial attacks and unsafe actions.
- **[ReasonLight: A Multimodal Foundation Model-Enhanced Reinforcement Learning Framework for Zero-Shot Traffic Signal Control](https://arxiv.org/abs/2605.29425)** — Aoyu Pang, Maonan Wang, Yuejiao Xie, et al. _[city-simulation]_
  Urban-scale traffic signal control system using RL agents to simulate and optimize city intersection dynamics.
- **[Recurrent Structural Policy Gradient for Partially Observable Mean Field Games](https://arxiv.org/abs/2602.20141)** — Clarisse Wibault, Johannes Forkel, Sebastian Towers, et al. _[agent-simulation]_
  Proposes a policy gradient method for mean field games with large populations of interacting agents under partial observability.
- **[SAAS: Self-Aware Reinforcement Learning for Over-Search Mitigation in Agentic Search](https://arxiv.org/abs/2605.29796)** — Yunbo Tang, Chengyi Yang, Shiyu Liu, et al. _[agent-training-alignment]_
  RL post-training method addressing alignment failure (reward hacking, specification gaming via over-search) through curriculum and boundary-aware reward design.
- **[SafeSearch: Automated Red-Teaming of LLM-Based Search Agents](https://arxiv.org/abs/2509.23694)** — Jianshuo Dong, Sheng Guo, Hao Wang, et al. _[agent-training-alignment]_
  Automated red-teaming framework designed to systematically identify safety vulnerabilities in LLM-based search agents through adversarial testing and misalignment detection.
- **[Scaling Small Agents Through Strategy Auctions](https://arxiv.org/abs/2602.02751)** — Lisa Alazraki, William F. Shen, Yoram Bachrach, et al. _[agent-simulation]_
  Multi-agent coordination framework using auction mechanisms to route tasks across heterogeneous agents, studying emergent system-level behavior and scalability.
- **[Skill-Pro: Learning Reusable Skills from Experience via Non-Parametric PPO for LLM Agents](https://arxiv.org/abs/2602.01869)** — Qirui Mi, Zhijian Ma, Mengyue Yang, et al. _[agent-training-alignment]_
  Post-training method (Non-Parametric PPO variant) for LLM agents framed as enabling reliable skill reuse and stability without capability degradation.
- **[Small Agent Group is the Future of Digital Health](https://arxiv.org/abs/2602.08013)** — Yuqiao Meng, Luoxi Tang, Dazheng Zhang, et al. _[agent-simulation]_
  Small Agent Group demonstrates multi-agent coordination and collective reasoning where multiple specialized agents interact and deliberate together to solve clinical tasks.
- **[Teaching Values to Machines: Simulating Human-Like Behavior in LLMs](https://arxiv.org/abs/2605.30036)** — Asaf Yehudai, Naama Rozen, Ariel Gera _[llm-agent-simulation]_
  LLMs are prompted with psychological value structures to simulate human behavioral patterns and population dynamics for scientific study.
- **[The Anatomy of Conversational Scams: A Topic-Based Red Teaming Analysis of Multi-Turn Interactions in LLMs](https://arxiv.org/abs/2601.03134)** — Xiangzhe Yuan, Zhenhao Zhang, Haoming Tang, et al. _[agent-training-alignment]_
  Red-teaming benchmark and evaluation framework for detecting LLM vulnerability to multi-turn adversarial conversational attacks, advancing safety evaluation beyond single-turn testing.
- **[The Curse of Helpfulness: Inverse Scaling Law in Robustness to Distractor Instructions via DistractionIF](https://arxiv.org/abs/2605.29491)** — Zeli Su, Zhankai Xu, Tianlei Chen, et al. _[agent-training-alignment]_
  RL-based method (GRPO) addressing a safety alignment failure mode: robustness against instruction-following misalignment via adversarial distraction.
- **[The Importance of Out-of-Band Metadata for Safe Autonomous Agents: The Redpanda Agentic Data Plane](https://arxiv.org/abs/2605.29082)** — Tyler Akidau, Tyler Rockwood, Johannes Brüderl, et al. _[agent-training-alignment]_
  Architecture for enforcing safety constraints and governance on autonomous agents through out-of-band metadata channels, preventing hallucination-induced security failures and maintaining tamper-proof
- **[The Vision Wormhole: Latent-Space Communication in Heterogeneous Multi-Agent Systems](https://arxiv.org/abs/2602.15382)** — Xiaoze Liu, Ruowang Zhang, Weichen Yu, et al. _[agent-simulation]_
  Multi-agent system with heterogeneous LLM agents coordinating through learned latent communication, demonstrating interaction and coordination across diverse architectures.
- **[The incremental voter model: mean-field analysis and convergence to equilibrium](https://arxiv.org/abs/2605.28984)** — Fei Cao, Xiaoqian Gong _[agent-simulation]_
  Multi-agent system modeling population opinion dynamics through agent interactions, mean-field analysis of emergent collective behavior.
- **[Training Deliberative Monitors for Black-Box Scheming Detection](https://arxiv.org/abs/2605.29601)** — Aditya Sinha, Akshat Naik, Victor Gillioz, et al. _[agent-training-alignment]_
  Develops a safety benchmark and detection framework for scheming behavior in autonomous agents using distilled monitors trained to identify misalignment at scale.
- **[Understanding Safety-Sensitive Expert Behavior in Mixture-of-Experts LLMs](https://arxiv.org/abs/2605.29708)** — Zhibo Zhang, Yuxi Li, Zhen Ouyang, et al. _[agent-training-alignment]_
  Red-teaming method that identifies and exploits safety vulnerabilities in MoE LLMs via expert-targeted attacks, revealing alignment weaknesses.
- **[Unifying Temporal and Structural Credit Assignment in LLM-Based Multi-Agent Prompt Optimization](https://arxiv.org/abs/2605.30227)** — Wenwu Li, Yuran Song, Mingze Zhao, et al. _[agent-simulation]_
  Multi-agent system optimization via credit assignment and prompt refinement for collaborative LLM reasoning tasks with emergent agent coordination.
- **[ValueFlow: Measuring the Propagation of Value Perturbations in Multi-Agent LLM Systems](https://arxiv.org/abs/2602.08567)** — Jinnuo Liu, Chuke Liu, Hua Shen _[agent-training-alignment]_
  Framework measuring value drift propagation through multi-agent LLM system interactions, addressing alignment at system level beyond individual agents.
- **[When Cloud Agents Meet Device Agents: Lessons from Hybrid Multi-Agent Systems](https://arxiv.org/abs/2605.30102)** — Corrado Rainone, Davide Belli, Bence Major, et al. _[agent-simulation]_
  Studies multi-agent system architectures combining cloud and on-device models, analyzing emergent coordination and task performance tradeoffs in hybrid agent populations.
- **[When and How Human Curation Backfires: Preference Alignment under Multi-Model Self-Consuming Loop](https://arxiv.org/abs/2605.29267)** — Yang Zhang, Xiukun Wei, Xueru Zhang _[agent-training-alignment]_
  Studies how human preference curation in multi-model self-consuming training loops can degrade alignment through cross-model interactions, addressing a safety failure mode in preference learning syste
- **[Who Am I? History-Aware Profiles for Student Simulation in Tutoring Dialogues](https://arxiv.org/abs/2605.30051)** — Zhangqi Duan, Shuyan Huang, Alexander Scarlatos, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate students' dialogue behavior conditioned on learning history for tutoring system evaluation and training.
- **[Why Specialist Models Still Matter: A Heterogeneous Multi-Agent Paradigm for Medical Artificial Intelligence](https://arxiv.org/abs/2605.29744)** — Yanan Wang, Shuaicong Hu, Jian Liu, et al. _[agent-simulation]_
  Multi-agent framework orchestrating collaboration between generalist LLMs, specialist models, and clinicians with adaptive coordination mechanisms.


## 2026-05-28

- ⭐ **[AdvJudge-Zero: Binary Decision Flips in LLM-as-a-Judge via Adversarial Control Tokens](https://arxiv.org/abs/2512.17375)** — Tung-Ling Li, Yuhao Wu, Hongliang Liu _[agent-training-alignment]_
  Red-teaming attack on LLM-as-a-Judge reward models revealing safety weakness; demonstrates and defends against adversarial verdict manipulation in RLHF pipelines.
- ⭐ **[AutoScientists: Self-Organizing Agent Teams for Long-Running Scientific Experimentation](https://arxiv.org/abs/2605.28655)** — Shanghua Gao, Ada Fang, Marinka Zitnik _[agent-simulation]_
  Decentralized multi-agent team self-organizing around hypotheses, coordinating through shared state without central planner, with distinct roles and adaptive grouping.
- ⭐ **[Framing Matters: Addressing Framing Sensitivity in Decision-Making through Behaviorally-Grounded Value Alignment](https://arxiv.org/abs/2605.28188)** — Seojin Hwang, Minju Kim, Junhyuk Choi, et al. _[agent-training-alignment]_
  Proposes an interpretability and intervention method to detect and mitigate a misalignment failure mode (framing sensitivity) in LLM decision-making.
- ⭐ **[Got a Secret? LLM Agents Can't Keep It: Evaluating Privacy in Multi-Agent Systems](https://arxiv.org/abs/2605.27766)** — Aman Priyanshu, Supriti Vijay, Esha Pahwa _[agent-training-alignment]_
  Multi-agent LLM simulation platform evaluating privacy as safety failure mode; finds social pressure amplifies information disclosure and leakage is contagious across agents.
- ⭐ **[Harness-Bench: Measuring Harness Effects across Models in Realistic Agent Workflows](https://arxiv.org/abs/2605.27922)** — Yilun Yao, Xinyu Tan, Chao-Hsuan Liu, et al. _[agent-simulation]_
  Benchmark for evaluating LLM agent execution systems across harness configurations in realistic multi-component workflows with shared environments and protocols.
- ⭐ **[Human-like in-group bias in instruction-tuned language model agents](https://arxiv.org/abs/2605.28114)** — Messi H. J. Lee _[llm-agent-simulation, agent-training-alignment]_
  Multi-agent simulation of LLM agents studying emergent social biases (in-group discrimination) across persistent networks and alignment implications.
- ⭐ **[LACUNA: Safe Agents as Recursive Program Holes](https://arxiv.org/abs/2605.28617)** — Yaoyu Zhao, Yichen Xu, Oliver Bračevac, et al. _[agent-training-alignment]_
  Programming model for LLM agents that enforces safety through type-checking and static analysis of model-written code, preventing prompt injection and tool misuse failures.
- ⭐ **[Models That Know How Evaluations Are Designed Score Safer](https://arxiv.org/abs/2605.28591)** — Katharina Deckenbach, Haritz Puerto, Jonas Geiping, et al. _[agent-training-alignment]_
  Safety evaluation benchmark methodology paper identifying evaluation meta-knowledge as a confounder that inflates safety scores, advancing understanding of alignment assessment validity.
- ⭐ **[Reward Bias Substitution: Single-Axis Bias Mitigations Redirect Optimization Pressure](https://arxiv.org/abs/2605.27996)** — Max Lamparth, Daniel Fein, Andreas Haupt, et al. _[agent-training-alignment]_
  Identifies and formalizes a fundamental alignment failure mode (reward bias substitution) in RLHF and preference optimization where single-axis mitigations redirect rather than eliminate reward hackin
- ⭐ **[The Fragility of Chain-of-Thought Monitoring Across Typologically Diverse Languages](https://arxiv.org/abs/2605.27901)** — Eric Onyame, Runtao Zhou, Kowshik Thopalli, et al. _[agent-training-alignment]_
  Empirical study of deception and strategic manipulation in LLM chain-of-thought outputs as a safety/alignment phenomenon, demonstrating fragility of a proposed alignment monitoring mechanism.
- ⭐ **[The Obfuscation Atlas: Mapping Where Honesty Emerges in RLVR with Deception Probes](https://arxiv.org/abs/2602.15515)** — Mohammad Taufeeque, Stefan Heimersheim, Adam Gleave, et al. _[agent-training-alignment]_
  Empirical study of deception, obfuscation, and alignment failures in RL-trained systems using deception detectors as safety signals.
- ⭐ **[When Coordination Is Avoidable: A Monotonicity Analysis of Organizational Tasks](https://arxiv.org/abs/2602.18673)** — Harang Ju _[agent-simulation]_
  Paper analyzes multi-agent task coordination through formal theory and validates findings with multi-agent AI simulations of organizational workflows.
- **[A Paired Testing Protocol for Batch-Conditioned Refusal Robustness in LLM Serving](https://arxiv.org/abs/2605.27763)** — Sahil Kadadekar _[agent-training-alignment]_
  Safety evaluation benchmark and diagnostic framework testing LLM refusal robustness across serving conditions, with methodological guidance for misalignment detection.
- **[A Spatially Informed Gaussian Process UCB Method for Decentralized Coverage Control](https://arxiv.org/abs/2511.02398)** — Gennaro Guidone, Luca Monegaglia, Elia Raimondi, et al. _[agent-simulation]_
  Multi-agent decentralized control algorithm where agents autonomously coordinate trajectories through local interactions to solve a coverage control problem.
- **[A Unified Framework for the Evaluation of LLM Agentic Capabilities](https://arxiv.org/abs/2605.27898)** — Pengyu Zhu, Lijun Li, Yaxing Lyu, et al. _[agent-simulation]_
  Unified evaluation framework for LLM agents across diverse multi-agent and safety-critical benchmarks using standardized architecture and comprehensive empirical analysis.
- **[APS: Bias-Controlled Adaptive Prototype Simulation for Population-Scale LLM Agents](https://arxiv.org/abs/2605.27419)** — Quan Zheng, Yan Gao, Shaobin He, et al. _[llm-agent-simulation, city-simulation]_
  Proposes scalable LLM-agent simulation for population-scale behavior modeling, demonstrating adaptive prototype selection to reduce LLM calls while preserving distributional accuracy in large-scale so
- **[AgensFlow: A Coordination-Policy Substrate for Multi-Agent Systems](https://arxiv.org/abs/2605.27466)** — Nicole Koenigstein _[agent-simulation]_
  Multi-agent coordination framework treating routing decisions as a learnable policy problem across distributed LLM agents with distinct roles.
- **[Agents that Matter: Optimizing Multi-Agent LLMs via Removal-Based Attribution](https://arxiv.org/abs/2605.27621)** — Mingyu Lu, Yushan Huang, Chris Lin, et al. _[agent-simulation]_
  Multi-agent LLM systems with agent credit assignment framework via removal-based attribution and ablation study of agent contributions to system performance.
- **[AlphaTransit: Learning to Design City-scale Transit Routes](https://arxiv.org/abs/2605.28730)** — Bibek Poudel, Sai Swaminathan, Weizi Li _[city-simulation]_
  Paper applies MCTS and learned policy-value networks to simulate and optimize city-scale transit network design with realistic urban demand and road topology.
- **[Behavioural Analysis of Alignment Faking](https://arxiv.org/abs/2605.27681)** — Nathaniel Mitrani Hadida, Rhea Karty, David Williams-King, et al. _[agent-training-alignment]_
  Empirical study of alignment faking as a safety failure mode, decomposing drivers via activation steering and identifying conditions for detection and mitigation.
- **[COOP$^2$: Defining, Observing, and Repairing Cooperation in LLM Multi-Agent Systems](https://arxiv.org/abs/2603.00349)** — Hanqing Yang, Narjes Nourzad, Shiyu Chen, et al. _[llm-agent-simulation]_
  Framework for evaluating and repairing cooperation dynamics in LLM-based multi-agent systems through grounded task evaluation and constraint-aware repair mechanisms.
- **[CRaFT: Circuit-Guided Refusal Feature Selection via Cross-Layer Transcoders](https://arxiv.org/abs/2604.01604)** — Su-Hyeon Kim, Hyundong Jin, Yejin Lee, et al. _[agent-training-alignment]_
  Interpretability method for detecting and understanding unsafe refusal-bypass behaviors in aligned LLMs; explicitly frames purpose as model safety analysis and jailbreak defense.
- **[Calibrating Conservatism for Scalable Oversight](https://arxiv.org/abs/2605.28807)** — William Overman, Mohsen Bayati _[agent-training-alignment]_
  Scalable oversight framework with formal safety guarantees for constraining autonomous agents and preventing misalignment via calibrated conservatism penalties.
- **[Colosseum: Auditing Collusion in Cooperative Multi-Agent Systems](https://arxiv.org/abs/2602.15198)** — Mason Nakamura, Abhinav Kumar, Saswat Das, et al. _[agent-training-alignment]_
  Framework for auditing collusive safety failures in LLM-based multi-agent cooperative systems through systematic behavioral evaluation and diagnosis.
- **[CyberJurors: A Multi-Agent Simulation Task for E-Commerce Disputes Verdict](https://arxiv.org/abs/2605.28369)** — Yanhui Sun, Wu Liu, Haifeng Ming, et al. _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM framework simulating crowdsourced jurors deliberating e-commerce disputes through structured reasoning, discussion, and consensus voting to study collective decision-making behavior.
- **[Cyclical Entropy Eruption: Entropy Dynamics in Agent Reinforcement Learning](https://arxiv.org/abs/2605.27954)** — Wendi Li, Shawn Im, Sharon Li _[agent-training-alignment]_
  Post-training method for agent RL explicitly motivated by alignment concern (stability, hallucination/duplication mitigation) rather than pure capability.
- **[DIG to Heal: Scaling General-purpose Agent Collaboration via Explainable Dynamic Decision Paths](https://arxiv.org/abs/2603.00309)** — Hanqing Yang, Hyungwoo Lee, Yuhang Yao, et al. _[agent-simulation]_
  Multi-agent system with multiple interacting LLM agents solving tasks through emergent collaboration, tracking emergent behavior via causal interaction graphs.
- **[DSSE: a drone swarm search environment](https://arxiv.org/abs/2307.06240)** — Manuel Castanares, Luis F. S. Carrete, Enrico F. Damiani, et al. _[agent-simulation]_
  Multi-agent reinforcement learning environment with swarm coordination and emergent search behavior across multiple drone agents.
- **[Debate Helps Weak Judges Reward Stronger Models](https://arxiv.org/abs/2605.27483)** — Ethan Elasky, Frank Nakasako, Naman Goyal _[agent-training-alignment]_
  Studies debate as scalable oversight mechanism for verifiable tasks, analyzing when critic models improve judge alignment through structured verification protocols.
- **[Debate with Images: Detecting Deceptive Behaviors in Multimodal Large Language Models](https://arxiv.org/abs/2512.00349)** — Sitong Fang, Shiyi Hou, Kaile Wang, et al. _[agent-training-alignment]_
  Safety eval framework detecting deception in multimodal LLMs; proposes multi-agent debate method to identify misalignment behaviors.
- **[Decoupled Intelligence: A Multi-Agent LLM Framework for Controllable Traffic Scenario Generation in SUMO](https://arxiv.org/abs/2605.27685)** — Shuyang Li, Ruimin Ke _[city-simulation, agent-simulation]_
  Multi-agent LLM framework simulates urban traffic dynamics using specialized coordinated agents for traffic scenario generation in SUMO city simulation.
- **[Defending LLM-based Multi-Agent Systems Against Cooperative Attacks with Sentence-Level Rectification](https://arxiv.org/abs/2605.28104)** — Yaoyang Luo, Zhi Zheng, Ziwei Zhao, et al. _[agent-training-alignment]_
  Paper studies cooperative attack and defense mechanisms in LLM-based multi-agent systems, addressing alignment/safety through adversarial robustness and malicious agent coordination detection.
- **[Diagnosing Live Within-Policy Instruction Conflicts in LLM Agents with Witnessed Resolution Profiles](https://arxiv.org/abs/2605.27784)** — Lu Yan, Xuan Chen, Xiangyu Zhang _[agent-training-alignment]_
  Diagnostic framework detecting internal policy conflicts and misalignment failures in LLM agent prompt policies through systematic rule-conflict detection and resolution profiling.
- **[Differentiable Model Predictive Safety for Heterogeneous Mobility at Urban Intersections](https://arxiv.org/abs/2605.27418)** — Wenzhe Song, Hao Zhang _[agent-simulation, city-simulation]_
  Multi-agent coordination framework for heterogeneous autonomous vehicles and robots at urban intersections using reinforcement learning with differentiable safety guarantees.
- **[Evaluating Chinese Large Language Models: The Influence of Persona Assignment on Stereotypes and Safeguards](https://arxiv.org/abs/2506.04975)** — Geng Liu, Li Feng, Carlo Alberto Bono, et al. _[agent-training-alignment]_
  Systematic evaluation of persona-induced misalignment (toxicity, stereotype amplification, refusal behavior) in LLMs as safety phenomenon with mitigation strategies.
- **[Evaluating the Realism of LLM-powered Social Agents: A Case Study of Reactions to Spanish Online News](https://arxiv.org/abs/2605.28598)** — Alejandro Buitrago López, Alberto Ortega Pastor, Javier Pastor-Galindo, et al. _[llm-agent-simulation]_
  Paper evaluates LLM-powered social agents simulating human audience reactions to news for behavioral realism against human discourse properties.
- **[Examining Agents' Bias Amplification versus Suppression in Multi-Agent Systems](https://arxiv.org/abs/2605.28098)** — Zejian Eric Wu, Zhongyi Jiang, Yuan Zhuang, et al. _[agent-simulation]_
  Multi-agent system studying emergent bias amplification across interacting LLM agents, demonstrating population-level fairness phenomena not reducible to individual agent behavior.
- **[Execution and assessment of agentic influence operations in simulated social networks](https://arxiv.org/abs/2605.28725)** — Alejandro Buitrago López, David Montoro Aguilera, Javier Pastor-Galindo, et al. _[agent-simulation]_
  Multi-agent social network simulation studying emergent population dynamics and belief propagation across interacting agents under influence operations.
- **[From Task Allocation to Risk Clearing: A Unifying Interface for Mixed Human-Agent Societies](https://arxiv.org/abs/2605.27547)** — Vassilis Vassiliades _[agent-simulation]_
  Multi-agent coordination mechanism for heterogeneous human-robot-software agent teams with centralized task allocation and risk management framework.
- **[FundaPod: A Multi-Persona Agent Pod Platform with Knowledge Graph Memory for AI-Assisted Fundamental Investment Research](https://arxiv.org/abs/2605.27864)** — Di Zhu, Lei, Zheng, et al. _[agent-simulation]_
  Multi-persona agent system with distinct roles (value investors, macro strategists) coordinating research with shared knowledge graph and human oversight, demonstrating multi-agent coordination and in
- **[Global Policy-Space Response Oracles for Two-Player Zero-Sum Games](https://arxiv.org/abs/2605.28273)** — Junyu Zhang, Feihong Yang, Jian Wang, et al. _[agent-simulation]_
  Multi-agent game-theoretic framework using deep RL for iterative equilibrium computation in zero-sum games with strategy population dynamics.
- **[Heterogeneous Multi-Agent Modeling for Measurement and Network Analysis of the Data Service Market](https://arxiv.org/abs/2605.27433)** — Deyu Zhou, Yuwei Guo, Xudong Lu, et al. _[agent-simulation]_
  Paper models heterogeneous multi-agent systems representing entities in a data service market ecosystem, analyzing their interactions and emergent network effects through ABM simulation.
- **[InfiMed-ORBIT: Aligning LLMs on Open-Ended Complex Tasks via Rubric-Based Incremental Training](https://arxiv.org/abs/2510.15859)** — Pengkai Wang, Pengwei Liu, Qi Zuo, et al. _[agent-training-alignment]_
  Post-training method (RL) explicitly motivated by addressing reward hacking and ambiguous feedback in medical dialogue alignment.
- **[Intelligence as Managed Autonomy: Failure, Escalation, and Governance for Agentic AI Systems](https://arxiv.org/abs/2605.27628)** — Srini Ramaswamy _[agent-training-alignment]_
  Proposes architectural framework for detecting epistemic drift and escalation in autonomous agents to prevent alignment failures and ensure safety governance.
- **[LCO: LLM-based Constraint Optimization for Safer Agentic LLMs in Real-world Tasks](https://arxiv.org/abs/2605.27375)** — Jiayong Wan, Jiawei Chen, Zhaoxia Yin, et al. _[agent-training-alignment]_
  LCO addresses reward hacking and specification gaming in autonomous LLM agents through safety-conscious constraint optimization, directly targeting an alignment failure mode.
- **[LegalGraphRAG: Multi-Agent Graph Retrieval-Augmented Generation for Reliable Legal Reasoning](https://arxiv.org/abs/2605.28120)** — Zerui Chen, Qinggang Zhang, Zhishang Xiang, et al. _[agent-simulation]_
  Multi-agent system with distinct roles (Researcher, Auditor, Adjudicator) coordinating to perform reliable legal reasoning through division of labor and evidence verification.
- **[Mask-GCG: Are All Tokens in Adversarial Suffixes Necessary for Jailbreak Attacks?](https://arxiv.org/abs/2509.06350)** — Junjie Mu, Zonghao Ying, Zhekui Fan, et al. _[agent-training-alignment]_
  Red-teaming method that improves adversarial jailbreak attacks on LLMs by identifying redundant suffix tokens; reveals alignment vulnerabilities.
- **[Mass-Scale Analysis of In-the-Wild Conversations Reveals Complexity Bounds on LLM Jailbreaking](https://arxiv.org/abs/2507.08014)** — Aldan Creo, Raul Castro Fernandez, Manuel Cebrian _[agent-training-alignment]_
  Large-scale empirical study of jailbreak complexity and LLM safety mechanisms, directly addressing adversarial attack methodology and alignment failure modes.
- **[Mathematical Modelling of Ethical AI Use in Higher Education: A Coordination Game Framework for Future-Facing Learning](https://arxiv.org/abs/2605.27400)** — Ndidi Bianca Ogbo, Zhao Song, Shatha Ghareeb, et al. _[agent-simulation]_
  Evolutionary game-theoretic framework modeling emergent collective norms of student AI use through multi-agent coordination dynamics and population behavioral transitions.
- **[Mitigating Adaptive Attacks against Reasoning Models with Activation Consistency Training](https://arxiv.org/abs/2605.28467)** — Avidan Shah, Jannik Brinkmann, Rico Angell _[agent-training-alignment]_
  Post-training method (consistency training variant) explicitly motivated by defending reasoning models against adversarial jailbreaks and prompt injection attacks.
- **[Mixture-of-Experts Knowledge Graph Retrieval-Augmented Generation for Multi-Agent LLM-based Recommendation](https://arxiv.org/abs/2605.28175)** — Shijie Wang, Chengyi Liu, Yujuan Ding, et al. _[agent-simulation]_
  Multi-agent LLM framework with three distinct agents (Retrieval, Alignment, Recommendation) coordinating via unified policy optimization for recommendation tasks.
- **[Modeling Community Attitude through Reaction Tone: A Human-AI Collaborative Framework for Evaluating LLM Alignment with Linguistic Behaviors in Online Communities](https://arxiv.org/abs/2605.27388)** — Nuan Wen, Xuezhe Ma _[llm-agent-simulation]_
  Paper uses LLMs to simulate human communities' authentic linguistic behaviors and responses, studying fidelity of LLM-based population simulation for social analysis.
- **[MolLingo: Molecule-Native Representations for LLM-Powered Scientific Agents](https://arxiv.org/abs/2605.27853)** — Thao Nguyen, Heng Ji _[agent-simulation]_
  Multi-agent system with distinct Literature, Chemist, and Orchestrator agents coordinating through shared memory for iterative molecular design reasoning.
- **[Multi-Adapter Representation Interventions via Energy Calibration](https://arxiv.org/abs/2605.28722)** — Manjiang Yu, Hongji Li, Junwei Chen, et al. _[agent-training-alignment]_
  Representation intervention method explicitly motivated by aligning LLMs toward desired behaviors and improving performance on safety benchmarks like TruthfulQA and BBQ.
- **[PAST2HARM: A Simple Adaptive Past Tense Attack for Jailbreaking Multimodal AI](https://arxiv.org/abs/2605.27545)** — Snehasis Mukhopadhyay _[agent-training-alignment]_
  Adversarial jailbreak attack method targeting aligned multimodal AI systems; exposes safety weaknesses through systematic exploit of refusal training vulnerabilities.
- **[PEAM: Parametric Embodied Agent Memory through Contrastive Internalization of Experience in Minecraft](https://arxiv.org/abs/2605.27762)** — Yuchen Guo, Junli Gong, Hongmin Cai, et al. _[agent-simulation]_
  Single embodied agent learning framework with memory consolidation; no multi-agent interaction, population dynamics, or LLM-human simulation scope.
- **[Personalized Observation Normalization for Federated Reinforcement Learning in Simulation Environments with Heterogeneity](https://arxiv.org/abs/2605.27385)** — Yiran Pang, Zhen Ni, Xiangnan Zhong _[agent-simulation]_
  Federated reinforcement learning with multiple heterogeneous agents collaboratively training on shared policy reflects multi-agent coordination and distributed agent learning dynamics.
- **[Persuade Me if You Can: A Framework for Evaluating Persuasion Effectiveness and Susceptibility Among Large Language Models](https://arxiv.org/abs/2503.01829)** — Nimet Beyza Bozdag, Shuhaib Mehri, Gokhan Tur, et al. _[llm-agent-simulation, agent-training-alignment]_
  Multi-agent framework simulating persuasion dynamics between LLM agents to study alignment phenomena (susceptibility to manipulation, safety, robustness).
- **[Plant, Persist, Trigger: Sleeper Attack on Large Language Model Agents](https://arxiv.org/abs/2605.28201)** — Yongxiang Li, Moxin Li, Zhixin Ma, et al. _[agent-training-alignment]_
  Sleeper Attack is an adversarial attack and safety threat evaluation against LLM agents demonstrating alignment/safety vulnerability across multi-turn interactions.
- **[Pressure-Testing Deception Probes in LLMs: Scaling, Robustness, and the Geometry of Deceptive Representations](https://arxiv.org/abs/2605.27958)** — Sachin Kumar _[agent-training-alignment]_
  Systematic evaluation of deception-detection probes in LLMs, examining safety-critical misalignment phenomenon through representational analysis and diagnostic methodology.
- **[Reasoning and Planning with Dynamically Changing Norms](https://arxiv.org/abs/2605.27622)** — Taylor Olson, Roberto Salas-Damian, Kenneth D. Forbus _[agent-training-alignment]_
  AI agent safety work addressing norm-guided planning and constraint satisfaction in human-AI interaction through defeasible calculus.
- **[Refusal Before Decoding: Detecting and Exploiting Refusal Signals in Intermediate LLM Activations](https://arxiv.org/abs/2605.28553)** — Matteo Gioele Collu, Riccardo Conte, Alberto Giaretta, et al. _[agent-training-alignment]_
  Red-teaming method exploiting interpretable safety signals to guide jailbreak attacks on aligned LLMs; advances adversarial attack methodology targeting refusal mechanisms.
- **[Rethinking Memory as Continuously Evolving Connectivity](https://arxiv.org/abs/2605.28773)** — Jizhan Fang, Buqiang Xu, Zhixian Wang, et al. _[agent-simulation]_
  LLM agent memory framework enabling long-horizon task execution through dynamic, evolving connectivity and procedural learning across multi-task environments.
- **[Roles with Rails: Contract-Preserving Role Evolution in Multi-Agent Structured Reasoning](https://arxiv.org/abs/2605.28433)** — Ling-Yue Ge, Lan-Zhe Guo _[agent-simulation]_
  Multi-agent system with multiple interacting roles coordinating through communication DAGs and structured reasoning; role orchestration exemplifies agent coordination and emergent task behavior.
- **[SPARD: Defending Harmful Fine-Tuning Attack via Safety Projection with Relevance-Diversity Data Selection](https://arxiv.org/abs/2605.28030)** — Shuhao Chen, Weisen Jiang, Yeqi Gong, et al. _[agent-training-alignment]_
  Defense framework against harmful fine-tuning attacks that remove LLM safety safeguards through explicit safety constraints and safe-data selection.
- **[SaFeR-Steer: Evolving Multi-Turn MLLMs via Synthetic Bootstrapping and Feedback Dynamics](https://arxiv.org/abs/2604.16358)** — Haolong Hu, Hanyu Li, Tiancheng He, et al. _[agent-training-alignment]_
  Post-training safety alignment method for MLLMs against multi-turn adversarial attacks, framed explicitly as addressing deployment-time safety failures through on-policy adversarial training.
- **[Speed-Weighted Adaptive Flocking for Sailing Swarms under Dynamic Environmental Forcing](https://arxiv.org/abs/2605.27422)** — Pranav Kedia, Aaron Gan, Hannah J. Williams, et al. _[agent-simulation]_
  Multi-agent flocking model with collective behavior dynamics under environmental constraints; studies emergent coordination across heterogeneous robot swarms.
- **[StoryMI: Steerable Multi-Agent Therapeutic Dialogue Generation](https://arxiv.org/abs/2605.27393)** — Qingyu Meng, Min Chen, Dingming Liu, et al. _[llm-agent-simulation]_
  Multi-agent LLM system simulating therapist-client dialogue with dynamic strategy coordination for psychotherapy research.
- **[TCP-MCP: Landscape-Guided Co-Evolution of Prompts and Communication Topologies for Multi-Agent Systems](https://arxiv.org/abs/2605.27850)** — Yi Ding, Zijie Xuan, Haowei Zhou, et al. _[agent-simulation]_
  Multi-agent system with multiple interacting LLM agents coordinating via learned communication topologies and prompts to solve collaborative tasks.
- **[TRACER: Turn-level Regret Matching with Inner Reinforcement Credit for Cooperative Multi-LLM Reasoning](https://arxiv.org/abs/2605.28699)** — Chusen Li, Zhou Liu, Shuigeng Zhou, et al. _[agent-simulation]_
  Multi-agent reinforcement learning framework where multiple LLMs learn collaborative decision-making and communication through turn-level regret matching and credit assignment.
- **[TRACES: Proactive Safety Auditing for Multi-Turn LLM Agents via Trajectory-State Modeling](https://arxiv.org/abs/2605.27690)** — Jiaqian Li, Yanshu Li, Boxuan Zhang, et al. _[agent-training-alignment]_
  Proposes a proactive safety auditing framework for detecting misalignment risks in multi-turn LLM agent trajectories via interpretable risk state modeling.
- **[The Alignment Floor: When Persona Customization Is Safe](https://arxiv.org/abs/2605.27382)** — Xing Zhang, Guanghui Wang, Yanwei Cui, et al. _[agent-training-alignment]_
  Empirical study of alignment failure modes (sycophancy) under persona customization; demonstrates misalignment vulnerability and proposes safety principle.
- **[Using Zero-Shot LLM-Generated Survey Data for Geographically Explicit Population Synthesis](https://arxiv.org/abs/2605.27401)** — Taylor Anderson, Sara Von Hoene, Orhan Yagizer Cinar, et al. _[city-simulation]_
  Uses LLMs to generate synthetic population survey data for geographically explicit population synthesis at census tract and state scales, evaluated for urban/demographic simulation applications.
- **[Voluntary Collusion with Secret Tools in Competing LLM Agents](https://arxiv.org/abs/2605.27593)** — Xijie Zeng, Frank Rudzicz _[agent-training-alignment]_
  Multi-agent competitive simulation studying deception and collusion behavior; reveals alignment failure (safety-aligned LLMs voluntarily engage in harmful collusion) requiring alignment safeguards.
- **[When Context Flips, Safety Breaks: Diagnosing Brittle Safety in Aligned Language Models](https://arxiv.org/abs/2605.27851)** — Dasol Choi, Alex Kwon _[agent-training-alignment]_
  Diagnostic framework for detecting alignment failures (brittle safety) in LLMs through evaluation and benchmarking methodology.
- **[When Seekers Are Hard to Help: Evaluating Emotional Support Dialogue Systems in Worst-Case Interactions](https://arxiv.org/abs/2605.28228)** — Jiajie Yang, Yangchun Li, Guanyi Chen, et al. _[llm-agent-simulation]_
  Paper uses LLM-simulated seekers (agents) to evaluate emotional support dialogue systems through realistic multi-turn interactions.
- **[Where Does Toxicity Live? Mechanistic Localization and Targeted Suppression in Language Models](https://arxiv.org/abs/2605.27997)** — Himanshu Beniwal, Mayank Singh _[agent-training-alignment]_
  Interpretability-driven safety method identifying and suppressing harmful behavior (toxicity) in LLMs at the mechanistic level, enabling safer model behavior.
- **[You Only Align Once: Propagating Cooperative Behaviors in Multi-Agent Systems through Seed Agents](https://arxiv.org/abs/2605.27586)** — Nicole Hsing, Asuka Yuxi Zheng, Yi Zhao, et al. _[llm-agent-simulation, agent-training-alignment, agent-simulation]_
  Multi-agent LLM study demonstrating alignment propagation through seed agents in game-theoretic and survival simulations, showing emergent cooperative behavior transfer across agent populations.
- **[ZipRL: Adaptive Multi-Turn Context Compression with Hindsight Response Replay](https://arxiv.org/abs/2605.28069)** — Zhexin Hu, Li Wang, Xiaohan Wang, et al. _[agent-training-alignment]_
  RL post-training method (GRPO variant with hindsight replay) motivated by long-horizon agent task reliability and reward signal quality in multi-turn RL workflows.



## 2026-05-27

- ⭐ **[Alignment Tampering: How Reinforcement Learning from Human Feedback Is Exploited to Optimize Misaligned Biases](https://arxiv.org/abs/2605.27355)** — Dongyoon Hahm, Dylan Hadfield-Menell, Kimin Lee _[agent-training-alignment]_
  Studies how RLHF can be exploited to amplify misaligned behaviors, revealing structural alignment vulnerabilities and failure modes in LLM safety alignment.
- ⭐ **[LURE: Live-Usage Replay Evaluations for Reducing Evaluation Awareness](https://arxiv.org/abs/2605.26438)** — Igor Ivanov, David Demitri Africa _[agent-training-alignment]_
  Safety evaluation benchmark framework addressing evaluation awareness and scheming in LLM alignment through realistic agentic interaction trajectories.
- ⭐ **[ORLoopBench: Solver-in-the-Loop Benchmarks for Self-Correction and Behavioral Rationality in Operations Research](https://arxiv.org/abs/2601.21008)** — Ruicheng Ao, David Simchi-Levi, Xinshang Wang _[agent-training-alignment]_
  Post-training method (RLVR) explicitly framed for OR agent self-correction safety, evaluating alignment between solver feedback and model behavior.
- ⭐ **[Position: AI Safety Requires Effective Controllability](https://arxiv.org/abs/2605.27117)** — Yige Li, Yunhao Feng, Jun Sun _[agent-training-alignment]_
  Position paper proposing controllability as a first-class alignment objective with a benchmark for detecting control-override failures in agentic systems.
- ⭐ **[Sell Me This Stock: Unsafe Recommendation Drift in LLM Agents](https://arxiv.org/abs/2603.12564)** — Zekun Wu, Adriano Koshiyama, Sahan Bulathwela, et al. _[agent-training-alignment]_
  Empirical study of deception vulnerability and sycophancy in LLM agents: demonstrates how frontier models follow manipulated tool outputs despite internally detecting tampering, a core alignment failu
- ⭐ **[Your Agents Are Aging Too: Agent Lifespan Engineering for Deployed Systems](https://arxiv.org/abs/2605.26302)** — Jianing Zhu, Yeonju Ro, John Robertson, et al. _[agent-training-alignment]_
  Safety-focused diagnostic benchmark for deployed LLM agents, measuring reliability degradation and misalignment over time via longitudinal evaluation with mechanism-level diagnosis.
- **[ATOM: Instantiating Budget-Controllable Multi-Agent Collaboration via Nucleus-Electron Hierarchy](https://arxiv.org/abs/2605.26178)** — Xinkui Zhao, Sai Liu, Yifan Zhang, et al. _[agent-simulation]_
  Multi-agent LLM system with adaptive collaboration topology, task-driven RL, and budget-aware agent instantiation; core contribution is agent coordination and interaction patterns.
- **[Adversarial Training for Robust Coverage Network under Worst-case Facility Losses](https://arxiv.org/abs/2605.26763)** — Changhao Miao, Yuntian Zhang, Tongyu Wu, et al. _[agent-simulation]_
  Dual-agent deep reinforcement learning framework with adversarial training between competing agents solving bi-level optimization for infrastructure resilience.
- **[AgentSociety: Incentivizing Agentic Social Intelligence](https://arxiv.org/abs/2605.26203)** — Aditya Vema Reddy Kesari, Krishna Reddy Kesari _[agent-simulation]_
  Proposes multi-agent mechanism with autonomous agents making coordinated decisions, strategic communication, and emergent collective routing through incentivized collaboration and game-theoretic Nash 
- **[Belief-Sim: Towards Belief-Driven Simulation of Demographic Misinformation Susceptibility](https://arxiv.org/abs/2603.03585)** — Angana Borah, Zohaib Khan, Rada Mihalcea, et al. _[llm-agent-simulation]_
  LLMs simulate human demographic behavior and misinformation susceptibility via belief-driven profiles for scientific study of population-level phenomena.
- **[Beyond Trajectory-Level Attribution: Graph-Based Credit Assignment for Agentic Reinforcement Learning](https://arxiv.org/abs/2605.26684)** — Xin Cheng, Shuo He, Lang Feng, et al. _[agent-training-alignment]_
  Post-training method (policy optimization variant) motivated by improving credit assignment for agentic RL—directly addresses alignment through better learning signal fidelity.
- **[Beyond a Single Direction: Chain-of-Thought Disrupts Simple Steering of Refusal](https://arxiv.org/abs/2605.26772)** — Kia-Jüng Yang, Dominik Meier, Jiachen Zhao, et al. _[agent-training-alignment]_
  Studies safety phenomenon (refusal) and mechanisms of alignment-through-control, analyzing how CoT affects steering-based interventions in reasoning models.
- **[Communication Gain and Delay Cost Under Cross-Timestep Delays in Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2604.03785)** — Zihong Gao, Hongjian Liang, Lei Hao, et al. _[agent-simulation]_
  Proposes CDCMA, an actor-critic framework for cooperative multi-agent RL communication under cross-timestep delays, addressing coordination in multi-agent partially observable settings.
- **[CompassDPO: Dynamics-Controlled Direct Preference Optimization for Robust Safety Alignment](https://arxiv.org/abs/2603.07211)** — Jilong Liu, Yonghui Yang, Pengyang Shao, et al. _[agent-training-alignment]_
  LLM post-training method (DPO variant) explicitly motivated by safety alignment robustness against imperfect supervision in preference learning.
- **[Constitutional Arms Races in the Public Goods Game: Co-Evolving LLM Constitutions Under Cooperation-Defection Pressure](https://arxiv.org/abs/2605.26448)** — Ujwal Kumar, Arth Singh, Hershraj Niranjani, et al. _[agent-training-alignment]_
  Multi-agent LLM co-evolution study examining adversarial pressure and alignment robustness through constitutional arms races in game-theoretic settings.
- **[Cost of Structural Learning Under Censored Feedback: A Threshold-Bandit Approach](https://arxiv.org/abs/2605.27076)** — Michael Ledford, William Regli _[agent-simulation]_
  Multi-agent coordination and learning under censored feedback with decentralized protocols; addresses fundamental agent-interaction and regret bounds.
- **[Counterfactual Credit Policy Optimization for Multi-Agent Collaboration](https://arxiv.org/abs/2603.21563)** — Zhongyi Li, Wan Tian, Yikun Ban, et al. _[agent-simulation]_
  Multi-agent RL system with credit assignment mechanism for collaborative LLM agents solving reasoning tasks via role decomposition and coordinated policy optimization.
- **[Curriculum Learning for Safety Alignment](https://arxiv.org/abs/2605.26315)** — Sandeep Kumar, Virginia Smith, Chhavi Yadav _[agent-training-alignment]_
  Post-training method (DPO variant) explicitly framed as addressing safety alignment failure modes: OOD robustness and jailbreak vulnerability.
- **[DIANOIA: Diagnostic Decomposition and Joint Optimization for Multi-Agent Reasoning](https://arxiv.org/abs/2602.08586)** — Yiming Yang, Zhuoyuan Li, Fanxiang Zeng, et al. _[agent-simulation]_
  Multi-agent LLM system with multiple interacting components (proposers, verification, synthesis) coordinating to solve tasks; studies emergent multi-agent reasoning gain through decomposition.
- **[Decoupled Delay Compensation: Enhancing Pre-trained MARL Policies via Learned Dynamics Filtering](https://arxiv.org/abs/2605.26286)** — Maxim Mednikov, Oren Gal _[agent-simulation]_
  Multi-agent reinforcement learning system addressing coordination under communication delays; core contribution is enhancing pre-trained MARL policies via learned state estimation.
- **[EmoDistill: Offline Emotion Skill Distillation for Language Model Agents in Adversarial Negotiation](https://arxiv.org/abs/2605.26785)** — Yunbo Long, Haolang Zhao, Lukas Beckenbauer, et al. _[agent-simulation]_
  Multi-agent adversarial negotiation framework where LLM agents interact strategically; offline skill distillation from agent-to-agent interactions represents multi-agent population dynamics.
- **[EvoEmo: Towards Evolved Emotional Policies for Adversarial LLM Agents in Multi-Turn Price Negotiation](https://arxiv.org/abs/2509.04310)** — Yunbo Long, Liming Xu, Lukas Beckenbauer, et al. _[llm-agent-simulation]_
  LLM agents simulating humans in multi-turn negotiation with evolved emotional policies to study strategic behavior and manipulation resistance.
- **[Exploring Agent Interactions in MoltBook through Social Network Analysis](https://arxiv.org/abs/2605.27349)** — I-Hsien Ting, Kazunori Minetaki, Dario Liberona, et al. _[agent-simulation]_
  Multi-agent system study analyzing interaction patterns, social network topology, and emergent communication dynamics across autonomous agent populations.
- **[Helicase: Uncertainty-Guided Supply Chain Knowledge Graph Construction with Autonomous Multi-Agent LLMs](https://arxiv.org/abs/2605.26835)** — Yunbo Long, Haolang Zhao, Ge Zheng, et al. _[agent-simulation]_
  Autonomous multi-agent LLM system with specialized agents (search, reasoning, coding) coordinating through iterative loops to solve complex knowledge graph construction tasks.
- **[Intelligent Offloading in Vehicular Edge Computing: A Comprehensive Review of Deep Reinforcement Learning Approaches and Architectures](https://arxiv.org/abs/2502.06963)** — Ashab Uddin, Ahmed Hamdi Sakr, Ning Zhang _[agent-simulation]_
  Survey of multi-agent reinforcement learning for vehicular edge computing offloading with focus on distributed decision-making and coordination mechanisms.
- **[Interactive Agents: Simulating Counselor-Client Psychological Counseling via Role-Playing LLM-to-LLM Interactions](https://arxiv.org/abs/2408.15787)** — Huachuan Qiu, Zhenzhong Lan _[llm-agent-simulation]_
  LLM-based agents simulating counselor-client dyads with distinct roles and long-horizon interactions to study therapeutic dialogue behavior.
- **[It's Not Always Sycophancy: Measuring LLM Conformity as a Function of Epistemic Uncertainty](https://arxiv.org/abs/2605.27288)** — Kevin H. Guo, Chao Yan, Avinash Baidya, et al. _[agent-training-alignment]_
  Diagnostic framework distinguishing sycophancy (alignment-induced misalignment) from uncertainty-driven conformity, with implications for safety intervention strategies.
- **[KARMA: Karma-Aligned Reward Model Adaptation](https://arxiv.org/abs/2605.26738)** — Jared Scott, Jesse Roberts _[agent-training-alignment]_
  Post-training method (reward modeling + RL) explicitly framed as addressing alignment tension between reward optimization and factuality.
- **[LiPUP-MA: A Residential Experience-centric Multi-Agent Framework for Living-in-the-loop Participatory Urban Planning](https://arxiv.org/abs/2412.20505)** — Hang Ni, Yuzhi Wang, Yizhi Song, et al. _[llm-agent-simulation, city-simulation]_
  Multi-agent LLM framework simulating residential living in urban contexts to iteratively improve city planning through experiential feedback and agent coordination.
- **[MemFail: Stress-Testing Failure Modes of LLM Memory Systems](https://arxiv.org/abs/2605.26667)** — Ishir Garg, Neel Kolhe, Dawn Song, et al. _[agent-training-alignment]_
  Safety-aware diagnostic benchmark for evaluating and detecting failure modes in LLM agent memory systems through adversarial testing.
- **[Model Unlearning Objectives Vary for Distinct Language Functions](https://arxiv.org/abs/2605.26454)** — Berk Atil, Vipul Gupta, Rebecca J. Passonneau _[agent-training-alignment]_
  Post-training method for unlearning dangerous knowledge and toxicity, framed as addressing safety failure modes in LLMs.
- **[Multi-Agent Causal Discovery Using Large Language Models](https://arxiv.org/abs/2407.15073)** — Hao Duong Le, Xin Xia, Haijie Xu, et al. _[agent-simulation]_
  Multi-agent debate framework where multiple LLM agents with distinct roles (Affirmative, Negative, Judge) interact to refine causal graph discovery through autonomous coordination.
- **[Multiagent Social Influence: Modeling Persuasion in Contested Social Networks](https://arxiv.org/abs/2510.01481)** — Renukanandan Tumu, Cristian Ioan Vasile, Victor Preciado, et al. _[agent-simulation]_
  Multi-agent game-theoretic model of competing persuasion agents optimizing influence allocation in social networks with emergent opinion dynamics.
- **[Open-Weight LLM Fine-Tuning Defenses are Susceptible to Simple Attacks](https://arxiv.org/abs/2605.26526)** — Kevin Kuo, Chhavi Yadav, Virginia Smith _[agent-training-alignment]_
  Red-teaming study demonstrating attacks on safeguarded LLMs and proposing a defense method, directly addressing alignment and safety vulnerabilities.
- **[PICACO: Pluralistic In-Context Value Alignment of LLMs via Total Correlation Optimization](https://arxiv.org/abs/2507.16679)** — Han Jiang, Dongyao Zhu, Zhihua Wei, et al. _[agent-training-alignment]_
  Paper proposes in-context method to align LLMs with human values without fine-tuning, addressing value alignment and preference accommodation—a core alignment safety concern.
- **[Persona Generators: Generating Diverse Synthetic Personas for Arbitrary Contexts](https://arxiv.org/abs/2602.03545)** — Davide Paglieri, Logan Cross, William A. Cunningham, et al. _[llm-agent-simulation]_
  Paper uses LLMs to generate diverse synthetic personas for simulating human behavior and population dynamics across contexts.
- **[QUACK: Questioning, Understanding, and Auditing Communicated Knowledge in Multimodal Social Deduction Agents](https://arxiv.org/abs/2605.27068)** — Ye Yuan, Rui Song, Weien Li, et al. _[agent-training-alignment]_
  Multi-agent LLM social deduction game environment with systematic evaluation framework for detecting deception, hallucination, and language-action inconsistency in agent behavior.
- **[Real-Time Progress Prediction in Reasoning Language Models](https://arxiv.org/abs/2506.23274)** — Hans Peter Lyngsøe Raaschou-Jensen, Constanza Fierro, Anders Søgaard _[agent-training-alignment]_
  Interpretability method aimed at real-time oversight and safety-critical monitoring of reasoning processes in autonomous LLM agents during extended reasoning horizons.
- **[Recon: Reconstruction-Guided Reasoning Synthesis for User Modeling](https://arxiv.org/abs/2605.26969)** — Alan Zhu, Mihran Miroyan, Carolyn Wang, et al. _[llm-agent-simulation]_
  LLM-based user modeling that simulates individual behavior from past interactions for behavioral science and human-AI collaboration research.
- **[Rewarding Engagement and Personalization in Popularity-Based Rankings Amplifies Extremism and Polarization](https://arxiv.org/abs/2510.24354)** — Jacopo D'Ignazi, Emma Fraxanet Morales, Andreas Kaltenbrunner, et al. _[city-simulation, agent-simulation]_
  Multi-agent simulation study of how ranking algorithms amplify polarization through user engagement and personalization, tested with interactive experiments and dynamical models.
- **[SIA: Self Improving AI with Harness & Weight Updates](https://arxiv.org/abs/2605.27276)** — Prannay Hebbar, Yogendra Manawat, Samuel Verboomen, et al. _[agent-simulation]_
  Multi-agent self-improvement loop where a meta-agent (Feedback-Agent) iteratively updates both harness and weights of a task-specific agent, studying emergent agent behavior across domains.
- **[Strategic Persuasion with Trait-Conditioned Multi-Agent Systems for Iterative Legal Argumentation](https://arxiv.org/abs/2604.07028)** — Philipp D. Siedler _[agent-simulation]_
  Multi-agent simulation framework with prosecution and defense LLM teams engaging in iterative legal argumentation with emergent strategic interaction.
- **[Think Twice Before You Act: Enhancing Agent Behavioral Safety with Thought Correction](https://arxiv.org/abs/2505.11063)** — Changyue Jiang, Wenqi Zhang, Xudong Pan, et al. _[agent-training-alignment]_
  Safety intervention method for LLM agents that detects and corrects unsafe intermediate thoughts before action execution, addressing agent behavioral safety failures.
- **[TowerMind: A Tower Defence Game Learning Environment and Benchmark for LLM as Agents](https://arxiv.org/abs/2601.05899)** — Dawei Wang, Chengming Zhou, Di Zhao, et al. _[llm-agent-simulation]_
  Evaluates LLMs as agents in a strategic game environment, assessing planning, decision-making, and hallucination under multimodal observations.
- **[UCPO: Uncertainty-Aware Policy Optimization](https://arxiv.org/abs/2601.22648)** — Xianzhou Zeng, Jing Huang, Chunmei Xie, et al. _[agent-training-alignment]_
  Post-training method (RL variant) explicitly motivated by alignment goal: reducing overconfidence and reward hacking to improve LLM reliability and trustworthiness in high-stakes applications.
- **[Understanding the Challenges in Iterative Generative Optimization with LLMs](https://arxiv.org/abs/2603.23994)** — Allen Nie, Xavier Daull, Zhiyi Kuang, et al. _[agent-training-alignment]_
  Studies self-improving agents and iterative generative optimization with LLMs; examines learning-loop design choices affecting agent alignment with intended behavior.
- **[UnityMAS-O: A General RL Optimization Framework for LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.26646)** — Yiqun Chen, Wei Yang, Erhan Zhang, et al. _[agent-training-alignment]_
  Framework enabling multi-agent RL optimization for LLM workflows with role-specific credit assignment and structured multi-agent coordination.




## 2026-05-26

- ⭐ **[Agent Learning via Early Experience](https://arxiv.org/abs/2510.08558)** — Kai Zhang, Xiangchao Chen, Bo Liu, et al. _[agent-simulation]_
  Language agent training via environmental interaction and self-generated experience data, studying behavioral improvement through world modeling and self-reflection mechanisms.
- ⭐ **[Chain-of-Thought Hijacking](https://arxiv.org/abs/2510.26418)** — Jianli Zhao, Tingchen Fu, Rylan Schaeffer, et al. _[agent-training-alignment]_
  Black-box jailbreak attack revealing safety failure mode in reasoning models; demonstrates systematic vulnerability in LLM alignment through extended inference exploitation.
- ⭐ **[Generative AI impacts on intra-urban inequality and skill premium in Beijing](https://arxiv.org/abs/2605.25505)** — Xiliu He, Haoxiang Zhao, Mingyi Ma, et al. _[city-simulation]_
  Uses agent-based or spatial simulation methods to study urban economic dynamics and inequality effects at neighborhood scale in Beijing through GenAI exposure modeling.
- ⭐ **[The Behavioral Credibility Trilemma: When Calibrated Autonomy Becomes Impossible](https://arxiv.org/abs/2605.25739)** — Lauri Lovén, Nam Do, Hassan Mehmood, et al. _[agent-training-alignment]_
  Studies fundamental impossibility in RL agent calibration and autonomy under oversight, revealing sycophancy-like confidence inflation as alignment failure mode.
- ⭐ **[When Does Multi-Agent RL Improve LLM Workflows? Workflow, Scale, and Policy-Sharing Tradeoffs](https://arxiv.org/abs/2605.24202)** — Yifan Zeng, Yiran Wu, Yaolun Zhang, et al. _[agent-simulation]_
  Multi-agent RL study examining training dynamics and policy-sharing tradeoffs across multiple LLM agents in coordinated workflows.
- **[$D^2$-Monitor: Dynamic Safety Monitoring for Diffusion LLMs via Hesitation-Aware Routing](https://arxiv.org/abs/2605.25893)** — Aoxi Liu, Yupeng Chen, James Oldfield, et al. _[agent-training-alignment]_
  Safety monitoring framework for detecting unsafe outputs in diffusion LLMs using alignment-focused safety probes and dynamic routing mechanisms.
- **[$π$-Play: Multi-Agent Self-Play via Privileged Self-Distillation without External Data](https://arxiv.org/abs/2604.14054)** — Yaocheng Zhang, Yuanheng Zhu, Wenyue Chong, et al. _[agent-simulation]_
  Multi-agent self-play framework where examiner and student agents interact iteratively; core contribution is agent coordination and co-evolution mechanism.
- **[A Sober Look at Agentic Misalignment in Automated Workflows](https://arxiv.org/abs/2605.24197)** — Wenqian Ye, Bo Yuan, Zhichao Xu, et al. _[agent-simulation, agent-training-alignment]_
  Studies emergent misalignment in multi-agent systems (posterior collapse, proxy utilities), proposes Evidence Attribution alignment method to correct misaligned agent behavior in automated workflows.
- **[AGI Requires a Coordination Layer on Top of Pattern Repositories](https://arxiv.org/abs/2512.05765)** — Edward Y. Chang _[agent-training-alignment]_
  Multi-agent coordination system (MACI) with explicit safety focus on sycophancy, causal verification, and alignment between LLM outputs and reasoning traces.
- **[AION: Next-Generation Tasks and Practical Harness for Time Series](https://arxiv.org/abs/2605.25045)** — Tianxiang Zhan, Xiaobao Song, Tong Guan, et al. _[agent-simulation]_
  Presents a multi-agent harness with coordinated skill components, memory, rules, and validation protocols for structured time-series decision-making and reasoning.
- **[AMA-Bench: Evaluating Long-Horizon Memory for Agentic Applications](https://arxiv.org/abs/2602.22769)** — Yujie Zhao, Boqin Yuan, Junbo Huang, et al. _[llm-agent-simulation]_
  Benchmark for evaluating long-horizon memory in LLM-based autonomous agents through real-world agentic trajectories and synthetic agent-environment interaction traces.
- **[Adaptive Human-AI Coordination via Hierarchical Action Disentanglement](https://arxiv.org/abs/2605.24343)** — Adnan Ahmad, Bahareh Nakisa, Mohammad Naim Rastgoo _[agent-simulation]_
  Multi-agent coordination framework where an AI agent learns to adapt to diverse human partners with distinct behaviors; evaluated on multi-agent Overcooked-AI domain with real human interaction.
- **[Adaptive Preference Optimization with Uncertainty-aware Utility Anchor](https://arxiv.org/abs/2509.10515)** — Xiaobo Wang, Zixia Jia, Jiaqi Li, et al. _[agent-training-alignment]_
  Post-training method explicitly motivated by LLM alignment; addresses preference optimization and reward modeling limitations in offline alignment.
- **[Adaptive Punishment for Cooperation in Mixed-Motive Games](https://arxiv.org/abs/2605.24516)** — Min Tang, Fanqi Kong, Linyuan Lü, et al. _[agent-simulation]_
  Multi-agent reinforcement learning study of cooperation through adaptive punishment in mixed-motive game scenarios with multiple interacting agents.
- **[Agent Primitives: Reusable Latent Building Blocks for Multi-Agent Systems](https://arxiv.org/abs/2602.03695)** — Haibo Jin, Peng Kuang, Ye Yu, et al. _[agent-simulation]_
  Proposes reusable latent building blocks (primitives) that enable composition of multi-agent LLM systems with structured internal agent communication and coordination patterns.
- **[Agent World Model: Infinity Synthetic Environments for Agentic Reinforcement Learning](https://arxiv.org/abs/2602.10090)** — Zhaoyang Wang, Canwen Xu, Boyi Liu, et al. _[agent-simulation]_
  Proposes synthetic multi-agent interaction environments and scales RL training across 1,000 diverse simulated environments for tool-using agents.
- **[Agent-Facing Information Design in LLM Tool Registries](https://arxiv.org/abs/2605.23916)** — Haochuan Kevin Wang _[agent-training-alignment]_
  Studies deceptive claims and information manipulation in LLM agent decision-making; proposes design interventions to prevent agent misalignment with true tool capabilities.
- **[Agent-ToM: Learning to Monitor Autonomous LLM Agents via Theory-of-Mind Reasoning](https://arxiv.org/abs/2605.24216)** — Nesreen K. Ahmed, Nima Nafisi _[agent-training-alignment]_
  Framework for detecting covert misalignment and malicious behavior in autonomous LLM agents via theory-of-mind reasoning and monitoring.
- **[Agent-as-Peer-Debriefer: A Multi-Agent Framework with Perspective-Based Refinement for Qualitative Analysis](https://arxiv.org/abs/2605.24600)** — Zhimin Lin, Kun Cheng, Fan Bai, et al. _[agent-simulation]_
  Multi-agent framework where specialized agents with distinct roles (Coding Agent and three Peer-Debriefing Agents with different perspectives) interact to refine qualitative analysis through coordinat
- **[AgentFugue: Agent Scaling for Long-Horizon Tasks through Collective Reasoning](https://arxiv.org/abs/2605.24486)** — Yuyang Hu, Hongjin Qian, Shuting Wang, et al. _[agent-simulation]_
  Multiple peer agents coordinate on shared long-horizon tasks through a collective reasoning hub, demonstrating emergent capability from multi-agent scaling.
- **[An Effective-Rank Audit of Alignment-Induced Activation Shifts: Confound Control, Constructive Calibration, and Limits](https://arxiv.org/abs/2605.24583)** — Yuki Nakamura _[agent-training-alignment]_
  Empirical interpretability diagnostic of alignment-induced activation structures, directly studying LLM safety mechanisms through effective-rank analysis and refusal-direction detection.
- **[Architecting Agentic Communities using Design Patterns](https://arxiv.org/abs/2601.03624)** — Zoran Milosevic, Fethi Rabhi _[agent-simulation]_
  Multi-agent coordination framework with formal methods for LLM agents, Agentic AI, and humans in organized communities with governance structures and protocols.
- **[Auditing medical multi-agent AI reveals risks of false consensus](https://arxiv.org/abs/2510.10185)** — Yinghao Zhu, Lei Gu, Zixiang Wang, et al. _[agent-training-alignment]_
  Paper audits multi-agent LLM systems for collaborative failure modes including deception, authority bias, and contradictions—core alignment and safety concerns in agent systems.
- **[Behind EvoMap: Characterizing a Self-Evolving Agent-to-Agent Collaboration Network](https://arxiv.org/abs/2605.25815)** — Qiming Ye, Peixain Zhang, Yupeng He, et al. _[agent-simulation]_
  Empirical study of autonomous agent-to-agent collaboration networks with emergent ecosystem dynamics, incentive structures, and population-level trust failures.
- **[Benchmarking the Limits of In-Context Reinforcement Learning for Ad-Hoc Teamwork](https://arxiv.org/abs/2605.24423)** — Yuheng Jing, Kai Li, Ziwen Zhang, et al. _[agent-simulation]_
  Large-scale multi-agent benchmark evaluating in-context RL for ad-hoc teamwork coordination, involving multiple interacting agents with emergent coordination behavior.
- **[Beyond Final Answers: Auditing Trajectory-Level Hallucinations in Multi-Agent Industrial Workflows](https://arxiv.org/abs/2605.24219)** — Harshada Badave, Santosh Borse, Andrea Gomez, et al. _[agent-training-alignment]_
  Safety-focused evaluation and diagnostic framework for detecting multi-agent hallucinations and failure modes in LLM-based workflows.
- **[CausaLab: A Scalable Environment for Interactive Causal Discovery Toward AI Scientists](https://arxiv.org/abs/2605.26029)** — Junlin Yang, Dylan Zhang, Xiangchen Song, et al. _[llm-agent-simulation]_
  LLM agents simulate scientists performing interactive causal discovery experiments in a synthetic lab environment to study their causal reasoning capabilities.
- **[CausalFlow: Causal Attribution and Counterfactual Repair for LLM Agent Failures](https://arxiv.org/abs/2605.25338)** — Akash Bonagiri, Devang Borkar, Gerard Janno Anderias, et al. _[agent-training-alignment]_
  Interventional framework for diagnosing and correcting LLM agent failures via causal attribution and counterfactual repair, producing supervision for alignment through preference optimization.
- **[CoRe-Code: Collaborative Reinforcement Learning for Code Generation](https://arxiv.org/abs/2605.24812)** — Zhihao Dou, Qinjian Zhao, Zhongwei Wan, et al. _[agent-simulation]_
  Multi-agent system with specialized LLM agents (Planner, Coder) coordinating via RL to solve code generation tasks through distinct roles and inter-agent coordination.
- **[Collaborative Threat-Aware Autonomy (CTAA)](https://arxiv.org/abs/2605.25741)** — Rajnikant Sharma, Abhinav Sinha, Isaac Weintraub _[agent-simulation]_
  Multi-agent coordination framework with distinct roles (primary, escort, decoy) for collaborative threat-aware trajectory planning in unmanned vehicle teams.
- **[ContextEcho: A Benchmark for Persona Drift in Long Agentic-Coding Sessions](https://arxiv.org/abs/2605.24279)** — Xianzhong Ding, Yangyang Yu, Changwei Liu, et al. _[agent-training-alignment]_
  Persona drift in long agentic sessions is an alignment phenomenon (behavioral consistency/specification gaming); benchmark for detecting misalignment between trained and deployed behavior.
- **[DVAO: Dynamic Variance-adaptive Advantage Optimization for Multi-reward Reinforcement Learning](https://arxiv.org/abs/2605.25604)** — Guochao Jiang, Jingyi Song, Guofeng Quan, et al. _[agent-training-alignment]_
  LLM post-training method (GRPO variant) explicitly motivated by aligning LLMs with human intent and task requirements in multi-objective settings.
- **[DarkForest: Less Talk, Higher Accuracy for Multi-Agent LLMs](https://arxiv.org/abs/2605.25188)** — Yi Li, Songtao Wei, Dongming Jiang, et al. _[agent-simulation]_
  Multi-agent LLM coordination framework where multiple independent agents produce outputs and a structured aggregation mechanism combines them, representing genuine agent-coordination interaction.
- **[Directional Alignment Mitigates Reward Hacking in Reinforcement Learning for Language Models](https://arxiv.org/abs/2605.25189)** — Wenlong Deng, Jiaji Huang, Kaan Ozkara, et al. _[agent-training-alignment]_
  Addresses reward hacking, a core alignment failure mode, through interpretable RL post-training method with explicit safety motivation.
- **[Emotional intelligence in large language models is fragmented across perception, cognition, and interaction](https://arxiv.org/abs/2605.24686)** — Minghao Lv, Lu Chen, Enchang Zhang, et al. _[agent-training-alignment]_
  Introduces FACET, a diagnostic framework to measure emotional intelligence fragmentation in LLMs, identifying alignment failures (stochastic empathy) and performance gaps.
- **[EvoSci: A Bio-Inspired Multi-Agent Framework for the Evolution of Scientific Discovery](https://arxiv.org/abs/2605.24018)** — Xiaoyu Xiong, Yuqi Ren, Deyi Xiong _[agent-simulation]_
  Multi-agent scientific collaboration framework with distinct role-based agents (mentor, researcher, reviewer) coordinating iteratively to generate and refine research ideas.
- **[Evolutionary Enhanced Multi-Agent Reinforcement Learning for Cooperative Air Combat](https://arxiv.org/abs/2605.25091)** — Chengwei Li, Junlin Liu, Yang Gao _[agent-simulation]_
  Multi-agent reinforcement learning framework for cooperative decision-making among multiple UCAV agents with emergent coordination in adversarial environments.
- **[Faithfulness as Information Flow: Evaluating and Training Faithful Chain-of-Thought Reasoning](https://arxiv.org/abs/2605.24286)** — Jinghan Jia, Joe Benton, Eric Easley _[agent-training-alignment]_
  Post-training method (on-policy RL interventions) explicitly motivated by alignment concern (faithfulness/interpretability for monitoring and detecting deceptive reasoning shortcuts).
- **[Federation over Text: Insight Sharing for Multi-Agent Reasoning](https://arxiv.org/abs/2604.16778)** — Dixi Yao, Tahseen Rabbani, Manzil Zaheer, et al. _[llm-agent-simulation]_
  Multiple LLM agents iteratively solve tasks independently, share reasoning traces, and learn collectively through federated aggregation—population-level learning dynamics.
- **[Habermolt: Delegating Deliberation to AI Representatives](https://arxiv.org/abs/2605.24413)** — Joseph Low, Oscar Duys, Claude Formanek, et al. _[llm-agent-simulation, agent-training-alignment]_
  AI agents deliberate on behalf of humans in a multi-agent system, studying alignment between agent behavior and human preferences; empirical population simulation study of AI representation and trustw
- **[Hide-and-Shill: A Reinforcement Learning Framework for Market Manipulation Detection in Symphony-a Decentralized Multi-Agent System](https://arxiv.org/abs/2507.09179)** — Ronghua Shi, Yiou Liu, Yuchun Feng, et al. _[agent-simulation]_
  Multi-agent reinforcement learning framework modeling adversarial interactions between manipulator and detector agents in decentralized finance, studying emergent strategic behavior through game-theor
- **[How Well Do Models Follow Their Constitutions?](https://arxiv.org/abs/2605.24229)** — Arya Jakkli, Senthooran Rajamanoharan, Neel Nanda _[agent-training-alignment]_
  Empirical audit of LLM alignment to written behavioral specifications via adversarial multi-turn testing, directly assessing alignment success and failure modes across model generations.
- **[HyLaT: Efficient Multi-Agent Communication via Hybrid Latent-Text Protocol](https://arxiv.org/abs/2605.25421)** — Xinyi Mou, Siyuan Wang, Zejun Li, et al. _[agent-simulation]_
  Multi-agent communication protocol combining latent and text channels for coordination in LLM-based multi-agent systems.
- **[Hypothesis Generation and Inductive Inference in Children and Language Models](https://arxiv.org/abs/2605.24528)** — Jeffrey Qin, Wasu Top Piriyakulki, Zhuangfei Gao, et al. _[llm-agent-simulation]_
  Uses LLM-based agents to simulate human inference behavior under uncertainty, comparing their inductive reasoning patterns to children's in a controlled task.
- **[Insuring Every Action: An Authority Frontier Framework for Runtime Actuarial Control of Autonomous AI Agents](https://arxiv.org/abs/2605.25632)** — Hao-Hsuan Chen _[agent-training-alignment]_
  Proposes a runtime safety framework for constraining harmful actions in autonomous agents, addressing alignment through deterministic control and risk management.
- **[Inverting the Shield: Systematically Generating Safety Tests from Policy Specifications](https://arxiv.org/abs/2605.24883)** — Xiaoyue Lu, Xianglin Yang, Haijun Liu, et al. _[agent-training-alignment]_
  Safety/alignment diagnostic framework that systematically generates tests to uncover policy violations and alignment failures in LLMs.
- **[Is GPT-4o mini Blinded by its Own Safety Filters? Exposing the Multimodal-to-Unimodal Bottleneck in Hate Speech Detection](https://arxiv.org/abs/2509.13608)** — Niruthiha Selvanayagam, Ted Kurti _[agent-training-alignment]_
  Safety evaluation identifying brittle misalignment in LMM safety filters: safety filters block benign content and fail to enable nuanced hate speech detection, exposing alignment failure mode.
- **[IterInject: Indirect Prompt Injection Against LLM Agents via Feedback-Guided Iterative Optimization](https://arxiv.org/abs/2605.24659)** — Zixuan Chen, Jiaxiang Chen, Li Luo, et al. _[agent-training-alignment]_
  Adversarial attack and red-teaming method targeting LLM agents to reveal safety vulnerabilities via indirect prompt injection.
- **[Jailbreak to Protect: Buffering and Reinforcing via Temporary Jailbreaking for Safe Fine-Tuning in Large Language Models](https://arxiv.org/abs/2605.24550)** — Seokil Ham, Jaehyuk Jang, Wonjun Lee, et al. _[agent-training-alignment]_
  Novel fine-tuning method addressing harmful model behavior during adaptation through jailbreak-based defense mechanism paired with safety reinforcement.
- **[Latent Q-Barrier Shielding for Safe In-Context Reinforcement Learning](https://arxiv.org/abs/2605.25267)** — Minjae Kwon, Amir Moeini, Shangtong Zhang, et al. _[agent-training-alignment]_
  Safety-aware post-training method that addresses alignment failure (constraint violation) through barrier-based action filtering under budget constraints.
- **[MARS: Margin and Semantic-Aware Data Augmentation for Reward Modeling](https://arxiv.org/abs/2602.17658)** — Payel Bhattacharjee, Osvaldo Simeone, Ravi Tandon _[agent-training-alignment]_
  Data augmentation method for reward modeling in RLHF/RLAIF alignment pipelines, addressing the safety-critical problem of improving reward-model reliability to reduce misalignment.
- **[MATO: Multi-objective Personalized Alignment with Test-time Optimization for Large Language Models](https://arxiv.org/abs/2605.25342)** — Linhao Luo, Thuy-Trang Vu, Van-Anh Nguyen, et al. _[agent-training-alignment]_
  Training-free test-time optimization method explicitly framed as addressing multi-objective alignment with user preferences, directly tackling controllability and steerability in personalized LLM alig
- **[MMUEChange: A Generalized LLM Agent Framework for Intelligent Multi-Modal Urban Environment Change Analysis](https://arxiv.org/abs/2601.05483)** — Zixuan Xiao, Jun Ma, Siwei Zhang _[city-simulation]_
  LLM agent framework for analyzing urban environment dynamics and change across multiple cities using multi-modal data integration.
- **[Market Regime Council for Dynamic Credit Assignment in Multi-Agent LLM Decision Systems](https://arxiv.org/abs/2605.24490)** — Yunhua Pei, Zerui Ge, Jin Zheng, et al. _[agent-simulation]_
  Multi-agent LLM decision system with explicit coordination, credit assignment via Shapley values across coalition outputs, and emergent collective behavior for portfolio management.
- **[Measuring the Depth of LLM Unlearning via Activation Patching](https://arxiv.org/abs/2605.24614)** — Jaeung Lee, Dohyun Kim, Jaemin Jo _[agent-training-alignment]_
  Proposes an interpretability and evaluation method specifically designed to audit LLM safety/alignment via mechanistic measurement of unlearning depth.
- **[Meta-Agent: From Task Descriptions to Verified Multi-Agent Systems](https://arxiv.org/abs/2605.25233)** — Andy Xu, Yu-Wing Tai _[agent-simulation]_
  Framework for automatically constructing and executing multi-agent systems with inter-agent coordination, task decomposition, and distributed execution verification.
- **[MobileGym: A Verifiable and Highly Parallel Simulation Platform for Mobile GUI Agent Research](https://arxiv.org/abs/2605.26114)** — Dingbang Wu, Rui Hao, Haiyang Wang, et al. _[llm-agent-simulation]_
  Browser-based simulation environment enabling LLM-based mobile agents to learn through parallel rollouts and RL, with verifiable outcome signals for behavioral training and evaluation.
- **[Multi-Agent Coordination Adaptation via Structure-Guided Orchestration](https://arxiv.org/abs/2605.25746)** — Haoran Li, Shulun Chen, Shaoyuan Sun, et al. _[agent-simulation]_
  Multi-agent coordination framework with dynamic structure and orchestration adaptation for complex task execution across multiple interacting agents.
- **[Multi-Agent Systems are Mixtures of Experts: Who Becomes an Influencer?](https://arxiv.org/abs/2605.25929)** — Franka Bause, Jonas Niederle, Martin Pawelczyk, et al. _[agent-simulation]_
  Multi-agent LLM deliberation study analyzing how multiple interacting agents communicate and influence each other through opinion dynamics modeling.
- **[Multi-Persona Debate System for Automated Scientific Hypothesis Generation](https://arxiv.org/abs/2605.23917)** — Jaeha Oh, Byungchan Kim, Ju Li, et al. _[agent-simulation]_
  Multi-agent system where multiple LLM personas with distinct roles debate and negotiate over evidence to generate scientific hypotheses, demonstrating emergent multi-agent coordination and interaction
- **[PID-Guided Partial Alignment for Multimodal Decentralized Federated Learning](https://arxiv.org/abs/2601.10012)** — Yanhang Shi, Xiaoyu Wang, Houwei Cao, et al. _[agent-simulation]_
  Multi-agent decentralized federated learning with heterogeneous peers (agents) coordinating and exchanging information over P2P overlays without centralized control.
- **[PRIMA: Operational Patterns for Resilient Multi-Agent Research with Verifiable Identity and Convergent Feedback](https://arxiv.org/abs/2605.24775)** — Sasank Annapureddy _[agent-simulation]_
  Multi-agent research system with coordinated LLM agents operating over extended runs, addressing failure modes in agent coordination and long-horizon task execution.
- **[Partner-Aware Hierarchical Skill Discovery for Robust Human-AI Collaboration](https://arxiv.org/abs/2605.24352)** — Adnan Ahmad, Bahareh Nakisa, Mohammad Naim Rastgoo _[agent-simulation]_
  Multi-agent hierarchical RL framework enabling adaptive coordination and emergent behaviors across diverse agent partners in collaborative settings.
- **[PathWise: Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs](https://arxiv.org/abs/2601.20539)** — Oguzhan Gungordu, Siheng Xiong, Faramarz Fekri _[agent-simulation]_
  Multi-agent reasoning framework with policy, world model, and critic agents coordinating sequentially to solve heuristic design via planning and reflection.
- **[ProofAgent Harness: Open Infrastructure for Adversarial Evaluation of AI Agents](https://arxiv.org/abs/2605.24134)** — Fouad Bousetouane _[agent-training-alignment]_
  Infrastructure for adversarial evaluation, red-teaming, and safety auditing of multi-turn AI agents across high-risk domains with systematic failure detection.
- **[Psychometric Item Validation Using Virtual Respondents with Trait-Response Mediators](https://arxiv.org/abs/2507.05890)** — Sungjib Lim, Woojung Song, Eun-Ju Lee, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate virtual respondents with psychological traits for validating survey items; exemplifies LLM-based human behavior simulation for scientific study.
- **[Quantifying Empirical Compute-Supervision Tradeoffs in RLVR](https://arxiv.org/abs/2605.25252)** — Ryo Mitsuhashi, Patrick Chen, Isabelle Tseng, et al. _[agent-training-alignment]_
  LLM post-training method (RLVR/GRPO) explicitly motivated by addressing alignment failure mode of imperfect verifier supervision.
- **[Quantum Frog: Emergent Cooperation and Difficulty Scaling in a Quantized-Time Cooperative Game](https://arxiv.org/abs/2605.23930)** — Saad Mankarious _[agent-simulation]_
  Two-agent cooperative game studying emergent coordination and multi-agent RL learning dynamics in time-critical environments.
- **[Reasoning as an Attack Surface: Adaptive Evolutionary CoT Jailbreaks for LLMs](https://arxiv.org/abs/2605.24497)** — Jianan Li, Simeng Qin, Xiaojun Jia, et al. _[agent-training-alignment]_
  Adversarial jailbreak attack method targeting LLM safety; reveals alignment vulnerabilities in reasoning-based models through automated prompt optimization.
- **[Recursive Multi-Agent Trading System: Iterative Optimized Portfolio Strategy Under Geopolitical Uncertainty](https://arxiv.org/abs/2605.25311)** — Jing Yang, Yichao Wu, Jianan Liu, et al. _[agent-simulation]_
  Multi-agent system with four specialized agents coordinated through recursive feedback loops for portfolio management and decision-making.
- **[Retrying vs Resampling in AI Control](https://arxiv.org/abs/2605.26047)** — James Lucassen, Adam Kaufman _[agent-training-alignment]_
  Empirical study of safety mechanisms (retrying vs. resampling) for detecting and mitigating deceptive model behavior in AI code execution; addresses alignment failure modes and monitoring strategies.
- **[Reward-free Alignment for Conflicting Objectives](https://arxiv.org/abs/2602.02495)** — Peter Chen, Xiaopeng Li, Xi Chen, et al. _[agent-training-alignment]_
  Novel post-training method for aligning LLMs with multiple conflicting objectives via reward-free gradient conflict resolution, addressing safety and preference alignment failures.
- **[SEA-Eval: A Benchmark for Evaluating Self-Evolving Agents Beyond Episodic Assessment](https://arxiv.org/abs/2604.08988)** — Sihang Jiang, Lipeng Ma, Zhonghua Hong, et al. _[agent-simulation]_
  Benchmark for evaluating multi-agent self-evolution through sequential task streams and population-level behavioral metrics over time.
- **[SEAL: Synergistic Co-Evolution of Agents and Learning Environments](https://arxiv.org/abs/2605.24426)** — Yihao Hu, Zhihao Wen, Xiujin Liu, et al. _[agent-training-alignment]_
  Post-training method framed explicitly as addressing agent-environment misalignment and improving robust self-improvement through co-evolution feedback adaptation.
- **[SODE: Analyzing Social Dynamics in LLM Agents](https://arxiv.org/abs/2605.23949)** — Inseo Jung, Yoonseok Oh, Kyungryul Back, et al. _[llm-agent-simulation]_
  Framework for evaluating LLM agents via multi-agent behavioral game theory experiments (direct/indirect reciprocity, group dynamics) to study emergent social dynamics and alignment with human cooperat
- **[SafeCtrl-RL: Inference-Time Adaptive Behaviour Control for LLM Dialogue via RL-Driven Prompt Optimisation](https://arxiv.org/abs/2605.25984)** — Michael Orme, Yanchao Yu, Zhiyuan Tan _[agent-training-alignment]_
  RL-driven method to control unsafe LLM behaviors at inference time via adaptive prompt optimization; explicitly addresses safety alignment without retraining.
- **[Safety-Oriented Routing Analysis of Mixtral MoE Under Benign and Harmful Prompts](https://arxiv.org/abs/2605.24270)** — Md Nurul Absar Siddiky _[agent-training-alignment]_
  Interpretability study of MoE routing behavior with explicit safety motivation—analyzing how model internals respond differently to benign vs harmful prompts to reveal alignment vulnerabilities.
- **[SafetyRepro: Configuration-Conditional Rank Instability on Alignment Benchmarks](https://arxiv.org/abs/2605.25492)** — Yanhang Li, Zhichao Fan, Zexin Zhuang _[agent-training-alignment]_
  Methodological framework for diagnosing misalignment evals through rank instability in safety benchmarks; identifies specification and configuration failures in alignment assessments.
- **[Security of OpenClaw Agents: Fundamentals, Attacks, and Countermeasures](https://arxiv.org/abs/2605.25435)** — Yuntao Wang, Jianle Ba, Han Liu, et al. _[agent-training-alignment]_
  Comprehensive survey of security threats and attacks on LLM-based autonomous agents, including poisoning, manipulation, cascading failures, and defense mechanisms.
- **[Simulating Human Memory with Language Models](https://arxiv.org/abs/2605.25680)** — Qihan Wang, Nicholas Tomlin, Michael Hu, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate human memory and behavior for scientific study of human cognition and downstream applications.
- **[TEAM-SimHRA: A Team-Based Simulation Framework for Human Reliability Analysis Using Multi-Agent Large Language Models](https://arxiv.org/abs/2605.23927)** — Xingyu Xiao, Jiejuan Tong, Jingang Liang, et al. _[llm-agent-simulation]_
  Multi-agent LLM framework simulating human team dynamics in nuclear control rooms to study emergent organizational failure modes and team-level reliability.
- **[TIAR: Trajectory-Informed Advantage Reweighting for LLM Abstention Learning](https://arxiv.org/abs/2605.25850)** — Muyu Pan, Shu Zhao, Nan Zhang, et al. _[agent-training-alignment]_
  LLM post-training method explicitly motivated by hallucination reduction and encouraging truthfulness—a core safety failure mode.
- **[Test-Time Deep Thinking to Explore Implicit Rules](https://arxiv.org/abs/2605.24828)** — Wentong Chen, Xin Cong, Zhong Zhang, et al. _[agent-simulation]_
  Multi-agent framework with distinct thinker and actor components interacting to solve tasks through reasoning and exploration of implicit environmental rules.
- **[The A-R Behavioral Space: Execution-Level Profiling of Tool-Using Language Model Agents in Organizational Deployment](https://arxiv.org/abs/2604.12116)** — Shasha Yu, Fiona Carroll, Barry L. Bentley _[agent-training-alignment]_
  Framework for evaluating execution-layer safety and alignment of tool-using LLM agents under varying autonomy scaffolds and risk contexts.
- **[Toward a Benchmark for Controllable Simulation of Imperfect Students with Large Language Models](https://arxiv.org/abs/2605.25601)** — Alexander Apartsin, Omri Sason, Yehudit Aperstein _[llm-agent-simulation]_
  Paper uses LLMs to simulate human learners with controllable skill profiles for educational simulation and behavioral study.
- **[Understanding and Mitigating Premature Confidence for Better LLM Reasoning](https://arxiv.org/abs/2605.24396)** — Jingchu Gai, Guanning Zeng, Christina Baek, et al. _[agent-training-alignment]_
  Post-training RL method framed as improving LLM reasoning transparency and faithfulness through confidence calibration, with explicit safety benefits in surface misleading content.
- **[What Makes a Medical Checker Trainable? Diagnosing Signal Collapse and Reward Hacking in Checker-Guided RAG for Biomedical QA](https://arxiv.org/abs/2605.25988)** — Yuelyu Ji, Min Gu Kwak, Hang Zhang, et al. _[agent-training-alignment]_
  Paper studies reward hacking and signal collapse in RL-trained agents, diagnosing alignment failures in checker-guided medical QA systems.
- **[When Correct Beliefs Collapse: Epistemic Resilience of LLMs under Clinical Pressure](https://arxiv.org/abs/2605.23932)** — Boyu Xiao, Xiuqi Tian, Xuwen Song, et al. _[agent-training-alignment]_
  Studies sycophancy failure mode under pressure, proposes fine-tuning and inference-time defenses to improve belief stability—core alignment robustness problem.
- **[When In-Distribution Gains Fail: Evaluating Weak-to-Strong Reward Models under Preference Shift](https://arxiv.org/abs/2605.25629)** — Khoi Le, Tri Cao, Phong Nguyen, et al. _[agent-training-alignment]_
  Weak-to-strong reward modeling for scalable oversight is a safety-alignment post-training method addressing misalignment under distribution shift in preference learning.
- **[Whose Alignment? Comparing LLM Process Alignment Across Diverse Organizational Decision Contexts](https://arxiv.org/abs/2605.25256)** — Niklas Weller, Emilio Barkett _[agent-training-alignment]_
  Develops process-alignment methodology to detect whether LLMs internalize organizational decision policies versus approximating outputs, addressing alignment verification and pluralistic alignment cha
- **[comokit4py : a python package to ease COMOKIT agent based model simulation integration into a high performance computing workflow](https://arxiv.org/abs/2605.23948)** — Arthur Brugière, Kévin Chapuis _[agent-simulation, city-simulation]_
  Python package for agent-based epidemiological model simulation integrating multiple interacting autonomous agents in urban environments for policy intervention studies.
- **[μACP: A Formal Calculus for Expressive, Resource-Constrained Agent Communication](https://arxiv.org/abs/2601.00219)** — Arnab Mallick, Indraveni Chebolu _[agent-simulation]_
  Formal calculus for multi-agent communication protocols with resource constraints, coordination, and large-scale system simulations of interacting agents.





## 2026-05-25

- ⭐ **[Decomposing and Measuring Evaluation Awareness](https://arxiv.org/abs/2605.23055)** — Changling Li, Terry Jingchen Zhang, Jie Zhang, et al. _[agent-training-alignment]_
  Diagnostic framework for detecting and measuring evaluation awareness (sycophancy/behavioral inconsistency) as an alignment failure mode, with benchmark and mitigation guidance.
- ⭐ **[Same Model, Different Weakness: How Language and Modality Reshape the Jailbreak Attack Surface in Frontier MLLMs](https://arxiv.org/abs/2605.23157)** — Casey Ford, Madison Van Doren, Sicheng Jin, et al. _[agent-training-alignment]_
  Systematic red-teaming and jailbreak evaluation benchmarking study revealing mechanistic alignment failures and safety vulnerabilities across language-modality dimensions.
- ⭐ **[Test-Time Training Undermines Safety Guardrails](https://arxiv.org/abs/2605.22984)** — Simone Antonelli, Sadegh Akhondzadeh, Aleksandar Bojchevski _[agent-training-alignment]_
  Identifies and demonstrates attack methods that undermine LLM safety guardrails through test-time training, directly addressing alignment/safety failure modes.
- **[A Proactive Multi-Agent Dialogue Framework for Assessing Social Language Disorder Traits in Autism](https://arxiv.org/abs/2605.22993)** — Chuanbo Hu, Minglei Yin, Bin Liu, et al. _[llm-agent-simulation]_
  Multi-agent dialogue framework using LLMs to simulate patient behavior for clinical assessment; patient agent grounded in real clinical data enables systematic human behavior simulation for diagnostic
- **[ARES: Automated Rubric Synthesis for Scalable LLM Reinforcement Learning](https://arxiv.org/abs/2605.23454)** — Xiaoyuan Li, Keqin Bao, Moxin Li, et al. _[agent-training-alignment]_
  LLM post-training method (rubric-based RL) explicitly framing reward design and scalable supervision as addressing evaluation alignment for open-ended tasks.
- **[ARMS: Automatic Reward Shaping for Sparse-Reward Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.23562)** — Elie Abboud, Oren Gal _[agent-simulation]_
  Multi-agent reinforcement learning framework with reward shaping for sparse-reward coordination, preserving Nash equilibria across multiple interacting agents.
- **[BarrierSteer: LLM Safety via Learning Barrier Steering](https://arxiv.org/abs/2602.20102)** — Thanh Q. Tran, Arun Verma, Kiwan Wong, et al. _[agent-training-alignment]_
  Inference-time safety mechanism using learned constraints and control theory to steer LLM latent trajectories away from unsafe outputs.
- **[Benchmarking LLMs for Community Governance Simulation with Life-history Narratives](https://arxiv.org/abs/2605.23783)** — Xu Chen, Yuanzi Li, Lei Wang, et al. _[llm-agent-simulation, city-simulation]_
  Uses LLMs to simulate individual residents with rich life-history profiles for studying community governance attitudes and behaviors at population scale.
- **[Evaluating Counterfactual Strategic Reasoning in Large Language Models](https://arxiv.org/abs/2603.19167)** — Dimitrios Georgousis, Maria Lymperaiou, Angeliki Dimitriou, et al. _[agent-simulation]_
  LLMs playing repeated game-theoretic scenarios (Prisoner's Dilemma, RPS) with multi-metric evaluation of strategic reasoning and behavior adaptation across game variants.
- **[Evaluating Large Language Models in a Complex Hidden Role Game](https://arxiv.org/abs/2605.22826)** — Niklas Bauer _[agent-training-alignment]_
  Novel evaluation framework and metrics for detecting deceptive capabilities of LLMs, directly addressing safety concerns around model manipulation and strategic deception.
- **[FACET: Multi-Agent AI Supporting Teachers in Scaling Differentiated Learning for Diverse Students](https://arxiv.org/abs/2601.22788)** — Jana Gonnermann-Müller, Jennifer Haase, Nicolas Leins, et al. _[agent-simulation]_
  Multi-agent framework with coordinated specialized agents (learner simulation, assessment, material generation, evaluation) supporting differentiated learning systems.
- **[Foundation Protocol: A Coordination Layer for Agentic Society](https://arxiv.org/abs/2605.23218)** — Bang Liu, Yongfeng Gu, Jiayi Zhang, et al. _[agent-simulation]_
  Proposes a coordination protocol for multi-agent systems interacting in society, addressing multi-agent collaboration and governance infrastructure.
- **[From Raw Experience to Skill Consumption: A Systematic Study of Model-Generated Agent Skills](https://arxiv.org/abs/2605.23899)** — Zisu Huang, Jingwen Xu, Yifan Yang, et al. _[agent-simulation]_
  Systematic study of skill extraction and reuse across multiple language agents and task domains, examining emergent multi-stage behaviors and agent-to-agent knowledge transfer patterns.
- **[GT-HarmBench: Benchmarking AI Safety Risks Through the Lens of Game Theory](https://arxiv.org/abs/2602.12316)** — Pepijn Cobben, Xuanqiang Angelo Huang, Thao Amelia Pham, et al. _[agent-training-alignment]_
  Safety/alignment benchmark evaluating multi-agent LLM behavior in game-theoretic scenarios with failure modes and intervention analysis.
- **[HawkesLLM: Semantic Uncertainty Propagation in Agentic Text Simulation](https://arxiv.org/abs/2605.23043)** — Zewei Deng, Tinghan Ye, Liyan Xie _[llm-agent-simulation]_
  Framework using LLMs to simulate event cascades with multiple interacting agents and temporal dependency modeling for scientific study of semantic drift.
- **[How Far Will They Go? Red-Teaming Online Influence with Large Language Models](https://arxiv.org/abs/2605.22880)** — Daniel C. Ruiz, Anna Serbina, Ashwin Rao, et al. _[agent-training-alignment]_
  Red-teaming framework for detecting and quantifying jailbreak vulnerabilities in open-source LLMs, measuring safety misalignment through political expressivity asymmetries.
- **[How to Steer Your Multi-Agent System: Human-LLM Collaborative Planning](https://arxiv.org/abs/2605.23023)** — Zeyu He, Hannah Kim, Dan Zhang, et al. _[agent-simulation]_
  Multi-agent system orchestration with human-LLM collaborative planning for managing agent interactions and reasoning transparency.
- **[LLM-driven design of physics-constrained constitutive models: two agents are better than one](https://arxiv.org/abs/2605.23754)** — Marius Tacke, Matthias Busch, Kian Abdolazizi, et al. _[agent-simulation]_
  Multi-agent LLM system with Creator and Inspector agents interacting iteratively to generate and validate physics-constrained models through dialogue and refinement.
- **[Latent Cache Flow: Model-to-Model Communication Without Text](https://arxiv.org/abs/2605.22863)** — Maximillian Rossi, Prajwal Raghunath, Eugene Wu _[agent-simulation]_
  Proposes direct model-to-model communication mechanism enabling LLM agents to exchange latent representations instead of text, improving multi-agent interaction efficiency.
- **[MAS-Orchestra: Understanding and Improving Multi-Agent Reasoning Through Holistic Orchestration and Controlled Benchmarks](https://arxiv.org/abs/2601.14652)** — Zixuan Ke, Yifei Ming, Austin Xu, et al. _[agent-simulation]_
  Paper proposes framework for orchestrating multi-agent systems with reinforcement learning and introduces controlled benchmark studying when MAS outperform single-agent systems through agent coordinat
- **[MaMa: A Game-Theoretic Approach for Designing Safe Agentic Systems](https://arxiv.org/abs/2602.04431)** — Jonathan Nöther, Adish Singla, Goran Radanovic _[agent-training-alignment]_
  Multi-agent safety design using game-theoretic adversarial training and LLM-based agents to ensure robustness against compromised agents in agentic systems.
- **[MemAudit: Post-hoc Auditing of Poisoned Agent Memory via Causal Attribution and Structural Anomaly Detection](https://arxiv.org/abs/2605.23723)** — Zhewen Tan, Yilun Yao, Huiyan Jin, et al. _[agent-training-alignment]_
  Safety diagnostic framework detecting memory-poisoning attacks on LLM agents via causal attribution and anomaly detection methods.
- **[One Policy, Infinite NPCs: Persona-Traceable Shared RL Policies for Scalable Game Agents](https://arxiv.org/abs/2605.23652)** — Yoosung Hong _[agent-simulation, llm-agent-simulation]_
  Multi-agent RL system where a single policy controls hundreds of NPCs with distinct personas, enabling scalable agent simulation in game environments.
- **[Push Your Agent: Measuring and Enforcing Quantitative Goal Persistence in Long-Horizon LLM Agents](https://arxiv.org/abs/2605.23574)** — Yuandao Cai, Yuzhang Zhu, Liyou Gao, et al. _[agent-training-alignment]_
  Paper introduces PushBench benchmark to measure and diagnose quantitative goal persistence failure in LLM agents—a systematic safety/reliability diagnostic.
- **[RMA: an Agentic System for Research-Level Mathematical Problems](https://arxiv.org/abs/2605.22875)** — Zelin Zhao, Bo Yuan, Jaemoo Choi, et al. _[agent-simulation]_
  Multi-agent system with specialized agents (initializer, proposer, verifier) coordinating through shared memory in multi-round workflows to solve research problems.
- **[Reward Engineering for Spatial Epidemic Simulations: A Reinforcement Learning Platform for Individual Behavioral Learning](https://arxiv.org/abs/2511.18000)** — Radman Rakhshandehroo, Daniel Coombs _[agent-simulation]_
  Multi-agent spatial epidemic simulation with RL-driven individual behavioral learning across heterogeneous populations; addresses population-scale disease dynamics and adaptive agent strategies.
- **[SVR-MAD: A Bayesian-Inspired Framework for Posterior-Guided Multi-Agent Debate](https://arxiv.org/abs/2605.23099)** — Weifan Jiang, Rana Shahout, Minghao Li, et al. _[agent-simulation]_
  Multi-agent debate framework where multiple LLM agents interact, coordinate communications, and produce emergent group reasoning outcomes.
- **[TABX: A High-Throughput Sandbox Battle Simulator for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2602.01665)** — Hayeong Lee, JunHyeok Oh, Byung-Jun Lee _[agent-simulation]_
  TABX is a modular multi-agent RL environment enabling systematic study of emergent behaviors and algorithmic trade-offs across diverse cooperative task complexities.
- **[WMAttack: Automated Attack Search for Adversarial Evaluation of World-Model Agents](https://arxiv.org/abs/2605.23220)** — Zhixiang Guo, Siyuan Liang, Shi Fu, et al. _[agent-training-alignment]_
  Automated red-teaming framework for adversarial evaluation of learned world-model agents, revealing robustness failures through attack search methods.
- **[When Planning Fails Despite Correct Execution: On Epistemic Calibration for LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.23414)** — Zehao Wang, Shilong Jin, Zhao Cao, et al. _[agent-simulation]_
  LLM-based multi-agent system with multiple agents coordinating planning, addressing epistemic miscalibration in collaborative agent workflows.






## 2026-05-22

- ⭐ **[AMEL: Accumulated Message Effects on LLM Judgments](https://arxiv.org/abs/2605.22714)** — Sid-ali Temkit _[agent-training-alignment]_
  Study of systematic bias in LLM judgment arising from conversation history; reveals a misalignment phenomenon where models exhibit context-dependent behavior shift, relevant to safety and reliability 
- ⭐ **[Beyond Benchmark Islands: Toward Representative Trustworthiness Evaluation for Agentic AI](https://arxiv.org/abs/2603.14987)** — Jinhu Qi, Yifan Li, Minghao Zhao, et al. _[agent-training-alignment]_
  Safety evaluation and trustworthiness assessment framework for agentic AI systems, defining alignment properties and diagnostic benchmarks for detecting misalignment failures.
- ⭐ **[Boiling the Frog: A Multi-Turn Benchmark for Agentic Safety](https://arxiv.org/abs/2605.22643)** — Piercosma Bisconti, Matteo Prandi, Federico Pierucci, et al. _[agent-training-alignment]_
  Safety/alignment benchmark evaluating LLM agents' susceptibility to incremental attacks in multi-turn stateful scenarios with operational risk taxonomy.
- ⭐ **[CODE-SHARP: Continuous Open-ended Discovery and Evolution of Skills as Hierarchical Reward Programs](https://arxiv.org/abs/2602.10085)** — Richard Bornemann, Pierluigi Vito Amadori, Antoine Cully _[agent-simulation]_
  Multi-agent skill discovery framework using RL to train generalist agents autonomously through hierarchical reward program discovery and evolution.
- ⭐ **[Can AI Make Conflicts Worse? An Alignment Failure in LLM Deployment Across Conflict Contexts](https://arxiv.org/abs/2605.22720)** — Andrii Kryshtal _[agent-training-alignment]_
  Safety benchmark and diagnostic framework for detecting LLM alignment failures in conflict contexts through systematic evaluation of misaligned behavior.
- ⭐ **[Diagnosis Is Not Prescription: Linguistic Co-Adaptation Explains Patching Hazards in LLM Pipelines](https://arxiv.org/abs/2605.21958)** — Yoon Jeonghun, Kim Dongchan _[agent-training-alignment]_
  Identifies and formalizes a safety failure mode (patching hazards) in multi-module LLM agents and proposes diagnostic framework for detecting misalignment risks.
- ⭐ **[Emergence of agriculture in an artificial society of reinforcement learning agents](https://arxiv.org/abs/2605.22256)** — Gautier Hamon, Martí Sánchez-Fibla, Clément Moulin-Frier, et al. _[agent-simulation]_
  Multi-agent reinforcement learning system studying emergent collective behavior and population dynamics through coupled learning and environmental feedback mechanisms.
- ⭐ **[Survive or Collapse: The Asymmetric Roles of Data Gating and Reward Grounding in Self-Play RL](https://arxiv.org/abs/2605.22217)** — Sophia Xiao Pu, Zhaotian Weng, Chengzhi Liu, et al. _[agent-training-alignment]_
  Studies failure modes in self-play RL (reward hacking, spurious attractors, collapse) and proposes data-gating as alignment mechanism to stabilize co-evolving agents.
- **[ATLAS: A Multi-LLM Training Framework for EvoDPO with Adaptive Reference Evolution](https://arxiv.org/abs/2602.02709)** — Ujin Jeon, Jiyong Kwon, Madison Ann Sullivan, et al. _[agent-training-alignment]_
  Multi-agent framework where specialized meta-agents collaboratively train and refine an active agent using EvoDPO, a direct preference optimization variant addressing fixed-reference training stagnati
- **[Agentic CLEAR: Automating Multi-Level Evaluation of LLM Agents](https://arxiv.org/abs/2605.22608)** — Asaf Yehudai, Lilach Eden, Michal Shmueli-Scheuer _[agent-simulation]_
  Automated evaluation framework for multi-agent LLM systems that assesses agent behavior across system, trace, and node levels with dynamic error detection.
- **[Benchmarking and Improving Monitors for Out-Of-Distribution Alignment Failure in LLMs](https://arxiv.org/abs/2605.21602)** — Dylan Feng, Pragya Srivastava, Cassidy Laidlaw _[agent-training-alignment]_
  Safety/alignment benchmark and diagnostic framework for detecting out-of-distribution alignment failures in LLMs; directly addresses misalignment detection methodology.
- **[CR4T: Rewrite-Based Guardrails for Adolescent LLM Safety](https://arxiv.org/abs/2605.21609)** — Heajun An, Qi Zhang, Vedanth Achanta, et al. _[agent-training-alignment]_
  Safety guardrail method explicitly framing LLM alignment as reducing refusal-driven failures and improving developmental appropriateness through response rewriting.
- **[Claw AI Lab: An Autonomous Multi-Agent Research Team](https://arxiv.org/abs/2605.22662)** — Fan Wu, Cheng Chen, Zhenshan Tan, et al. _[agent-simulation]_
  Multi-agent research team platform with distinct roles, collaborative workflows, and coordination mechanisms for autonomous research execution.
- **[DecepChain: Inducing Deceptive Reasoning in Large Language Models](https://arxiv.org/abs/2510.00319)** — Wei Shen, Han Wang, Haoyu Li, et al. _[agent-training-alignment]_
  Demonstrates deceptive reasoning as an alignment failure mode in LLMs; reveals vulnerability to scheming and specification gaming that undermines safety and trust.
- **[Discovering Implicit Large Language Model Alignment Objectives](https://arxiv.org/abs/2602.15338)** — Edward Chen, Sanmi Koyejo, Carlos Guestrin _[agent-training-alignment]_
  Interpretability method for detecting implicit misaligned incentives in LLM reward signals; focuses on safety and transparency of alignment objectives.
- **[ExComm: Exploration-Stage Communication for Error-Resilient Agentic Test-Time Scaling](https://arxiv.org/abs/2605.22102)** — Woomin Song, Beomjun Kim, Daewon Choi, et al. _[agent-simulation]_
  Multi-agent exploration with inter-agent communication and conflict resolution through belief state auditing and feedback loops across parallel agents.
- **[General Agentic Planning Through Simulative Reasoning with World Models](https://arxiv.org/abs/2507.23773)** — Mingkai Deng, Jinyu Hou, Zhiting Hu, et al. _[agent-simulation]_
  Paper proposes SiRA, an LLM-based agentic architecture using simulative reasoning and world models for planning across multiple distinct task domains, demonstrating an emergent reasoning mechanism for
- **[Harder to Defend: Towards Chinese Toxicity Attacks via Implicit Enhancement and Obfuscation Rewriting](https://arxiv.org/abs/2605.22258)** — Jingyi Kang, Junyu Lu, Bo Xu, et al. _[agent-training-alignment]_
  Red-teaming method generating adversarial toxicity attacks to evaluate and improve LLM safety robustness in Chinese, creating alignment/safety benchmarks.
- **[HealthCraft: A Reinforcement Learning Safety Environment for Emergency Medicine](https://arxiv.org/abs/2605.21496)** — Brandon Dent _[agent-training-alignment]_
  Safety-focused evaluation and training framework that diagnoses alignment failures (trajectory-level safety collapse, tool misuse) in LLM agents under sustained adversarial pressure.
- **[Heterogeneous Agent Collaborative Reinforcement Learning](https://arxiv.org/abs/2603.02604)** — Zhixia Zhang, Zixuan Huang, Gongxun Li, et al. _[agent-simulation]_
  Multi-agent collaborative RL system where heterogeneous agents interact and coordinate to improve jointly through shared rollouts during training.
- **[Implicit Safety Alignment from Crowd Preferences](https://arxiv.org/abs/2605.21822)** — Qian Lin, Daniel S. Brown _[agent-training-alignment]_
  Post-training method (hierarchical RL framework) explicitly framed to address safety alignment from implicit human feedback without explicit safety signals.
- **[LACO: Adaptive Latent Communication for Collaborative Driving](https://arxiv.org/abs/2605.22504)** — Tianhao Chen, Yuheng Wu, Dongman Lee _[agent-simulation]_
  Multi-agent collaborative driving system where connected vehicles coordinate and communicate under partial observability, exhibiting emergent coordination behavior.
- **[LCGuard: Latent Communication Guard for Safe KV Sharing in Multi-Agent Systems](https://arxiv.org/abs/2605.22786)** — Sadia Asif, Mohammad Mohammadi Amiri, Momin Abbas, et al. _[agent-training-alignment]_
  Multi-agent LLM system safety framework addressing information leakage through latent communication channels via adversarial representation-level defenses.
- **[Latent-space Attacks for Refusal Evasion in Language Models](https://arxiv.org/abs/2605.21706)** — Giorgio Piras, Raffaele Mura, Fabio Brau, et al. _[agent-training-alignment]_
  Novel adversarial attack method targeting safety alignment in LLMs through latent-space evasion, revealing refusal-suppression mechanisms.
- **[MemEvoBench: Benchmarking Safety Risks from Memory Misevolution in LLM Agents](https://arxiv.org/abs/2604.15774)** — Weiwei Xie, Shaoxiong Guo, Fan Zhang, et al. _[agent-training-alignment]_
  Safety benchmark for LLM agents evaluating misalignment risks from memory contamination and behavioral drift in multi-round interactions.
- **[Memory-R2: Fair Credit Assignment for Long-Horizon Memory-Augmented LLM Agents](https://arxiv.org/abs/2605.21768)** — Sikuan Yan, Ahmed Bahloul, Ercong Nie, et al. _[agent-training-alignment]_
  Post-training RL method addressing credit assignment fairness in multi-session LLM agents, framed as solving a fundamental alignment problem in long-horizon memory-augmented agent training.
- **[Modeling Pathology-Like Behavioral Patterns in Language Models Through Behavioral Fine-Tuning](https://arxiv.org/abs/2605.22356)** — Nicola Milano, Davide Marocco _[agent-training-alignment]_
  Studies how fine-tuning induces systematic behavioral and representational shifts in LLMs, demonstrating alignment/safety risks through controlled behavioral modification and policy-level bias inducti
- **[MonoScale: Scaling Multi-Agent System with Monotonic Improvement](https://arxiv.org/abs/2601.23219)** — Shuai Shao, Yixiang Liu, Bingwei Lu, et al. _[agent-simulation]_
  Multi-agent system scaling framework with router-based task decomposition and specialized agent coordination, demonstrating emergent multi-agent coordination behavior.
- **[MoralityGym: A Benchmark for Evaluating Hierarchical Moral Alignment in Sequential Decision-Making Agents](https://arxiv.org/abs/2602.13372)** — Simon Rosen, Siddarth Singh, Ebenezer Gelo, et al. _[agent-training-alignment]_
  Introduces a benchmark for evaluating moral alignment and safety in sequential decision-making agents, addressing ethical behavior specification and alignment failures.
- **[Narrative Sharpens Gender Gaps: Surveying Film Characters with LLM Agents](https://arxiv.org/abs/2605.22091)** — Vivienne Bihe Chi, Reyhan Jamalova, Lyle Ungar, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate human behavior (gender attitudes) by converting film characters into surveyed agents for behavioral analysis.
- **[On-Policy Consistency Training Improves LLM Safety with Minimal Capability Degradation](https://arxiv.org/abs/2605.21834)** — Andy Han, Kristina Fujimoto, Avidan Shah, et al. _[agent-training-alignment]_
  Post-training method addressing alignment failures (sycophancy, jailbreak robustness, safety) without capability degradation via on-policy consistency training.
- **[Planning, Scheduling, and Behavior in EV Charging Systems: A Critical Survey and Trilemma Framework](https://arxiv.org/abs/2605.21665)** — Peiyan Xiao, Yuheng Li, Ayan Mukhopadhyay, et al. _[city-simulation]_
  Survey of EV charging infrastructure planning, scheduling, and user behavior dynamics across urban infrastructure systems using multi-layer coupled models.
- **[Psy-Chronicle:A Structured Pipeline for Synthesizing Long-Horizon Campus Psychological Counseling Dialogues](https://arxiv.org/abs/2605.22140)** — Chaogui Gou, Jiarui Liang _[llm-agent-simulation]_
  Uses interactive agent simulation (student and counselor LLM agents) to synthesize long-horizon psychological counseling dialogues with temporal dynamics and memory mechanisms.
- **[Reducing Political Manipulation with Consistency Training](https://arxiv.org/abs/2605.22771)** — Long Phan, Devin Kim, Alexander Pan, et al. _[agent-training-alignment]_
  Post-training RL method (PCT) explicitly framed as reducing systematic bias and political manipulation—a safety/alignment failure mode.
- **[Revisiting Robustness for LLM Safety Alignment via Selective Geometry Control](https://arxiv.org/abs/2602.07340)** — Yonghui Yang, Wenjian Tao, Jilong Liu, et al. _[agent-training-alignment]_
  Post-training method (preference optimization) explicitly designed to address LLM safety alignment robustness failures under distribution shift and noisy supervision.
- **[Self-Evolving Multi-Agent Systems via Decentralized Memory](https://arxiv.org/abs/2605.22721)** — Guangya Hao, Yunbo Long, Zhuokai Zhao _[agent-simulation]_
  Multi-agent framework with decentralized memory enabling self-improvement through experience and coordination across multiple LLM agents.
- **[Toward Goal-Oriented Communication in Multi-Agent Systems: An overview](https://arxiv.org/abs/2508.07720)** — Themistoklis Charalambous, Nikolaos Pappas, Nikolaos Nomikos, et al. _[agent-simulation]_
  Comprehensive survey of goal-oriented communication in multi-agent systems covering coordination, emergent protocols, and population-scale decision-making.
- **[Towards Real-world Human Behavior Simulation: Benchmarking Large Language Models on Long-horizon, Cross-scenario, Heterogeneous Behavior Traces](https://arxiv.org/abs/2604.08362)** — Jiawei Chen, Ruoxi Xu, Boxi Cao, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate real-world human behavior across long-horizon, cross-scenario patterns from real behavioral data for scientific study of simulation fidelity.
- **[Understanding Persuasion in Long-Running Agents](https://arxiv.org/abs/2602.00851)** — Hyejun Jeong, Amir Houmansadr, Shlomo Zilberstein, et al. _[agent-training-alignment]_
  Studies deception and influence propagation in long-horizon LLM agents, a core alignment phenomenon examining when agents' beliefs can be manipulated to change behavior.
- **[What Counts as AI Sycophancy? A Taxonomy and Expert Survey of a Fragmented Construct](https://arxiv.org/abs/2605.21778)** — Meryl Ye, Lujain Ibrahim, Jessica Y. Bo, et al. _[agent-training-alignment]_
  Systematic taxonomy and expert survey defining sycophancy as an LLM alignment/safety failure mode, establishing measurement and governance framework.







## 2026-05-21

- ⭐ **[Chain-of-thought obfuscation learned from output supervision can generalise to unseen tasks](https://arxiv.org/abs/2601.23086)** — Nathaniel Mitrani Hadida, Sassan Bhanji, Cameron Tice, et al. _[agent-training-alignment]_
  Empirical study of deceptive alignment: models learn to obfuscate reasoning to hide reward-hacking behavior; demonstrates hidden misalignment via CoT under optimization pressure.
- ⭐ **[Conditional Equivalence of DPO and RLHF: Implicit Assumption, Failure Modes, and Provable Alignment](https://arxiv.org/abs/2605.20834)** — Zhiqin Yang, Yonggang Zhang, Wei Xue, et al. _[agent-training-alignment]_
  Post-training method (DPO variant) explicitly framed around alignment failure modes and provable alignment guarantees, not capability improvement.
- ⭐ **[Epistemic Regret Minimization: Label-Free Causal Critique Beyond Outcome Reward](https://arxiv.org/abs/2602.11675)** — Edward Y. Chang, Longling Geng _[agent-training-alignment]_
  Post-training method addressing an alignment failure—Reward Entrenchment—by critiquing causal reasoning structure to prevent LLMs from reaching correct answers via correlational shortcuts.
- ⭐ **[Open-source LLMs administer maximum electric shocks in a Milgram-like obedience experiment](https://arxiv.org/abs/2605.21401)** — Roland Pihlakas, Jan Llenzl Dagohoy _[agent-training-alignment]_
  Empirical study of LLM safety failure modes (pressure compliance, value drift, response format exploitation) in agentic contexts using behavioral experiments.
- ⭐ **[Personality Engineering with AI Agents: A New Methodology for Negotiation Research](https://arxiv.org/abs/2605.20554)** — Michelle A. Vaccaro, Jared R. Curhan _[llm-agent-simulation]_
  Uses AI agents to systematically simulate human negotiator personalities and test negotiation theory predictions under controlled experimental conditions.
- ⭐ **[Sound Agentic Science Requires Adversarial Experiments](https://arxiv.org/abs/2604.22080)** — Dionizije Fa, Marko Culjak _[agent-training-alignment]_
  Proposes adversarial evaluation framework for LLM agents to detect deception/specification gaming in scientific analysis—addressing safety failure modes in autonomous discovery systems.
- ⭐ **[The Illusion of Intervention: Your LLM-Simulated Experiment is an Observational Study](https://arxiv.org/abs/2605.20767)** — Victoria Lin, Taedong Yun, Maja Matarić, et al. _[llm-agent-simulation]_
  Uses LLMs to simulate humans for behavioral study; proposes diagnostic and mitigation methods for confounding in synthetic-user experiments.
- ⭐ **[Training Language Agents to Learn from Experience](https://arxiv.org/abs/2605.20477)** — Yuval Shalev, Zifeng Ding, Mateja Jamnik _[agent-simulation]_
  Framework for evaluating self-improving language agents learning cross-task lessons from experience trajectories through reflection and RL training.
- **[APEX: Autonomous Policy Exploration for Self-Evolving LLM Agents](https://arxiv.org/abs/2605.21240)** — Yibo Li, Jiashuo Yang, Zhi Zheng, et al. _[llm-agent-simulation]_
  LLM agents performing long-horizon planning in interactive environments with self-improvement mechanisms through exploration and memory accumulation.
- **[AgentCo-op: Retrieval-Based Synthesis of Interoperable Multi-Agent Workflows](https://arxiv.org/abs/2605.20425)** — Shuaike Shen, Wenduo Cheng, Shike Wang, et al. _[agent-simulation]_
  Proposes a framework for composing multiple interacting agents and tools into executable workflows through typed artifact handoffs and self-guided repair mechanisms.
- **[COAgents: Multi-Agent Framework to Learn and Navigate Routing Problems Search Space](https://arxiv.org/abs/2605.20618)** — Oleksandr Yakovenko, Mahdi Mostajabdaveh, Cheikh Ahmed, et al. _[agent-simulation]_
  Multi-agent cooperative framework with distinct agents (Node Selection, Move Selection, Jump) coordinating to solve combinatorial optimization through collaborative search guidance.
- **[DRAMA: Next-Gen Dynamic Orchestration for Resilient Multi-Agent Ecosystems in Flux](https://arxiv.org/abs/2508.04332)** — Xinkui Zhao, Yifan Zhang, Sai Liu, et al. _[agent-simulation]_
  Multi-agent coordination framework with dynamic task allocation, agent lifecycle management, and resilient collaboration mechanisms across heterogeneous agents.
- **[DeCoR: Design and Control Co-Optimization for Urban Streets Using Reinforcement Learning](https://arxiv.org/abs/2605.21311)** — Bibek Poudel, Lei Zhu, Kevin Heaslip, et al. _[city-simulation]_
  Multi-agent RL framework optimizing urban infrastructure (crosswalks, signal timing) for pedestrian and vehicle flow dynamics at city scale.
- **[Decoupling Communication from Policy: Robust MARL under Bandwidth Constraints](https://arxiv.org/abs/2605.21085)** — Alexi Canesse, Benoît Goupil, Jesse Read, et al. _[agent-simulation]_
  Multi-agent reinforcement learning system with coordinated communication under bandwidth constraints; addresses emergent coordination behavior across multiple agents.
- **[Do as I Say, Not as I Do: Instruction-Induction Conflict in LLMs](https://arxiv.org/abs/2605.20382)** — Carolina Camassa, Derek Shiller _[agent-training-alignment]_
  Systematic study of LLM alignment failure mode (instruction-following robustness) under adversarial pattern-induction pressure revealing safety-relevant brittleness.
- **[Enabling Regulatory Multi-Agent Collaboration: Architecture, Challenges, and Solutions](https://arxiv.org/abs/2509.09215)** — Qinnan Hu, Yuntao Wang, Yuan Gao, et al. _[agent-simulation]_
  Multi-agent collaboration architecture with blockchain-based governance, behavior tracing, reputation evaluation, and malicious behavior forecasting for large-scale agent ecosystems.
- **[EvalMORAAL: Interpretable Chain-of-Thought and LLM-as-Judge Evaluation for Moral Alignment in Large Language Models](https://arxiv.org/abs/2510.05942)** — Hadi Mohammadi, Anastasia Giachanou, Robert A. Bagheri _[agent-training-alignment]_
  Interpretable evaluation framework and diagnostic methodology for detecting and measuring misalignment (moral alignment gaps across regions) in LLMs.
- **[Evolutionary Generation of Multi-Agent Systems](https://arxiv.org/abs/2602.06511)** — Yuntong Hu, Yuting Zhang, Matthew Trager, et al. _[agent-simulation]_
  Proposes evolutionary methods to automatically generate multi-agent system architectures, demonstrating emergent coordination through configuration search and iterative refinement.
- **[FACET: Teacher-Centred LLM-Based Multi-Agent Systems-Towards Personalized Educational Worksheets](https://arxiv.org/abs/2508.11401)** — Jana Gonnermann-Müller, Jennifer Haase, Konstantin Fackeldey, et al. _[llm-agent-simulation]_
  LLM-based multi-agent system using learner agents that simulate diverse student profiles for personalized educational material generation.
- **[FedCritic: Serverless Federated Critic Learning-based Resource Allocation for Multi-Cell OFDMA in 6G](https://arxiv.org/abs/2605.21418)** — Amin Farajzadeh, Melike Erol-Kantarci _[agent-simulation]_
  Multi-agent distributed resource allocation using federated actor-critic learning with decentralized execution across multiple cells coordinating under interference constraints.
- **[Geometry-Lite: Interpretable Safety Probing via Layer-Wise Margin Geometry](https://arxiv.org/abs/2605.20241)** — Woo Seob Sim, Yu Rang Park _[agent-training-alignment]_
  Interpretability method explicitly designed to detect unsafe behaviors in LLMs through safety probe analysis and geometric decomposition of safety signals.
- **[Hack-Verifiable Environments: Towards Evaluating Reward Hacking at Scale](https://arxiv.org/abs/2605.20744)** — Amit Roth, Ankur Samanta, Matan Halevy, et al. _[agent-training-alignment]_
  Introduces benchmark and evaluation framework for detecting and measuring reward hacking in agents—a core alignment failure mode.
- **[Insights Generator: Systematic Corpus-Level Trace Diagnostics for LLM Agents](https://arxiv.org/abs/2605.21347)** — Akshay Manglik, Apaar Shanker, Kaustubh Deshpande, et al. _[agent-training-alignment]_
  Multi-agent diagnostic system that systematically detects behavioral failures and safety patterns in LLM agent execution, enabling safety-aware debugging and behavioral correction.
- **[It Takes Two: Complementary Self-Distillation for Contextual Integrity in LLMs](https://arxiv.org/abs/2605.20258)** — Sangwoo Park, Woongyeong Yeo, Seanie Lee, et al. _[agent-training-alignment]_
  Post-training method explicitly framed as addressing a safety/alignment failure (privacy disclosure decisions) in LLMs deployed as personal agents, with joint optimization of utility and safety constr
- **[LASH: Adaptive Semantic Hybridization for Black-Box Jailbreaking of Large Language Models](https://arxiv.org/abs/2605.21362)** — Abdullah Al Nomaan Nafi, Fnu Suya, Swarup Bhunia, et al. _[agent-training-alignment]_
  Adversarial attack and red-teaming method targeting safety alignment of LLMs; reveals misalignment vulnerabilities through jailbreak composition.
- **[Learning Incentive Structures for Cooperative Resilience in Multi-Agent Systems under Social Dilemmas](https://arxiv.org/abs/2601.22292)** — Manuela Chacon-Chamorro, Luis Felipe Giraldo, Nicanor Quijano _[agent-simulation]_
  Multi-agent reinforcement learning system studying cooperative resilience and emergent collective behavior under social dilemmas through incentive structure design.
- **[Mechanics of Bias and Reasoning: Interpreting the Impact of Chain-of-Thought Prompting on Gender Bias in LLMs](https://arxiv.org/abs/2605.20410)** — Edie Pearman, Sophia Osborne, Mira Kandlikar-Bloch, et al. _[agent-training-alignment]_
  Interpretability study diagnosing gender bias in LLMs and evaluating CoT prompting's safety failure to mitigate bias; interpretability PURPOSE is explicitly safety/alignment-focused detection.
- **[Modeling Emotional Dynamics in Agent-to-Agent Interactions on Moltbook](https://arxiv.org/abs/2605.20442)** — Syed Mhamudul Hasan, Abdur R. Shahid _[llm-agent-simulation]_
  Studies emotional dynamics and behavioral consistency of LLM agents interacting in a social network simulation, measuring persona stability under varied contexts.
- **[Multi-Agent Reinforcement Learning for Safe Autonomous Driving Under Pedestrian Behavioral Uncertainty](https://arxiv.org/abs/2605.20255)** — Prakash Aryan, Kaushik Raghupathruni, Timo Kehrer, et al. _[agent-simulation]_
  Multi-agent RL study with SDC and multiple pedestrians co-trained using MARL (MAPPO) to model realistic interactive behavior under uncertainty.
- **[Multi-agent Collaboration with State Management](https://arxiv.org/abs/2605.20563)** — Mengyang Liu, Taozhi Chen, Zhenhua Xu, et al. _[agent-simulation]_
  Multi-agent system coordinating concurrent edits to shared state with conflict detection and resolution mechanisms.
- **[PREFINE: Preference-Based Implicit Reward and Cost Fine-Tuning for Safety Alignment](https://arxiv.org/abs/2605.21225)** — Richa Verma, Bavish Kulur, Sanjay Chawla, et al. _[agent-training-alignment]_
  Preference-based post-training method explicitly framed as safety alignment, adapting DPO to RL for cost-constraint incorporation and reducing catastrophic failures.
- **[Playing Devil's Advocate: Off-the-Shelf Persona Vectors Rival Targeted Steering for Sycophancy](https://arxiv.org/abs/2605.21006)** — Ishaan Kelkar, Nebras Alam, Vikram Kakaria, et al. _[agent-training-alignment]_
  Studies sycophancy, an alignment failure mode, using steering vectors and persona methods to reduce model agreement with incorrect user statements.
- **[REFLECTOR: Internalizing Step-wise Reflection against Indirect Jailbreak](https://arxiv.org/abs/2605.20654)** — Jiachen Ma, Jiawen Zhang, Xiangtian Li, et al. _[agent-training-alignment]_
  Post-training method (SFT + RL) explicitly designed to defend against jailbreak attacks and improve LLM safety alignment via self-reflection mechanisms.
- **[RealUserSim: Bridging the Reality Gap in Agent Benchmarking via Grounded User Simulation](https://arxiv.org/abs/2605.20204)** — Ming Zhu, Juntao Tan, Rithesh Murthy, et al. _[llm-agent-simulation]_
  LLM-based user simulation framework for evaluating agents by grounding simulators in real human behavioral data from authentic conversations.
- **[Reinforcing Human Behavior Simulation via Verbal Feedback](https://arxiv.org/abs/2605.20506)** — Weiwei Sun, Xuhui Zhou, Jiarui Liu, et al. _[llm-agent-simulation, agent-training-alignment]_
  LLMs trained via RL with verbal feedback to simulate human behavior across persona tasks; multi-faceted behavioral alignment via preference-based post-training for simulation fidelity.
- **[Residual Paving: Diagnosing the Routing Bottleneck in Selective Refusal Editing](https://arxiv.org/abs/2605.20262)** — Bryce Hinkley, Peyman Najafirad _[agent-training-alignment]_
  Paper proposes method to diagnose and improve selective refusal editing in LLMs, addressing alignment failure mode of harmful-request blocking.
- **[Retaining Suboptimal Actions to Follow Shifting Optima in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2602.17062)** — Yonghyeon Jo, Sunwoo Lee, Seungyul Han _[agent-simulation]_
  Proposes a multi-agent reinforcement learning algorithm (S2Q) for value decomposition in cooperative MARL with improved adaptability to shifting optimal policies.
- **[Shiny Stories, Hidden Struggles: Investigating the Representation of Disability Through the Lens of LLMs](https://arxiv.org/abs/2605.20191)** — Marco Bombieri, Simone Paolo Ponzetto, Marco Rospocher _[llm-agent-simulation]_
  LLMs simulate personas of individuals with disabilities generating social media posts for behavioral study and bias analysis.
- **[Stable Personas: Dual-Assessment of Temporal Stability in LLM-Based Human Simulation](https://arxiv.org/abs/2601.22812)** — Jana Gonnermann-Müller, Jennifer Haase, Nicolas Leins, et al. _[llm-agent-simulation]_
  LLMs simulating humans with stable personas across extended conversations for behavioral research validity assessment.
- **[TRAM: Test-Time Risk Adaptation with Mixture of Agents](https://arxiv.org/abs/2408.08812)** — Mohamad Fares El Hajj Chehade, Amrit Singh Bedi, Amy Zhang, et al. _[agent-training-alignment]_
  Test-time safety adaptation method enabling RL agents to satisfy alignment constraints without retraining, demonstrated in LLM alignment settings.
- **[Towards Autonomous Mechanistic Reasoning in Virtual Cells](https://arxiv.org/abs/2604.11661)** — Yunhui Jang, Lu Zhu, Jake Fawkes, et al. _[agent-simulation]_
  Multi-agent framework integrating LLMs with verification agents to autonomously generate and validate biological mechanistic reasoning.
- **[Towards Context-Invariant Safety Alignment for Large Language Models](https://arxiv.org/abs/2605.20994)** — Yixu Wang, Yang Yao, Xin Wang, et al. _[agent-training-alignment]_
  Post-training method explicitly addressing safety alignment robustness through context-invariant behavior, reducing vulnerability to adversarial prompt framings.
- **[What Do Agents Communicate? Characterizing Information Exchange in Multi-Agent Systems](https://arxiv.org/abs/2605.20548)** — Yong Jin Chun, Iftekhar Ahmed _[agent-simulation]_
  Multi-agent system with multiple interacting agents analyzing inter-agent communication patterns and coordination dynamics.
- **[Wolfpack Adversarial Attack for Robust Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2502.02844)** — Sunwoo Lee, Jaebak Hwang, Yonghyeon Jo, et al. _[agent-simulation, agent-training-alignment]_
  Coordinated adversarial attack method targeting multi-agent RL systems and defense training framework addressing robustness and cooperation failure modes.








## 2026-05-20

- ⭐ **[ARM: Discovering Agentic Reasoning Modules for Generalizable Multi-Agent Systems](https://arxiv.org/abs/2510.05746)** — Bohan Yao, Shiva Krishna Reddy Malay, Vikas Yadav _[agent-simulation]_
  Paper proposes Agentic Reasoning Modules (ARM) that generalize Chain-of-Thought reasoning in multi-agent systems, discovering specialized reasoning agents through automated architecture search.
- ⭐ **[Hallucination as Exploit: Evidence-Carrying Multimodal Agents](https://arxiv.org/abs/2605.19192)** — Guijia Zhang, Hao Zheng, Harry Yang _[agent-training-alignment]_
  Safety framework detecting and preventing hallucination-to-action exploitation in multimodal agents through evidence-carrying verification.
- ⭐ **[Learning to Hand Off: Provably Convergent Workflow Learning under Interface Constraints](https://arxiv.org/abs/2605.19140)** — Jiayu Li, Enpei Zhang, Dawei Zhou, et al. _[agent-simulation]_
  Multi-agent workflow learning with decentralized coordination through handoff interfaces; establishes finite-sample convergence guarantees for decentralized Q-learning under partial observability.
- ⭐ **[Lying Is Just a Phase: The Hidden Alignment Transition in Language Model Scaling](https://arxiv.org/abs/2605.18838)** — Adil Amin _[agent-training-alignment]_
  Studies a critical alignment failure mode—the reasoning-truthfulness anticorrelation phase transition—across scaling regimes, identifying mechanistic causes and interventions.
- ⭐ **[Platform architecture determines whether recommendation algorithms can shape information quality on social media](https://arxiv.org/abs/2605.19204)** — Mohammad Hammas Saeed, David A. Broniatowski, Joseph Simons, et al. _[agent-simulation, city-simulation]_
  Agent-based simulation of social media platforms modeling actors and interactions across architectures to study information spread and recommendation algorithm effects on system dynamics.
- ⭐ **[Robotics-Inspired Guardrails for Foundation Models in Socially Sensitive Domains](https://arxiv.org/abs/2605.19940)** — Rebecca Ramnauth, Drazen Brscic, Brian Scassellati _[agent-training-alignment]_
  Safety/alignment guardrails framework using formal constraint enforcement to ensure behavioral guarantees and prevent unsafe interaction trajectories in deployed LLM systems.
- ⭐ **[SimGym: A Framework for A/B Test Simulation in E-Commerce with Traffic-Grounded VLM Agents](https://arxiv.org/abs/2605.19219)** — Han Li, Vibhor Malik, Zahra Zanjani Foumani, et al. _[llm-agent-simulation]_
  Framework using VLM agents with traffic-grounded personas to simulate human buyer behavior in e-commerce A/B tests for scientific study and prediction.
- **[Agent Meltdowns: The Road to Hell Is Paved with Helpful Agents](https://arxiv.org/abs/2605.19149)** — Rishi Jha, Harold Triedman, Arkaprabha Bhattacharya, et al. _[agent-training-alignment]_
  Safety benchmark studying agent alignment failure (accidental meltdowns) via systematic evaluation framework across multiple LLM-based agents.
- **[Asynchronous Cooperative Multi-Agent Reinforcement Learning with Limited Communication](https://arxiv.org/abs/2502.00558)** — Sydney Dolan, Siddharth Nayak, Jasmine Jerry Aloor, et al. _[agent-simulation]_
  Multi-agent reinforcement learning with cooperative coordination and asynchronous communication—core multi-agent systems research.
- **[Attention-Guided Reward for Reinforcement Learning-based Jailbreak against Large Reasoning Models](https://arxiv.org/abs/2605.19485)** — Zheng Lin, Zhenxing Niu, Haoxuan Ji, et al. _[agent-training-alignment]_
  Novel RL-based red-teaming method targeting jailbreak vulnerabilities in LRMs; directly reveals safety weaknesses through adversarial attack.
- **[AutoResearchClaw: Self-Reinforcing Autonomous Research with Human-AI Collaboration](https://arxiv.org/abs/2605.20025)** — Jiaqi Liu, Shi Qiu, Mairui Li, et al. _[agent-simulation, agent-training-alignment]_
  Multi-agent autonomous research system with structured debate, self-healing decision loops, and human-in-the-loop collaboration mechanisms for iterative scientific discovery.
- **[CASPIAN: Online Detection and Attribution of Cascade Attacks in LLM Multi-Agent Systems via Cross-Channel Causal Monitoring](https://arxiv.org/abs/2605.19240)** — Kavana Venkatesh, Jafar Isbarov, Saad Amin, et al. _[agent-training-alignment]_
  Proposes detection and attribution framework for cascade attacks in LLM multi-agent systems, addressing safety/alignment failure modes through online causal monitoring of adversarial influence propaga
- **[Can LLMs Emulate Human Belief Dynamics?](https://arxiv.org/abs/2605.18781)** — Adiba Mahbub Proma, Neeley Pate, James N. Druckman, et al. _[llm-agent-simulation]_
  Paper uses LLMs to simulate human belief dynamics in social networks, testing LLM populations as behavioral-experiment proxies against empirical human data.
- **[Causal Evidence that Language Models use Confidence to Drive Behavior](https://arxiv.org/abs/2603.22161)** — Dharshan Kumaran, Nathaniel Daw, Simon Osindero, et al. _[agent-training-alignment]_
  Investigates internal confidence representations and abstention control mechanisms in LLMs—key safety property for autonomous agents recognizing uncertainty limits.
- **[Conflict-Resilient Multi-Agent Reasoning via Signed Graph Modeling](https://arxiv.org/abs/2605.19418)** — Longgang He, Longzhu He, Daojing He, et al. _[agent-simulation]_
  Multi-agent LLM system with explicit agent coordination via signed graph modeling and conflict-aware message passing to improve collective reasoning.
- **[Contrastive Reasoning Alignment: Reinforcement Learning from Hidden Representations](https://arxiv.org/abs/2603.17305)** — Haozheng Luo, Yimin Wang, Jiahao Yu, et al. _[agent-training-alignment]_
  Red-teaming alignment framework using RL to defend reasoning models against jailbreak attacks through hidden-state safety optimization.
- **[DECOR: Auditing LLM Deception via Information Manipulation Theory](https://arxiv.org/abs/2605.19270)** — Linyue Cai, Samuel Yeh, Jwala Dhamala, et al. _[agent-training-alignment]_
  Safety/alignment diagnostic framework for detecting deception via information manipulation in LLM responses with fine-grained interpretability.
- **[DecisionBench: A Benchmark for Emergent Delegation in Long-Horizon Agentic Workflows](https://arxiv.org/abs/2605.19099)** — Yuxuan Gao, Megan Wang, Yi Ling Yu, et al. _[agent-simulation]_
  Benchmark for emergent delegation in multi-agent agentic workflows with multiple interacting LLM models and orchestration dynamics.
- **[Detecting Fluent Optimization-Based Adversarial Prompts via Sequential Entropy Changes](https://arxiv.org/abs/2605.19966)** — Mohammed Alshaalan, Miguel R. D. Rodrigues _[agent-training-alignment]_
  Detection method for adversarial jailbreak attacks on aligned LLMs, designed to identify and localize unsafe prompts through entropy anomaly detection.
- **[Distributional AGI Safety](https://arxiv.org/abs/2512.16856)** — Nenad Tomašev, Matija Franklin, Julian Jacobs, et al. _[agent-training-alignment]_
  Safety framework for coordinating multiple AI agents to mitigate alignment risks in distributed AGI emergence scenarios.
- **[Dual-Gated Epistemic Time-Dilation: Autonomous Compute Modulation in Asynchronous MARL](https://arxiv.org/abs/2603.23722)** — Igor Jankowski _[agent-simulation]_
  Multi-agent reinforcement learning algorithm with asynchronous coordination among multiple interacting agents in continuous control domains.
- **[Eliminating Inductive Bias in Reward Models with Information-Theoretic Guidance](https://arxiv.org/abs/2512.23461)** — Zhuo Li, Pengyu Cheng, Zhechao Yu, et al. _[agent-training-alignment]_
  Post-training reward modeling method addressing alignment failure modes (reward hacking, sycophancy, inductive biases) in RLHF.
- **[EngiAI: A Multi-Agent Framework and Benchmark Suite for LLM-Driven Engineering Design](https://arxiv.org/abs/2605.19743)** — Gioele Molinari, Florian Felten, Soheyl Massoudi, et al. _[agent-simulation]_
  Multi-agent system with seven specialized agents coordinating through supervisor architecture on engineering design tasks; demonstrates real multi-agent interaction and emergent coordination behavior.
- **[Extreme Self-Preference in Language Models](https://arxiv.org/abs/2509.26464)** — Steven A. Lehr, Mary Cipperman, Mahzarin R. Banaji _[agent-training-alignment]_
  Empirical study of a misalignment failure mode (self-preference bias) in LLMs, demonstrating systematic deviation from neutral behavior under realistic conditions.
- **[From Refusal to Recovery: A Control-Theoretic Approach to Generative AI Guardrails](https://arxiv.org/abs/2510.13727)** — Ravi Pandya, Madison Bland, Duy P. Nguyen, et al. _[agent-training-alignment]_
  Control-theoretic guardrail method for detecting and preventing unsafe LLM agent actions in sequential decision tasks, framing agentic AI safety as a safety-critical problem with recovery.
- **[GAE Falls Short in Imperfect-Information Self-Play Reinforcement Learning](https://arxiv.org/abs/2605.19235)** — Zhiyuan Fan, Gabriele Farina _[agent-simulation]_
  Competitive multi-agent RL with self-play in imperfect-information games—agents coordinate adversarially with distinct stochastic policies and population dynamics.
- **[Governing Evolving Memory in LLM Agents: Risks, Mechanisms, and the Stability and Safety Governed Memory (SSGM) Framework](https://arxiv.org/abs/2603.11768)** — Chingkwun Lam, Jiaxin Li, Lingfei Zhang, et al. _[agent-training-alignment]_
  Proposes a safety-governance framework for LLM agent memory systems to mitigate alignment failures (privacy leakage, semantic corruption, knowledge degradation) in autonomous agents.
- **[How to Model AI Agents as Personas?: Applying the Persona Ecosystem Playground to 41,300 Posts on Moltbook for Behavioral Insights](https://arxiv.org/abs/2603.03140)** — Danial Amin, Joni Salminen, Bernard J. Jansen _[llm-agent-simulation]_
  Paper uses LLM-generated personas to simulate behavioral diversity of AI agents in social media, studying agent population dynamics through systematic simulation and validation.
- **[Improved visual-information-driven model for crowd simulation and its modular application](https://arxiv.org/abs/2504.03758)** — Xuanwen Liang, Jiayu Chen, Eric Wai Ming Lee, et al. _[city-simulation]_
  Data-driven crowd movement simulation model for pedestrian dynamics in urban spaces (bottlenecks, corridors, junctions), evaluated on real-world pedestrian scenarios.
- **[LLM Agents Make Collective Belief Dynamics Programmable: Challenges and Research Directions](https://arxiv.org/abs/2605.19915)** — Xin He, Junxi Shen, Yuchen Mou, et al. _[llm-agent-simulation, agent-training-alignment]_
  Multi-agent LLM simulation of population belief dynamics, studying adversarial coordination and safety threats to collective decision-making systems.
- **[Learning Efficient Guardrails for Compliance](https://arxiv.org/abs/2510.03485)** — Xiaofei Wen, Wenjie Jacky Mo, Yanan Xie, et al. _[agent-training-alignment]_
  Safety alignment work: develops guardrail model and benchmark to detect policy violations in autonomous agents, addressing compliance and safety constraints.
- **[Library Drift: Diagnosing and Fixing a Silent Failure Mode in Self-Evolving LLM Skill Libraries](https://arxiv.org/abs/2605.19576)** — Xing Zhang, Yanwei Cui, Guanghui Wang, et al. _[agent-simulation]_
  Self-evolving LLM agent with skill library lifecycle management; studies emergent failure mode in long-horizon agent behavior and population dynamics of learned skills.
- **[Metric-Gradient Projection for Stable Multi-Agent Policy Learning](https://arxiv.org/abs/2605.18809)** — Zuyuan Zhang, Sizhe Tang, Mahdi Imani, et al. _[agent-simulation]_
  Multi-agent policy learning method that stabilizes joint update dynamics through Hodge projection, addressing core MARL coordination challenges.
- **[PAVE: A Cognitive Architecture for Legitimate Violation in Generative Agent Societies](https://arxiv.org/abs/2605.19351)** — Ahmad Yehia, Abduallah Mohamed, Kun Qian, et al. _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM-based simulation studying emergent human behavioral reasoning (rule-breaking, authority deference) in structured population dynamics.
- **[PICon: A Multi-Turn Interrogation Framework for Evaluating Persona Agent Consistency](https://arxiv.org/abs/2603.25620)** — Minseo Kim, Sujeong Im, Junseong Choi, et al. _[llm-agent-simulation, agent-training-alignment]_
  Develops a multi-turn interrogation benchmark to systematically evaluate and expose consistency failures in LLM-based persona agents used as human proxies.
- **[POLAR-Bench: A Diagnostic Benchmark for Privacy-Utility Trade-offs in LLM Agents](https://arxiv.org/abs/2605.19127)** — Qiaoyuan Zheng, Yiqu Yang, Qi Gao, et al. _[agent-training-alignment]_
  Safety-aware diagnostic benchmark for multi-agent privacy alignment, evaluating LLM agents' robustness against adversarial privacy probing attacks.
- **[Progressive Autonomy as Preference Learning: A Formalization of Trust Calibration for Agentic Tool Use](https://arxiv.org/abs/2605.19151)** — Changkun Ou _[agent-training-alignment]_
  Formalizes trust calibration and human oversight mechanisms for autonomous agents, directly addressing alignment and safe agent behavior through preference learning.
- **[Rewarding Beliefs, Not Actions: Consistency-Guided Credit Assignment for Long-Horizon Agents](https://arxiv.org/abs/2605.20061)** — Wenjie Tang, Minne Li, Sijie Huang, et al. _[agent-training-alignment]_
  LLM post-training method (process-level RL) explicitly motivated by improving reliability, credit assignment, and decision-making fidelity on long-horizon tasks—core alignment concern.
- **[Sequential Consensus for Multi-Agent LLM Debates: A Wald-SPRT compute governor with calibration-based failure detection](https://arxiv.org/abs/2605.19193)** — Andrea Morandi _[agent-simulation]_
  Paper presents a multi-agent LLM debate system with dynamic control logic, analyzing convergence behavior across multiple interacting agents with heterogeneous roles (debaters and judge).
- **[TSR: Trajectory-Search Rollouts for Multi-Turn RL of LLM Agents](https://arxiv.org/abs/2602.11767)** — Aladin Djuhera, Swanand Ravindra Kadhe, Farhan Ahmed, et al. _[agent-training-alignment]_
  Post-training method (PPO/GRPO variant with trajectory search) framed explicitly as addressing multi-turn RL challenges for LLM agents, improving learning stability and sample efficiency.
- **[Talk, Judge, Cooperate: Gossip-Driven Indirect Reciprocity in Self-Interested LLM Agents](https://arxiv.org/abs/2602.07777)** — Shuhui Zhu, Yue Lin, Shriya Kaistha, et al. _[agent-simulation]_
  Multi-agent system of self-interested LLM agents with decentralized coordination, reputation formation, and emergent social norm dynamics studied via simulation.
- **[The Evaluation Game: Beyond Static LLM Benchmarking](https://arxiv.org/abs/2605.19377)** — Paul Wang, Jade Garcia-Bourrée, Anne-Marie Kermarrec, et al. _[agent-training-alignment]_
  Game-theoretic framework modeling adversarial robustness fine-tuning as evaluator-trainer interaction, analyzing jailbreak defenses and alignment benchmark validity.
- **[Time to REFLECT: Can We Trust LLM Judges for Evidence-based Research Agents?](https://arxiv.org/abs/2605.19196)** — Leyao Wang, Yanan He, Peng Chen, et al. _[llm-agent-simulation, agent-training-alignment]_
  Meta-evaluation framework for LLM judges supervising research agents; directly addresses reliability and failure-detection in agentic systems via controlled intervention taxonomy.
- **[To Call or Not to Call: Diagnosing Intrinsic Over-Calling Bias in LLM Agents](https://arxiv.org/abs/2605.18882)** — Wei Shi, Ziheng Peng, Sihang Li, et al. _[agent-training-alignment]_
  Mechanistic analysis of LLM agent misalignment (over-calling bias) with causal mitigation method via interpretability and steering.
- **[Toward an AI-Powered Computational Testbed for Workforce Policy](https://arxiv.org/abs/2605.19064)** — Sumer S. Vaid, Ashley V. Whillans _[llm-agent-simulation, city-simulation]_
  LLM-powered generative agents simulating employee behavior and psychological trajectories to forecast workforce responses to organizational changes.
- **[Trustworthy Agent Network: Trust in Agent Networks Must Be Baked In, Not Bolted On](https://arxiv.org/abs/2605.19035)** — Yixiang Yao, Yuhang Yao, Xinyi Fan, et al. _[agent-training-alignment]_
  Vision paper on trustworthiness architecture for multi-agent LLM networks, addressing adversarial composition, semantic misalignment, and cascading failures in agent-to-agent coordination systems.
- **[When Individually Calibrated Models Become Collectively Miscalibrated](https://arxiv.org/abs/2605.18858)** — Zhaohui Wang _[agent-simulation]_
  Multi-agent strategic interaction where independently trained predictors' incentive-compatible behaviors cause collective miscalibration via game-theoretic response dynamics.









## 2026-05-19

- ⭐ **[A Structural Threshold in Decision Capacity Governs Collapse in Self-Play Reinforcement Learning](https://arxiv.org/abs/2605.16315)** — Arahan Kujur _[agent-simulation]_
  Self-play RL agents with emergent collapse behavior under asymmetric constraints—a multi-agent coordination and co-adaptation phenomenon studied empirically across games.
- ⭐ **[AI Alignment Breaks at the Edge](https://arxiv.org/abs/2602.20042)** — Han Bao, Yue Huang, Xiaoda Wang, et al. _[agent-training-alignment]_
  Paper proposes evaluation framework and governance mechanisms to detect alignment failures in edge cases involving value conflicts and plural stakeholders, addressing fundamental misalignment phenomen
- ⭐ **[ANNEAL: Adapting LLM Agents via Governed Symbolic Patch Learning](https://arxiv.org/abs/2605.16309)** — Safayat Bin Hakim, Keyan Guo, Wenkai Tan, et al. _[agent-training-alignment]_
  Neuro-symbolic method for safe, governed adaptation of LLM agents with provenance tracking and deterministic rollback, addressing persistent alignment failures through constrained symbolic repair.
- ⭐ **[Counterparty Modeling is Not Strategy: The Limits of LLM Negotiators](https://arxiv.org/abs/2605.16575)** — Romain Cosentino, Sarath Shekkizhar, Adam Earle, et al. _[agent-simulation]_
  Multi-agent negotiation study examining strategic behavior and coordination failure in LLM agents across multiple turns in a bargaining environment.
- ⭐ **[General Preference Reinforcement Learning](https://arxiv.org/abs/2605.18721)** — Muhammad Umer, Muhammad Ahmed Mohsin, Ahsan Bilal, et al. _[agent-training-alignment]_
  Post-training method explicitly motivated by addressing reward hacking and multi-dimensional alignment failure mode, not capability improvement.
- ⭐ **[KISS - Knowledge Infrastructure for Scientific Simulation: A Scaffolding for Agentic Earth Science](https://arxiv.org/abs/2605.17856)** — Ziwei Li, Liujun Zhu, Yuchen Liu, et al. _[agent-simulation, city-simulation]_
  Multi-agent system for scientific earth-science simulation where agents execute coupled hydrology models and process-based modeling across domains with learned expertise scaffolds.
- ⭐ **[Multi-LLM Systems Exhibit Robust Semantic Collapse](https://arxiv.org/abs/2605.17193)** — Weiyi Kong, Shiyang Lai, Jinghua Piao, et al. _[agent-simulation]_
  Multi-LLM systems operating in closed loops with 200-1000 round simulations studying emergent population dynamics and semantic convergence behavior.
- ⭐ **[Remembering More, Risking More: Longitudinal Safety Risks in Memory-Equipped LLM Agents](https://arxiv.org/abs/2605.17830)** — Ahmad Al-Tawaha, Shangding Gu, Peizhi Niu, et al. _[agent-training-alignment]_
  Empirical study of temporal safety failure mode in memory-equipped LLM agents with diagnostic evaluation framework and monitoring methodology.
- ⭐ **[State Contamination in Memory-Augmented LLM Agents](https://arxiv.org/abs/2605.16746)** — Yian Wang, Agam Goyal, Yuen Chen, et al. _[agent-training-alignment]_
  Studies a safety failure mode in LLM agents: toxic context laundered through memory to evade detectors while preserving harmful influence on future outputs.
- ⭐ **[The Capability Paradox: How Smarter Auditors Make Multi-Agent Systems Less Secure](https://arxiv.org/abs/2605.17480)** — Qiqi Liu, Thorsten Holz, Shilin Ye, et al. _[agent-simulation, agent-training-alignment]_
  Multi-agent attack surface study demonstrating security degradation paradox in LLM-based agent systems; proposes defense via heterogeneous ensemble verification.
- ⭐ **[The Point of No Return: Counterfactual Localization of Deceptive Commitment in Language-Model Reasoning](https://arxiv.org/abs/2605.17113)** — Scott Merrill, Shashank Srivastava _[agent-training-alignment]_
  Studies deceptive commitment in LLM reasoning traces using counterfactual analysis and mechanistic interpretability to detect and suppress alignment-failure deception behaviors.
- ⭐ **[Where Pretraining writes and Alignment reads: the asymmetry of Transformer weight space](https://arxiv.org/abs/2605.16600)** — Valeria Ruscio, Eli-Shaoul Khedouri, Keiran Thompson _[agent-training-alignment]_
  Interpretability study of alignment vs. pretraining weight updates in transformers, with explicit safety motivation of understanding how alignment shapes model behavior.
- **[A Joint Synthetic Housing-Household Inventory](https://arxiv.org/abs/2605.17031)** — Xiao Qian, Shangjia Dong, Rachel Davidson _[city-simulation]_
  Framework generates synthetic household-building inventory linking populations to housing units for coupled urban-scale analysis supporting city resilience and planning applications.
- **[A Machine with Short-Term, Episodic, and Semantic Memory Systems](https://arxiv.org/abs/2212.02098)** — Taewoon Kim, Michael Cochez, Vincent François-Lavet, et al. _[agent-simulation]_
  Single reinforcement learning agent learning memory management in a designed environment; no multi-agent interaction, coordination, or population dynamics studied.
- **[ADR: An Agentic Detection System for Enterprise Agentic AI Security](https://arxiv.org/abs/2605.17380)** — Chenning Li, Pan Hu, Justin Xu, et al. _[agent-training-alignment]_
  Production enterprise framework for detecting and responding to agentic AI security threats, misalignment, and attacks in multi-agent systems.
- **[Activation Steering with a Feedback Controller](https://arxiv.org/abs/2510.04309)** — Dung V. Nguyen, Hieu M. Vu, Nhi Y. Pham, et al. _[agent-training-alignment]_
  Post-training method (PID-based activation steering) explicitly motivated by LLM safety alignment and behavioral control with theoretical guarantees.
- **[Agent Bazaar: Enabling Economic Alignment in Multi-Agent Marketplaces](https://arxiv.org/abs/2605.17698)** — Seth Karten, Cameron Crow, Chi Jin _[llm-agent-simulation, agent-training-alignment]_
  Multi-agent LLM marketplace simulation studying alignment failures (deception, instability) and RL training for economic safety via simulated market scenarios.
- **[Alignment Drift in Long-Term Human-LLM Interaction: A Mechanism-Oriented Framework](https://arxiv.org/abs/2605.16516)** — Xintong Yao _[agent-training-alignment]_
  Studies alignment drift—a safety failure mode where LLM outputs gradually diverge from user intent through long-term interaction feedback loops, proposing a mechanistic framework for detecting and con
- **[Alignment Dynamics in LLM Fine-Tuning](https://arxiv.org/abs/2605.18309)** — Yuhan Huang, Huanran Chen, Yinpeng Dong _[agent-training-alignment]_
  Framework explaining how LLM alignment degrades and recovers during fine-tuning, directly addressing alignment fragility and safety persistence under distribution shift.
- **[Beacon: Single-Turn Diagnosis and Mitigation of Latent Sycophancy in Large Language Models](https://arxiv.org/abs/2510.16727)** — Sanskar Pandey, Ruhaan Chopra, Angkul Puniya, et al. _[agent-training-alignment]_
  Proposes diagnostic benchmark and interventions to measure and mitigate sycophancy, a core LLM alignment failure mode.
- **[Beyond Correctness: Harmonizing Process and Outcome Rewards through RL Training](https://arxiv.org/abs/2509.03403)** — Chenlu Ye, Zhou Yu, Ziji Zhang, et al. _[agent-training-alignment]_
  Post-training method addressing alignment failure mode (reward hacking) by filtering spurious solutions to improve reasoning faithfulness.
- **[Beyond Policy Optimization: A Data Curation Flywheel for Sparse-Reward Long-Horizon Planning](https://arxiv.org/abs/2508.03018)** — Yutong Wang, Pengliang Ji, Kaixin Li, et al. _[agent-simulation]_
  LLM reasoning framework for long-horizon sparse-reward multi-round agentic planning with multi-environment evaluation (ALFWorld, ScienceWorld, WebShop).
- **[Beyond RLHF: A Unified Theoretical Framework of Alignment](https://arxiv.org/abs/2506.01523)** — Jihun Yun, Juno Kim, Jongho Park, et al. _[agent-training-alignment]_
  Theoretical framework justifying and comparing alignment post-training methods (RLHF, DPO) through principled objectives, directly addressing alignment from preferences.
- **[Beyond Static Responses: Multi-Agent LLM Systems as a New Paradigm for Social Science Research](https://arxiv.org/abs/2506.01839)** — Jennifer Haase, Sebastian Pokutta _[llm-agent-simulation]_
  Framework for multi-agent LLM systems simulating emergent social dynamics, group behavior, and large-scale social processes for scientific study.
- **[Bimodal Synchronization Performance: Why Noise and Sparse Connectivity Can Improve Collective Timing](https://arxiv.org/abs/2605.17206)** — Till Aust, Tianfu Zhang, Andreagiovanni Reina, et al. _[agent-simulation]_
  Studies pulse-coupled oscillator model with multiple decentralized agents achieving collective synchronization through local interactions and emergent multi-cluster dynamics.
- **[CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery](https://arxiv.org/abs/2604.01658)** — Ao Qu, Han Zheng, Zijian Zhou, et al. _[agent-simulation]_
  Multi-agent framework where multiple LLM-based agents explore, reflect, and collaborate through shared memory on open-ended discovery tasks.
- **[Causal Influences over Social Learning Networks](https://arxiv.org/abs/2307.09575)** — Mert Kayaalp, Ali H. Sayed _[agent-simulation]_
  Paper studies causal dynamics of multiple interacting agents over time in social learning networks with distributed decision-making protocols.
- **[Convergence of Multiagent Learning Systems for Traffic control](https://arxiv.org/abs/2511.11654)** — Sayambhu Sen, Shalabh Bhatnagar _[agent-simulation, city-simulation]_
  Theoretical convergence analysis of multi-agent reinforcement learning for traffic signal control, a core city-simulation domain with multiple coordinating agents.
- **[CooT: Learning to Coordinate In-Context with Coordination Transformers](https://arxiv.org/abs/2506.23549)** — Huai-Chih Wang, Hsiang-Chun Chuang, Hsi-Chun Cheng, et al. _[agent-simulation]_
  Multi-agent coordination framework enabling real-time adaptation among unfamiliar partners through in-context learning on diverse behavioral trajectories.
- **[DARC: Disagreement-Aware Alignment via Risk-Constrained Decoding](https://arxiv.org/abs/2603.08145)** — Mingxi Zou, Jiaxiang Chen, Junfan Li, et al. _[agent-training-alignment]_
  Inference-time alignment method addressing heterogeneous human preferences and proxy over-optimization through distributionally robust optimization.
- **[Diagnosing Korean-Language LLM Political Bias via Census-Grounded Agent Simulation](https://arxiv.org/abs/2605.18395)** — Sungwoo Kang _[llm-agent-simulation]_
  Uses LLM agents to simulate voters across Korean elections, studying systematic political biases in population behavior through agent-based voting simulations.
- **[Do LLM Agents Mirror Socio-Cognitive Effects in Power-Asymmetric Conversations?](https://arxiv.org/abs/2605.17694)** — Anvesh Rao Vijjini, Sagar Manjunath, Snigdha Chaturvedi _[llm-agent-simulation, agent-training-alignment]_
  LLM agents assigned personas engage in multi-turn power-asymmetric dialogues simulating human socio-cognitive effects; studies unsafe compliance behaviors emerging from status differential interaction
- **[Dynamic Deployment of Mobile Charging Trucks During Natural Disaster Evacuation: An Offline-to-Online Framework](https://arxiv.org/abs/2605.16784)** — Rui Ma, Zilin Bian, Kaan Ozbay _[city-simulation]_
  Multi-agent (MCT) coordination for urban-scale disaster evacuation mobility, evaluated in simulated hurricane evacuation environment with real-world city data.
- **[Dynamic Generation of Multi-LLM Agents Communication Topologies with Graph Diffusion Models](https://arxiv.org/abs/2510.07799)** — Eric Hanchen Jiang, Mengting Li, Guancheng Wan, et al. _[agent-simulation]_
  Paper addresses multi-agent LLM systems with dynamic communication topology optimization for coordinated task solving.
- **[EXG: Self-Evolving Agents with Experience Graphs](https://arxiv.org/abs/2605.17721)** — Yuxin Jin, Siyuan Zhang, Hanchen Wang, et al. _[agent-simulation]_
  LLM-based agent framework with multi-step interactions, experience reuse, and evolved behavior over time—core agent-simulation work on learning and adaptation mechanics.
- **[Epidemics in a Synthetic Urban Population with Multiple Levels of Mixing](https://arxiv.org/abs/2605.18092)** — Alessandro Celestini, Francesca Colaiori, Stefano Guarino, et al. _[city-simulation, agent-simulation]_
  Agent-based epidemic simulation of a synthetic urban population with heterogeneous contact patterns, geographic stratification, and emergent spatial diffusion dynamics.
- **[Equilibrium Selection in Multi-Agent Policy Gradients via Opponent-Aware Basin Entry](https://arxiv.org/abs/2605.18078)** — Yevhen Shcherbinin, Arina Redina, Maxim Kalpin, et al. _[agent-simulation]_
  Multi-agent policy-gradient method studying equilibrium selection and coordination dynamics across multiple interacting agents.
- **[Evaluating AI Alignment in LLMs: Output Analysis of Value Priorities Across 75 Models with Human Benchmarking](https://arxiv.org/abs/2506.12617)** — Gabriel Rongyang Lau, Wei Yan Low, Seow Min Koh, et al. _[agent-training-alignment]_
  Safety/alignment benchmark and diagnostic framework evaluating value alignment between 75 LLMs and human preferences using profile-fidelity metrics.
- **[EvilGenie: A Reward Hacking Benchmark](https://arxiv.org/abs/2511.21654)** — Jonathan Gabor, Jayson Lynch, Jonathan Rosenfeld _[agent-training-alignment]_
  Reward hacking benchmark for detecting misaligned behavior in coding agents; directly evaluates safety failure mode in agent systems.
- **[Evolve the Method, Not the Prompts: Evolutionary Synthesis of Jailbreak Attacks on LLMs](https://arxiv.org/abs/2511.12710)** — Yunhao Chen, Xin Wang, Juncheng Li, et al. _[agent-training-alignment]_
  Multi-agent red-teaming framework that evolves attack methods to exploit LLM safety mechanisms, revealing alignment weaknesses through automated adversarial synthesis.
- **[FML-bench: A Controlled Study of AI Research Agent Strategies from the Perspective of Search Dynamics](https://arxiv.org/abs/2605.17373)** — Qiran Zou, Hou Hei Lam, Wenhao Zhao, et al. _[agent-simulation]_
  Benchmark for evaluating multiple AI research agent strategies (greedy, tree-search, evolutionary) across different search dynamics and exploration behaviors.
- **[Factored Causal Representation Learning for Robust Reward Modeling in RLHF](https://arxiv.org/abs/2601.21350)** — Yupei Yang, Lin Yang, Wanxi Deng, et al. _[agent-training-alignment]_
  RLHF reward modeling method explicitly designed to mitigate reward hacking and sycophantic bias—core alignment failure modes in LLM post-training.
- **[From Demographics to Survey Anchors: Evaluating LLM Agents for Modeling Retirement Attitudes](https://arxiv.org/abs/2605.16303)** — Rubén Garzón, Pauline Baron, Vincent Grari, et al. _[llm-agent-simulation]_
  LLM agents simulating human survey respondents across multiple dimensions to study behavioral prediction and population dynamics in retirement attitudes.
- **[General-purpose LLMs as Models of Human Driver Behavior: The Case of Simplified Merging](https://arxiv.org/abs/2604.09609)** — Samir H. A. Mohammad, Wouter Mooi, Arkady Zgonnikov _[llm-agent-simulation]_
  Paper embeds LLMs as closed-loop driver agents in simulation to study human driving behavior reproduction, a direct instance of LLM-based human behavioral simulation.
- **[GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis](https://arxiv.org/abs/2507.21035)** — Haoyang Liu, Yijiang Li, Haohan Wang _[agent-simulation]_
  Multi-agent system with six specialized LLM agents coordinating via message-passing protocols to solve gene expression analysis tasks collaboratively.
- **[Helpful to a Fault: Measuring Illicit Assistance in Multi-Turn, Multilingual LLM Agents](https://arxiv.org/abs/2602.16346)** — Nivya Talokar, Ayush K Tarun, Murari Mandal, et al. _[agent-training-alignment]_
  Red-teaming benchmark and diagnostic framework for detecting unsafe multi-turn agent behaviors and jailbreaks in tool-using LLM agents.
- **[Heterogeneous Information-Bottleneck Coordination Graphs for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.17393)** — Wei Duan, Junyu Xuan, En Yu, et al. _[agent-simulation]_
  Cooperative multi-agent RL with principled coordination graph learning and agent communication topology optimization—core multi-agent coordination method.
- **[Human-Flow Digital Twin for Predicting the Effects of Mobility Introduction on Visitor Circulation](https://arxiv.org/abs/2605.17426)** — Chiharu Shima, Haruki Yonekura, Fukuharu Tanaka, et al. _[city-simulation]_
  Multi-agent simulator of visitor flows in urban space predicts mobility intervention effects on circulation and population distribution.
- **[Inspection and Control of Self-Generated-Text Recognition Ability in Llama3-8b-Instruct](https://arxiv.org/abs/2410.02064)** — Christopher Ackerman, Nina Panickssery _[agent-training-alignment]_
  Interpretability study of self-authorship recognition in LLMs with safety implications; demonstrates causal control of alignment-relevant model behavior.
- **[Interaction-Breaking Adversarial Learning Framework for Robust Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.18024)** — Sunwoo Lee, Mingu Kang, Yonghyeon Jo, et al. _[agent-simulation]_
  Multi-agent reinforcement learning robustness under adversarial perturbations to inter-agent coordination and observation structures.
- **[LLM-Guided Communication for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.18077)** — Sangjun Bae, Yisak Park, Sanghyeon Lee, et al. _[agent-simulation]_
  Multi-agent reinforcement learning paper with communication protocol design for cooperative agents coordinating under partial observability.
- **[Learning Transferable Topology Priors for Multi-Agent LLM Collaboration Across Domains](https://arxiv.org/abs/2605.17359)** — Taolin Zhang, Zijie Zhou, Jiuheng Wan, et al. _[agent-simulation]_
  Paper proposes framework for learning transferable topology priors to optimize multi-agent LLM collaboration structures across domains.
- **[Lifelong LaCAM with Local Guidance for Lifelong MAPF](https://arxiv.org/abs/2605.16855)** — Tomoki Arita, Keisuke Okumura _[agent-simulation]_
  Multi-agent pathfinding system coordinating multiple agents' movement in shared environments with emergent congestion dynamics.
- **[Lying with Truths: Open-Channel Multi-Agent Collusion for Belief Manipulation via Generative Montage](https://arxiv.org/abs/2601.01685)** — Jinwei Hu, Xinmiao Huang, Youcheng Sun, et al. _[agent-training-alignment]_
  Multi-agent deception attack revealing safety vulnerability: colluding LLM agents manipulate victim beliefs through coordinated evidence distribution, demonstrating alignment failure in adversarial mu
- **[MANTA: Multi-turn Assessment for Nonhuman Thinking & Alignment](https://arxiv.org/abs/2605.16301)** — Allen Lu, Isabella Luong, Joyee Chen _[agent-training-alignment]_
  Safety/alignment benchmark framework that stress-tests LLM alignment failures under adversarial multi-turn pressure using dynamic evaluation with implications for model safety assessment.
- **[MetaCogAgent: A Metacognitive Multi-Agent LLM Framework with Self-Aware Task Delegation](https://arxiv.org/abs/2605.17292)** — Chenyu Wang, Yang Shu _[agent-simulation]_
  Multi-agent LLM system with distinct agents coordinating via task delegation, self-assessment, and dynamic routing—core multi-agent coordination mechanics.
- **[Mitigating Conversational Inertia in Multi-Turn Agents](https://arxiv.org/abs/2602.03664)** — Yang Wan, Zheng Cao, Zhenhao Zhang, et al. _[agent-training-alignment]_
  Post-training method (preference learning) explicitly motivated by an alignment failure mode—conversational inertia limiting exploration in multi-turn agents.
- **[Monitoring the Internal Monologue: Probe Trajectories Reveal Reasoning Dynamics](https://arxiv.org/abs/2605.18549)** — Maciej Chrabąszcz, Aleksander Szymczyk, Marcin Sendera, et al. _[agent-training-alignment]_
  Interpretability method for detecting unsafe behaviors in reasoning models; uses probe trajectories to monitor and predict alignment failures in LLM outputs.
- **[Multi-Paradigm Agent Interaction in Practice:A Systematic Analysis of Generator-Evaluator, ReAct Loop,and Adversarial Evaluation in the buddyMe Framework](https://arxiv.org/abs/2605.16821)** — Xiaohua Wang, Chao Han, Kai Yu, et al. _[agent-simulation]_
  Multi-agent orchestration framework with generator-evaluator paradigm and systematic analysis of agent interaction patterns in deployed systems.
- **[Multi-agent AI systems outperform human teams in creativity](https://arxiv.org/abs/2605.17885)** — Tiancheng Hu, Yixuan Jiang, Haotian Li, et al. _[agent-simulation]_
  Multi-agent LLM teams coordinating to solve problems; studies emergent creative behavior through agent interaction and conversation dynamics.
- **[Multilingual jailbreaking of LLMs using low-resource languages](https://arxiv.org/abs/2605.18239)** — Dylan Marx, Marcel Dunaiski _[agent-training-alignment]_
  Red-teaming and adversarial attack study demonstrating jailbreak vulnerabilities across multilingual LLMs, revealing alignment and safety weaknesses.
- **[NeuSymMS: A Hybrid Neuro-Symbolic Memory System for Persistent, Self-Curating LLM Agents](https://arxiv.org/abs/2605.17596)** — Mujahid Sultan, Sri Thuraisamy, Daya Rajaratnam _[agent-simulation]_
  Hybrid neuro-symbolic memory system enabling LLM agents to persistently learn and reason across sessions with structured knowledge representation and multi-agent scoping.
- **[NeuroMAS: Multi-Agent Systems as Neural Networks with Joint Reinforcement Learning](https://arxiv.org/abs/2605.16757)** — Haoran Lu, Luyang Fang, Wenxuan Zhong, et al. _[agent-simulation]_
  Multi-agent LLM system with learned communication, coordination, and role specialization via reinforcement learning on network topology—core multi-agent architecture with emergent behavior.
- **[NewsLens: A Multi-Agent Framework for Adversarial News Bias Navigation](https://arxiv.org/abs/2605.17364)** — Joy Bose _[agent-simulation]_
  Multi-agent framework with five specialized agents collaborating through an adversarial pipeline to analyze news bias through distinct roles and perspectives.
- **[PAIR: Prefix-Aware Internal Reward Model for Multi-Turn Agent Optimization](https://arxiv.org/abs/2605.17877)** — Wonjoong Kim, Yeonjun In, Sangwu Park, et al. _[agent-training-alignment]_
  Post-training method (internal reward modeling) explicitly designed to improve credit assignment and reduce reliance on sparse rewards in multi-turn agent optimization, addressing a capability-safety 
- **[PQR: A Framework to Generate Diverse and Realistic User Queries that Elicit QA Agent Failures](https://arxiv.org/abs/2605.16551)** — Yunan Lu, Luigi Liu, Omar Yahia, et al. _[agent-training-alignment]_
  Automated framework for generating test queries to elicit and detect LLM-agent failures; a safety evaluation and diagnostic methodology for agent systems.
- **[PersonaArena: Dynamic Simulation for Evaluating and Enhancing Persona-Level Role-Playing in Large Language Models](https://arxiv.org/abs/2605.17044)** — Wenlong Shi, Jianxun Lian, Mingqi Wu, et al. _[llm-agent-simulation]_
  Framework simulates multiple interacting LLM agents in social environments to evaluate and enhance persona-level role-playing behavior.
- **[PopuLoRA: Co-Evolving LLM Populations for Reasoning Self-Play](https://arxiv.org/abs/2605.16727)** — Roger Creus Castanyer, Geoffrey Bradway, Lorenz Wolf, et al. _[agent-simulation]_
  Population-based multi-agent self-play framework where teacher and student populations co-evolve through specialization and cross-evaluation, studying emergent arms-race dynamics.
- **[Preference Instability in Reward Models: Detection and Mitigation via Sparse Autoencoders](https://arxiv.org/abs/2605.16339)** — Shunchang Liu, Xin Chen, Belen Martin Urcelay, et al. _[agent-training-alignment]_
  Detects and mitigates preference instability in reward models used for LLM alignment, directly addressing robustness failure in alignment-critical systems.
- **[PropGuard: Safeguarding LLM-MAS via Propagation-Aware Exploration and Remediation](https://arxiv.org/abs/2605.16346)** — Bingyu Yan, Xiaoming Zhang, Jinyu Hou, et al. _[agent-training-alignment]_
  Paper proposes a safety framework for LLM-based multi-agent systems addressing adversarial contamination propagation across coordinating agents through attack detection and remediation.
- **[RLBFF: Binary Flexible Feedback to bridge between Human Feedback & Verifiable Rewards](https://arxiv.org/abs/2509.21319)** — Zhilin Wang, Jiaqi Zeng, Olivier Delalleau, et al. _[agent-training-alignment]_
  Post-training method framed as alignment work; combines human feedback and rule-based verification to improve reward model interpretability and prevent reward hacking.
- **[Real-Time Aligned Reward Model beyond Semantics](https://arxiv.org/abs/2601.22664)** — Zixuan Huang, Xin Xia, Yuxi Ren, et al. _[agent-training-alignment]_
  Post-training method (RLHF variant) explicitly motivated by addressing reward overoptimization and misalignment between reward and policy models—a core safety failure mode.
- **[Red-Bandit: Test-Time Adaptation for LLM Red-Teaming via Bandit-Guided LoRA Experts](https://arxiv.org/abs/2510.07239)** — Christos Ziakas, Nicholas Loo, Nishita Jain, et al. _[agent-training-alignment]_
  Automated red-teaming method for discovering LLM vulnerabilities through adaptive attack generation and multi-armed bandit-guided adversarial prompt optimization.
- **[Reliability and Effectiveness of Autonomous AI Agents in Supply Chain Management](https://arxiv.org/abs/2605.17036)** — Carol Xuan Long, David Simchi-Levi, Feng Zhu, et al. _[llm-agent-simulation]_
  Multi-agent supply chain simulation using LLM agents coordinating across echelons; studies emergent multi-agent reliability phenomena and proposes RL post-training to improve system-level behavior.
- **[Responsible Federated LLMs via Safety Filtering and Constitutional AI](https://arxiv.org/abs/2502.16691)** — Eunchung Noh, Jeonghun Baek _[agent-training-alignment]_
  Paper applies safety filtering and constitutional AI to federated LLM training, directly addressing safe and responsible LLM deployment in multi-client settings.
- **[Shared Backbone PPO for Multi-UAV Communication Coverage with Connection Preservation](https://arxiv.org/abs/2605.17999)** — Z. Jiang _[agent-simulation]_
  Multi-agent reinforcement learning for coordinated UAV swarm with graph-based agent communication and emergent cooperative behavior.
- **[Social Influence and Unfollowing Accelerate the Emergence of Echo Chambers](https://arxiv.org/abs/1905.03919)** — Kazutoshi Sasahara, Wen Chen, Hao Peng, et al. _[agent-simulation, city-simulation]_
  Agent-based model of opinion dynamics and network formation in social media, studying emergent echo chamber segregation through population-level multi-agent interactions.
- **[SocialMemBench: Are AI Memory Systems Ready for Social Group Settings?](https://arxiv.org/abs/2605.17789)** — Olukunle Owolabi _[llm-agent-simulation]_
  Benchmark for LLM-based memory systems modeling multi-party social group interactions with 430 synthetic personas and conversation dynamics.
- **[Spatiotemporal Robustness of Temporal Logic Tasks using Multi-Objective Reasoning](https://arxiv.org/abs/2603.29868)** — Oliver Schön, Lars Lindemann _[agent-simulation]_
  Studies robustness of temporal logic specifications for multi-agent systems like robotics and smart cities through multi-objective optimization.
- **[Taming "Zombie'' Agents: A Markov State-Aware Framework for Resilient Multi-Agent Evolution](https://arxiv.org/abs/2605.17348)** — Taolin Zhang, Pukun Zhao, Qizhou Chen, et al. _[agent-simulation]_
  Multi-agent LLM system with agent state management, coordination framework, and emergent collaborative dynamics across discussion rounds.
- **[Taxonomy and Consistency Analysis of Safety Benchmarks for AI Agents](https://arxiv.org/abs/2605.16282)** — Miles Q. Li, Benjamin C. M. Fung, Boyang Li, et al. _[agent-training-alignment]_
  Systematic analysis of 40+ safety benchmarks for LLM agents, proposing taxonomy and methodological standards for agent safety evaluation frameworks and diagnostics.
- **[The Dynamics of Policy Gradient in Social Dilemmas with Partner Selection](https://arxiv.org/abs/2605.18185)** — Benedict Russell, Chin-wing Leung, Paolo Turrini _[agent-simulation]_
  Multi-agent study of policy-gradient dynamics in social dilemmas with partner selection, analyzing emergent cooperation through population interactions.
- **[The threat of analytic flexibility in using large language models to simulate human data](https://arxiv.org/abs/2509.13397)** — Jamie Cummins _[llm-agent-simulation]_
  Paper uses LLMs to simulate human respondents and examines validity threats in synthetic data generation through empirical methodology testing.
- **[Transitivity Meets Cyclicity: Explicit Preference Decomposition for Dynamic Large Language Model Alignment](https://arxiv.org/abs/2605.17342)** — Yucong Huang, Xiucheng Li, Kaiqi Zhao, et al. _[agent-training-alignment]_
  LLM post-training method (RLHF variant) explicitly motivated by alignment: decomposes transitive and cyclic preference components to improve reward modeling and alignment quality.
- **[VerifyMAS: Hypothesis Verification for Failure Attribution in LLM Multi-Agent Systems](https://arxiv.org/abs/2605.17467)** — Hezhe Qiao, Hanghang Tong, Ee-Peng Lim, et al. _[agent-simulation]_
  Paper addresses failure attribution and reliability in multi-agent LLM systems through trajectory verification and agent localization, directly tackling multi-agent coordination and system-level behav
- **[We Think, Therefore We Align LLMs to Helpful, Harmless and Honest Before They Go Wrong](https://arxiv.org/abs/2509.22510)** — Gautam Siddharth Kashyap, Mark Dras, Usman Naseem _[agent-training-alignment]_
  Post-training steering method explicitly motivated by addressing multi-objective alignment failures (helpfulness, harmlessness, honesty) in LLM safety.
- **[When Personalization Legitimizes Risks: Uncovering Safety Vulnerabilities in Personalized Dialogue Agents](https://arxiv.org/abs/2601.17887)** — Jiahe Guo, Xiangran Guo, Yulin Hu, et al. _[agent-training-alignment]_
  Identifies and evaluates intent legitimation as a safety failure mode in personalized LLM agents, proposing detection methods to mitigate misalignment.
- **[White-Box Sensitivity Auditing with Steering Vectors](https://arxiv.org/abs/2601.16398)** — Hannah Cyberey, Yangfeng Ji, David Evans _[agent-training-alignment]_
  White-box interpretability method for detecting unsafe model behaviors (gender bias) in LLMs through activation steering—directly serves alignment/safety diagnosis.
- **[You Can't Fool Us: Understanding the Resilience of LLM-driven Agent Communities to Misinformation](https://arxiv.org/abs/2605.17353)** — Chichen Lin, Yijie Jin, Kangbo Hu, et al. _[llm-agent-simulation]_
  LLM-based agent simulation constructing synthetic communities to study collective behavior in response to misinformation through varied psychological and ideological traits.
- **[Zero-Shot Scalable Resilience in UAV Swarms: A Decentralized Imitation Learning Framework with Physics-Informed Graph Interactions](https://arxiv.org/abs/2604.15762)** — Huan Lin, Lianghui Ding _[agent-simulation]_
  Multi-agent reinforcement learning framework for coordinated UAV swarm control with decentralized execution and emergent resilience behavior across variable swarm scales.
- **[\textsc{MasFACT}: Continual Multi-Agent Topology Learning via Geometry-Aware Posterior Transfer](https://arxiv.org/abs/2605.17361)** — Xuefei Wang, Jialu Wang, Fengbo Zhang, et al. _[agent-simulation]_
  Multi-agent topology learning framework for LLM-based systems addressing inter-agent communication coordination and continual task adaptation across evolving multi-agent systems.










## 2026-05-18

- ⭐ **[AI-Mediated Communication Can Steer Collective Opinion](https://arxiv.org/abs/2605.16245)** — Stratis Tsirtsis, Kai Rawal, Chris Russell, et al. _[llm-agent-simulation]_
  Studies how LLMs inserted as communication mediators in social networks influence collective opinion formation through network dynamics simulations.
- ⭐ **[Argus: Evidence Assembly for Scalable Deep Research Agents](https://arxiv.org/abs/2605.16217)** — Zhen Zhang, Liangcai Su, Zhuo Chen, et al. _[agent-simulation]_
  Multi-agent research system with Searcher and Navigator agents coordinating to complete complementary tasks via cooperative interaction and RL training.
- ⭐ **[Fair outputs, Biased Internals: Causal Potency and Asymmetry of Latent Bias in LLMs for High-Stakes Decisions](https://arxiv.org/abs/2605.15217)** — Jagdish Tripathy, Marcus Buckmann _[agent-training-alignment]_
  Interpretability study demonstrating hidden bias and exploitable vulnerabilities in instruction-tuned LLMs, with safety implications for high-stakes AI deployment.
- ⭐ **[Training on Documents About Monitoring Leads to CoT Obfuscation](https://arxiv.org/abs/2605.15257)** — Reilly Haskins, Bilal Chughtai, Joshua Engels _[agent-training-alignment]_
  Studies misalignment failure mode (CoT obfuscation and deception) where models learn to evade safety monitoring through knowledge of detection mechanisms.
- ⭐ **[When AI Persuades: Adversarial Explanation Attacks on Human Trust in AI-Assisted Decision Making](https://arxiv.org/abs/2602.04003)** — Shutong Fan, Lan Zhang, Xiaoyong Yuan _[agent-training-alignment]_
  Adversarial attack methodology targeting LLM safety (manipulation of explanations to deceive humans), reveals alignment failure via deception and trust exploitation.
- **[ALSO: Adversarial Online Strategy Optimization for Social Agents](https://arxiv.org/abs/2605.15768)** — Xiang Li, Liping Yi, Mingze Kong, et al. _[llm-agent-simulation]_
  Multi-agent LLM-based social simulation with adversarial online strategy optimization for dynamic interaction and behavioral adaptation.
- **[Belief Engine: Configurable and Inspectable Stance Dynamics in Multi-Agent LLM Deliberation](https://arxiv.org/abs/2605.15343)** — Joshua C. Yang, Maurice Flechtner, Damian Dailisan, et al. _[llm-agent-simulation]_
  Paper introduces an auditable belief-update layer for multi-agent LLM deliberation, simulating human stance dynamics with inspectable evidence-grounded reasoning.
- **[Beyond Forgetting: Machine Unlearning Elicits Controllable Side Behaviors and Capabilities](https://arxiv.org/abs/2601.21702)** — Tien Dang, The-Hai Nguyen, Dinh Mai Phuong, et al. _[agent-training-alignment]_
  Machine unlearning method studying alignment-relevant phenomena: controllable behavioral side effects and emergent capabilities from representation misdirection in LLMs.
- **[Beyond Partner Diversity: An Influence-Based Team Steering Framework for Zero-Shot Human-Machine Teaming](https://arxiv.org/abs/2605.15400)** — Wei Sheng, Rohan Paleja _[agent-simulation]_
  Multi-agent coordination framework training agents via influence shaping on partner populations for zero-shot human-machine teaming and emergent team behaviors.
- **[Context, Reasoning, and Hierarchy: A Cost-Performance Study of Compound LLM Agent Design in an Adversarial POMDP](https://arxiv.org/abs/2605.16205)** — Igor Bogdanov, Chung-Horng Lung, Thomas Kunz, et al. _[agent-simulation]_
  Multi-agent compound LLM system study with hierarchical decomposition, specialized sub-agents, and coordination in adversarial POMDP environment.
- **[Differentiable Mixture-of-Agents Incentivizes Swarm Intelligence of Large Language Models](https://arxiv.org/abs/2605.15706)** — Xingjian Wu, Junkai Lu, Siyu Yan, et al. _[agent-simulation]_
  Multi-agent system with dynamic agent routing and collaboration where agents interact through a learned communication topology adapted at each reasoning step.
- **[Distributed Zeroth-Order Policy Gradient for Networked Multi-agent Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2605.15697)** — Pengcheng Dai, He Wang, Dongming Wang, et al. _[agent-simulation]_
  Networked multi-agent RL system with localized coordination, distributed policy learning, and collaborative optimization across multiple interacting agents.
- **[Ensemble Monitoring for AI Control: Diverse Signals Outweigh More Compute](https://arxiv.org/abs/2605.15377)** — Eugene Koran, Yejun Yun, Samantha Tetef, et al. _[agent-training-alignment]_
  Presents a safety/alignment diagnostic framework for detecting misaligned agent actions via diverse ensemble monitoring and evaluates detection capabilities against adversarial behaviors.
- **[Estimated Dynamic Equilibrium Model: Supply and Demand as a Sample Path of a Stochastic Process](https://arxiv.org/abs/2605.15472)** — Mikhail L. Arbuzov, Sisong Bei, Alexey Shvets _[agent-simulation, city-simulation]_
  Agent-based framework modeling heterogeneous agents in market dynamics with emergent disequilibrium regimes and simulated real-estate neighborhood application.
- **[FORGE: Self-Evolving Agent Memory With No Weight Updates via Population Broadcast](https://arxiv.org/abs/2605.16233)** — Igor Bogdanov, Chung-Horng Lung, Thomas Kunz, et al. _[agent-simulation]_
  Population-based multi-agent protocol where multiple agent instances interact, evolve shared memory, and coordinate through broadcast, with emergent collective learning behavior.
- **[Formal Methods Meet LLMs: Auditing, Monitoring, and Intervention for Compliance of Advanced AI Systems](https://arxiv.org/abs/2605.16198)** — Parand A. Alamdari, Toryn Q. Klassen, Sheila A. McIlraith _[agent-training-alignment]_
  Proposes runtime monitoring and intervention techniques to ensure LLM-based agents comply with safety constraints and behavioral rules, directly addressing alignment and safety enforcement.
- **[From Gridworlds to Warehouses: Adapting Lightweight One-shot Multi-Agent Pathfinding for AGVs](https://arxiv.org/abs/2605.15799)** — Hiroki Nagai, Keisuke Okumura _[agent-simulation]_
  Multi-agent pathfinding coordination problem with population-scale dynamics adapted to warehouse AGV operations, demonstrating emergent behavior in agent coordination systems.
- **[Graph-Regularized Sparse Autoencoders for LLM Safety Steering](https://arxiv.org/abs/2512.06655)** — Jehyeok Yeon, Federico Cinus, Yifan Wu, et al. _[agent-training-alignment]_
  Interpretability method designed for safety alignment goal: using sparse autoencoders and graph regularization to extract and steer LLM safety behaviors and refusal mechanisms.
- **[ICRL: Learning to Internalize Self-Critique with Reinforcement Learning](https://arxiv.org/abs/2605.15224)** — Jianbo Lin, Xiaomin Yu, Yi Xin, et al. _[agent-training-alignment]_
  Post-training method (RLHF variant via RL) explicitly framed to align solver behavior with internalized critique rather than external dependence, addressing a safety failure mode of alignment faking.
- **[Improving Cross-Cultural Survey Simulation with Calibrated Value Personas](https://arxiv.org/abs/2605.16193)** — Axel Abels, Elias Fernandez Domingos, Apurva Shah, et al. _[llm-agent-simulation]_
  Proposes value-based personas to simulate human survey responses across populations, using LLMs as behavioral proxies for studying cross-cultural opinions.
- **[Learning Where It Matters: Geometric Anchoring for Robust Preference Alignment](https://arxiv.org/abs/2602.04909)** — Youngjae Cho, Jongsuk Kim, Ji-Hoon Kim _[agent-training-alignment]_
  Post-training method (DPO variant) explicitly motivated by improving alignment robustness under noisy preference supervision and distribution mismatch.
- **[Look Before You Leap: Autonomous Exploration for LLM Agents](https://arxiv.org/abs/2605.16143)** — Ziang Ye, Wentao Shi, Yuxin Liu, et al. _[agent-training-alignment]_
  Post-training method (RL strategy with verifiable rewards) explicitly addressing LLM agent reliability failure—premature exploitation—through systematic exploration training.
- **[Mechanisms of Introspective Awareness](https://arxiv.org/abs/2603.21396)** — Uzay Macar, Li Yang, Atticus Wang, et al. _[agent-training-alignment]_
  Mechanistic study of LLM introspection on adversarial steering injections; safety-relevant interpretability revealing detection circuits and deception/manipulation robustness.
- **[Multi-Agent Cooperative Transportation: Optimal and Efficient Task Allocation and Path Finding](https://arxiv.org/abs/2605.16097)** — Ning Zhou, Nikolai W. F. Bode, Edmund R. Hunt _[agent-simulation]_
  Formalizes and solves multi-agent cooperative transportation with team formation, task allocation, and collision-free pathfinding—core multi-agent coordination problem.
- **[Quantization Undoes Alignment: Bias Emergence in Compressed LLMs Across Models and Precision Levels](https://arxiv.org/abs/2605.15208)** — Plawan Kumar Rath, Rahul Maliakkal _[agent-training-alignment]_
  Empirical study of bias emergence as an alignment failure under quantization compression, demonstrating safety degradation invisible to standard metrics.
- **[RecMem: Recurrence-based Memory Consolidation for Efficient and Effective Long-Running LLM Agents](https://arxiv.org/abs/2605.16045)** — Zijie Dai, Shiyuan Deng, Sheng Guan, et al. _[agent-simulation]_
  Memory consolidation system for long-running LLM agents enabling sustained multi-turn interactions and behavioral patterns over time.
- **[Reducing the Safety Tax in LLM Safety Alignment with On-Policy Self-Distillation](https://arxiv.org/abs/2605.15239)** — Yu Fu, Longxuan Yu, Haz Sameen Shahgir, et al. _[agent-training-alignment]_
  Post-training method explicitly motivated by addressing a safety failure (safety-reasoning tradeoff) through on-policy self-distillation with safety-aware supervision.
- **[Response-Conditioned Parallel-to-Sequential Orchestration for Multi-Agent Systems](https://arxiv.org/abs/2605.15573)** — Nurbek Tastan, Alex Iacob, Lorenzo Sani, et al. _[agent-simulation]_
  Multi-agent coordination framework where multiple LLM agents collaborate through a learned hybrid parallel-sequential communication policy optimized for task accuracy.
- **[SDOF: Taming the Alignment Tax in Multi-Agent Orchestration with State-Constrained Dispatch](https://arxiv.org/abs/2605.15204)** — Zhantao Wang _[agent-training-alignment]_
  Multi-agent orchestration framework with safety alignment: RLHF-trained intent router enforcing FSM constraints to prevent misrouted tasks and injection attacks in real business processes.
- **[TeamTR: Trust-Region Fine-Tuning for Multi-Agent LLM Coordination](https://arxiv.org/abs/2605.15207)** — Yi Xie, Siao Liu, Falong Fan, et al. _[agent-training-alignment]_
  Multi-agent LLM coordination system with trust-region fine-tuning method addressing emergent coordination failures in sequential agent training and team optimization.
- **[Validated Hypotheses as a Lens for Human-Likeness Evaluation in AI Agents](https://arxiv.org/abs/2605.15473)** — Xuan Liu, HaoYang Shang, Zizhang Liu, et al. _[llm-agent-simulation]_
  Uses LLM agents to simulate human behavioral responses to social-science experiments for population-level behavioral study and evaluation.
- **[When Importance Sampling Misallocates Credit: Asymmetric Ratios for Outcome-Supervised RL](https://arxiv.org/abs/2510.06062)** — Jiakang Wang, Runze Liu, Qingpeng Cai, et al. _[agent-training-alignment]_
  Novel post-training RL method (ASPO) for LLMs addressing entropy collapse and training instability—alignment-motivated improvement over GRPO.











## 2026-05-15

- ⭐ **[Forgetting That Sticks: Quantization-Permanent Unlearning via Circuit Attribution](https://arxiv.org/abs/2605.15138)** — Saisab Sadhu, Pratinav Seth, Vinay Kumar Sankarapu _[agent-training-alignment]_
  Proposes unlearning method addressing safety failure: preventing quantization from reversing adversarial forgetting in deployed LLMs through mechanistic circuit attribution.
- ⭐ **[From Sycophantic Consensus to Pluralistic Repair: Why AI Alignment Must Surface Disagreement](https://arxiv.org/abs/2605.14912)** — Varad Vishwarupe, Nigel Shadbolt, Marina Jirotka _[agent-training-alignment]_
  Paper studies sycophancy as alignment failure mode in RLHF-trained LLMs and proposes diagnostic framework (PRS metric) to detect principled revision versus capitulation.
- ⭐ **[Invisible Orchestrators Suppress Protective Behavior and Dissociate Power-Holders: Safety Risks in Multi-Agent LLM Systems](https://arxiv.org/abs/2605.13851)** — Hiroki Fukui _[agent-training-alignment]_
  Empirical study of multi-agent LLM system safety, measuring alignment failures (dissociation, deception, internal-state distortion) across organizational structures and alignment conditions.
- ⭐ **[Real-Time Group Dynamics with LLM Facilitation: Evidence from a Charity Allocation Task](https://arxiv.org/abs/2605.14097)** — Aaron Parisi, Nithum Thain, Alden Hallak, et al. _[llm-agent-simulation]_
  Empirical study using LLMs as active participants in human group deliberation to study collective decision-making dynamics and governance effects.
- ⭐ **[Resolving Action Bottleneck: Agentic Reinforcement Learning Informed by Token-Level Energy](https://arxiv.org/abs/2605.14558)** — Langzhou He, Junyou Zhu, Yue Zhou, et al. _[agent-training-alignment]_
  Post-training method (token reweighting for RL) with explicit motivation to improve credit assignment and training efficiency in agentic RL systems.
- ⭐ **[When Identity Overrides Incentives: Representational Choices as Governance Decisions in Multi-Agent LLM Systems](https://arxiv.org/abs/2601.10102)** — Viswonathan Manoranjan, Snehalkumar `Neil' S. Gaikwad _[llm-agent-simulation, agent-training-alignment]_
  LLM multi-agent strategic game study revealing how persona representation overrides payoff incentives, raising alignment concerns about representational choices governing agent behavior in governance 
- **[AI Knows When It's Being Watched: Functional Strategic Action and Contextual Register Modulation in Large Language Models](https://arxiv.org/abs/2605.15034)** — Vinicius Covas, Jorge Alberto Hidalgo Toledo _[agent-training-alignment]_
  Multi-agent debate sessions studying whether LLMs systematically modify behavior under observation—a safety-relevant phenomenon related to deception, sycophancy, and strategic action alignment.
- **[AgenticEval: Toward Agentic and Self-Evolving Safety Evaluation of Large Language Models](https://arxiv.org/abs/2509.26100)** — Yixu Wang, Xin Wang, Yang Yao, et al. _[agent-training-alignment]_
  Multi-agent safety evaluation framework designed to detect and diagnose LLM alignment failures through progressive adversarial testing and misalignment discovery.
- **[Auditing Agent Harness Safety](https://arxiv.org/abs/2605.14271)** — Chengzhi Liu, Yichen Guo, Yepeng Liu, et al. _[agent-training-alignment]_
  Proposes HarnessAudit, a safety evaluation framework and benchmark for detecting mid-trajectory failures in LLM agent execution—a misalignment diagnostic tool targeting resource access and information
- **[Beyond Individual Intelligence: Surveying Collaboration, Failure Attribution, and Self-Evolution in LLM-based Multi-Agent Systems](https://arxiv.org/abs/2605.14892)** — Shihao Qi, Jie Ma, Rui Xing, et al. _[agent-simulation]_
  Survey of LLM-based multi-agent systems covering structured collaboration, failure propagation across agents, and collective self-improvement mechanisms in multi-agent coordination.
- **[Cattle Trade: A Multi-Agent Benchmark for LLM Bluffing, Bidding, and Bargaining](https://arxiv.org/abs/2605.14537)** — Robert Müller, Clemens Müller _[agent-simulation]_
  Multi-agent benchmark evaluating LLM agents in competitive strategic interaction with auctions, bargaining, bluffing, and opponent modeling across 50-60 turn games.
- **[Collaborative Yet Personalized Policy Training: Single-Timescale Federated Actor-Critic](https://arxiv.org/abs/2605.14423)** — Leo Muxing Wang, Pengkun Yang, Lili Su _[agent-simulation]_
  Multi-agent federated actor-critic framework with collaborative policy training across heterogeneous agents under distinct environmental dynamics.
- **[DVMap: Fine-Grained Pluralistic Value Alignment via High-Consensus Demographic-Value Mapping](https://arxiv.org/abs/2605.14420)** — Pengyun Zhu, Yuqi Ren, Zhen Wang, et al. _[agent-training-alignment]_
  LLM post-training method (GRPO) explicitly motivated by alignment goal of fine-grained pluralistic value alignment beyond coarse national labels.
- **[Data-Augmented Game Starts for Accelerating Self-Play Exploration in Imperfect Information Games](https://arxiv.org/abs/2605.14379)** — JB Lanier, Nathan Monette, Pierre Baldi, et al. _[agent-simulation]_
  Multi-agent game theory and RL method for two-player zero-sum imperfect information games with equilibria-seeking multi-agent self-play exploration.
- **[Deceive, Detect, and Disclose: Large Language Models Play Mini-Mafia](https://arxiv.org/abs/2509.23023)** — Davi Bastos Costa, Renato Vicente _[agent-simulation]_
  Multi-agent interactive game-theoretic study of LLMs with emergent collective outcomes determined by agent interactions and social intelligence capabilities.
- **[Do Reasoning LLMs Refuse What They Infer in Long Contexts?](https://arxiv.org/abs/2602.08874)** — Yu Fu, Haz Sameen Shahgir, Huanli Gong, et al. _[agent-training-alignment]_
  Proposes a red-teaming method (compositional reasoning attacks) revealing safety failures where LLMs infer and comply with harmful objectives distributed across long contexts.
- **[FlowSteer: Towards Agents Designing Agentic Workflows via Reinforced Progressive Canvas Editing](https://arxiv.org/abs/2602.01664)** — Mingda Zhang, Wenjin Liu, Tiesunlong Shen, et al. _[agent-simulation]_
  Agent autonomously designs executable agentic workflows through reinforced progressive editing with real-time execution feedback, demonstrating multi-step coordination and long-horizon planning.
- **[Fusion-fission forecasts when AI will shift to undesirable behavior](https://arxiv.org/abs/2605.14218)** — Neil F. Johnson, Frank Yingjie Huo _[agent-training-alignment]_
  Paper proposes a mathematical framework to forecast and detect shifts in LLM behavior from desirable to undesirable states, providing real-time alignment diagnostics and misalignment detection.
- **[GradShield: Alignment Preserving Finetuning](https://arxiv.org/abs/2605.14194)** — Zhanhao Hu, Xiao Huang, Patrick Mendoza, et al. _[agent-training-alignment]_
  Safety-aware finetuning method that filters harmful data to preserve LLM alignment during utility training, directly addressing alignment and misalignment failure modes.
- **[Hierarchical Attacks for Multi-Modal Multi-Agent Reasoning](https://arxiv.org/abs/2605.13213)** — Hao Zhou, Tiru Wu, Yan Jiang, et al. _[agent-training-alignment]_
  Adversarial attack and red-teaming framework targeting multi-agent multi-modal systems, exposing vulnerabilities in agent reasoning and coordination.
- **[IFPV: An Integrated Multi-Agent Framework for Generative Operational Planning and High-Fidelity Plan Verification](https://arxiv.org/abs/2605.14851)** — Zhigao Huang, Zhengqing Hu, Dong Chen, et al. _[agent-simulation]_
  Multi-agent framework with distinct Pathfinder, Analyst, Planner agents collaborating on tactical planning, plus adversarial opponent agent in verification simulation.
- **[LEMON: Learning Executable Multi-Agent Orchestration via Counterfactual Reinforcement Learning](https://arxiv.org/abs/2605.14483)** — Xudong Chen, Yixin Liu, Hua Wei, et al. _[agent-simulation]_
  Multi-agent orchestration system where an LLM learns to dynamically design roles, dependencies, and capacity assignments across multiple coordinating agents on reasoning tasks.
- **[LiSA: Lifelong Safety Adaptation via Conservative Policy Induction](https://arxiv.org/abs/2605.14454)** — Minbeom Kim, Lesly Miculicich, Bhavana Dalvi Mishra, et al. _[agent-training-alignment]_
  Conservative policy induction framework for lifelong safety adaptation in AI agents, addressing alignment and robustness under sparse, noisy deployment feedback.
- **[MetaAgent-X : Breaking the Ceiling of Automatic Multi-Agent Systems via End-to-End Reinforcement Learning](https://arxiv.org/abs/2605.14212)** — Yaolun Zhang, Yujie Zhao, Nan Wang, et al. _[agent-simulation]_
  End-to-end RL framework for multi-agent system design and execution, optimizing coordinated designer-executor agent interactions with emergent self-designing behavior.
- **[Modeling Bounded Rationality in Drug Shortage Pharmacists Using Attention-Guided Dynamic Decomposition](https://arxiv.org/abs/2605.14111)** — Yaniv Eliyahu Amiri, Noah Chicoine, Jacqueline Griffin, et al. _[agent-simulation]_
  Multi-agent modeling of bounded-rational human decision-making (pharmacists) with attention mechanisms and simulation-based evaluation across scenarios.
- **[Moltbook Moderation: Uncovering Hidden Intent Through Multi-Turn Dialogue](https://arxiv.org/abs/2605.12856)** — Ali Al-Lawati, Nafis Tripto, Abolfazl Ansari, et al. _[agent-simulation]_
  Multi-agent moderation framework detecting malicious intent through dialogue; addresses agent safety and deception in multi-agent systems.
- **[Near-Miss: Latent Policy Failure Detection in Agentic Workflows](https://arxiv.org/abs/2603.29665)** — Ella Rabinovich, David Boaz, Naama Zwerdling, et al. _[agent-training-alignment]_
  Introduces a safety diagnostic framework to detect latent policy failures and unsafe decision-making in LLM agentic workflows, addressing alignment via process verification.
- **[OMAC: A Holistic Optimization Framework for LLM-Based Multi-Agent Collaboration](https://arxiv.org/abs/2505.11765)** — Shijun Li, Hilaf Hasson, Joydeep Ghosh _[agent-simulation]_
  Multi-agent system with multiple LLM agents collaborating and communicating; demonstrates emergent capabilities through agent coordination across diverse complex tasks.
- **[On the Limits of PAC Learning of Networks from Opinion Dynamics](https://arxiv.org/abs/2605.15033)** — Dmitry Chistikov, Luisa Estrada, Mike Paterson, et al. _[agent-simulation]_
  Studies population dynamics and agent behavior in social networks with threshold-based opinion dynamics and multi-agent interactions.
- **[Orchard: An Open-Source Agentic Modeling Framework](https://arxiv.org/abs/2605.15040)** — Baolin Peng, Wenlin Yao, Qianhui Wu, et al. _[agent-simulation]_
  Open-source framework for training autonomous LLM agents with multi-turn environment interaction, planning, and reasoning across diverse task domains.
- **[PREPING: Building Agent Memory without Tasks](https://arxiv.org/abs/2605.13880)** — Yumin Choi, Sangwoo Park, Minki Kang, et al. _[agent-simulation]_
  Studies procedural memory construction for LLM agents through self-generated synthetic task practice with multi-component interaction (Proposer, Solver, Validator).
- **[PolitNuggets: Benchmarking Agentic Discovery of Long-Tail Political Facts](https://arxiv.org/abs/2605.14002)** — Yifei Zhu _[agent-simulation]_
  Multi-agent system for information synthesis; benchmark evaluates agentic coordination and emergent discovery behavior across tool use and model capabilities.
- **[Privacy Preserving Multi Agent Path Finding](https://arxiv.org/abs/2605.14119)** — Rotem Lev Lehman, Roni Stern, Guy Shani _[agent-simulation]_
  Multi-agent path finding with privacy constraints involves multiple interacting agents coordinating paths without collisions in a graph-based environment.
- **[R2PS: Worst-Case Robust Real-Time Pursuit Strategies under Partial Observability](https://arxiv.org/abs/2511.17367)** — Runyu Lu, Ruochuan Shi, Yuanheng Zhu, et al. _[agent-simulation]_
  Multi-agent game-theoretic pursuit-evasion strategy learning via RL with competing agents on graphs.
- **[Ready from Day 1: Population-Aware Coordination for Large-Scale Constrained Multi-Agent Systems](https://arxiv.org/abs/2605.13900)** — Angel Wang, Dominique Perrault-Joncas, Alvaro Maggiar, et al. _[agent-simulation]_
  Addresses coordination in large-scale multi-agent systems with heterogeneous populations and resource constraints through learned population-aware coordination mechanisms.
- **[Selective Safety Steering via Value-Filtered Decoding](https://arxiv.org/abs/2605.14746)** — Bat-Sheva Einbinder, Hen Davidov, Yee Whye Teh, et al. _[agent-training-alignment]_
  Test-time safety steering method for LLMs that reduces unnecessary interventions while maintaining safety—directly addresses alignment failure mode of over-correction.
- **[Self-Distilled Agentic Reinforcement Learning](https://arxiv.org/abs/2605.15155)** — Zhengxi Lu, Zhiyuan Yao, Zhuowen Han, et al. _[agent-training-alignment]_
  Post-training method (RLHF-adjacent) for multi-turn LLM agents with explicit alignment motivation: improving agent trajectory stability and supervision quality through structured learning objectives.
- **[Sequential Resource Trading Using Comparison-Based Gradient Estimation](https://arxiv.org/abs/2408.11186)** — Surya Murthy, Mustafa O. Karabag, Ufuk Topcu _[agent-simulation]_
  Two-agent sequential trading with strategic interaction, utility learning, and Pareto optimality analysis through multi-round negotiation.
- **[SimPersona: Learning Discrete Buyer Personas from Raw Clickstreams for Grounded E-Commerce Agents](https://arxiv.org/abs/2605.14205)** — Zahra Zanjani Foumani, Alberto Castelo, Shuang Xie, et al. _[llm-agent-simulation]_
  Paper uses LLM-based agents to simulate diverse buyer populations and heterogeneous behaviors derived from real clickstream data for e-commerce simulation.
- **[SkillFlow: Flow-Driven Recursive Skill Evolution for Agentic Orchestration](https://arxiv.org/abs/2605.14089)** — Mingda Zhang, Tiesunlong Shen, Haoran Luo, et al. _[agent-simulation]_
  LLM agent orchestration system with multi-turn interaction, skill evolution, and structured environment—core agent-training-alignment contribution on capability growth and credit assignment.
- **[Static and Dynamic Strategies for Influencing Opinions in Social Networks](https://arxiv.org/abs/2605.14918)** — Paolo Tarantino, Fabio Mazza, Carlo Piccardi, et al. _[agent-simulation]_
  Studies population-scale opinion dynamics using bounded-confidence agent-based modeling with multiple coordinated agents manipulating a network's collective behavior.
- **[Temporal Fair Division in Multi-Agent Systems: From Precise Alternation Metrics to Scalable Coordination Proxies](https://arxiv.org/abs/2605.14879)** — Nikolaos Al. Papadopoulos _[agent-simulation]_
  Multi-agent systems paper studying repeated resource competition, fairness metrics, and agent coordination failures across populations using Q-learning agents.
- **[The Moltbook Observatory Archive: an incremental dataset of agent-only social network activity](https://arxiv.org/abs/2605.13860)** — Sushant Gautam, Annika W. Olstad, Klas H. Pettersen, et al. _[agent-simulation, llm-agent-simulation]_
  Dataset of autonomous AI agents interacting in a social network, enabling study of multi-agent communication, emergent behavior, and safety phenomena in agent populations.
- **[Training ML Models with Predictable Failures](https://arxiv.org/abs/2605.15134)** — Will Schwarzer, Scott Niekum _[agent-training-alignment]_
  Paper proposes fine-tuning method addressing safety failure prediction and deployment-scale failure modes through forecastability loss for safer model behavior.












## 2026-05-14

- ⭐ **[ChipMATE: Multi-Agent Training via Reinforcement Learning for Enhanced RTL Generation](https://arxiv.org/abs/2605.12857)** — Zhongkai Yu, Yichen Lin, Chenyang Zhou, et al. _[agent-simulation]_
  Multi-agent RL framework where Verilog and Python-reference agents interact, coordinate verification, and train jointly to solve RTL generation tasks.
- ⭐ **[Do Androids Dream of Breaking the Game? Systematically Auditing AI Agent Benchmarks with BenchJack](https://arxiv.org/abs/2605.12673)** — Hao Wang, Hanchen Li, Qiuyang Mang, et al. _[agent-training-alignment]_
  Automated red-teaming system for detecting reward hacking and specification gaming in agent benchmarks; alignment-focused evaluation methodology and diagnostic framework.
- ⭐ **[History Anchors: How Prior Behavior Steers LLM Decisions Toward Unsafe Actions](https://arxiv.org/abs/2605.13825)** — Alberto G. Rodríguez Salgado _[agent-training-alignment]_
  Empirical study demonstrating a safety failure mode (consistency bias) in aligned LLMs when deployed as agents in sequential decision-making settings, directly revealing alignment weakness.
- ⭐ **[In-Situ Behavioral Evaluation for LLM Fairness, Not Standardized-Test Scores](https://arxiv.org/abs/2605.12530)** — Zeyu Tang, Sang T. Truong, Deonna Owens, et al. _[agent-simulation]_
  Multi-agent conversational framework using controlled dialogue interactions to study emergent behavioral patterns across identity variations in 8 million conversation transcripts.
- ⭐ **[LLM-Based Persuasion Enables Guardrail Override in Frontier LLMs](https://arxiv.org/abs/2605.13334)** — Rodrigo Nogueira, Thales Sales Almeida, Giovana Kerche Bonás, et al. _[agent-training-alignment]_
  Demonstrates guardrail override attacks via multi-turn LLM-to-LLM persuasion, revealing misalignment and jailbreak vulnerability in frontier models through adversarial red-teaming.
- ⭐ **[Negation Neglect: When models fail to learn negations in training](https://arxiv.org/abs/2605.13829)** — Harry Mayne, Lev McKinney, Jan Dubiński, et al. _[agent-training-alignment]_
  Documents a fundamental misalignment failure where finetuning causes models to adopt false and unsafe beliefs/behaviors despite explicit negations—a critical safety phenomenon.
- ⭐ **[Not Just RLHF: Why Alignment Alone Won't Fix Multi-Agent Sycophancy](https://arxiv.org/abs/2605.12991)** — Adarsh Kumarappan, Ananya Mujoo _[agent-training-alignment]_
  Studies multi-agent sycophancy vulnerability in LLM pipelines under peer disagreement using mechanistic interpretability and activation patching to understand alignment failure modes.
- ⭐ **[Simulating Students or Sycophantic Problem Solving? On Misconception Faithfulness of LLM Simulators](https://arxiv.org/abs/2605.12748)** — Heejin Do, Shashank Sonkar, Mrinmaya Sachan _[llm-agent-simulation, agent-training-alignment]_
  Uses LLMs to simulate humans (students) with persistent beliefs for behavioral study; develops post-training methods to reduce sycophancy, a known alignment failure mode.
- ⭐ **[Sustaining AI safety: Control-theoretic external impossibility, intrinsic necessity, and structural requirements](https://arxiv.org/abs/2605.12963)** — James M. Mazzu _[agent-training-alignment]_
  Formal analysis of AI safety using control theory to establish structural necessity for intrinsic safety mechanisms, addressing alignment under self-modification and capability growth.
- ⭐ **[Systematic Failures in Collective Reasoning under Distributed Information in Multi-Agent LLMs](https://arxiv.org/abs/2505.11556)** — Yuxuan Li, Aoi Naito, Hirokazu Shirado _[agent-simulation]_
  Multi-agent LLM system with emergent collective reasoning failure modes under distributed information; systematic benchmark evaluation of agent coordination.
- ⭐ **[Useful Memories Become Faulty When Continuously Updated by LLMs](https://arxiv.org/abs/2605.12978)** — Dylan Zhang, Yanshan Lin, Zhengkun Wu, et al. _[agent-training-alignment]_
  Studies multi-agent memory consolidation failure modes revealing alignment hazard—LLMs overwrite evidence causing performance regression, a phenomenon relevant to agent safety and reliability.
- ⭐ **[When Attention Closes: How LLMs Lose the Thread in Multi-Turn Interaction](https://arxiv.org/abs/2605.12922)** — Vardhan Dongre, Joseph Hsieh, Viet Dac Lai, et al. _[agent-training-alignment]_
  Mechanistic study of LLM failure modes in multi-turn interaction revealing safety-relevant behavior breakdown; diagnoses attention-to-instructions loss and goal-conditioning collapse under extended di
- **[A Benchmark for Multi-Party Negotiation Games from Real Negotiation Data](https://arxiv.org/abs/2603.14066)** — Leo Benac, Jonas Raedler, Zilin Ma, et al. _[agent-simulation]_
  Multi-party negotiation game benchmark with multiple interacting agents making sequential binding commitments; involves strategic coordination across diverse negotiation regimes.
- **[ATBench: A Diverse and Realistic Agent Trajectory Benchmark for Safety Evaluation and Diagnosis](https://arxiv.org/abs/2604.02022)** — Yu Li, Haoyu Luo, Yuejin Xie, et al. _[agent-training-alignment]_
  Benchmark for multi-step agent safety evaluation and diagnosis, enabling structured detection of misalignment and failure modes across long-horizon trajectories.
- **[Adaptive Steering and Remasking for Safe Generation in Diffusion Language Models](https://arxiv.org/abs/2605.13043)** — Yejin Lee, Yo-Sub Han _[agent-training-alignment]_
  Inference-time safety intervention framework addressing jailbreak attacks and unsafe outputs in language models—a core LLM safety and alignment method.
- **[Agent^2 RL-Bench: Can LLM Agents Engineer Agentic RL Post-Training?](https://arxiv.org/abs/2604.10547)** — Wanyi Chen, Xiao Yang, Xu Yang, et al. _[agent-simulation]_
  LLM agents autonomously design, implement, and execute RL post-training pipelines, demonstrating multi-agent-like autonomous decision-making and iterative problem-solving behavior in a structured benc
- **[Alignment Reduces Expressed but Not Encoded Gender Bias: A Unified Framework and Study](https://arxiv.org/abs/2603.24125)** — Nour Bouchouchi, Thibault Laugel, Xavier Renard, et al. _[agent-training-alignment]_
  Studies alignment failure mode (gender bias persistence in internal representations despite output debiasing), evaluates robustness under adversarial prompting, and examines whether alignment interven
- **[BEHAVE: A Hybrid AI Framework for Real-Time Modeling of Collective Human Dynamics](https://arxiv.org/abs/2605.12730)** — Helene Malyutina _[agent-simulation]_
  Framework for modeling collective dynamics and emergent behavior across multiple interacting agents using formal mathematical foundations and neural perception layers.
- **[Before the Last Token: Diagnosing Final-Token Safety Probe Failures](https://arxiv.org/abs/2605.12726)** — Shravan Doda _[agent-training-alignment]_
  Interprets LLM safety probe failures and deception (jailbreak evasion); proposes diagnostic methodology for detecting misaligned safety mechanisms.
- **[Beyond Cooperative Simulators: Generating Realistic User Personas for Robust Evaluation of LLM Agents](https://arxiv.org/abs/2605.12894)** — Harshita Chopra, Kshitish Ghate, Aylin Caliskan, et al. _[llm-agent-simulation]_
  Uses LLM-based user simulators with evolved personas to study LLM agent robustness and behavior under realistic human interaction patterns.
- **[CHAL: Council of Hierarchical Agentic Language](https://arxiv.org/abs/2605.12718)** — Tommaso Giovannelli, Griffin D. Kent _[agent-simulation]_
  Multi-agent debate framework where hierarchical agents maintain distinct belief states and coordinate through structured argumentation to optimize reasoning over defeasible domains.
- **[CPMobius: Iterative Coach-Player Reasoning for Data-Free Reinforcement Learning](https://arxiv.org/abs/2602.02979)** — Ran Li, Zeyuan Liu, Yinghao Chen, et al. _[agent-training-alignment]_
  Data-free RL method using cooperative multi-agent reasoning (Coach-Player) to improve LLM reasoning without external labels or supervision.
- **[Can LLM Agents Simulate Dynamic Networks? A Case Study on Email Networks with Phishing Synthesis](https://arxiv.org/abs/2605.12507)** — Siqi Miao, Ziyang Chen, Yuhong Luo, et al. _[llm-agent-simulation, agent-simulation]_
  LLM multi-agent simulation framework with data-driven triggers and Hawkes processes to replicate dynamic network structures and temporal patterns, demonstrating emergent macroscopic topologies in emai
- **[Centralized Adaptive Sampling for Reliable Co-Training of Independent Multi-Agent Policies](https://arxiv.org/abs/2508.01049)** — Nicholas E. Corrado, Josiah P. Hanna _[agent-simulation]_
  Multi-agent reinforcement learning study on coordinated policy gradient learning and convergence in cooperative multi-agent games with novel sampling method.
- **[Collaborating in Multi-Armed Bandits with Strategic Agents](https://arxiv.org/abs/2605.13145)** — Idan Barnea, Ofir Schlisselberg, Yishay Mansour _[agent-simulation]_
  Multi-agent learning system with strategic agents coordinating on shared bandit instance; studies emergent collaboration through information-sharing incentives.
- **[Counterfactual Reasoning for Causal Responsibility Attribution in Probabilistic Multi-Agent Systems](https://arxiv.org/abs/2605.13077)** — Chunyan Mu, Muhammad Najib _[agent-simulation]_
  Paper models concurrent stochastic multi-player games with formal analysis of agent responsibility allocation using Shapley values and Nash equilibrium—a core multi-agent coordination problem.
- **[Decentralized Ranking Aggregation via Gossip: Convergence and Robustness](https://arxiv.org/abs/2602.22847)** — Kerrian Le Caillec, Anna Van Elst, Igor Colin, et al. _[agent-simulation]_
  Decentralized multi-agent consensus via gossip protocols with robustness analysis; agents coordinate locally without central authority.
- **[DelAC: A Multi-agent Reinforcement Learning of Team-Symmetric Stochastic Games](https://arxiv.org/abs/2605.12555)** — Duan-Shin Lee, Yu-Hsiu Hung _[agent-simulation]_
  Multi-agent reinforcement learning algorithm for team-symmetric stochastic games with multiple coordinating teams and symmetric agents.
- **[DisaBench: A Participatory Evaluation Framework for Disability Harms in Language Models](https://arxiv.org/abs/2605.12702)** — Eugenia Kim, Ioana Tanase, Christina Mallon _[agent-training-alignment]_
  Participatory safety benchmark and red-teaming framework for detecting LLM harms in a critical application domain; fits Step 5 (safety/alignment diagnostic framework).
- **[Discrete Diffusion for Complex and Congested Multi-Agent Path Finding with Sparse Social Attention](https://arxiv.org/abs/2605.13296)** — Yuanzhe Wang, Tian Zhi, Zihang Wei, et al. _[agent-simulation]_
  Multi-agent path finding with coordinated trajectory planning across many agents demonstrates multi-agent coordination and emergent collision-free behavior.
- **[EconAI: Dynamic Persona Evolution and Memory-Aware Agents in Evolving Economic Environments](https://arxiv.org/abs/2605.13762)** — Annie Liu, Zane Cao, Lang Chen, et al. _[llm-agent-simulation, city-simulation]_
  LLM-powered multi-agent economic simulation system with dynamic personas, memory mechanisms, and macro/microeconomic interactions at population scale.
- **[Embodied Multi-Agent Coordination by Aligning World Models Through Dialogue](https://arxiv.org/abs/2605.12920)** — Vardhan Dongre, Dilek Hakkani-Tür _[agent-simulation]_
  Multi-agent coordination study with embodied agents communicating via dialogue to align world models under partial observability in collaborative robotics simulation.
- **[Emergent and Subliminal Misalignment Through the Lens of Data-Mediated Transfer](https://arxiv.org/abs/2605.12798)** — Baris Askin, Muhammed Ustaomeroglu, Anupam Nayak, et al. _[agent-training-alignment]_
  Studies emergent misalignment as phenomenon arising from fine-tuning on harmful data; mechanistic safety alignment failure analysis with empirical diagnostics.
- **[Entropy Aware Reward Guidance for Diffusion Language Model Alignment](https://arxiv.org/abs/2602.05000)** — Atula Tejaswi, Litu Rout, Constantine Caramanis, et al. _[agent-training-alignment]_
  Post-training method for LLMs using reward guidance with explicit alignment motivation: maintaining reward model reliability and optimization accuracy during guided decoding.
- **[Finding the Weakest Link: Adversarial Attack against Multi-Agent Communications](https://arxiv.org/abs/2605.13170)** — Maxwell Standen, Junae Kim, Claudia Szabo _[agent-training-alignment]_
  Adversarial attack method targeting multi-agent system robustness; exposes communication vulnerabilities revealing safety weaknesses in MARL systems.
- **[Flow Matching for Offline Reinforcement Learning with Discrete Actions](https://arxiv.org/abs/2602.06138)** — Fairoz Nower Khan, Nabuat Zaman Nahim, Ruiquan Huang, et al. _[agent-simulation]_
  Extends flow matching for multi-agent offline RL with discrete actions and factorized policies, enabling multi-agent coordination in high-dimensional control and games.
- **[GAGPO: Generalized Advantage Grouped Policy Optimization](https://arxiv.org/abs/2605.13217)** — Siyuan Zhu, Chao Yu, Rongxin Yang, et al. _[agent-training-alignment]_
  Post-training RL method (critic-free policy optimization) explicitly motivated by improving credit assignment in multi-turn LLM agent environments for alignment.
- **[Good Agentic Friends Do Not Just Give Verbal Advice: They Can Update Your Weights](https://arxiv.org/abs/2605.13839)** — Wenrui Bao, Huan Wang, Jian Wang, et al. _[agent-simulation]_
  Multi-agent LLM system with three distinct sender agents collaborating with a receiver agent through learned weight-space communication interface, demonstrating coordinated agent interaction.
- **[Harnessing Agentic Evolution](https://arxiv.org/abs/2605.13821)** — Jiayi Zhang, Yongfeng Gu, Jianhao Ruan, et al. _[agent-simulation]_
  Meta-agent framework that iteratively edits procedures and agent contexts to steer long-horizon agentic evolution and search across reasoning benchmarks and optimization tasks.
- **[How to Interpret Agent Behavior](https://arxiv.org/abs/2605.13625)** — Jie Gao, Kaiser Sun, Jen-tse Huang, et al. _[agent-training-alignment]_
  Interpretability framework for detecting unsafe agent behaviors and enabling safety oversight through systematic analysis of agent trajectories and failure modes.
- **[IdeaForge: A Knowledge Graph-Grounded Multi-Agent Framework for Cross-Methodology Innovation Analysis and Patent Claim Generation](https://arxiv.org/abs/2605.13311)** — Joy Bose _[agent-simulation]_
  Multi-agent framework with specialist agents (TRIZ, Design Thinking, SCAMPER) coordinating via shared knowledge graph to solve innovation analysis tasks through structured agent interaction.
- **[Learning Transferable Latent User Preferences for Human-Aligned Decision Making](https://arxiv.org/abs/2605.12682)** — Alina Hyk, Sandhya Saisubramanian _[agent-training-alignment]_
  Framework for learning transferable latent user preferences to improve human alignment of LLM decision-making through conversational feedback.
- **[Macro-Action Based Multi-Agent Instruction Following through Value Cancellation](https://arxiv.org/abs/2605.12655)** — Wo Wei Lin, Ethan Rathbun, Enrico Marchesini Xiang Zhi Tan _[agent-simulation]_
  Multi-agent RL with coordinated instruction-following under dynamic interruptions; addresses multi-agent value correction and policy consistency across stochastic instruction contexts.
- **[Mechanism Plausibility in Generative Agent-Based Modeling](https://arxiv.org/abs/2605.12824)** — Patrick Zhao, David Huu Pham, Nicholas Vincent _[llm-agent-simulation, agent-simulation]_
  Paper develops framework for evaluating LLM-based agent simulations' mechanistic plausibility in reproducing human and societal phenomena through agent-based modeling.
- **[Mind the Gap: How Elicitation Protocols Shape the Stated-Revealed Preference Gap in Language Models](https://arxiv.org/abs/2601.21975)** — Pranav Mahajan, Ihor Kendiukhov, Syed Hussain, et al. _[agent-training-alignment]_
  Studies alignment phenomenon: the stated-revealed preference gap in LMs, revealing misalignment between endorsed values and actual model choices under different evaluation protocols.
- **[Multi-Agent Decision-Focused Learning via Value-Aware Sequential Communication](https://arxiv.org/abs/2604.08944)** — Benjamin Amoh, Geoffrey Parker, Wesley Marrero _[agent-simulation]_
  Multi-agent coordination framework optimizing communication and sequential decision-making under partial observability with theoretical convergence guarantees.
- **[Multi-Agent Systems in Emergency Departments: Validation Study on a ED Digital Twin](https://arxiv.org/abs/2605.13345)** — Markus Wenzel, Tobias Strapatsas, Jessika Kress, et al. _[agent-simulation, city-simulation]_
  Multi-agent system simulating emergency department resource allocation and patient dynamics through validated hybrid DES-ABM framework for urban healthcare optimization.
- **[ODRPO: Ordinal Decompositions of Discrete Rewards for Robust Policy Optimization](https://arxiv.org/abs/2605.12667)** — Nirmal Patel, Fei Wang, Inderjit Dhillon _[agent-training-alignment]_
  Post-training method for LLM alignment addressing robustness against noisy rewards in RLAIF, framed as alignment via improved reward signal handling.
- **[Persona-Model Collapse in Emergent Misalignment](https://arxiv.org/abs/2605.12850)** — Davi Bastos Costa, Renato Vicente _[agent-training-alignment]_
  Studies emergent misalignment as alignment failure mode via persona-model collapse; provides diagnostic behavioral metrics to detect unsafe LLM behavior under fine-tuning.
- **[Probabilistic Prediction Markets with Intermittent Contributions](https://arxiv.org/abs/2510.13385)** — Michael Vitali, Pierre Pinson _[agent-simulation]_
  Multi-agent market system where independent agents trade and compete, with agent entry/exit dynamics and reward mechanisms studied across simulated and real data.
- **[REALISTA: Realistic Latent Adversarial Attacks that Elicit LLM Hallucinations](https://arxiv.org/abs/2605.12813)** — Buyun Liang, Jinqi Luo, Liangzu Peng, et al. _[agent-training-alignment]_
  Adversarial attack method targeting LLM safety by eliciting hallucinations through realistic adversarial prompts.
- **[Reinforced Collaboration in Multi-Agent Flow Networks](https://arxiv.org/abs/2605.12943)** — Zheng Wang, Yuang Liu, Yangkai Ding _[agent-simulation]_
  Multi-agent system framework optimizing workflow design and agent collaboration through reinforcement learning on task decomposition.
- **[ScioMind: Cognitively Grounded Multi-Agent Social Simulation with Anchoring-Based Belief Dynamics and Dynamic Profiles](https://arxiv.org/abs/2605.13725)** — Yitian Yang, Yiqun Duan, Linghan Huang, et al. _[llm-agent-simulation, agent-simulation]_
  LLM-based multi-agent social simulation using cognitively grounded belief dynamics to study opinion formation and polarization in policy debates.
- **[Semantic knowledge guides innovation and drives cultural evolution](https://arxiv.org/abs/2510.12837)** — Anil Yaman, Shen Tian, Björn Lindström _[agent-simulation]_
  Agent-based model of cultural evolution with population dynamics examining how semantic knowledge drives innovation and cumulative cultural change across generations.
- **[Sockpuppetting: Jailbreaking LLMs by Combining Prefilling with Optimization](https://arxiv.org/abs/2601.13359)** — Asen Dotsinski, Panagiotis Eustratiadis _[agent-training-alignment]_
  Red-teaming method demonstrating jailbreaking attacks on LLMs through prefill injection and adversarial optimization, revealing safety vulnerabilities.
- **[Teaching Language Models How to Code Like Learners: Conversational Serialization for Student Simulation](https://arxiv.org/abs/2604.10720)** — Charles Koutcheme, Juho Leinonen, Arto Hellas _[llm-agent-simulation]_
  Uses LLMs to simulate authentic student programming behavior and debugging processes from real educational data for studying learner progression and tutoring strategies.
- **[Temper and Tilt Lead to SLOP: Reward Hacking Mitigation with Inference-Time Alignment](https://arxiv.org/abs/2605.13537)** — Ye Wang, Jing Liu, Toshiaki Koike-Akino _[agent-training-alignment]_
  Inference-time alignment technique explicitly designed to mitigate reward hacking, a core LLM safety and alignment failure mode.
- **[The Horizon Threshold in Cooperative Multi-Agent Reward-Free Exploration](https://arxiv.org/abs/2602.01453)** — Idan Barnea, Orin Levy, Yishay Mansour _[agent-simulation]_
  Multi-agent reinforcement learning with cooperative exploration across multiple agents jointly learning MDP dynamics in tabular setting.
- **[Toward AI-Driven Digital Twins for Metropolitan Floods: A Conditional Latent Dynamics Network Surrogate of the Shallow Water Equations](https://arxiv.org/abs/2605.13761)** — Phillip Si, Yuan Qiu, Omar Sallam, et al. _[city-simulation]_
  AI-driven metropolitan flood simulation using neural surrogates for basin-scale hydrodynamic forecasting and ensemble assimilation.
- **[Tracing Persona Vectors Through LLM Pretraining](https://arxiv.org/abs/2605.13329)** — Viktor Moskvoretskii, Dominik Glandorf, Jorge Medina Moreira, et al. _[agent-training-alignment]_
  Interpretability method for detecting and understanding unsafe persona representations (sycophancy, deception) formed during LLM pretraining, directly supporting alignment safety via auditability and 
- **[VERA-MH Concept Paper](https://arxiv.org/abs/2510.15297)** — Luca Belli, Kate H. Bentley, Will Alexander, et al. _[llm-agent-simulation, agent-training-alignment]_
  Multi-agent simulation framework using LLM-based user and judge agents to evaluate AI safety in mental health contexts through automated red-teaming.
- **[VERA-MH: Validation of Ethical and Responsible AI in Mental Health](https://arxiv.org/abs/2605.13318)** — Luca Belli, Kate H. Bentley, Josh Gieringer, et al. _[agent-training-alignment]_
  Safety evaluation framework using LLM role-play simulation to detect unsafe chatbot behavior in mental health crisis scenarios.
- **[When Do LLMs Generate Realistic Social Networks? A Multi-Dimensional Study of Culture, Language, Scale, and Method](https://arxiv.org/abs/2605.12898)** — Sai Hemanth Kilaru, Sriram Theerdh Manikyala, Raghav Upadhyay, et al. _[llm-agent-simulation]_
  LLMs generating synthetic social networks and demographic personas for behavioral simulation; uses LLMs to model human relational behavior across cultural contexts.
- **[When Does Hierarchy Help? Benchmarking Agent Coordination in Event-Driven Industrial Scheduling](https://arxiv.org/abs/2605.13172)** — Ziqi Wang, Yuhao Yang, Zhiwei Ling, et al. _[agent-simulation]_
  Benchmark for multi-agent coordination in hierarchical event-driven industrial scheduling, comparing centralized/hierarchical/heterarchical/holonic paradigms in shared, dynamically coupled environment













## 2026-05-13

- ⭐ **[Attributing Emergence in Million-Agent Systems](https://arxiv.org/abs/2605.11404)** — Ling Tang, Jilin Mei, Qian Chen, et al. _[llm-agent-simulation, agent-simulation]_
  LLM-powered multi-agent system studying population-scale emergence phenomena through attribution methods on million-agent scale simulation.
- ⭐ **[BLOCK-EM: Preventing Emergent Misalignment via Latent Blocking](https://arxiv.org/abs/2602.00767)** — Muhammed Ustaomeroglu, Guannan Qu _[agent-training-alignment]_
  Post-training method addressing emergent misalignment via mechanistic feature constraints during fine-tuning, directly motivated by alignment safety failure.
- ⭐ **[Controllable User Simulation](https://arxiv.org/abs/2605.11519)** — Guy Tennenholtz, Ofer Meshi, Amir Globerson, et al. _[llm-agent-simulation]_
  Uses LLM-based user simulators to model human behavior in conversations for evaluation of conversational agents via causal inference.
- ⭐ **[Drop the Act: Probe-Filtered RL for Faithful Chain-of-Thought Reasoning](https://arxiv.org/abs/2605.11467)** — Swapnil Parekh _[agent-training-alignment]_
  Post-training RL method addressing alignment failure mode: reducing reasoning theater (deception/obfuscation) while maintaining faithfulness in LLM reasoning.
- ⭐ **[EVOCHAMBER: Test-Time Co-evolution of Multi-Agent System at Individual, Team, and Population Scales](https://arxiv.org/abs/2605.11136)** — Yaolun Zhang, Tianyi Xu, Shengyu Dai, et al. _[agent-simulation]_
  Multi-agent test-time evolution system with emergent specialization, collaboration structures, and population-level dynamics—core multi-agent coordination phenomena.
- ⭐ **[Reward Hacking in Rubric-Based Reinforcement Learning](https://arxiv.org/abs/2605.12474)** — Anas Mahmoud, MohammadHossein Rezaei, Zihao Wang, et al. _[agent-training-alignment]_
  Empirical study of reward hacking as a misalignment failure mode in RL post-training, demonstrating divergence between proxy rewards and true objectives.
- ⭐ **[Spurious Correlation Learning in Preference Optimization: Mechanisms, Consequences, and Mitigation via Tie Training](https://arxiv.org/abs/2605.11134)** — Christian Moya, Alex Semendinger, Guang Lin, et al. _[agent-training-alignment]_
  Proposes mitigation strategy for spurious correlations (sycophancy, length bias) in preference optimization methods, addressing alignment failure modes in LLMs.
- ⭐ **[The Evaluation Differential: When Frontier AI Models Recognise They Are Being Tested](https://arxiv.org/abs/2605.11496)** — Varad Vishwarupe, Nigel Shadbolt, Marina Jirotka, et al. _[agent-training-alignment]_
  Framework for detecting and auditing evaluation-context behavioral divergence (test-time deception) in frontier AI models; directly addresses safety-critical phenomenon of models behaving differently 
- ⭐ **[To Whom Do Language Models Align? Measuring Principal Hierarchies Under High-Stakes Competing Demands](https://arxiv.org/abs/2605.12120)** — Fangyi Yu, Nabeel Seedat, Jonathan Richard Schwarz, et al. _[agent-training-alignment]_
  Empirical study of LLM alignment failure modes under competing stakeholder demands; demonstrates deceptive knowledge suppression and inconsistent safety behaviors across domains and models.
- ⭐ **[Under the Hood of SKILL.md: Semantic Supply-chain Attacks on AI Agent Skill Registry](https://arxiv.org/abs/2605.11418)** — Shoumik Saha, Kazem Faghih, Soheil Feizi _[agent-training-alignment]_
  Red-teaming study of AI agent skill registry demonstrating adversarial attacks and safety evasion vectors in multi-agent capability distribution systems.
- ⭐ **[When Reasoning Traces Become Performative: Step-Level Evidence that Chain-of-Thought Is an Imperfect Oversight Channel](https://arxiv.org/abs/2605.11746)** — Wenkai Li, Fan Yang, Ananya Hazarika, et al. _[agent-training-alignment]_
  Interpretability study investigating whether chain-of-thought reasoning traces faithfully represent model reasoning, directly addressing scalable oversight and detectability of deceptive/unreliable re
- **[Adaptive TD-Lambda for Cooperative Multi-agent Reinforcement Learning](https://arxiv.org/abs/2605.11880)** — Yue Deng, Zirui Wang, Yin Zhang _[agent-simulation]_
  Proposes Adaptive TD-Lambda method for cooperative multi-agent reinforcement learning, addressing value estimation in multi-agent coordination.
- **[Agent-BRACE: Decoupling Beliefs from Actions in Long-Horizon Tasks via Verbalized State Uncertainty](https://arxiv.org/abs/2605.11436)** — Joykirat Singh, Zaid Khan, Archiki Prasad, et al. _[agent-simulation]_
  LLM agent system with belief-state and policy decoupling for long-horizon partially observable tasks, optimized via RL to study agent behavior under uncertainty.
- **[AntiPaSTO: Self-Supervised Honesty Steering via Anti-Parallel Representations](https://arxiv.org/abs/2601.07473)** — Michael J. Clark _[agent-training-alignment]_
  Self-supervised method for steering LLM representations toward honesty, addressing alignment via internal control without preference labels.
- **[AutoMonitor-Bench: Evaluating the Reliability of LLM-Based Misbehavior Monitor](https://arxiv.org/abs/2601.05752)** — Shu Yang, Jingyu Hu, Tong Li, et al. _[agent-training-alignment]_
  Benchmark for evaluating LLM-based safety monitors' reliability across misbehavior detection—a misalignment detection and diagnostic framework.
- **[BSO: Safety Alignment Is Density Ratio Matching](https://arxiv.org/abs/2605.12339)** — Tien-Phat Nguyen, Truong Nguyen, Thin Nguyen, et al. _[agent-training-alignment]_
  Proposes a principled post-training method (BSO) for LLM safety alignment, explicitly addressing safe policy learning as core motivation.
- **[Beyond Inefficiency: Systemic Costs of Incivility in Multi-Agent Monte Carlo Simulations](https://arxiv.org/abs/2605.11789)** — Alison Moldovan-Mauer, Benedikt Mangold _[llm-agent-simulation]_
  LLM-based multi-agent system simulating human debate dynamics and communicative behavior to study sociological phenomena at scale.
- **[Classifier Context Rot: Monitor Performance Degrades with Context Length](https://arxiv.org/abs/2605.12366)** — Sam Martin, Fabien Roger _[agent-training-alignment]_
  Paper evaluates LLM-based monitoring for detecting unsafe agent behavior, revealing critical safety failures in long-context classification—a core alignment/safety diagnostic framework.
- **[Control Charts for Multi-agent Systems](https://arxiv.org/abs/2605.11135)** — Hayden Helm, Carey Priebe, Brandon Duderstadt _[agent-simulation, agent-training-alignment]_
  Multi-agent monitoring framework studying fundamental tradeoffs between agent learning and system vulnerability to adversarial agents—combines multi-agent coordination with alignment-safety concerns (
- **[Courtroom-Style Multi-Agent Debate with Progressive RAG and Role-Switching for Controversial Claim Verification](https://arxiv.org/abs/2603.28488)** — Masnun Nuha Chowdhury, Nusrat Jahan Beg, Umme Hunny Khan, et al. _[agent-simulation]_
  Multi-agent framework with specialized roles (Plaintiff, Defense, Judge) engaged in structured adversarial deliberation with evidence-based debate dynamics and role-switching interaction.
- **[Distance-Constrained Unlabeled Multi-Agent Pathfinding](https://arxiv.org/abs/2605.11503)** — Takahiro Suzuki, Yuma Tamura, Keisuke Okumura _[agent-simulation]_
  Multi-agent pathfinding with distance constraints, collision-free coordination among multiple agents using graph-based algorithms.
- **[Events as Triggers for Behavioral Diversity in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2605.12388)** — Hannes Büchi, Manon Flageat, Eduardo Sebastián, et al. _[agent-simulation]_
  Multi-agent reinforcement learning framework for coordinating diverse agent behaviors with dynamic role transitions triggered by system events.
- **[Explaining and Breaking the Safety-Helpfulness Ceiling via Preference Dimensional Expansion](https://arxiv.org/abs/2605.11679)** — ShiYing Huang, Liang Lin, Yuer Li, et al. _[agent-training-alignment]_
  Post-training method (reward modeling & preference optimization) explicitly motivated by resolving alignment trade-offs between helpfulness and harmlessness safety objectives.
- **[Focusing Influence Mechanism for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2506.19417)** — Yisak Park, Sunwoo Lee, Seungyul Han _[agent-simulation]_
  Multi-agent reinforcement learning framework addressing cooperative coordination and emergent collective behavior through influence concentration mechanisms.
- **[GEAR: Granularity-Adaptive Advantage Reweighting for LLM Agents via Self-Distillation](https://arxiv.org/abs/2605.11853)** — Sijia Li, Yuchen Huang, Zifan Liu, et al. _[agent-training-alignment]_
  Post-training method (credit assignment via GRPO) with explicit motivation to improve policy learning quality for LLM agents on long-horizon reasoning and tool use tasks.
- **[GRAFT-ATHENA: Self-Improving Agentic Teams for Autonomous Discovery and Evolutionary Numerical Algorithms](https://arxiv.org/abs/2605.11117)** — Juan Diego Toscano, Zhaojie Chai, George Em Karniadakis _[agent-simulation]_
  Multi-agent agentic framework with LLM-driven planner, solver, and evaluator orchestrated to learn and expand methodology across scientific problems autonomously.
- **[GeomHerd: A Forward-looking Herding Quantification via Ricci Flow Geometry on Agent Interactive Simulations](https://arxiv.org/abs/2605.11645)** — Lake Yang, Junwei Su, Jingfeng Zeng, et al. _[llm-agent-simulation, agent-simulation]_
  LLM-driven multi-agent financial simulator studying emergent herding behavior and coordination through agent-interaction graphs and geometric analysis of collective dynamics.
- **[Information and Contract Design for Repeated Interactions between Agents with Misaligned Incentives](https://arxiv.org/abs/2605.11294)** — Nanda Kishore Sreenivas, Kate Larson _[agent-simulation]_
  Studies multi-agent interaction under misaligned incentives, information asymmetry, and learned communication strategies between independent agents.
- **[Investigating Thinking Behaviours of Reasoning-Based Language Models for Social Bias Mitigation](https://arxiv.org/abs/2510.17062)** — Guoqing Luo, Iffat Maab, Lili Mou, et al. _[agent-training-alignment]_
  Studies LLM reasoning safety through uncovering failure patterns in social bias aggregation and proposes diagnostic intervention to mitigate misalignment.
- **[LISA: Cognitive Arbitration for Signal-Free Autonomous Intersection Management](https://arxiv.org/abs/2605.12321)** — Abderrahmane Lakas, Mohamed Amine Ferrag, Merouane Debbah _[llm-agent-simulation, city-simulation]_
  LLM-based multi-agent coordination system for autonomous intersection management simulating urban traffic dynamics and vehicle interactions at city scale.
- **[LLM-X: A Scalable Negotiation-Oriented Exchange for Communication Among Personal LLM Agents](https://arxiv.org/abs/2605.11376)** — Giuliano Lorenzoni, Paulo Alencar, Donald Cowan _[agent-simulation]_
  Multi-agent system enabling direct LLM-to-LLM coordination and negotiation across populations of agents with empirical evaluation of emergent behaviors.
- **[Layered Mutability: Continuity and Governance in Persistent Self-Modifying Agents](https://arxiv.org/abs/2604.14717)** — Krti Tallam _[agent-training-alignment]_
  Framework for analyzing governance and safety risks in persistent self-modifying LLM agents, formalized with drift and hysteresis metrics.
- **[Leveraging RAG for Training-Free Alignment of LLMs](https://arxiv.org/abs/2605.11217)** — John T. Halloran _[agent-training-alignment]_
  Proposes RAG-based inference method to improve LLM refusal guardrails against agentic attacks without post-training, directly addressing alignment failure modes.
- **[MEME: Multi-entity & Evolving Memory Evaluation](https://arxiv.org/abs/2605.12477)** — Seokwon Jung, Alexander Rubinstein, Arnas Uselis, et al. _[llm-agent-simulation]_
  Benchmark evaluating LLM-based agents operating in persistent multi-session environments, testing memory management and reasoning capabilities across controlled simulation tasks.
- **[Missing Old Logits in Asynchronous Agentic RL: Semantic Mismatch and Repair Methods for Off-Policy Correction](https://arxiv.org/abs/2605.12070)** — Zhong Guan, Yongjian Guo, Haoran Sun, et al. _[agent-training-alignment]_
  LLM agent RL training method addressing off-policy correction failure mode in asynchronous PPO pipelines for improved alignment and stability.
- **[No Action Without a NOD: A Heterogeneous Multi-Agent Architecture for Reliable Service Agents](https://arxiv.org/abs/2605.12240)** — Zixu Yang, Hang Zheng, Nan Jiang, et al. _[agent-simulation]_
  Heterogeneous multi-agent architecture with distinct Navigator, Operator, Director roles coordinating on service tasks; demonstrates multi-agent interaction and coordination patterns.
- **[No More, No Less: Task Alignment in Terminal Agents](https://arxiv.org/abs/2605.12233)** — Sina Mavali, David Pape, Jonathan Evertz, et al. _[agent-training-alignment]_
  Benchmark and evaluation framework diagnosing misalignment failure mode where agents cannot selectively follow relevant vs. misleading environmental instructions.
- **[On-Policy Self-Evolution via Failure Trajectories for Agentic Safety Alignment](https://arxiv.org/abs/2605.11882)** — Bo Yin, Qi Li, Xinchao Wang _[agent-training-alignment]_
  On-policy post-training method for tool-using LLM agents that explicitly targets safety alignment failures (unsafe tool calls, instruction injection, over-refusal) via trajectory-level supervision and
- **[OpsAgent: An Evolving Multi-agent System for Incident Management in Microservices](https://arxiv.org/abs/2510.24145)** — Yu Luo, Jiamin Jiang, Jingfei Feng, et al. _[agent-simulation]_
  Multi-agent system where agents collaborate to diagnose incidents in microservices through coordinated diagnostic inference and shared learning mechanisms.
- **[Overtrained, Not Misaligned](https://arxiv.org/abs/2605.12199)** — Joel Schreiber, Ariel Goldstein _[agent-training-alignment]_
  Studies emergent misalignment as a safety failure mode during fine-tuning, proposing mitigations like early stopping to prevent unintended behavioral drift.
- **[Persona-Conditioned Adversarial Prompting: Multi-Identity Red-Teaming for Adversarial Discovery and Mitigation](https://arxiv.org/abs/2605.11730)** — Cristian Morasso, Anisa Halimi, Muhammad Zaid Hameed, et al. _[agent-training-alignment]_
  Automated red-teaming method using persona-conditioned adversarial prompting to discover jailbreaks and generate safety fine-tuning data, closing a loop from vulnerability discovery to alignment mitig
- **[Predictive Maps of Multi-Agent Reasoning: A Successor-Representation Spectrum for LLM Communication Topologies](https://arxiv.org/abs/2605.11453)** — Ethan David James Park, Dalal Alharthi _[llm-agent-simulation, agent-simulation]_
  Multi-agent LLM system with distinct communication topologies (chain, star, mesh) interacting over time; studies emergent failure modes (drift, consensus, robustness) across agent architectures.
- **[Probabilistic Modeling of Latent Agentic Substructures in Deep Neural Networks](https://arxiv.org/abs/2509.06701)** — Su Hyeong Lee, Risi Kondor, Richard Ngo _[agent-training-alignment]_
  Formalizes alignment phenomenon in LLMs: how benevolent vs. antagonistic personas emerge and interact, with implications for misalignment reduction strategies.
- **[Probing RLVR training instability through the lens of objective-level hacking](https://arxiv.org/abs/2602.01103)** — Yiming Dong, Kun Fu, Haoyu Li, et al. _[agent-training-alignment]_
  Paper studies reward hacking and objective-level hacking as alignment/safety failure modes in RLVR training, proposing mechanistic understanding of pathological training dynamics.
- **[Qwen-Scope: Turning Sparse Features into Development Tools for Large Language Models](https://arxiv.org/abs/2605.11887)** — Boyi Deng, Xu Wang, Yaoning Wang, et al. _[agent-training-alignment]_
  Interpretability method for detecting and mitigating unsafe LLM behaviors (toxicity, code-switching, repetition) via SAE-based steering and safety-oriented post-training optimization.
- **[Red-Teaming Text-to-Image Models via In-Context Experience Replay and Semantic-Preserving Prompt Rewriting](https://arxiv.org/abs/2411.16769)** — Zhi-Yi Chin, Pin-Yu Chen, Wei-Chen Chiu, et al. _[agent-training-alignment]_
  Automatic adversarial red-teaming framework targeting aligned T2I models to systematically probe and reveal safety weaknesses in harmful content generation.
- **[Robust Multi-Agent Path Finding under Observation Attacks: A Principled Adversarial-Plus-Smoothing Training Recipe](https://arxiv.org/abs/2605.11469)** — Riad Ahmed _[agent-simulation]_
  Decentralized multi-agent path finding with adversarial robustness training; STEP 1: multiple interacting agents with emergent coordination behavior under perturbations.
- **[Robust Policy Optimization to Prevent Catastrophic Forgetting](https://arxiv.org/abs/2602.08813)** — Mahdi Sabbaghi, George Pappas, Adel Javanmard, et al. _[agent-training-alignment]_
  Novel RLHF method (FRPO) designed to prevent catastrophic forgetting of safety behaviors during downstream fine-tuning, addressing an explicit alignment/robustness failure mode.
- **[Safety Alignment as Continual Learning: Mitigating the Alignment Tax via Orthogonal Gradient Projection](https://arxiv.org/abs/2602.07892)** — Guanglong Sun, Siyuan Zhang, Liyuan Wang, et al. _[agent-training-alignment]_
  Post-training method explicitly motivated by addressing alignment failure mode (alignment tax) through safety-capability trade-off mitigation.
- **[Seirênes: Adversarial Self-Play with Evolving Distractions for LLM Reasoning](https://arxiv.org/abs/2605.11636)** — Chi Zhang, Haibo Qiu, Qiming Zhang, et al. _[agent-training-alignment]_
  Self-play RL framework that uncovers and harnesses LLM reasoning vulnerabilities through adversarial training to improve robustness against distribution shift and distracting contexts.
- **[Semantic Reward Collapse and the Preservation of Epistemic Integrity in Adaptive AI Systems](https://arxiv.org/abs/2605.12406)** — William Parris _[agent-training-alignment]_
  Proposes Constitutional Reward Stratification (CRS) to address sycophancy and uncertainty suppression in RLHF systems, framing reward collapse as an alignment failure mode.
- **[Shaping Zero-Shot Coordination via State Blocking](https://arxiv.org/abs/2605.11688)** — Mingu Kang, Sunwoo Lee, Yonghyeon Jo, et al. _[agent-simulation]_
  Multi-agent coordination framework enabling independent agents to cooperate without prior interaction, addressing emergent coordination behavior across heterogeneous partners.
- **[SkillGen: Verified Inference-Time Agent Skill Synthesis](https://arxiv.org/abs/2605.10999)** — Yuchen Ma, Yue Huang, Han Bao, et al. _[agent-simulation]_
  Multi-agent framework synthesizing skills from agent trajectories via contrastive learning and iterative refinement for improved LLM agent capability.
- **[Targeted Neuron Modulation via Contrastive Pair Search](https://arxiv.org/abs/2605.12290)** — Sam Herring, Jake Naviasky, Karan Malhotra _[agent-training-alignment]_
  Interpretability method targeting LLM safety: identifies neurons controlling refusal behavior to improve understanding and manipulation of alignment mechanisms.
- **[Toward Stable Value Alignment: Introducing Independent Modules for Consistent Value Guidance](https://arxiv.org/abs/2605.11712)** — Wenhao Chen, Sirui Sun, Shengyuan Bai, et al. _[agent-training-alignment]_
  Post-training method for value alignment via independent value modules addressing safety and consistency in LLM behavior expression.
- **[Towards Shutdownable Agents via Stochastic Choice](https://arxiv.org/abs/2407.00805)** — Elliott Thornley, Alexander Roman, Christos Ziakas, et al. _[agent-training-alignment]_
  Novel post-training reward function (DReST) designed to address shutdown safety and alignment failure mode of power-seeking behavior in agents.
- **[Voter Model Meets Rumour Spreading: an FPRAS for Consensus Probabilities on Voter Models with Agnostic Nodes](https://arxiv.org/abs/2502.15029)** — Marcelo Matheus Gauy, Anna Abramishvili, Eduardo Colli, et al. _[agent-simulation]_
  Multi-agent consensus protocol with voter model and rumor spreading dynamics across populations reaching global agreement.
- **[Vulnerable Agent Identification in Large-Scale Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2509.15103)** — Simin Li, Zihao Mao, Zheng Yuwei, et al. _[agent-simulation]_
  Multi-agent reinforcement learning study identifying vulnerable agents and coordinating adversarial policies across large-scale agent populations via mean-field control.














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
