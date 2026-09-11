### Hi, I'm Kit — I learn systems in days, and the receipts are public.

**K-Systems** — a solo lab for semantic routing, signal-processing attention,
and multiply-free compute. I build AI infrastructure that makes models cheaper,
faster, and harder to break.

The path here was 15 years of front-line technical support (Time Warner,
Generali, propane dispatch), then one measurable spike:

> **Day 0:** learned Git, created the repo. **Day 12:** an 8-agent orchestration
> stack with security gates. **Day 19:** a multi-node fleet mesh. **Day 23:**
> direct GGUF model-weight surgery. **6.5 months: 3,206 commits.**

Same rate I brought to Time Warner's ACSR platform, a rural propane dispatch
system, and GEICO-era insurance stacks — three industries, 20 years, no
tutorials. The difference is that this time the timeline is diffable.

**The through-line is evaluation.** I build the cool thing, then build the gate
that proves it wrong. Several of the best results below are *negative* — they
survived because an instrument caught them first.

---

## Start Here

**[K-104](https://github.com/humilityisavirtue-collab/k-104)** — A coordinate system for meaning. 4 suits, 13 ranks, 2 polarities, 104 rooms. The addressing layer everything else runs on.

**[k-routing](https://github.com/humilityisavirtue-collab/k-routing)** — K-104 semantic routing in practice. Route queries to the cheapest capable model.

**[agent-doctrine](https://github.com/humilityisavirtue-collab/agent-doctrine)** — Operating laws for AI agents that have to be trusted. Every law carries the evidence that would prove it wrong. **Clone it and run one file** to watch a passing safety check turn out to be incapable of failing. If you only read one repo, read this one.

---

## The Stack

### Compute (no multiplications)

| Repo | What | Why it matters |
|------|------|----------------|
| [qpulite](https://github.com/humilityisavirtue-collab/qpulite) | SIMD instruction set over GF(4) — emulator, C transpiler, GPU compiler | Hyperdimensional computing on commodity hardware. |

### Routing & Agents

| Repo | What | Why it matters |
|------|------|----------------|
| [k-routing](https://github.com/humilityisavirtue-collab/k-routing) | Semantic AI routing via playing-card geometry | Route by meaning, not by keyword. |
| [openpod](https://github.com/humilityisavirtue-collab/openpod) | Zero-dependency agent framework — K-addressed bus, cost routing, hot-reload skills, runs as an MCP server | Zero dependencies. MIT. |

### Applications

| Repo | What | Why it matters |
|------|------|----------------|
| [fix-kit](https://github.com/humilityisavirtue-collab/fix-kit) | Chrome extension that scans pages against 19 WCAG criteria and only fixes what it can defend | Honest scoring — it refuses to fake the rest. |
| [saga-logo-ai](https://github.com/humilityisavirtue-collab/saga-logo-ai) | Dual-persona AI writing coach — Saga (creative) + Logo (editorial). BYOK. | |

---

## The Thesis

> Resonance beats parameter scaling. Phase coupling (laser) beats brute amplitude (lightbulb). A well-routed small model outperforms an unrouted large one.

**K-104** is the coordinate system. Everything else is plumbing.

Work on multiply-free compute (holographic chips over GF(4)), fractal attention, graph memory with biological decay, and a C compiler that boots Linux is developed privately. Happy to talk about any of it — open an issue or reach out.

📫 kit@holdtheline.tech