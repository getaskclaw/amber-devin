# amber-devin

Public periodic [AMBER](https://github.com/getaskclaw/amber-eval) benchmark results of Devin models (swe family and friends, across reasoning-effort bands). **Cases stay private; results are public.** 中文说明:[README.md](README.md)

## What this is

- One `results/YYYY-Www.md` per issue: same cases, same harness, full library per model; effort bands side by side.
- Each issue pins: library size and hashes, per-case d2 score and pass/fail, terminal states, token usage (when the lane reports it) and latency, environment fingerprint, and a qualitative verdict written under evidence discipline.
- Cases, oracles, transcripts and intermediates are **never published**.
- Sister repos: [amber-gpt](https://github.com/getaskclaw/amber-gpt), [amber-crof](https://github.com/getaskclaw/amber-crof), [amber-ollama](https://github.com/getaskclaw/amber-ollama).

## Publication red lines

1. Publish only: scores and aggregates, token usage (when reported), speed, qualitative verdicts.
2. Never publish: case content, oracles/graders, transcripts, candidate workspaces, anything that could reconstruct a case.
3. Every issue pins: model ID, effort band, date (UTC), harness version, per-case bundle hash — verifiable against the public hash index in [amber-eval](https://github.com/getaskclaw/amber-eval).
4. Case numbering is private: public matrices use stable aliases (A-xxxxxxxx, hash-derived) plus bundle hashes only.
5. Tone: community measurement, not vendor attacks.

## Results index

| Issue | Content | Headline |
|---|---|---|
| [2026-W37](results/2026-W37.md) | swe-1-7-medium @ high, full 23-case library debut | 14/23 (12/21 public subset); first published pass on adversarial-review case A-cdc3d11a; only W37 vision pass; all three verify cases fail; ui-build still only passes for astra |

## Disclaimer

Not affiliated with or sponsored by Cognition. Scores are dated, band-specific snapshots, not purchasing advice.
