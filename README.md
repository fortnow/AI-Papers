# AI Papers

Expository rewrites, for human readers, of two results in OpenAI's
[openai/math](https://github.com/openai/math) release (September 2026). An
unreleased OpenAI model wrote the original manuscripts. These rewrites were
prepared with Claude (Anthropic) for Lance Fortnow.

| Paper | PDF | LaTeX source |
|---|---|---|
| The Unique Games Theorem: an expository account | [PDF](unique-games-theorem-expository.pdf) | [tex](unique-games-theorem-expository.tex) |
| L = RL = BPL: an expository account | [PDF](L-equals-RL-equals-BPL-expository.pdf) | [tex](L-equals-RL-equals-BPL-expository.tex) |

Both rewrites explain the architecture of each proof and point back to the
original statements. They do not replace the original manuscripts. The Unique
Games result has a Lean formalization in the original repository; the L = RL =
BPL result does not.

Each `.tex` file is self-contained and compiles with `pdflatex`.
