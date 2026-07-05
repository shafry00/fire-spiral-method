# Gap Log Template

Reusable template. Copy-paste for each gap. Print extras.

---

## Single Gap

```
GAP: [one-line title]
────────────────────────────────────────────
Thought:  [what I expected before acting]

Reality:  [what actually happened — be specific,
          include error messages, timestamps,
          concrete observations]

Insight:  [the gap between expectation and reality.
          What does this reveal that I didn't
          anticipate?]
────────────────────────────────────────────
Proof Anchor: □ Gate 1 (Reproduce)
              □ Gate 2 (Explain)
              □ Gate 3 (Break)
Triage:       □ Go   □ Review   □ Kill
```

---

## Gap Nesting (Complex Gaps)

Use when a single gap branches into sub-problems:

```
GAP: [parent gap title]
┌──────────────────────────────────────────┐
│ Thought:                                 │
│ Reality:                                 │
│ Insight:                                 │
└──────────────────────────────────────────┘
│
├─ CHILD GAP: [sub-problem 1]
│  ┌──────────────────────────────────────┐
│  │ Thought:                             │
│  │ Reality:                             │
│  │ Insight:                             │
│  │ Triage: □ Go  □ Review  □ Kill      │
│  └──────────────────────────────────────┘
│
├─ CHILD GAP: [sub-problem 2]
│  ┌──────────────────────────────────────┐
│  │ Thought:                             │
│  │ Reality:                             │
│  │ Insight:                             │
│  │ Triage: □ Go  □ Review  □ Kill      │
│  └──────────────────────────────────────┘
│
└─ CHILD GAP: [sub-problem 3]
   ┌──────────────────────────────────────┐
   │ Thought:                             │
   │ Reality:                             │
   │ Insight:                             │
   │ Triage: □ Go  □ Review  □ Kill      │
   └──────────────────────────────────────┘
```

---

## Example: Good Gap Log (with Anchor)

```
GAP: Nested routing in Next.js App Router
────────────────────────────────────────────
Thought:  From the Next.js docs "Getting Started"
          section, routing just requires creating
          folders in app/ directory. A 3-level
          nested route should take 5 minutes.

Reality:  Created app/blog/[slug]/comments/page.tsx.
          Hit the route → 404 Not Found.
          Error: "Module not found: Can't resolve
          './layout'"
          Took 45 minutes of debugging.

Insight:  Each segment in App Router needs its own
          layout.tsx. This is different from Pages
          Router where layouts auto-inherited. The
          docs assume Pages Router familiarity —
          migration context is missing.
────────────────────────────────────────────
Proof Anchor: ☑ Gate 1 — can reproduce nested 404
              ☑ Gate 2 — can explain to a new dev
              □ Gate 3 — can't yet identify all
                layout failure modes
Triage:       ☑ Go
```

---

## Red Flags — When Your Gap Log Is Too Vague

| Vague (weak) | Specific (strong) |
|--------------|-------------------|
| "It was harder than expected" | "Took 2 hours instead of 30 minutes because of authentication loop (error: 'session expired' at step 3)" |
| "The API was confusing" | "3 endpoints return similar JSON but `/v2/search` uses snake_case while `/v2/lookup` uses camelCase" |
| "I need to learn more about this" | "I can build routes but can't explain why middleware fires twice in edge runtime" |
| "The tutorial was outdated" | "Tutorial uses v14 API. In v15, `createServerClient` replaces `createClientComponentClient` — found this in the v15 migration guide" |

### The Rule

If someone else can't verify your gap independently, it's too vague. Add concrete data.

---

## Gap Quality Self-Check

After writing each gap, ask:

1. **Falsifiable?** — Can someone else prove this wrong if it is?
2. **Specific?** — "Error 404 on route `/x`, 3 attempts" vs "didn't work"
3. **Actionable?** — Can I design the next practice session around this gap?
4. **Anchored?** — Is there an external source or observation backing the "Reality"?

All 4 = gold. 3 = good. 2 = fix it. 1 = rewrite.

---

*File under CC BY-SA 4.0.*
