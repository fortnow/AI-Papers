---
title: "Mathematicians React to OpenAI's October 6, 2026 Math Release"
subtitle: "A review of the commentary, with links"
date: "October 18, 2026"
---

On October 6, 2026, OpenAI posted 722 manuscripts in 372 result families to [openai/math](https://github.com/openai/math), produced by an unreleased internal model ([OpenAI announcement](https://openai.com/index/sharing-ai-progress-in-mathematics/)). By OpenAI's account the model was posed roughly 4,000 problems, with an average of about three hours of ChatGPT Pro–level compute per result. Lean formalizations accompany some but not all results, and three manuscripts were withdrawn within a day over a sign error ([history](https://github.com/openai/math/blob/main/history.md)). The reactions from mathematicians fall roughly into four camps.

## The awed

Levent Alpöge, now at Anthropic, called it [the most significant moment in mathematical history](https://x.com/__alpoge__/status/2107616859595981117), notable given his earlier dispute with OpenAI over its Navier–Stokes claim. Alvaro Lozano-Robledo called October 6 possibly the most important day in the history of mathematics, while noting that the model targeted the Riemann Hypothesis and got only a quasi-RH. Ben Green said the release resolved roughly three-quarters of the research goals of a European grant he had received that June, and Roman Sauer recognized a technique he had developed over years in solutions to two unrelated problems ([The Decoder](https://the-decoder.com/how-much-beauty-have-we-lost-mathematicians-react-with-shock-and-disgust-as-openai-bulldozes-their-field/), summarizing the [Proofs and Prompts collection](https://proofsandprompts.com/2026/10/08/100-reactions-to-100-solutions/) of over 100 responses).

For theoretical computer science, Scott Aaronson's ["The Mathocalypse"](https://scottaaronson.blog/?p=10169) is the essential read. He catalogs the TCS results (the Unique Games Conjecture, L = BPL, sub-*n* log *n* FFT and integer multiplication, the unitary synthesis problem, parity not in QAC⁰, deterministic polynomial factoring over prime fields, among others) and relays Dana Moshkovitz's real-time reading of the UGC proof, which moved from "unreadable" to genuine admiration for its strange new recursive code within a day. He also notes what is missing: no P ≠ NP, no P = BPP, no NEXP ⊄ P/poly. Dakshita Khurana wrote [a reflective post](https://dakshitakhurana.substack.com/p/classical-at-heart) on working through the AI's proof of the unitary synthesis problem she spent years on. Constantin Kogler, who had been working on one of the problems with OpenAI's model, described feeling like he was living in a mathematical wonderland.

## The measured

Terence Tao's Mastodon thread introduced the "Math 1.0 / Math 2.0" framing that everyone now uses ([summary](https://blog.donweb.com/terence-tao-openai-matematica-math-1-0/)): the goal of being first to solve open problems has been optimized to the point of unsustainability, so the field must decenter raw problem solving and value exposition, community building and new directions. He also said the proofs appear to contain clever new ideas that will be fruitful once digested, while lamenting the absence of anyone who can present and teach them.

Peter Scholze urged patience — mathematics is a marathon, not a sprint — and warned that the systems may be close to finding attacks on widely used cryptography. Ian Agol compared the release to Perelman's 2002 proof, which took teams years to reconstruct. Martin Bridson cautioned against letting AI labs set the research agenda. The [AGMAI statement](https://agmai.org/#openai-release) from the advisory group (Gowers, Hairer, Witten and others) neither endorses nor condemns, calling the release the beginning, not the completion, of human understanding.

On reliability, Andrew Sutherland said some proofs will likely contain mistakes, possibly serious ones, and Alex Townsend said OpenAI should have released the Lean-verified manuscripts first ([NYU Shanghai RITS summary](https://rits.shanghai.nyu.edu/ai/openai-drops-722-math-manuscripts-from-an-unreleased-model)). Melissa Lee of Monash gave a balanced outsider's view in [The Conversation](https://www.zmescience.com/science/news-science/openai-released-722-math-papers-at-once-and-mathematicians-are-freaking-out/), flagging questions about the formalizations.

## The grieving

This is the most striking part of the Proofs and Prompts collection. Hugo Duminil-Copin said OpenAI claimed results on every major unsolved problem he had publicly discussed in his career and that he was paralysed. Matt Zaremsky compared four years of progress on his problem to an archaeological dig that a trillion-dollar company blasted with TNT before handing over the skeleton. PhD student Tristan Humbert learned that morning that the problem at the center of his dissertation had been claimed, and spent the day rewriting his postdoc research statement. Sam Hughes asked how much beauty had been lost; Giovanni Mongardi described mathematicians reduced to priests of a machine god. Bryna Kra at Northwestern worries the episode has made mathematicians more secretive, undermining the collaboration the field depends on ([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/ai-causes-uproar-in-mathematics-as-experts-warn-against-sharing-research-with-llms-after-openai-shares-722-manuscripts-and-proofs-professor-argues-that-the-field-must-focus-on-building-community-over-raw-solutions)). Danny Calegari offered a counterpoint: his curiosity-driven work was unaffected.

## The hostile

The [Association for Human Mathematics statement](https://www.ahmath.org/statements), reposted on Tao's blog, called the release a demonstration of power rather than scholarship and urged colleagues to stop working with OpenAI ([coverage](https://mezha.ua/en/news/mathematicians-urge-end-to-openai-collaboration-315962/)). Its line that mathematicians did not ask for this work to be done drew mockery, including from Aaronson, who compared it to Hardy asking Ramanujan who requested his identities. Henry Wilton said this would be a great way to destroy the mathematical community and criticized the absence of named authors and failure rates. Enrico Fatighenti objected that AI papers get a pass on writing quality that would sink a human submission, while the community bears the cost of deciphering them. Michael Harris at Columbia said he will not read the papers, and David Madore offered the [crudest summary](https://x.com/gro_tsen/status/2108217461577294035).

Straight news coverage: [Nature](https://www.nature.com/articles/d41586-026-03196-8), [Scientific American](https://www.scientificamerican.com/article/openai-unleashes-hundreds-more-math-results-upon-a-field-already-in-shock/), [Futurism](https://futurism.com/artificial-intelligence/mathematicians-openai-furious).

## Assessment

The durable criticism is about process, not entitlement. Withholding the model name, the prompts and the failure rates, and dumping undigested proofs, deserve the pushback they are getting. The AHM's "nobody asked" position, by contrast, will not survive the model's public release. Aaronson's contrast between the "OpenAI model" (dump raw proofs and let humans race to digest them) and the "Anthropic model" (give Vassilevska Williams and Alman time to write up the 3SUM/APSP result) may prove more consequential than any single theorem, since both leave a company deciding who gets credit, just in different ways. Neither addresses Tao's real worry: what happens to the fertility of a field once its open problems have been strip-mined.

## Sources

- OpenAI, [Sharing AI progress in mathematics](https://openai.com/index/sharing-ai-progress-in-mathematics/) and [openai/math](https://github.com/openai/math)
- The Decoder, ["How much beauty have we lost?"](https://the-decoder.com/how-much-beauty-have-we-lost-mathematicians-react-with-shock-and-disgust-as-openai-bulldozes-their-field/)
- Proofs and Prompts, [100 reactions to 100 solutions](https://proofsandprompts.com/2026/10/08/100-reactions-to-100-solutions/)
- Scott Aaronson, [The Mathocalypse](https://scottaaronson.blog/?p=10169)
- Dakshita Khurana, [Classical at heart](https://dakshitakhurana.substack.com/p/classical-at-heart)
- AGMAI, [Statement on the OpenAI release](https://agmai.org/#openai-release)
- Association for Human Mathematics, [Statements](https://www.ahmath.org/statements)
- Melissa Lee, [The Conversation, via ZME Science](https://www.zmescience.com/science/news-science/openai-released-722-math-papers-at-once-and-mathematicians-are-freaking-out/)
- [Nature](https://www.nature.com/articles/d41586-026-03196-8), [Scientific American](https://www.scientificamerican.com/article/openai-unleashes-hundreds-more-math-results-upon-a-field-already-in-shock/), [Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/ai-causes-uproar-in-mathematics-as-experts-warn-against-sharing-research-with-llms-after-openai-shares-722-manuscripts-and-proofs-professor-argues-that-the-field-must-focus-on-building-community-over-raw-solutions), [Futurism](https://futurism.com/artificial-intelligence/mathematicians-openai-furious)
- [NYU Shanghai RITS summary](https://rits.shanghai.nyu.edu/ai/openai-drops-722-math-manuscripts-from-an-unreleased-model)
- [Summary of Tao's Mastodon thread](https://blog.donweb.com/terence-tao-openai-matematica-math-1-0/)
