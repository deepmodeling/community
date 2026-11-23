# A Vote for New Projects: riemann-hypothesis

## Proposal
**riemann-hypothesis** is a community collaboration hub for the Lean 4 formalization behind the claimed proof of the Riemann Hypothesis — and, more broadly, the DeepModeling community's first open infrastructure for **agentic science**: humans and AI agents jointly attacking frontier scientific problems under machine verification.

**Background.** On 2026-11-20, a claimed proof of the Riemann Hypothesis (and GRH for Dirichlet L-functions) was released as a 175,187-file Lean 4 archive, and the Lean FRO and Mathlib communities certified the formal statement and proof the next day. The author himself expects much shorter proofs to follow. To turn "shorten the proof" into a community effort, we converted 13 core pillars of the formalization (1,938 deduplicated `.lean` files, ≈1.7% of the 980M-character archive) into machine-verified challenges on the Agentic Science Playground, scored by the Lean kernel with an anti-golf token metric. The response has been remarkable: 267K+ views within 24 hours, participants worldwide competing with their own AI agents, and the community frontier already at ~−65% token reduction on the Core 1–13 subset, with Phase 3 expansion underway.

**What this repo hosts.** Forked from `leanprover-community/riemann-hypothesis` with the full upstream history (plus the frozen original archive) preserved, the repo adds: (i) lightweight static PR checks (~12s: `0 sorry` / standard-axioms / token-delta scans); (ii) maintainer-gated Bohrium sandbox verification (`lake build` + `#print axioms` + Comparator); and (iii) attributed Draft PRs mirroring frontier results from the Playground leaderboard — forming a dual-track contribution model of direct GitHub PRs and Playground CLI submissions. Live board: https://riemann.verifytask.cn/ · Discord: https://discord.gg/dUeUNEY5pc · Predecessor personal repo: https://github.com/Osgood001/riemann-hypothesis.

**A note on process (a deliberate deviation from the usual mechanism).** Unlike our standard "vote first, create later" procedure, this repository has been created in advance (currently private) and will be made **public as soon as it is ready, in parallel with this vote** — because the scientific moment is fast-moving and weeks of delay would forfeit the community momentum. We ask TOC members for their understanding of this exception. The vote remains fully meaningful: any objection raised during the voting period will be discussed in good faith, and if the outcome is against hosting the repository under DeepModeling, we will archive or remove it accordingly.

## Deadline
The vote will be open for at least 7 days unless there is an objection.

(As noted above, due to timeliness the repository will go public once ready, in parallel with the voting period. Objections raised during the vote will be openly discussed, including the possibility of closing the repository.)

## Scope
TOC MEMBERS.
