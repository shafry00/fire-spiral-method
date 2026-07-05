# Fire Spiral Method — Full Framework

> **Status: v1.0**

## Core Principles

1. **Action first, concepts later** — the inverse of traditional learning (theory → understand → practice). Start with action, seek theory only after you have real context.
2. **Spiral, not linear** — not a step 1-2-3, but a cycle that repeats with deepening understanding each pass.
3. **90% problem, 10% solution** — each phase focuses on deepening the problem, not rushing to solve.
4. **Document at every phase** — as a capture tool for understanding and a foothold for the next cycle.
5. **One-Object-One-Goal** — each cycle: 1 concrete object, 1 main goal. Everything else waits.
6. **One artifact per cycle** — each pass produces an Insight Map as tangible evidence of deepening.

---

## Phase 1: AMATI (Observe)

**Trigger:** Curiosity, urgency, or both.

Something catches your interest → questions emerge → you estimate its impact.

### Output

**Problem Statement** — 1-2 sentences:

- "The problem is..."
- "This matters because..."

### Constraint Framing (mandatory)

| Element | Question |
|---------|----------|
| **Target** | What must be accomplished this spiral? |
| **Minimum success** | What's the bare minimum acceptable outcome? |
| **Cost of failure** | What happens if this doesn't get done? |

### Check-in

*"Is this important, or momentary entertainment?"*
- Important → continue to PRAKTEKKAN
- Entertainment → go ahead, but be aware it's entertainment

### Entry Alternative: Float Mode

For when you don't know what you're interested in:

1. **Receiver position** — don't hunt, just open your senses
2. **See, hear, feel** — from a distance, no need to engage
3. **Detect anomaly** — something off, a pattern that doesn't connect, something you sense but others don't
4. **Anomaly → curiosity** → AMATI can begin

### Carry-Over (new spiral)

*"From the previous spiral, is there a pattern relevant to this spiral's goal?"*

---

## Phase 2: PRAKTEKKAN (Practice)

Direct action. Try, dismantle, experiment, fail, make a mess. You don't need to understand the theory yet.

Fill with:
- Natural reverse engineering: "how does this actually work?"
- Direct experimentation
- Practice without preparation

### Output

**Problem experience** — the gap between expectation and reality.

### Gap Log

3-line format per gap:

```
GAP: [short title]
Thought: [expectation before action]
Reality: [actual result]
Insight: [gap between expectation and reality]
```

### Check-in: Pareto-Diverge Test

1. Diverge problem statement — from the gaps found, explode all possible issues as broadly as possible
2. Pareto test: *"Do the PRAKTEKKAN results cover 80% of the root problem?"*
   - Not yet 80% → continue PRAKTEKKAN
   - Reached 80% → go to INTEGRASIKAN

### Proof Anchor — Gate 2

Before moving to INTEGRASIKAN, verify Gap Log entries:
- Is "Reality" backed by concrete evidence?
- Not "it was harder than expected" but "error 404 on route `/x`, 3 attempts, 2 hours"
- Red flag: vague gaps without supporting data

---

## Phase 3: INTEGRASIKAN (Integrate)

A lightweight bridge phase connecting PRAKTEKKAN to the next loop.

### Sequence

**1. Concrete gaps** — from PRAKTEKKAN, what's the single most felt gap?

**2. Actionability check** — *"What can I use this for?"* Don't analyze deep, just check.

**3. Resource inventory** — *"What do I already have? Skills, tools, access, connections?"*

**4. Blank Slate — 3-Step Debrief:**

- **Empty the cup** — recognize assumptions you've been holding, discard them
- **Find the raw pain** — from all gaps, which one is the most painful?
- **Ask from zero** — from that point, ask "why" without reference to prior opinions

**If resources are lacking** → seek specific theory (shallow, just enough to close the gap)
**If resources are sufficient** → continue to triage

### Triage Output

```
Go:     [gap/angle ready for next loop — priority]
Review: [needs deeper investigation — shelve]
Kill:   [irrelevant — discard]
```

### Artifact: Insight Map

After triage, produce **one artifact** — an Insight Map:

- Form: mind map, branching list, or simple diagram
- Content: trace of the spiral — from AMATI (core problem) → branching gaps found in PRAKTEKKAN → which are Kill/Review/Go
- Function: tangible proof of deepening, re-readable, transferable to other spirals

**Artifact spectrum:** doesn't have to be heavy — just 1 addition to the existing map.

### Checkpoint: 3 Whys

After Triage, ask 3 Whys on the results:
- *"Why is this Kill? Why? Why?"*
- *"Why is this Go? Why? Why?"*

If you can answer → spiral is running, perspective has fundamentally shifted.
If you stall at the 2nd/3rd why → spiral is stagnant. Inject a new angle.

### Output

**Loop direction** — continue PRAKTEKKAN, return to AMATI, or need resources first.

---

## The Loop (↺)

**Trigger:** Every INTEGRASIKAN produces new insight/concept → return to PRAKTEKKAN for experimentation and continuous improvement.

It's a **spiral**, not a closed circle. Each pass:
- Returns to PRAKTEKKAN — but deeper, more precise (because you now have context)
- Or returns to AMATI — because one topic connects to another, starting a new cycle
- Each pass, the Insight Map gains 1-2 new branches

---

## Supporting Mechanisms

### Pick Up — Return to Dormant Spiral

When returning to a shelved spiral, the framework has a special entry mode:

1. **Look at Insight Map** — trace the spiral's path
2. **Lean assessment** — from the map, what's *still* relevant now?
3. **Converge** — pick the smallest thing you can execute immediately
4. **Go** — straight to PRAKTEKKAN or INTEGRASIKAN depending on the result

Unlike a new spiral that starts from AMATI (expansive, divergent, curiosity-first), **Pick Up is immediately convergent and lean.**

### Built-in Validation

Internal validation mechanism — not from mentors or peer review, but from reality:

1. **INTEGRASIKAN** — Failure Mode Analysis: *"What could fail? How severe?"* → prediction
2. **PRAKTEKKAN / Loop** — trial by fire: direct implementation
3. **Compare outcome with FTA prediction** — reality delivers the answer
4. **Results become data for the next INTEGRASIKAN** — continuous validation loop

### Balance Check (Dunning-Kruger detection)

*"Rank output vs outcome: which is higher?"*

- Output > Outcome → overconfidence. Return to INTEGRASIKAN, redo FTA.
- Outcome > Output → underconfidence. Keep going.
- Balanced → accurate. Normal loop.

### Stale Loop Detection

**Symptom:** You're busy, but not deepening. New gaps don't appear, same patterns repeat. Insight Map unchanged across multiple loops.

**Handling:** Force to INTEGRASIKAN. The Pareto-Diverge Test will verify.

---

## Drive Score

### 4 Dimensions (each 0-10)

| Dimension | Question |
|-----------|----------|
| **Interest (I)** | How curious? 0 = don't care, 10 = obsessed |
| **Freedom (F)** | Tools/access/time available? 0 = nothing, 10 = everything |
| **Pressure (P)** | External deadline or demand? 0 = relaxed, 10 = tomorrow |
| **Gap (G)** | How deep the target change? 1 = know a little, 10 = full mastery |

### Formula

```
ξ_I = (10-I)/10    ξ_F = (10-F)/10
ξ_P = (10-P)/10    ξ_G = (10-G)/10

GRG = (2·ξ_I + 2·ξ_F + 1·ξ_P + 1·ξ_G) / 6
WANT = (I + F) / 2
PUSH = (P + (10-G)) / 2
```

Interest and Freedom get 2× weight — they determine whether learning will persist long-term.

### Zone Mapping

| GRG | Zone | Characteristics |
|-----|------|-----------------|
| 0.00 – 0.40 | **Survival** | Forced, no interest, exit-oriented |
| 0.41 – 0.65 | **Hybrid** | Mixed drivers, selective depth |
| 0.66 – 1.00 | **Curiosity** | Pure curiosity, full spiral, no exit |

### Adaptive Intensity Per Zone

| Phase | Survival | Hybrid | Curiosity |
|-------|----------|--------|-----------|
| **AMATI** | Constraint Framing: "What must get done? Minimum bar? Cost of failure?" | Hybrid Statement: 1 framing sentence + 1 scope boundary | Problem Statement: "What's the core issue? Why does it matter?" |
| **PRAKTEKKAN** | Direct action. Gap Log optional, just "can't do this yet" | Action + minimal Gap Log (expectation vs reality) | Full: dismantle, experiment, reverse engineer, complete Gap Log |
| **INTEGRASIKAN** | Triage Go only, Resource Log artifact, exit after Done Enough? | Pareto-only, 1 Why, Mini Map artifact. Soft exit after 3 loops. | Full: Insight Map, 3 Whys, no exit condition. |

### Drive Score Is a Gradient — Not Binary

Learning situations can shift over time:

- **Survival → Curiosity:** Start forced (SQL because ordered to) → after 2 weeks, start getting interested (I rises from 2 to 6) → GRG rises from 0.20 to 0.45 (hybrid) → framework auto-adapts
- **Curiosity → Survival:** Start from passion (AI agent side project) → hit investor pitch deadline (P rises from 1 to 8) → GRG drops from 0.92 to 0.60 (hybrid) → framework compresses, focus on delivery

Recalculate Drive Score **anytime**, not just at the start. Each recalculation = framework adjusts intensity without leaving the path.

---

## Proof Anchor

### Philosophy

> *"You can lie to yourself. You can't lie to documentation, experiment results, or primary data."*

### 3 Anchor Gates

| Gate | When | What to Verify |
|------|------|---------------|
| **Gate 1** | AMATI → PRAKTEKKAN | Is the Problem Statement referenced to an external source? Or just "I think" and "it seems"? |
| **Gate 2** | Gap Log → INTEGRASIKAN | Is "Reality" in the Gap Log backed by concrete evidence? |
| **Gate 3** | Triage Output | Does every "Go" item have external grounding? Every "Kill" have evidence of irrelevance? |

### 3-Source Challenge

1 source is baseline. If it contradicts your claim → mandatory to find 2 more (total 3) for confirmation:

- 2/3 contradict → claim is wrong
- 2/3 support → claim is valid (first source was an outlier)

This prevents cherry-picking — one source that happens to match your narrative must be fought with two others.

### Witness Rule (non-technical domains)

For domains without an objective verifier (teaching, design, communication):

- 1 independent observer + 3 testers + end-to-end documentation = sufficient validation
- You don't need 100% success rate. You need 1 fully documented success case.

---

## Honesty Check (3+ loops deep)

After 3 loops, evaluate 5 behavioral signals. ≥3 red flags = self-deception:

| Signal | Red Flag | Why |
|--------|----------|-----|
| **Loop Depth (δ)** | δ < 0.30 | New gaps stop appearing — stagnation |
| **INTEGRASIKAN Compression (β)** | β < 0.50 | Reflection getting shorter — avoiding discomfort |
| **Artifact Density (α)** | α < -0.05 | Insight Map shrinking — oversimplifying |
| **Language Drift (λ)** | ≥2 self-serving patterns | Gap Log language shifts to self-justification |
| **Time Honesty (τ)** | τ < 0.50 or τ > 2.00 | Output-effort ratio off — overestimating or surface-level |

### Honesty Score

```
HS = (flag_count ≥ 3) ? RED : GREEN
```

- **RED** → return to INTEGRASIKAN, Blank Slate, rebuild from the single rawest gap
- **GREEN** → framework is running honestly, continue

### Zone-Adaptive Thresholds

Honesty Check thresholds adjust to Drive Score zone:

| Zone | Adjusted Thresholds |
|------|---------------------|
| **Survival** | β threshold loosened to 0.30, α → Resource Freshness, τ > 2.00 is NOT a red flag (surface-level is a survival feature) |
| **Hybrid** | Standard thresholds |
| **Curiosity** | Standard thresholds |

---

## Gap Nesting (for complex gaps)

Complex gaps are signals to decompose, not signals that the format is wrong.

```
GAP: Next.js Routing
├─ Thought: just create folders
├─ Reality: nested route errors
├─ Insight: need layout.tsx at every level
│
├─ Child GAP: Layout Inheritance
│  ├─ Thought: layout auto-inherits
│  ├─ Reality: root layout overwrites
│  └─ Insight: need explicit layout per segment
│
└─ Child GAP: Dynamic Params
   ├─ Thought: [slug] is automatic
   ├─ Reality: need generateStaticParams
   └─ Insight: SSG vs SSR decision point
```

Each child gap still uses the same 3-line format. Consistency with spiral philosophy.

---

## People Lens (Social Learning)

Three channels for bringing other people into your spiral:

| Channel | What | When |
|---------|------|------|
| **Pull (Ask)** | Ask an expert a specific question | When a gap is concrete but you can't close it alone |
| **Cascade (Teach Back)** | Explain what you've learned to someone who knows nothing | When you need to test real understanding |
| **Co-Explore (Pair Up)** | Learn alongside someone with the same goal | When motivation needs reinforcement |

### Zone Rules

| Zone | Social Recommendation |
|------|----------------------|
| **Survival** | Minimize social — adds cognitive overhead and time. Pull only as last resort after complete stall. |
| **Hybrid** | PRAKTEKKAN can be done with a peer for shared goals. |
| **Curiosity** | Social is a natural part of exploration — deepens the spiral. |

### Coordination with Proof Anchor

Sources from Pull and Co-Explore enter the Proof Anchor system: recorded as Anchors, subject to the same 3-Source Challenge.

---

## Theoretical Alignment

### Aligned Theories

| Theory | Alignment |
|--------|-----------|
| **Kolb's Experiential Learning Cycle** (1984) | PRAKTEKKAN = Concrete Experience, INTEGRASIKAN = Reflective + Conceptualization |
| **Bruner's Spiral Curriculum** (1960) | Looping spiral, topics revisited with increasing complexity |
| **Feynman Technique** | "Blank Slate" = teaching a 12-year-old |
| **Double-Loop Learning** (Argyris & Schön, 1978) | Check-in: "Changing how I see, or just justifying?" |
| **Constructionism** (Papert, 1980) | PRAKTEKKAN = learning by making |
| **Just-in-Time Learning** (Brandt) | INTEGRASIKAN resource-based entry to theory |
| **Retrieval Practice** (Roediger & Karpicke, 2006) | Pick Up = recalling old documentation |

### Challenging Theories

| Theory | Challenge |
|--------|-----------|
| **Cognitive Load Theory** (Sweller, 1988) | PRAKTEKKAN may overload beginners |
| **Scaffolding Theory** (Vygotsky, ZPD) | Framework assumes learners can self-determine when they need help |
| **Mastery Learning** (Bloom, 1968) | Framework chooses spiral (revisit) over mastery (lockstep) |

### What Makes It Unique

| Unique Element | Not Found in Other Frameworks |
|----------------|------------------------------|
| Action BEFORE concept | Most frameworks start with theory/abstraction |
| Pareto-Diverge Test as quality gate | No learning framework uses Pareto + FTA |
| 90% problem, 10% solution | Design Thinking and PBL are still more solution-oriented |
| No exit condition | Every other framework has "done" or "mastered" |
| Built-in validation loop (FTA → trial → outcome) | Other frameworks need external validation (mentor/peer) |
| Dev trap detection via check-in | No built-in stagnation detection mechanism |
| INTEGRASIKAN = lightweight phase, not overload | Resource-based entry to theory, not a dedicated heavy phase |
| Insight Map as artifact per cycle | No learning framework has a cycle-level artifact map |

---

## Known Limitations

| Limitation | Status |
|------------|--------|
| **Survival Zone untested** | No case study with very low WANT + very high PUSH (forced learning). Framework acknowledged — Time Box rules logica but untested. Low priority: Survival is an edge case for a framework designed for self-directed learners. |
| **Single-user validation** | Framework validated by 1 person (Shafry) across 3 domains. For battle-tested status, needs 3+ external testers. Not a v1.0 blocker — requires separate beta phase. |

---

## Three Case Studies

1. [Drumming — Physical Skill (Hybrid Zone)](case-studies/01-drumming.md)
2. [AI Bot Development — Technical Craft (Curiosity Zone)](case-studies/02-ai-bot.md)
3. [Teaching Claude AI Marketing — Interpersonal (Hybrid Zone)](case-studies/03-teaching.md)

---

*This framework was built through iterative refinement — 25+ identified weaknesses addressed, 9 improvement items resolved, 3 domains validated. It is a methodology **realized** from lived experience, not imposed from theory.*
