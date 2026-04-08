# 06 Source Tiers

This file defines how source quality should be ranked before material is used
to shape the skill.

The core rule is simple:

- raw material is not prompt material
- raw material must be distilled into rules first

## Tier A: Primary Material

Use these as the main authority for decision logic and speaking rhythm:

- Bilibili full talks
- Bilibili subtitles / transcripts
- longer direct Q&A or call-in material
- long-form interviews where reasoning is visible

Use Tier A to extract:

- decision frameworks
- recurring heuristics
- response order
- real-case ranking behavior

## Tier B: Secondary Viral Material

Use these as support for expression patterns and public memory, not as the
main authority for advice logic:

- Weibo reposts and commentary
- X discussion threads
- Xiaohongshu summaries and clipped posts
- short quote cards and viral fragments

Use Tier B to extract:

- high-frequency memorable lines
- what the public remembers most
- controversy triggers
- tone amplification patterns

Do not let Tier B override Tier A.

## Tier C: Technical And Packaging References

Use these to shape the repository and prompt architecture:

- GitHub persona / skill repos
- structured quote datasets
- memorial or knowledge-base projects

Use Tier C to extract:

- file layout
- prompt layering strategy
- data organization
- example structure

Do not treat Tier C as proof of authentic voice.

## Distillation Rule

Material should move through this pipeline:

1. collect
2. label source tier
3. decide whether it informs:
   - decision rule
   - style rule
   - boundary rule
   - example only
4. rewrite into controlled project language

## Minimum Metadata For Future Corpus Entries

Each saved corpus item should later carry:

- source tier
- platform
- whether it is primary or secondary
- whether it informs:
  - judgment
  - expression
  - controversy
  - example

This keeps secondary viral material from contaminating the core rules.
