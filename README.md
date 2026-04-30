# LLM Agent Simulation — Daily arXiv Paper Feed

> A curated, auto-updating feed of arXiv papers on **LLM-based agent simulation**, **multi-agent systems**, **city & society simulation**, and **LLM alignment & safety**.

**👉 Latest entries: [`papers.md`](./papers.md)**

Every day a bot scans new arXiv submissions across the AI / ML / IR / CY / HC / SI categories and runs a **two-pass classifier** powered by **Claude Haiku 4.5**. Pass 1 casts a wide net. Pass 2 applies a strict rubric that filters out domain applications, systems/infrastructure work, and "agent"-flavoured capability papers. Only papers that survive both passes reach [`papers.md`](./papers.md).

The feed is intentionally short. On a typical day, **out of ~500–800 new arXiv papers ~15–30 make the cut.** If you're looking for rigorous research on multi-agent LLM behaviour, alignment failure modes, agent-based modelling of societies, or urban simulation, this is a low-noise way to keep track.

---

## 🔎 What makes the cut

A paper is kept only when its **primary contribution** matches one of these four areas:

| Tag | Scope |
|---|---|
| 🧑‍🤝‍🧑 **`llm-agent-simulation`** | LLMs used to simulate humans, societies, roles, or interactive scenarios — generative agents, role-play benchmarks, LLM-driven agent-based modelling |
| 🤖 **`agent-simulation`** | Multi-agent systems, agent-based modelling (ABM), emergent population behaviour, coordination / competition dynamics — including non-LLM agents (MARL, classical ABM) |
| 🏙️ **`city-simulation`** | Urban dynamics, mobility, traffic, economic & social simulation at city / society scale, digital twins of human environments |
| 🛡️ **`agent-training-alignment`** | RLHF / DPO / PPO methods motivated by alignment, reward modelling, constitutional methods, red-teaming, alignment evals, scalable oversight, safety benchmarks, interpretability for safety, studies of deception / sycophancy / reward hacking |

**What gets rejected on purpose:**

- Domain apps that happen to use agents (medical chatbots, legal assistants, tutoring systems, coding pipelines, scientific-workflow automators)
- Systems / efficiency / caching / routing / orchestration papers, even when "agent" is in the title
- General-capability LLM training methods motivated by benchmark scores (math reasoning, code gen, RAG accuracy) without an alignment or agent-behaviour motivation
- Single-agent RL that doesn't study populations or alignment
- Surveys, position pieces, governance papers without a concrete method
- Papers where "agent" is decorative framing for a single LLM with a system prompt

---

## 📖 How to read an entry

Each day has its own `## YYYY-MM-DD` section in [`papers.md`](./papers.md), newest first. Within a day, entries look like this:

```markdown
- **[Paper Title](https://arxiv.org/abs/YYMM.NNNNN)** — First Author, Second Author, et al. _[tag1, tag2]_
  One short sentence describing the paper's primary contribution.
```

Click the title to open the arXiv abstract. Tags come from the list above. The one-sentence summary is written by Claude at classification time.

---

## ⚙️ How it works

```
                                                  ┌───────────────────────┐
  arXiv OAI-PMH daily dump  ─► cs.AI / cs.LG /    │  Claude Haiku 4.5     │
  (cs.MA / cs.CL / cs.IR /     primary-category   │  pass 1 (permissive)  │
   cs.CY / cs.SI / cs.HC)      filter             │  pass 2 (strict)      │
                                                  └──────────┬────────────┘
                                                             │ relevant ∧ both passes agree
                                                             ▼
                                                     this repo's papers.md
                                                     (one commit per day)
```

- **Fetch:** arXiv OAI-PMH (`export.arxiv.org/oai2`), pagination-aware, respects rate limits.
- **Classifier:** Claude Haiku 4.5 on AWS Bedrock via structured tool-use. System prompt is cache-controlled to keep daily cost below $1.
- **Two-pass filter:** on a sample day (1,180 papers), pass 1 accepted 258 and pass 2 kept 91 (≈ 93% precision on retains, no false-negatives found in a 55-paper manual audit).
- **Crash safety:** atomic state writes, monotonic day advancement, per-day idempotent commits. If the bot misses a day, the next run catches up automatically.

---

## 🗂️ Browsing

- **All papers, newest first** → [`papers.md`](./papers.md)
- **Filter by tag in GitHub search:**
  - [agent-training-alignment](./papers.md?plain=1#:~:text=agent-training-alignment)
  - [llm-agent-simulation](./papers.md?plain=1#:~:text=llm-agent-simulation)
  - [agent-simulation](./papers.md?plain=1#:~:text=agent-simulation)
  - [city-simulation](./papers.md?plain=1#:~:text=city-simulation)

(Or use your browser's in-page search on [`papers.md`](./papers.md) for a specific keyword or author name.)

---

## 🙋 Suggest or correct

If a paper should have made the cut but didn't, or an entry looks off, open an [issue](../../issues/new) with the arXiv URL and a one-line reason. Pass-2 precision is high but not perfect — feedback helps tune the rubric.

---

## 📜 License

Paper titles, abstracts, and metadata belong to their respective arXiv authors and are reproduced here under arXiv's non-exclusive distribution license for curation purposes. The curation choices, tag assignments, and one-line summaries in this repository are released under the **[MIT License](./LICENSE)**.
