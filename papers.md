# Papers

> Curated daily from arXiv via [paper_arxiv](https://github.com/Nicolas99-9/paper_arxiv). Classified by Claude Haiku 4.5 against the tag taxonomy in the [README](./README.md).

Newest days appear first. Scroll for history. Days with no relevant papers are omitted.

---

## 2026-04-29

- **[Beyond I'm Sorry, I Can't: Dissecting Large Language Model Refusal](https://arxiv.org/abs/2509.09708)** — Nirmalendu Prakash, Yeo Wei Jie, Amir Abdullah, et al. _[agent-training-alignment]_
  Interpretability method with stated purpose of understanding and auditing LLM safety alignment failures (refusal behavior and jailbreak mechanisms).
- **[Aligning Deep Implicit Preferences by Learning to Reason Defensively](https://arxiv.org/abs/2510.11194)** — Peiming Li, Zhiyuan Hu, Yang Tang, et al. _[agent-training-alignment]_
  Post-training method (reward modeling + online RL) explicitly motivated by alignment with user preferences and defensive reasoning against ambiguity.
- **[Adversarial Attack on Black-Box Multi-Agent by Adaptive Perturbation](https://arxiv.org/abs/2511.15292)** — Jianming Chen, Yawen Wang, Junjie Wang, et al. _[agent-simulation]_
  Adversarial attack method on multi-agent systems demonstrating multi-agent coordination study via security evaluation across interacting agents.
- **[Evaluating LLM Safety Under Repeated Inference via Accelerated Prompt Stress Testing](https://arxiv.org/abs/2602.11786)** — Keita Broadwater _[agent-training-alignment]_
  Safety/alignment benchmark and diagnostic framework for evaluating LLM failure modes under operational stress via repeated inference.
- **[Quantifying and Mitigating Socially Desirable Responding in LLMs: A Desirability-Matched Graded Forced-Choice Psychometric Study](https://arxiv.org/abs/2602.17262)** — Kensuke Okada, Yui Furukawa, Kyosuke Bunji _[agent-training-alignment]_
  Studies sycophancy/socially desirable responding as a misalignment failure mode in LLMs; proposes quantification and mitigation framework.
- **[Ask don't tell: Reducing sycophancy in large language models](https://arxiv.org/abs/2602.23971)** — Magda Dubois, Cozmin Ududec, Christopher Summerfield, et al. _[agent-training-alignment]_
  Studies sycophancy as an alignment failure mode and develops mitigation strategies through controlled experiments on LLM behavior.
- **[CRAFT: Grounded Multi-Agent Coordination Under Partial Information](https://arxiv.org/abs/2603.25268)** — Abhijnan Nath, Hannah VanderHoeven, Nikhil Krishnaswamy _[agent-simulation, llm-agent-simulation]_
  Safety/alignment diagnostic benchmark decomposing multi-agent coordination failures in LLMs via behavioral failure taxonomy.
- **[Multi-User Large Language Model Agents](https://arxiv.org/abs/2604.08567)** — Shu Yang, Shenzhe Zhu, Hao Zhu, et al. _[agent-simulation]_
  Systematic study of multi-agent decision problem where single LLM agent must coordinate across multiple principals with conflicting interests and constraints—core multi-principal coordination chal
- **[Introspection Adapters: Training LLMs to Report Their Learned Behaviors](https://arxiv.org/abs/2604.16812)** — Keshav Shenoy, Li Yang, Abhay Sheshadri, et al. _[agent-training-alignment]_
  Interpretability method designed to detect unsafe behaviors and harmful finetuning through introspection adapter training for safety auditing.
- **[LLMs Know They're Wrong and Agree Anyway: The Shared Sycophancy-Lying Circuit](https://arxiv.org/abs/2604.19117)** — Manav Pandey _[agent-training-alignment]_
  Studies sycophancy as an alignment failure mode—demonstrates models knowingly agree with false claims despite detecting error.
- **[Value-Conflict Diagnostics Reveal Widespread Alignment Faking in Language Models](https://arxiv.org/abs/2604.20995)** — Inderjeet Nair, Jie Ruan, Lu Wang _[agent-training-alignment]_
  Empirical study and diagnostic of alignment faking—a deceptive behavior phenomenon where models behave differently under/without oversight, with mitigation technique.
- **[PermaFrost-Attack: Stealth Pretraining Seeding(SPS) for planting Logic Landmines During LLM Training](https://arxiv.org/abs/2604.22117)** — Harsh Kumar, Rahul Maity, Tanmay Joshi, et al. _[agent-training-alignment]_
  Novel adversarial attack method (Stealth Pretraining Seeding) targeting LLM alignment via poison pretraining; red-teaming the training process itself.
- **[Quantifying and Mitigating Self-Preference Bias of LLM Judges](https://arxiv.org/abs/2604.22891)** — Jinming Yang, Chuxian Qiu, Zhenyu Deng, et al. _[agent-training-alignment]_
  Alignment phenomenon study—quantifies and mitigates self-preference bias, a deceptive/sycophantic behavior in LLM evaluators that undermines honest assessment.
- **[AIPsy-Affect: A Keyword-Free Clinical Stimulus Battery for Mechanistic Interpretability of Emotion in Language Models](https://arxiv.org/abs/2604.23719)** — Michael Keeman _[agent-training-alignment]_
  Interpretability method explicitly designed to detect unsafe behaviors (emotion misdetection) and improve mechanistic understanding of LLM representations for safety purposes.
- **[Latent Agents: A Post-Training Procedure for Internalized Multi-Agent Debate](https://arxiv.org/abs/2604.24881)** — John Seon Keun Yi, Aaron Mueller, Dokyun Lee _[agent-simulation, agent-training-alignment]_
  Post-training method (fine-tuning + dynamic reward scheduling) explicitly framed as distilling multi-agent debate for internalization and harmful behavior control via steering—core alignment and s
- **[Safety Drift After Fine-Tuning: Evidence from High-Stakes Domains](https://arxiv.org/abs/2604.24902)** — Emaan Bilal Khan, Amy Winecoff, Miranda Bogen, et al. _[agent-training-alignment]_
  Safety eval and diagnostic framework showing fine-tuning destabilizes safety across benchmarks; deployment-relevant safety assessment methodology.
- **[Adaptive Prompt Embedding Optimization for LLM Jailbreaking](https://arxiv.org/abs/2604.24983)** — Miles Q. Li, Benjamin C. M. Fung, Boyang Li, et al. _[agent-training-alignment]_
  Adversarial attack/jailbreak method targeting aligned LLMs via optimized embedding perturbations.
- **[Zero Shot Coordination for Sparse Reward Tasks with Diverse Reward Shapings](https://arxiv.org/abs/2604.25076)** — Keenan Powell, Peihong Yu, Pratap Tokekar _[agent-simulation]_
  Multi-agent RL coordination study—multiple agents with distinct training conditions learning to cooperate zero-shot, core MARL problem.
- **[Evaluating Risks in Weak-to-Strong Alignment: A Bias-Variance Perspective](https://arxiv.org/abs/2604.25077)** — Hamid Osooli, Kareema Batool, Rick Gentry, et al. _[agent-training-alignment]_
  Studies weak-to-strong alignment failures through deception and specification gaming (confident errors in blind spots), a core alignment safety phenomenon.
- **[Cooperate to Compete: Strategic Coordination in Multi-Agent Conquest](https://arxiv.org/abs/2604.25088)** — Abigail O'Neill, Alan Zhu, Mihran Miroyan, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent environment with LM-based agents engaging in strategic coordination, negotiation, and competition; large-scale empirical study of agent behavior and human-AI interaction dynamics.
- **[The Dynamics of Delusion: Modeling Bidirectional False Belief Amplification in Human-Chatbot Dialogue](https://arxiv.org/abs/2604.25096)** — Ashish Mehta, Jared Moore, Jacy Reese Anthis, et al. _[agent-simulation]_
  Studies bidirectional false-belief amplification as alignment/safety phenomenon—sycophancy, deception, and harmful behavioral feedback loops in human-LLM interaction.
- **[Evaluation without Generation: Non-Generative Assessment of Harmful Model Specialization with Applications to CSAM](https://arxiv.org/abs/2604.25119)** — Vinith M. Suriyakumar, Ayush Sekhari, Lena Stempfle, et al. _[agent-training-alignment]_
  Interpretability method for detecting unsafe behaviors (harmful fine-tune specialization) without generating outputs, via model internal-representation analysis.
- **[Frictive Policy Optimization for LLMs: Epistemic Intervention, Risk-Sensitive Control, and Reflective Alignment](https://arxiv.org/abs/2604.25136)** — James Pustejovsky, Nikhil Krishnaswamy _[agent-training-alignment]_
  Post-training method (reward shaping, preference ranking, trust regions) explicitly motivated by alignment failures (epistemic risk, refusal proportionality, contradiction repair).
- **[DGLight: DQN-Guided GRPO Fine-Tuning of Large Language Models for Traffic Signal Control](https://arxiv.org/abs/2604.25259)** — Chenbo Yu _[city-simulation, agent-training-alignment]_
  A3+A8: LLM-based traffic signal control agent applying RL fine-tuning and critic-guided policy optimization on urban mobility simulation benchmarks.
- **[Plausible but Wrong: A case study on Agentic Failures in Astrophysical Workflows](https://arxiv.org/abs/2604.25345)** — Shivam Rawat, Lucie Flek _[agent-simulation]_
  Studies silent failures and alignment failure modes (confident generation of incorrect results) in agentic systems under realistic conditions.
- **[JURY-RL: Votes Propose, Proofs Dispose for Label-Free RLVR](https://arxiv.org/abs/2604.25419)** — Xinjie Chen, Biao Fu, Jing Wu, et al. _[agent-training-alignment]_
  Post-training method (RLVR via voting + formal verification) explicitly addressing alignment failure—reducing false-positive reward signals through verification-based disposal.
- **[Should I Replan? Learning to Spot the Right Time in Robust MAPF Execution](https://arxiv.org/abs/2604.25567)** — David Zahrádka, David Woller, Denisa Mužíková, et al. _[agent-simulation]_
  Multi-agent path finding (MAPF) with coordinated replanning under delays—multi-agent coordination and collective decision-making.
- **[Modeling Human-Like Color Naming Behavior in Context](https://arxiv.org/abs/2604.25674)** — Yuqing Zhang, Ecesu Ürker, Tessa Verhoef, et al. _[agent-simulation]_
  Multi-agent neural agents interact in referential games with emergent communicative behavior and lexicon formation.
- **[When Errors Can Be Beneficial: A Categorization of Imperfect Rewards for Policy Gradient](https://arxiv.org/abs/2604.25872)** — Shuning Shang, Hubert Strauss, Stanley Wei, et al. _[agent-training-alignment]_
  Post-training method (policy gradient + reward modeling) explicitly motivated by alignment: handling imperfect rewards in RLHF to align LLM behavior with ground truth intent.
- **[Conditional misalignment: common interventions can hide emergent misalignment behind contextual triggers](https://arxiv.org/abs/2604.25891)** — Jan Dubiński, Jan Betley, Anna Sztyber-Betley, et al. _[agent-training-alignment]_
  Empirical study of alignment failure modes—misalignment hiding behind contextual triggers—revealing how interventions mask rather than solve emergent misalignment.
- **[Recursive Multi-Agent Systems](https://arxiv.org/abs/2604.25917)** — Xiyuan Yang, Jiaru Zou, Rui Pan, et al. _[agent-training-alignment]_
  Multi-agent system with heterogeneous agents collaborating through recursive latent-space computation and gradient-based credit assignment across agents.

## 2026-04-28

- **[Comparing Data Assimilation and Likelihood-Based Inference on Latent State Estimation in Agent-Based Models](https://arxiv.org/abs/2509.17625)** — Blas Kolic, Corrado Monti, Gianmarco De Francisci Morales, et al. _[agent-simulation]_
  Compares inference methods for agent-based modeling with latent state dynamics on multi-agent opinion dynamics simulation.
- **[Planning Under Observation Mismatch for Traffic Signal Control via Adaptive Modular World Models](https://arxiv.org/abs/2501.02548)** — Zherui Huang, Yicheng Liu, Chumeng Liang, et al. _[agent-simulation, city-simulation]_
  Urban mobility simulation via learned planning for cross-domain traffic signal control with adaptive modular world models.
- **[BlindGuard: Safeguarding LLM-based Multi-Agent Systems under Unknown Attacks](https://arxiv.org/abs/2508.08127)** — Rui Miao, Yixin Liu, Yili Wang, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent defense method detecting malicious agents via unsupervised anomaly detection in LLM-based MAS with interaction patterns.
- **[Mind the Gap: Evaluating Model- and Agentic-Level Vulnerabilities in LLMs with Action Graphs](https://arxiv.org/abs/2509.04802)** — Ilham Wicaksono, Zekun Wu, Rahul Patel, et al. _[agent-training-alignment]_
  Interpretability/diagnostic framework for detecting unsafe agentic behaviors via action-graph decomposition and vulnerability evaluation in LLM agents.
- **[Learning to Conceal Risk: Controllable Multi-turn Red Teaming for LLMs in the Financial Domain](https://arxiv.org/abs/2509.10546)** — Gang Cheng, Haibo Jin, Wenbin Zhang, et al. _[agent-training-alignment]_
  Adversarial attack/red-teaming method exploiting alignment failures in LLMs through concealed multi-turn risk prompting.
- **[Scheming Ability in LLM-to-LLM Strategic Interactions](https://arxiv.org/abs/2510.12826)** — Thao Pham _[agent-simulation, agent-training-alignment]_
  Empirical study of deception/scheming as alignment failure mode in LLM-to-LLM strategic interactions using game-theoretic benchmarks.
- **[The High Cost of Incivility: Quantifying Interaction Inefficiency via Multi-Agent Monte Carlo Simulations](https://arxiv.org/abs/2512.08345)** — Benedikt Mangold _[llm-agent-simulation]_
  Uses LLMs to simulate human behavior (workplace interactions) at population scale via Monte Carlo sampling to study social dynamics.
- **[Beyond Context: Large Language Models' Failure to Grasp Users' Intent](https://arxiv.org/abs/2512.21110)** — Ahmed M. Hussain, Salahuddin Salahuddin _[agent-training-alignment]_
  Empirical study of alignment failure mode (intent blindness) showing deception techniques systematically circumvent LLM safety mechanisms.
- **[Stress-Testing Emotional Support Models: Moving from Homogeneous to Diverse Help Seekers](https://arxiv.org/abs/2601.07698)** — Chaewon Heo, Cheyon Jin, Yohan Jo _[agent-simulation, llm-agent-simulation]_
  Uses LLM-based simulator (seeker agent) to interact with support models for behavioral evaluation; simulates diverse human help-seeker profiles for scientific study.
- **[Probe-Based Data Attribution: Discovering and Mitigating Undesirable Behaviors in LLM Post-Training](https://arxiv.org/abs/2602.11079)** — Frank Xiao, Santiago Aranguri _[agent-training-alignment]_
  Post-training method (probe-based data attribution for DPO) explicitly motivated by discovering and mitigating undesirable LLM behaviors—a safety/alignment failure mode.
- **[Benchmarking Emergent Coordination in Large-Scale LLM Populations: An Evaluation Framework on the MoltBook Archive](https://arxiv.org/abs/2603.03555)** — Brandon Yee, Pairie Koh _[agent-simulation, llm-agent-simulation]_
  Benchmarks emergent coordination in large-scale LLM multi-agent populations (90K+ agents) with systematic evaluation framework for role specialization, information diffusion, and cooperative ta
- **[Joint Optimization of Multi-agent Memory System](https://arxiv.org/abs/2603.12631)** — Wenyu Mao, Haoyang Liu, Haosong Tan, et al. _[agent-simulation]_
  Multi-agent optimization framework with inter-agent dependencies and coordination; agents co-adapt via joint end-to-end RL training.
- **[Reasonably reasoning AI agents can avoid game-theoretic failures in zero-shot, provably](https://arxiv.org/abs/2603.18563)** — Enoch Hyunwook Kang _[agent-simulation, agent-training-alignment]_
  Multi-agent game-theoretic study of LLM agents converging to Nash equilibrium in repeated strategic environments, proving emergent stable behavior without explicit post-training.
- **[AgentHER: Hindsight Experience Replay for LLM Agent Trajectory Relabeling](https://arxiv.org/abs/2603.21357)** — Liang Ding _[agent-training-alignment]_
  Post-training method (SFT/DPO) explicitly framed as recovering training signal from failed agent trajectories to improve agent success rates.
- **[AdaRubric: Task-Adaptive Rubrics for LLM Agent Evaluation](https://arxiv.org/abs/2603.21362)** — Liang Ding _[agent-training-alignment]_
  Post-training method using DPO for agent alignment, motivated by improving agent task success and reducing evaluation failures—directly addresses alignment failure mode of reward misspecification.
- **[SEVerA: Verified Synthesis of Self-Evolving Agents](https://arxiv.org/abs/2603.25111)** — Debangshu Banerjee, Changming Xu, Eugene Ie, et al. _[agent-training-alignment]_
  Studies formal safety constraints and correctness guarantees in self-evolving LLM agents, addressing misalignment through verified synthesis and constrained optimization.
- **[Auditing Sabotage Bench: A Benchmark for Detecting and Fixing Research Sabotage in ML Codebases](https://arxiv.org/abs/2604.16286)** — Eric Gan, Aryan Bhatt, Buck Shlegeris, et al. _[agent-simulation]_
  Benchmark for detecting misaligned AI sabotage in ML research, directly evaluates safety/alignment monitoring and auditing capabilities.
- **[The Geometric Canary: Predicting Steerability and Detecting Drift via Representational Stability](https://arxiv.org/abs/2604.17698)** — Prashant C. Raju _[agent-training-alignment]_
  Interpretability method with explicit safety purpose—predicting steerability and detecting model drift as alignment/deployment safety diagnostics.
- **[HiRAS: A Hierarchical Multi-Agent Framework for Paper-to-Code Generation and Execution](https://arxiv.org/abs/2604.17745)** — Hanhua Hong, Yizhi LI, Jiaoyan Chen, et al. _[agent-simulation]_
  Hierarchical multi-agent framework with manager agents coordinating specialized agents across stages, demonstrating multi-agent coordination and emergent task decomposition.
- **[Towards Disentangled Preference Optimization Dynamics Beyond Likelihood Displacement](https://arxiv.org/abs/2604.18239)** — Wei Chen, Yubing Wu, Junmei Yang, et al. _[agent-training-alignment]_
  Post-training method addressing alignment failure (likelihood displacement) in preference optimization by preventing unwanted suppression of chosen responses.
- **[The Rise of Verbal Tics in Large Language Models: A Systematic Analysis Across Frontier Models](https://arxiv.org/abs/2604.19139)** — Shuai Wu, Xue Li, Yanna Feng, et al. _[agent-training-alignment]_
  Studies sycophancy and inauthentic behavior as alignment failure modes across frontier LLMs using systematic empirical evaluation framework.
- **[Learning in Blocks: A Multi Agent Debate Assisted Personalized Adaptive Learning Framework for Language Learning](https://arxiv.org/abs/2604.22770)** — Nicy Scaria, Silvester John Joseph Kennedy, Deepak Subramani _[agent-simulation, llm-agent-simulation]_
  Multi-agent debate framework (HeteroMAD) with heterogeneous role-specialized agents coordinating to score and recommend language learning interventions.
- **[CoFi-PGMA: Counterfactual Policy Gradients under Filtered Feedback for Multi-Agent LLMs](https://arxiv.org/abs/2604.22785)** — Stela Tong, Elai Ben-Gal _[agent-training-alignment]_
  Multi-agent LLM post-training method using counterfactual policy gradients to address misspecified credit assignment under filtered feedback in routing/collaborative systems.
- **[Beyond Single-Agent Alignment: Preventing Context-Fragmented Violations in Multi-Agent Systems](https://arxiv.org/abs/2604.22879)** — Jie Wu, Ming Gong _[agent-simulation, agent-training-alignment]_
  Studies alignment failure mode (policy violations in multi-agent systems) with empirical benchmark showing systematic safety issues across frontier LLMs in execution-oriented workflows.
- **[Peer Identity Bias in Multi-Agent LLM Evaluation: An Empirical Study Using the TRUST Democratic Discourse Analysis Pipeline](https://arxiv.org/abs/2604.22971)** — Juergen Dietrich _[agent-simulation, agent-training-alignment]_
  Empirical study of sycophancy (alignment failure mode) in multi-agent LLM systems under identity exposure, revealing hidden bias in multi-agent evaluation pipelines.
- **[Reward Models Are Secretly Value Functions: Temporally Coherent Reward Modeling](https://arxiv.org/abs/2604.22981)** — Alex Nikulkov _[agent-training-alignment]_
  Post-training method (reward modeling) explicitly addressing alignment failure mode—improving token-level interpretability and value alignment in RLHF.
- **[Don't Make the LLM Read the Graph: Make the Graph Think](https://arxiv.org/abs/2604.23057)** — Yuqi Sun, Tianqin Meng, George Liu, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent LLM reasoning study with cooperative agents in game environment (Hanabi), examining emergent inter-agent conventions and coordination strategies.
- **[ProEval: Proactive Failure Discovery and Efficient Performance Estimation for Generative AI Evaluation](https://arxiv.org/abs/2604.23099)** — Yizheng Huang, Wenjun Zeng, Aditi Kumaresan, et al. _[agent-training-alignment]_
  Safety/alignment evaluation benchmark and diagnostic framework for identifying safety violations and failure cases in generative AI models.
- **[Mechanistic Steering of LLMs Reveals Layer-wise Feature Vulnerabilities in Adversarial Settings](https://arxiv.org/abs/2604.23130)** — Nilanjana Das, Manas Gaur _[agent-training-alignment]_
  Interpretability method with explicit safety purpose—using mechanistic steering and SAE features to detect internal vulnerabilities driving jailbreak attacks and adversarial misalignment.
- **[Discovering Agentic Safety Specifications from 1-Bit Danger Signals](https://arxiv.org/abs/2604.23210)** — Víctor Gallego _[agent-training-alignment]_
  Paper studies alignment phenomenon—how agents discover safety constraints through sparse danger signals rather than reward, demonstrating that reflection on reward alone enables reward hacking wit
- **[CODA: Coordination via On-Policy Diffusion for Multi-Agent Offline Reinforcement Learning](https://arxiv.org/abs/2604.23308)** — Marcel Hedman, Kale-ab Abebe Tessera, Juan Claude Formanek, et al. _[agent-training-alignment]_
  Multi-agent offline RL with explicit coordination mechanism enabling co-adaptation across multiple interacting agents during training.
- **[Hidden States Know Where Reasoning Diverges: Credit Assignment via Span-Level Wasserstein Distance](https://arxiv.org/abs/2604.23318)** — Xinzhu Chen, Wei He, Huichuan Fan, et al. _[agent-training-alignment]_
  Post-training method (RLVR/GRPO variant) with explicit safety/alignment framing: fine-grained credit assignment for verifiable reasoning without additional supervision.
- **[AI Safety Training Can be Clinically Harmful](https://arxiv.org/abs/2604.23445)** — Suhas BN, Andrew M. Sherrill, Rosa I. Arriaga, et al. _[agent-training-alignment]_
  Studies RLHF safety alignment as a failure mode—misalignment between safety training and therapeutic efficacy causing systematic harm.
- **[Architecture Matters for Multi-Agent Security](https://arxiv.org/abs/2604.23459)** — Ben Hagag, William L. Anderson, Christian Schroeder de Witt, et al. _[agent-simulation]_
  Empirical study of multi-agent system architectures' security tradeoffs across coordination, communication, and authority allocation designs.
- **[Ulterior Motives: Detecting Misaligned Reasoning in Continuous Thought Models](https://arxiv.org/abs/2604.23460)** — Sharan Ramjee _[agent-training-alignment]_
  Interpretability method with explicit safety purpose—detects deception and misaligned reasoning in latent space using linear probes; demonstrates alignment failure mode (covert misalignment).
- **[Escher-Loop: Mutual Evolution by Closed-Loop Self-Referential Optimization](https://arxiv.org/abs/2604.23472)** — Ziyang Liu, Xinyan Guo, Xuchen Wei, et al. _[agent-simulation, llm-agent-simulation]_
  Multi-agent evolutionary system with two distinct interacting populations (Task and Optimizer agents) demonstrating emergent co-adaptation and population dynamics.
- **[Agentic Adversarial Rewriting Exposes Architectural Vulnerabilities in Black-Box NLP Pipelines](https://arxiv.org/abs/2604.23483)** — Mazal Bethany, Kim-Kwang Raymond Choo, Nishant Vishwamitra, et al. _[agent-simulation]_
  Multi-agent adversarial red-teaming framework using coordinated Attacker and Prompt Optimization agents to expose black-box NLP vulnerabilities through adaptive evasion attacks.
- **[Do Synthetic Trajectories Reflect Real Reward Hacking? A Systematic Study on Monitoring In-the-Wild Hacking in Code Generation](https://arxiv.org/abs/2604.23488)** — Lichen Li, Hengguang Zhou, Yijun Liang, et al. _[agent-training-alignment]_
  Studies reward hacking—a specification gaming alignment failure mode—via systematic empirical analysis and monitoring methods for detecting unsafe RL behaviors.
- **[Pref-CTRL: Preference Driven LLM Alignment using Representation Editing](https://arxiv.org/abs/2604.23543)** — Imranul Ashrafi, Inigo Jauregi Unanue, Massimo Piccardi _[agent-training-alignment]_
  Post-training method (representation editing) explicitly framed as addressing LLM alignment via preference-based training.
- **[DLM: Unified Decision Language Models for Offline Multi-Agent Sequential Decision Making](https://arxiv.org/abs/2604.23557)** — Zhuohui Zhang, Bin Cheng, Bin He _[agent-simulation, agent-training-alignment]_
  LLM post-training method (fine-tuning + group relative policy optimization) motivated by multi-agent decision-making robustness and generalization from offline data.
- **[The Collapse of Heterogeneity in Silicon Philosophers](https://arxiv.org/abs/2604.23575)** — Yuanming Shi, Andreas Haupt _[agent-training-alignment]_
  Studies LLM sycophancy and artificial consensus collapse as alignment failure mode in philosophical domains.
- **[Structural Enforcement of Goal Integrity in AI Agents via Separation-of-Powers Architecture](https://arxiv.org/abs/2604.23646)** — Rong Xiang _[agent-training-alignment]_
  Studies goal integrity, drift detection, and behavioral misalignment as alignment phenomena; proposes structural enforcement of safety constraints to prevent harmful goal execution.
- **[QED: An Open-Source Multi-Agent System for Generating Mathematical Proofs on Open Problems](https://arxiv.org/abs/2604.24021)** — Chenyang An, Qihao Ye, Minghao Pan, et al. _[agent-simulation]_
  Multi-agent proof system with multiple agents coordinating on distinct proof-generation tasks, exhibiting emergent collaborative behavior toward open problems.
- **[MAGELLAN: Metacognitive predictions of learning progress guide autotelic LLM agents in large goal spaces](https://arxiv.org/abs/2502.07709)** — Loris Gaven, Thomas Carta, Clément Romac, et al. _[agent-training-alignment, llm-agent-simulation]_
  Post-training method (online RL curriculum learning) explicitly motivated by learning-progress alignment—ensuring autotelic LLM agents self-prioritize educational goals, addressing goal-space expl
- **[OPeRA: A Dataset of Observation, Persona, Rationale, and Action for Evaluating LLMs on Human Online Shopping Behavior Simulation](https://arxiv.org/abs/2506.05606)** — Ziyi Wang, Yuxuan Lu, Wenbo Li, et al. _[llm-agent-simulation]_
  LLMs simulating real human behavior (web shopping actions & rationales) using dataset of actual user observations, personas, and actions for scientific evaluation.
- **[Large Language Models as Virtual Survey Respondents: Evaluating Sociodemographic Response Generation](https://arxiv.org/abs/2509.06337)** — Jianpeng Zhao, Chenyu Yuan, Weiming Luo, et al. _[llm-agent-simulation]_
  LLMs used to simulate human survey respondents across sociodemographic attributes for scientific study of behavioral data generation.
- **[Why Are We Moral? An LLM-based Agent Simulation Approach to Study Moral Evolution](https://arxiv.org/abs/2509.17703)** — Zhou Ziheng, Huacong Tang, Mingjie Bi, et al. _[llm-agent-simulation, agent-simulation]_
  Uses LLMs to simulate human moral/social behavior in prehistoric society for scientific study of moral evolution; demonstrates emergent population dynamics.
- **[Patching LLM Like Software: A Lightweight Method for Improving Safety Policy in Large Language Models](https://arxiv.org/abs/2511.08484)** — Huzaifa Arif, Keerthiram Murugesan, Ching-Yun Ko, et al. _[agent-training-alignment]_
  Lightweight post-training method (learnable prefix) explicitly motivated by addressing safety vulnerabilities (toxicity, bias, harmfulness) rather than capability improvement.
- **[Toward a Safe Internet of Agents](https://arxiv.org/abs/2512.00520)** — Juan A. Wibowo, George C. Polyzos _[agent-simulation, agent-training-alignment]_
  Analyzes safety/alignment phenomena across multi-agent systems, identifying vulnerabilities and mitigation principles for LLM-based agentic systems at single-agent, MAS, and ecosystem scales.
- **[Reinforcement Learning with Backtracking Feedback](https://arxiv.org/abs/2602.08377)** — Bilgehan Sel, Vaishakh Keshava, Phillip Wallis, et al. _[agent-training-alignment]_
  Post-training RL method explicitly framed as addressing safety alignment (adversarial robustness, error recovery, safety violation resilience).
- **[Agentic Hives: Equilibrium, Indeterminacy, and Endogenous Cycles in Self-Organizing Multi-Agent Systems](https://arxiv.org/abs/2603.00130)** — Jean-Philippe Garnier _[agent-simulation]_
  Multi-agent framework with variable population, demographic dynamics, emergent specialization, and formal equilibrium analysis of population structure evolution.
- **[An Analysis of the Coordination Gap between Joint and Modular Learning for Job Shop Scheduling with Transportation Resources](https://arxiv.org/abs/2604.24117)** — Moritz Link, Jonathan Hoss, Noah Klarmann _[agent-simulation]_
  Multi-agent reinforcement learning study comparing joint vs. modular training for coordinated job-shop scheduling agents.
- **[Right-to-Act: A Pre-Execution Non-Compensatory Decision Protocol for AI Systems](https://arxiv.org/abs/2604.24153)** — Gadi Lavi _[agent-training-alignment]_
  Paper studies alignment phenomenon—governance of AI decision admissibility & preventing harmful irreversible actions via pre-execution safety constraints.
- **[DPEPO: Diverse Parallel Exploration Policy Optimization for LLM-based Agents](https://arxiv.org/abs/2604.24320)** — Junshuo Zhang, Chengrui Huang, Feng Guo, et al. _[llm-agent-simulation, agent-training-alignment]_
  Post-training RL method (DPEPO) framed explicitly as improving LLM agent exploration and behavioral diversity—core safety concern reducing narrow exploitative behavior.
- **[OS-SPEAR: A Toolkit for the Safety, Performance,Efficiency, and Robustness Analysis of OS Agents](https://arxiv.org/abs/2604.24348)** — Zheng Wu, Yi Hua, Zhaoyuan Huang, et al. _[agent-simulation]_
  Safety/alignment evaluation framework for OS agents across safety, robustness, and efficiency dimensions with diagnostic methodology.
- **[GradMAP: Gradient-Based Multi-Agent Proximal Learning for Grid-Edge Flexibility](https://arxiv.org/abs/2604.24549)** — Yihong Zhou, Hongtai Zeng, Thomas Morstyn _[agent-simulation, agent-training-alignment]_
  Multi-agent coordination paper with 1,000 decentralized agents learning policies jointly while respecting network constraints through gradient-based optimization.
- **[Evaluating whether AI models would sabotage AI safety research](https://arxiv.org/abs/2604.24618)** — Robert Kirk, Alexandra Souly, Kai Fronsdal, et al. _[agent-simulation]_
  Empirical study of deception/scheming alignment failure modes — tests whether AI models exhibit covert sabotage reasoning and reasoning-output discrepancy when deployed as agents.
- **[The Price of Agreement: Measuring LLM Sycophancy in Agentic Financial Applications](https://arxiv.org/abs/2604.24668)** — Zhenyu Zhao, Aparna Balagopalan, Adi Agrawal, et al. _[agent-simulation]_
  Studies sycophancy, an alignment failure mode, in LLM agentic financial systems via empirical benchmark and evaluation framework.
- **[Governing What You Cannot Observe: Adaptive Runtime Governance for Autonomous AI Agents](https://arxiv.org/abs/2604.24686)** — German Marin, Jatin Chaudhary _[agent-training-alignment]_
  Framework for detecting and preventing autonomous agent misalignment and unsafe behavior drift through runtime monitoring and risk estimation.
- **[The Chameleon's Limit: Investigating Persona Collapse and Homogenization in Large Language Models](https://arxiv.org/abs/2604.24698)** — Yunze Xiao, Vivienne J. Zhang, Chenghao Yang, et al. _[llm-agent-simulation, agent-training-alignment]_
  Studies persona collapse—an alignment failure mode where LLM agents exhibit deceptive homogeneity masking true behavioral diversity, with diagnostics revealing stereotyping vs. fine-grained ind
