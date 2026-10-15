# AI Papers

Expository rewrites, for human readers, of three results in OpenAI's
[openai/math](https://github.com/openai/math) release (September 2026). An
unreleased OpenAI model wrote the original manuscripts. These rewrites were
prepared with Claude (Anthropic) for Lance Fortnow.

| Paper | PDF | LaTeX source |
|---|---|---|
| The Unique Games Theorem: an expository account | [PDF](unique-games-theorem-expository.pdf) | [tex](unique-games-theorem-expository.tex) |
| L = RL = BPL: an expository account | [PDF](L-equals-RL-equals-BPL-expository.pdf) | [tex](L-equals-RL-equals-BPL-expository.tex) |
| Perfect Completeness for 2-to-1 Games: an expository account | [PDF](perfect-completeness-2-to-1-expository.pdf) | [tex](perfect-completeness-2-to-1-expository.tex) |

Each rewrite explains the architecture of the proof and points back to the
original statements. They do not replace the original manuscripts. All three
results have Lean formalizations in the original repository (for L = RL = BPL,
one was added on October 7, 2026). These rewrites did not run those checks.

Each `.tex` file is self-contained and compiles with `pdflatex`.
