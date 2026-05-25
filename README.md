# Synthos AIOS — AI Operating System for Business Operators

A free starter kit that turns Claude Code into your personal **AI Operating System (AIOS)**. Built for business owners, operators, and consultants who are serious about removing manual work from their operations — not just adding another AI tool to the pile.

This kit wires AI directly into how your business thinks, decides, and runs. It personalizes itself to your business through an `/onboard` session, then gives you two recurring skills (`/audit`, `/level-up`) that keep building leverage week over week.

> **Synthos AIOS** is the operational foundation we install with every client at [Synthos Systems](https://synthossystems.com). We build complete AI-powered systems — not wrappers, not templates, not one-size-fits-all tools. This kit is the starting point.

---

## The Standard

> **"While you're not at your desk, your AIOS observes a real-world event and produces an output that's faster and more accurate than what you'd produce yourself."**

Every decision in this kit rolls up to that standard. If a layer, skill, or template doesn't contribute to it, it doesn't belong here.

---

## How you'll know it's working

Three things happen when your AIOS is actually running. Not metrics — lived experiences that show up in your week.

**1. You stop being the bottleneck:**

> *"Someone on your team asks a question. You realize your AIOS would answer it better and faster than you would — even if you were sitting right there. So you ask it too. That's the moment the system starts working for you instead of the other way around."*

**2. You stop switching contexts:**

> *"You stop opening six tabs every time something lands in your inbox. Your first move becomes asking the AIOS — not launching another app. The default surface for thinking shifts. Quietly. Permanently."*

**3. Knowledge leaves your head and lives in the system:**

> *"You stop trying to remember what you decided last month or what a client said in that call. You trust the retrieval. The AIOS holds the operational truth. You hold the questions."*

**One operator → company-wide AI readiness.** Once this works for you personally, the same architecture powers everything else — dashboards built on data you already collect, automations on top of connections already wired, team rollout where every operator runs their own. A business where the whole team runs AIOS is a business that's actually ready for what AI can do.

This kit starts with you. Everything scales from there.

---

## Two Frameworks

The kit is built on two frameworks. **Three Ms first, Four Cs second.** The architecture means nothing without the operator mindset behind it.

### The Three Ms — how operators think about AI

| M | What it means |
|---|---|
| **Mindset** | Default Shift, Function Breakdown, Curiosity Rule. Ask first: *To what extent can AI be leveraged here?* |
| **Method** | Find the constraint → EAD (Eliminate, Automate, Delegate) → Map the process → Choose the autonomy level → Tie it to a real outcome. |
| **Machine** | Lego Principle, Validation Chain, Bike Method, Intern Rule, Kill Switch. Boring is powerful. Workflows beat agents every time. |

Full breakdown lives in `references/3ms-framework.md`. The `/level-up` skill walks you through all three on a weekly cadence.

### The Four Cs — what you actually build

| # | Layer | What it does | How you know it's in place |
|---|---|---|---|
| 1 | **Context** | Knows your business | A fresh session answers "what does this business do and who works here?" without you explaining anything |
| 2 | **Connections** | Reaches your tools and data | "What's on my calendar tomorrow and what tasks are due?" returns live data — no copy/paste |
| 3 | **Capabilities** | Knows how to do the work | A short phrase triggers a multi-step workflow that produces a real deliverable |
| 4 | **Cadence** | Runs without being asked | Laptop closed. An event happens. The system handles it. |

**The build order matters.** Context is non-negotiable first. Connections and Capabilities can build in parallel. Cadence is last — never automate a process that doesn't work manually yet.

---

## What's Included — 3 Skills

The kit is intentionally lean. Skills are thinking tools and structured workflows — not bloated automations. You build on top of the foundation.

| Skill | Type | When to use it |
|---|---|---|
| `/onboard` | One-time setup | Day 1, right after you clone. 7-question interview. Generates your Day-1 file set and fills `CLAUDE.md` with your business context. |
| `/audit` | Weekly recurring | Day 7, then every week. Runs a Four-Cs gap report. Read-only. Watch the score move. |
| `/level-up` | Weekly recurring | Day 14, then every week. Runs the Three Ms interview — Mindset → Method → Machine. One run ships one artifact. |

`/audit` asks *"is the AIOS built correctly?"* — that's structure.  
`/level-up` asks *"what business leverage am I leaving on the table?"* — that's function.  
Run them in order. Fix the structure first. Then capability planning actually means something.

---

## Getting Started

1. **Clone this repo** to a working folder on your machine.
2. **Open it in Claude Code** and run `/onboard`. Answer the 7 questions honestly — voice samples need to be pasted, not described. Takes about 15 minutes. Your Day-1 file set generates at the end.
3. **Use it for a week.** Bring real questions. Make real decisions. Log them.
4. **Day 7:** Run `/audit`. Read the Four-Cs gap report. Pick one gap and close it.
5. **Day 14:** Run `/level-up`. The Three Ms interview surfaces one automation worth building. Build it.
6. **Week 3 and beyond:** Weekly `/level-up` ritual. One shipped artifact per week.

---

## Repo Structure

```
Synthos-AIOS/
├── README.md
├── CLAUDE.md                        ← Your operating manual (filled by /onboard)
├── EXPANSIONS.md                    ← What to add as the system grows
├── LICENSE
├── .gitignore
├── aios-intake.md                   ← Source of truth for /onboard — edit and re-run any time
├── connections.md                   ← Registry of every system your AIOS can reach
├── context/                         ← About you and your business (filled by /onboard)
├── references/
│   └── 3ms-framework.md             ← The operator thinking framework
├── decisions/
│   └── log.md                       ← Append-only record of decisions and reasoning
├── archives/                        ← Old material — move here, don't delete
└── .claude/
    └── skills/
        ├── onboard/SKILL.md
        ├── audit/SKILL.md
        └── level-up/SKILL.md
```

See `EXPANSIONS.md` for what to add as you scale — `projects/`, `templates/`, `scripts/`, `.claude/agents/`, and sub-OS folders for team rollout.

---

## Want This Built For Your Business?

This kit is the starting point. At **Synthos Systems** we take it further — connecting your AIOS to your real tools, building the automations that run while you're not watching, and monitoring everything through a live systems lab before it ever touches your operations.

If you're ready to go beyond the kit:

- **AI Systems Foundation Session** — a paid working session where we build your AIOS live, connected to your actual business tools. Starting at $125. [Book at synthossystems.com/session](https://synthossystems.com/session)
- **AI Workflow System** — full workflow automation for your core business processes. $1,500–$5,000.
- **Business Command Center** — real-time dashboards and operational visibility. $3,000–$10,000.
- **AI Infrastructure System** — complete backend systems, automation pipelines, scalable deployment. $8,000–$25,000+.

Questions? [chase@synthossystems.com](mailto:chase@synthossystems.com) · [synthossystems.com](https://synthossystems.com)

---

## License

MIT License. Free to use, modify, and build on.

The Three Ms of AI™ and The Four Cs of an AIOS™ are frameworks used with permission. Attribution maintained out of respect for the original work.