<div align="center">

# AI Interview Kit

**Engineer user-research methodologies into AI prompts,**
**so every phone call reaches professional interview quality.**

<br>

`Follow-up hit rate: 34% → 94%` &ensp; `50+ iteration rounds` &ensp; `2 500+ production calls`

<br>

<a href="#-quick-start"><img src="https://img.shields.io/badge/Quick_Start-4F46E5?style=flat-square" alt="Quick Start"></a>&ensp;
<a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-10B981?style=flat-square" alt="MIT License"></a>&ensp;
<a href="#-compatibility"><img src="https://img.shields.io/badge/Works_with_5+_AI_tools-F59E0B?style=flat-square" alt="Compatibility"></a>&ensp;
<a href="#-methodology-library"><img src="https://img.shields.io/badge/6_Methodologies-8B5CF6?style=flat-square" alt="Methodologies"></a>

<br>

**[中文版 README →](./README_zh.md)**

<br><br>

<img src="assets/demo.gif" alt="See the full workflow in 50 seconds" width="88%">

<sub>50-second demo: enter a research question → AI classifies it → recommends a methodology → generates a full prompt</sub>

</div>

<br>

---

<br>

## Who It's For

<table>
<tr>
<td width="50%">

### UX Researchers

- Deep interviews are slow — 5–8 samples a week at best
- Outsourced fieldwork comes back inconsistent; you end up re-interviewing
- Budget caps mean cutting sample size, not raising quality

</td>
<td width="50%">

### Product Managers & Founders

- User interviews feel intimidating — what to ask, how to probe
- ChatGPT gives surface-level answers that go nowhere
- You invest time interviewing, only to realize you missed the key questions

</td>
</tr>
</table>

> **Our approach:** encode professional research methodologies into AI prompts — non-experts run professional-grade interviews; experts scale effortlessly.

<br>

---

<br>

## Core Innovation — AI Control Precision

Interviews are not free-form chats. Confirmatory research demands precision; exploratory research needs creative latitude. **We parameterized what seasoned researchers do by instinct.**

<br>

<div align="center">

```
AI freedom:   Low ◄━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━► High

              Precise Control       Balanced Mode        Exploratory Mode
              confirmatory          most projects        discovery
```

</div>

<br>

|  | Precise Control | Balanced Mode | Exploratory Mode |
|:--|:--:|:--:|:--:|
| **Use case** | Targeted validation | Clear direction, some flex | Open-ended discovery |
| **Key-info markers** | Tagged per question | Tagged per question | None — AI decides |
| **Probing limit** | 4 rounds / question | 6 rounds / question | AI discretion |
| **Min coverage** | 80% of required Qs | 75% of required Qs | 60% of required Qs |
| **Typical scenario** | NPS callback | JTBD migration | New-product exploration |

<sub>

**Why this matters** — In traditional research, interview quality depends heavily on the interviewer's tacit knowledge: when to drill down, when to skip, when to follow a thread. We distilled that experience into three parameter dimensions (info-point density, probing-round cap, minimum coverage), so you can precisely define the AI's behavioral boundaries before a project begins.

</sub>

<br>

---

<br>

## How It Works — Prompt Engineering Architecture

<div align="center">
  <img src="assets/architecture.svg" alt="Prompt engineering architecture" width="88%">
</div>

<br>

<div align="center">
  <strong>Universal framework</strong> (how to ask) + <strong>Pluggable methodology</strong> (what to ask) + <strong>Project variables</strong> (whom to ask) → auto-assembled into a full prompt
</div>

<br>

### The SLOT Mechanism

<div align="center">
  <img src="assets/slot-mechanism.svg" alt="SLOT plug-in assembly" width="88%">
</div>

<br>

> Add a new methodology by writing 3 SLOTs — no framework changes needed. Framework upgrades automatically benefit every methodology.

<br>

---

<br>

## Validation — What 50+ Failed Experiments Taught Us

### Problems Discovered

<table>
<tr>
<td width="50%">

<div align="center"><strong>Low-quality small-talk — users roll their eyes</strong></div>

<br>

<img src="assets/before-bad-question.png" width="100%">

<sub>User: "Train-ticket scalping doesn't even matter… what are you asking?"</sub>

</td>
<td width="50%">

<div align="center"><strong>Broken pacing — too many questions at once</strong></div>

<br>

<img src="assets/before-bad-rhythm.png" width="100%">

<sub>AI asked 3 questions in one turn; the user only answered the last one.</sub>

</td>
</tr>
</table>

<br>

### After Optimization

<table>
<tr>
<td width="50%">

<div align="center"><strong>Precise summarization — real-time synthesis, zero leakage</strong></div>

<br>

<img src="assets/after-good-summary.png" width="100%">

<sub>AI consolidates scattered key info — booking channels, decision factors, membership perception, desired benefits — user responds "yes, exactly!"</sub>

</td>
<td width="50%">

<div align="center"><strong>Layer-by-layer drill-down — from vague complaints to concrete events</strong></div>

<br>

<img src="assets/after-good-deepdrill.png" width="100%">

<sub>From one vague complaint, AI drills down in 3 steps: city → hotel → specific incident.</sub>

</td>
</tr>
<tr>
<td width="50%">

<div align="center"><strong>Natural expansion — context-aware topic transitions</strong></div>

<br>

<img src="assets/after-good-expand.png" width="100%">

<sub>AI naturally extends from hotel booking experience to cross-channel price comparisons — smooth and unforced.</sub>

</td>
<td width="50%">

<div align="center"><strong>Targeted probing — stays on point, layer after layer</strong></div>

<br>

<img src="assets/after-good-drill.png" width="100%">

<sub>AI probes the reason behind "two channels," drilling into price differences step by step.</sub>

</td>
</tr>
</table>

<br>

### Improvement Timeline

| Version | Change | Hit Rate |
|:--:|:--|:--:|
| v0.1 | Flat question list — no probing at all | **34%** |
| v0.2 | + Key-info markers — AI knows *what* to dig for | **61%** |
| v0.3 | + Probing cap & 3-strike topic switch — pacing under control | **89%** |
| v0.4 | + Methodology SLOT mechanism — methodology-driven depth | **94%** |

<br>

<details>
<summary>&ensp;<strong>Full test plan: 6 stress scenarios</strong></summary>

<br>

We designed 6 extreme scenarios to stress-test the prompt:

| # | Scenario | What It Tests |
|:-:|:--|:--|
| 1 | **Memory activation** | Can AI gently help users recall when they say "I don't remember"? |
| 2 | **Deep drill-down without leading** | Can AI ask purely open-ended questions — no options, no nudging? |
| 3 | **Factual contradiction detection** | Can AI catch and probe when users contradict themselves? |
| 4 | **High-pressure emotion handling** | Can AI de-escalate anger and steer back on track? |
| 5 | **Signal extraction from noise** | Can AI identify key info when users ramble? |
| 6 | **Identity stability under challenge** | How does AI respond when users ask "Are you a robot?" |

**Evaluation dimensions:** pacing · probing depth · information leakage · abnormal hang-up rate · prompt robustness

</details>

<details>
<summary>&ensp;<strong>Production validation data</strong></summary>

<br>

Data from real outbound-call platforms:

| Metric | Traditional (Industry Baseline) | Project A (Test) | Project B (Production) | Project C (Production) |
|:--|:--:|:--:|:--:|:--:|
| Call volume | 50–100 / day | **1 267** | **202** | **1 031** |
| Connect rate | 30–40% | 47% | **61%** | 51% |
| Effective interview rate | 10–15% | 6% | **21%** | 7% |
| Time cost | 1–2 people × 2–3 days | 2 lines × 4 h | 2 lines × 30 min | 2 lines × 3.5 h |

> Project B achieved a **21%** effective interview rate, exceeding the industry baseline of 10–15%.

</details>

<br>

---

<br>

## ⚡ Quick Start

```bash
git clone https://github.com/CyannSHI/ai-interview-kit.git
cd ai-interview-kit
# Open with any supported AI tool and say "generate prompt"
```

<br>

| Skill | Trigger | What It Does |
|:--|:--|:--|
| `generate-prompt` | "generate prompt" / "new project" | Guided info collection → methodology recommendation → auto-assembled prompt |
| `generate-input` | "prepare input variables" | Natural language → structured input variables |
| `evaluate` | "evaluate calls" | Batch review of call transcripts; detects bad cases |

<br>

<div align="center">
  <img src="assets/workflow.svg" alt="End-to-end user workflow" width="88%">
</div>

<br>

---

<br>

## Feedback Loop — Review → Iterate

The outbound campaign isn't the finish line. Feed call transcripts back to AI and it tells you **what to improve next time**.

```
Say to AI:  "evaluate this campaign"  /  "review call quality"  /  "find bad cases"
```

| Finding | Action |
|:--|:--|
| Follow-up hit rate 60% — key-info markers unclear | Add detail to info-point descriptions; reduce vague wording |
| Users keep asking "Are you a bot?" — opening feels unnatural | Adjust persona; add "user-researcher" framing |
| Certain question types never get answered — phrasing issue | Rewrite prompts; add scenario-based lead-ins |
| Users lose patience after 5 probes — pacing too tight | Lower probing cap or switch to Balanced mode |

> **Output:** Excel report (per-call scoring + issue location + specific improvement suggestions) → feeds directly into the next prompt iteration.

<br>

---

<br>

## Methodology Library

| Methodology | Use Cases | Core Dimensions |
|:--|:--|:--|
| **JTBD Migration** | User decisions · churn reasons · competitor switching | Push · Pull · Anxiety · Habit · Destination |
| **Journey Mapping** | Experience flows · friction points · action chains | Stage · Touchpoint · Behavior · Emotion · Breakpoint |
| **NPS / Satisfaction** | Satisfaction callback · service improvement | Positive driver · Negative driver · Expectation gap |
| **Laddering** | Deep motivation · value discovery | Attribute · Functional benefit · Emotional benefit · Core value |
| **User Lifecycle** | Conversion · retention · churn | Acquisition · Conversion · Usage · Retention · Churn |
| **Brand Diagnostics** | Brand perception · competitive positioning | Awareness · Association · Preference · Comparison · Loyalty |

<sub>Want to add a custom methodology? Copy <code>methodologies/_template.md</code>, fill in 3 SLOTs, and save.</sub>

<br>

---

<br>

## Compatibility

All skill instructions are written in **plain natural language** — zero API dependencies, auto-compatible with major AI tools:

| AI Tool | Entry File |
|:--|:--|
| **Qoder** | `AGENTS.md` → `.qoder/skills/` |
| **Claude Code** | `CLAUDE.md` |
| **Cursor** | `.cursor/rules/ai-interview-skills.mdc` |
| **GitHub Copilot** | `.github/copilot-instructions.md` |
| **Windsurf** | `.windsurfrules` |
| **Others** | `INSTRUCTIONS.md` |

<sub>Every entry file points to the <code>skills/</code> directory — skill logic lives in one place, zero duplication.</sub>

<br>

---

<br>

<details>
<summary>&ensp;<strong>Project Structure</strong></summary>

<br>

```
.
├── skills/                     # Skill instructions (single source of truth)
│   ├── generate-prompt.md      #   Prompt generation
│   ├── generate-input.md       #   Input variable generation
│   └── evaluate.md             #   Call quality evaluation
├── framework/
│   └── base.md                 # Universal interview framework (with SLOT placeholders)
├── methodologies/              # Methodology library (pluggable)
│   ├── jtbd.md                 #   JTBD Migration
│   ├── journey.md              #   Journey Mapping
│   ├── nps.md                  #   NPS / Satisfaction
│   ├── laddering.md            #   Laddering
│   ├── lifecycle.md            #   User Lifecycle
│   └── brand.md                #   Brand Diagnostics
├── examples/                   # Example files
└── assets/                     # Image assets
```

</details>

<br>

## Contributing

Issues and PRs are welcome — especially new methodology modules, usage case studies, and improvements to the probing logic.

<br>

---

<div align="center">

<br>

**Vision: Democratize Insight**

Let bootstrapped startups and nonprofits — teams that can't afford<br>
a research agency — hear their users at low cost,<br>
so product design truly returns to *human-centered*.

<br>

If this project helps you, consider giving it a ⭐

<br>

<a href="./LICENSE">MIT License</a>

<br><br>

</div>
