## Nick Trapp

CS master's student at UIUC, graduating December 2026. Currently a software
engineering intern at Microsoft; previously an SDE intern at Amazon and AWS.

I like problems where a system has to be *correct*, not just working — solvers
whose speedups you can measure, LLM pipelines that can't quietly make numbers up,
evaluation sets that are allowed to return bad news. Most of what's here is that
instinct applied to a different domain each time.

Looking for new grad roles starting 2027 — software engineering, and research
engineering / applied science where the work stays close to the systems.

### Selected work

**[combinatorial-auctions](https://github.com/NickTrapp/combinatorial-auctions)** —
Engineering faster exact solvers for the auction Winner Determination Problem.
Branching guidance gives up to 11× over Gurobi's default on hard mid-size
instances — and is slower on the largest one tested, which is in the README too.

**[tv-writer-ai](https://github.com/NickTrapp/tv-writer-ai)** — A workspace for
writing a TV pilot with a language model, where output is a branch rather than an
answer. Every step generates competing alternatives; promoting one folds it into
the project's canon, which then constrains everything generated afterwards, so the
model can't contradict a choice you locked in three scenes ago. Next.js, Prisma,
Gemini.

**[poker-coach](https://github.com/NickTrapp/poker-coach)** — A no-limit hold'em
coaching system built on one invariant: the model explains, it never calculates.
Equity, pot odds, EV and MDF come from a deterministic layer and are handed to the
model as given facts; a separate checker fails any response that cites a figure it
wasn't given. A right answer reached by fabricating numbers is still a failure.
872 tests.

**[rag-document-qa](https://github.com/NickTrapp/rag-document-qa)** —
Retrieval-augmented QA over private PDFs: OCR fallback for scanned documents,
sentence-boundary chunking, ChromaDB retrieval, and a ROUGE-scored evaluation set
so the quality claims are checkable.

**[linking-wikipedia-pages](https://github.com/NickTrapp/linking-wikipedia-pages)** —
BFS, iterative-deepening DFS and simplified PageRank over the SNAP Wikipedia link
graph. C++, course team project.

### Tools

Python · C++ · TypeScript · PyTorch · Gurobi · Docker · AWS

### Elsewhere

[nicktrapp.com](https://nicktrapp.com) · [ndtrapp2@illinois.edu](mailto:ndtrapp2@illinois.edu) 
