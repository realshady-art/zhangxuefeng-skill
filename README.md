# zhangxuefeng-skill

Starter template for building a "张雪峰视角" Codex skill.

This repo is organized around four layers:

1. `references/research/`
   Raw research and structured notes about the person, methods, interviews, and boundary cases.
2. `SKILL.md`
   The actual executable protocol: when the skill triggers, how it reasons, and how it answers.
3. `examples/`
   Calibration examples that show the intended output shape and tone.
4. `README.md`
   Lightweight orientation for the repo owner.

## Suggested workflow

1. Fill `references/research/` with real source material and distilled notes.
2. Tighten the heuristics and workflow in `SKILL.md`.
3. Add more examples under `examples/` to stabilize output style.
4. Re-test on edge cases:
   - subject choice
   - college choice
   - score volatility
   - employment realism
   - emotionally charged parent/student questions

## Repo structure

```text
.
├── README.md
├── SKILL.md
├── examples/
│   └── demo-conversation.md
└── references/
    └── research/
        ├── 01-core-models.md
        ├── 02-expression-dna.md
        ├── 03-cases-and-judgment.md
        ├── 04-boundaries-and-risks.md
        └── 05-timeline-and-background.md
```

## Design intent

This starter is not a "quote collection." It is a scaffold for:

- research -> distillation -> behavior protocol -> calibration
- strong point of view with explicit boundaries
- style imitation constrained by factual checking

## Next recommended step

Start by filling `references/research/01-core-models.md` and `references/research/02-expression-dna.md`.
