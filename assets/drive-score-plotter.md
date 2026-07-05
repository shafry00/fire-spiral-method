# Drive Score Visual Plotter

Plot your zone visually. Recalculate anytime — Drive Score shifts as your situation changes.

---

## Current State

```
Interest:  ___ / 10
Freedom:   ___ / 10
Pressure:  ___ / 10
Gap:       ___ / 10
```

## Calculation

```
WANT = (Interest + Freedom) / 2 = (___ + ___) / 2 = ___
PUSH = (Pressure + (10 - Gap)) / 2 = (___ + (10 - ___)) / 2 = ___
```

## Plot

Draw your dot on the zone map:

```
PUSH ↑
10  │                    ╔══════════════╗
    │  SURVIVAL          ║   HYBRID     ║
 9  │  constrained,      ║   mixed,     ║
    │  fast, exit        ║   selective  ║
 8  │                    ║              ║
    │                    ║              ║
 7  │ ───────────────────║──────────────║─────────────
    │                    ║              ║
 6  │                    ║              ║
    │                    ║              ║
 5  │     START          ║              ║
    │     too early      ║              ║
 4  │     to tell        ║              ║
    │                    ║   CURIOSITY  ║
 3  │ ───────────────────║──────────────║─────────────
    │                    ║   deep,      ║
 2  │                    ║   no exit    ║
    │                    ║              ║
 1  │                    ║              ║
    │                    ║              ║
 0  └────────────────────╚══════════════╝─────────────→ WANT
    0   1   2   3   4   5   6   7   8   9   10
```

### What Your Zone Means

| Zone | Range | Strategy |
|------|-------|----------|
| **Start** | WANT < 5, PUSH < 5 | Too early. No urgency, no interest. Go to Float Mode — observe, detect anomaly, wait for a trigger. |
| **Survival** | WANT < 7, PUSH ≥ 7 | Forced learning. Constraint Framing is mandatory. Honor Time Box. Exit after Done Enough. |
| **Hybrid** | Mixed | Selective depth. Use all tools but apply Pareto filter aggressively. Soft exit after 3 loops. |
| **Curiosity** | WANT ≥ 7, PUSH < 7 | Full spiral. Full toolkit. Constraint Framing still mandatory to prevent over-engineering drift. |

### Zone Boundary Explained

The boundaries are approximate — Drive Score is a gradient, not a switch:

- **WANT=5** — below this, curiosity is too weak to drive sustained action without external push
- **PUSH=7** — above this, external pressure dominates, learning becomes exit-oriented
- **WANT=7, PUSH=3** — the Curiosity sweet spot: high intrinsic motivation, low external noise
- **WANT=3, PUSH=9** — the Survival grind: forced, no interest, pure throughput

---

## Zone Shift Tracker

Track how your zone changes over time:

```
Date        I   F   P   G   WANT  PUSH  Zone
────────    ──  ──  ──  ──  ────  ────  ────────
Start       _   _   _   _   ___   ___   ________
Mid-loop    _   _   _   _   ___   ___   ________
End-loop    _   _   _   _   ___   ___   ________
```

### Common Shifts

| From | To | Why |
|------|----|-----|
| Survival → Hybrid | P drops as deadline passes, I rises as you get into it | Common for mandatory training that turns interesting |
| Curiosity → Hybrid | P rises (investor pitch, presentation deadline) | Side project becomes urgent |
| Hybrid → Curiosity | P drops (deadline met), I remains high | Post-deadline, can go deeper |
| Start → Any | Anomaly detected, curiosity triggered, or deadline imposed | Float Mode worked |

---

## Example Plots

### Example 1: Survival

```
Interest: 3   Freedom: 3   Pressure: 9   Gap: 8
WANT = 3.0   PUSH = 5.5   Zone: Survival/Hybrid border
```
→ Strategy: Constraint Framing, 3×25m sessions, Go-only triage, exit fast.

### Example 2: Curiosity

```
Interest: 10  Freedom: 9   Pressure: 2   Gap: 3
WANT = 9.5   PUSH = 4.0   Zone: Curiosity
```
→ Strategy: Full spiral, 4×45m sessions, 3 Whys, Constraint Framing mandatory.

### Example 3: Hybrid

```
Interest: 7   Freedom: 8   Pressure: 6   Gap: 7
WANT = 7.5   PUSH = 4.5   Zone: Hybrid
```
→ Strategy: 3-4×45m sessions, Pareto filter, 1 Why, Mini Map.

---

*File under CC BY-SA 4.0. Plot freely.*
