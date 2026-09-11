# erdos-release-index

An index to thirty-six public repositories of mathematics: Erdős problem attacks, Lean
formalizations, computational certificates, papers, and the record of what failed.

Author: Jared Wilder. Released 2026-09-10.

---

## The release was re-checked after it was published

Every verifier in these repositories was re-run from committed source on 2026-09-10/11, hours after
going public. **All 14 exit 0.** Two took arguments that the documentation never mentioned, so no
reader could have invoked them; both are now documented.

The headline computation was re-run too. The exhaustive exact-integer sweep behind
**d(2,8) > 30000** reproduced its committed receipt in **every field but the wall clock** -
136,801,313 cells, 6 solutions, 0 non-trivial, correctness gate 6/6, all six solution records
byte-identical including their exact coordinates over Q(sqrt 2002).

The cover verifier is the one to look at: it **rejects** the 8-block receipt and names the two
pairs it fails to cover. A verifier that only ever agrees is indistinguishable from one that does
nothing.

Details: [RUNNING-THE-VERIFIERS.md](https://github.com/jaredwilder/erdos-campaign-archive/blob/main/RUNNING-THE-VERIFIERS.md)
and [REPRODUCTION.md](https://github.com/jaredwilder/integral-point-sets/blob/main/REPRODUCTION.md).

---

## Start here

The results that move a published number are in the next section. If you want to know why to
trust them, the three repositories below are the reason: this program publishes its retractions,
its false closures and its failed audits under their own names, with the same timestamps as its
successes.

| repository | what it contains |
|---|---|
| [eg411-superseded-closure-claims](https://github.com/jaredwilder/eg411-superseded-closure-claims) | A Lean theorem with a **perfect axiom footprint and a false conclusion**, published beside the author's own retraction fourteen days later. The check it proved was true at every prime the problem asks you to rule out, so proving it universally carried zero information. |
| [oracle-math-honest-inventory](https://github.com/jaredwilder/oracle-math-honest-inventory) | A problem-by-problem inventory written under the rule *"partial is not rounded up to closed."* It flags a contradiction between two of the author's own documents and refuses to pick the larger number, and records one computation as *"never finished... not a null and not a refutation."* |
| [erdos411-retraction-record](https://github.com/jaredwilder/erdos411-retraction-record) | 75 research packets under their original filenames, including `ABSOLUTE_KILLSHOT` and `FULL_VICTORY_PROOF_FRONTIER`, shipped with the retraction that kills them. |

---

## Results that move a published number

| repository | result |
|---|---|
| [integral-point-sets](https://github.com/jaredwilder/integral-point-sets) | **ḋ(2,8) > 30000** for integral octagons in general position. The prior bound was the hereditary ḋ(2,8) ≥ ḋ(2,7) = 22270 from Kreisel–Kurz 2008. Proved via maximality of the Kreisel–Kurz heptagon, with no height bound required. Plus 394 impossibility certificates and ḋ(2,4)=8, ḋ(2,5)=73, ḋ(2,6)=174. |
| [erdos902-tournament-f4](https://github.com/jaredwilder/erdos902-tournament-f4) | A **candidate f(4) ≥ 49** against the published record of 48 (Reid–McRae–Hedetniemi–Hedetniemi 2004). Python-replicated, **not kernel-sealed**, McKay–Spence completeness cited not re-derived. Withdrawn on request if already known. |
| [graham-alspach-certificates](https://github.com/jaredwilder/graham-alspach-certificates) · [·sequenceability](https://github.com/jaredwilder/graham-alspach-sequenceability) | Graham/Alspach certified for subset sizes **21–28 in ℤ₂₉ and 21–30 in ℤ₃₁**, where published general results reach 20. Dual-verified in Go and Python, with four classes of corrupted certificate rejected by both. |
| [erdos1084-harborth](https://github.com/jaredwilder/erdos1084-harborth) | A **correction to DeepMind's formal-conjectures metadata**: `erdos_1084.variants.triangular_optimal_d2` is tagged `research open` but follows from Harborth 1974. |

## New to Mathlib

| repository | contribution |
|---|---|
| [lean-contributions](https://github.com/jaredwilder/lean-contributions) | An **unsubmitted Mathlib PR** for Steiner triple systems and Kirkman's theorem: 1,473 lines, `import Mathlib` only, **0 sorry**, 38 lemmas. Plus the first Lean formalization of Erdős 1066. |
| [erdos-close-campaigns](https://github.com/jaredwilder/erdos-close-campaigns) | **`rothNumberNat 14 = 8` and `rothNumberNat 15 = 8`** — the first exact values of Mathlib's own `rothNumberNat` — plus a supermultiplicativity lemma absent from Mathlib. No `sorryAx`, no `native_decide`. |

## Sharp finite results

| repository | result |
|---|---|
| [additive-combinatorics-campaigns](https://github.com/jaredwilder/additive-combinatorics-campaigns) | First 13-element C₃-free set has **minimum span exactly 60**; all 13-sets of span ≤ 63 classified as exactly 6 sets in 4 orbits; eight-element C₅-free minimum span **exactly 25**; exponent **log₇3 = 0.5646 > ½**; and a kernel-checked theorem backed by a **447,254-addition LRAT proof** shipped in 270 chunks. |
| [erdos595-barrier-tower](https://github.com/jaredwilder/erdos595-barrier-tower) | **Non-coverability begins exactly at 𝔠⁺.** Every graph on ≤ continuum vertices is coverable by countably many triangle-free graphs; the least witness has uncountable cofinality and lives in one component. 27 Lean files, all sorry-free. **The problem is not closed.** |
| [combinatorial-records](https://github.com/jaredwilder/combinatorial-records) | **f(7) ≥ 24** for binary Sidon sets with a verifier that exits 0; 677 covering numbers with monotonicity validated; **two triples proved strictly above the Schoenheim bound**; circulant Ramsey exhaustion at R(3,10) n=40 and R(4,6) n=36. |
| [erdos710-descent-and-1044](https://github.com/jaredwilder/erdos710-descent-and-1044) | f(p) < f(p−1) for **every prime 13 ≤ p ≤ 113, 25 of 25**, with the last five computed *after* the law was stated. Marked **OBSERVED, not a theorem.** Plus a closed form for the Erdős 1044 extremal family. |

## Formal corpora

| repository | scale |
|---|---|
| [lean-forge-graph-theory](https://github.com/jaredwilder/lean-forge-graph-theory) | 218 Lean files on C₄-free and K₄-free structure, **0 containing `sorry`**, standalone with no Mathlib dependency |
| [erdos-theorems](https://github.com/jaredwilder/erdos-theorems) | 79 declarations across 15 problems, **every one clean-axiom**, with `.axioms.txt` and `.verify.json` per file |
| [erdos-cable-corpus](https://github.com/jaredwilder/erdos-cable-corpus) | 914 Lean files over 152 problems. 891 are sorry-free **in the text**; joining the receipts to the files shows **211 with a clean axiom footprint and 267 that failed to compile**. Lean supplies `sorryAx` itself when elaboration fails, so textually sorry-free is not verified. The join and the per-file verdicts are published as `JOIN.json`. |
| [erdos152](https://github.com/jaredwilder/erdos152) | 160 statement formalizations with the full defect audit, **including the 72 the gate rejected** |
| [eg203-eg411-corpus](https://github.com/jaredwilder/eg203-eg411-corpus) | ω(N) ≥ 8 unconditional, the ω≤7 kill tree with **272,676 empty terminals**, no exceptional prime below 1.33×10¹⁴ |

## Papers

| repository | contents |
|---|---|
| [eg203-kummer-papers](https://github.com/jaredwilder/eg203-kummer-papers) | 17 papers with compiled PDFs, headlined by Sharp Dichotomy at ℓ log ℓ ≍ log Q, **including paper 05, an audit of the routes that fail** |
| [unpublished-math-papers](https://github.com/jaredwilder/unpublished-math-papers) | A combinatorial sieve lower bound π_V(m,D) ≥ c·𝔖(m)·D for the EG203 family, marked by its own title page **"preprint, expert review pending"** |
| [erdos203-obstruction-calculus](https://github.com/jaredwilder/erdos203-obstruction-calculus) | The seven-round converged packet with its own no-overclaim rules and a failed-routes audit paper |

## Data and tooling

| repository | contents |
|---|---|
| [open-math-frontier](https://github.com/jaredwilder/open-math-frontier) | **9,926 open problems**, 8,501 with a callable mechanical verifier, openness marked by source across seven databases |
| [frontier-math-target-data](https://github.com/jaredwilder/frontier-math-target-data) | Target registries, problem shapes, a normalized technique catalog, the Erdős database. **The strategy layer is deliberately withheld and named.** |
| [lean-semantic-blades](https://github.com/jaredwilder/lean-semantic-blades) | A 33-blade semantic certification gate. Over 160 formalizations it certified **zero**, and the README explains why that is a missing input rather than a verdict. |
| [ck-gold-and-r3-envelope](https://github.com/jaredwilder/ck-gold-and-r3-envelope) | 380 verified r₃ bounds, each carrying its witness and the weaker bound it supersedes |

## The working record, published whole

| repository | contents |
|---|---|
| [erdos-campaign-archive](https://github.com/jaredwilder/erdos-campaign-archive) | **266 campaigns across 241 problems**, published entire. A representative audit of twenty found one proved theorem, four refutations, and seven that produced nothing. |
| [erdos-attack-logs](https://github.com/jaredwilder/erdos-attack-logs) | Erdős 345, 835, and **950 refuted**, published under its own name |
| [erdos-computational-searches](https://github.com/jaredwilder/erdos-computational-searches) | A 4.6×10¹¹ exhaustion frontier for Erdős 850, and the prior-art verdict that retired the lane: **Langevin 1993, "a correct rediscovery, not a discovery"** |
| [erdos-findings-ledger](https://github.com/jaredwilder/erdos-findings-ledger) | 51 verdicts with claim ceilings, including **a fabricated benchmark citation the author caught and retracted** |

## Added after the index was first written

| repository | contents |
|---|---|
| [kreisel-kurz-heptagon-extension](https://github.com/jaredwilder/kreisel-kurz-heptagon-extension) | An **exact Diophantine reduction** of the integral-octagon existence question over Q(sqrt 2002). Both Kreisel-Kurz heptagons reconstructed exactly; a master quartic with four linkage equations linear in the squares; the three-point sub-condition shown to be a **genus-zero conic**, so all difficulty sits in four stacked square-conditions. Verdict REDUCED, not closed. |
| [zero-sum-theorem-closures](https://github.com/jaredwilder/zero-sum-theorem-closures) | A deterministic generator **saturating at 889 typed theorems** from 27 seeds over 7 generations, independently re-verified with **10,528,320 assignment checks and modelCalls: 0** |
| [erdos-lean-remainder](https://github.com/jaredwilder/erdos-lean-remainder) | Two finished proofs, and **73 formalization attempts of which 70 still contain sorry** |

## Published in parallel by a second session

[combinatorial-records](https://github.com/jaredwilder/combinatorial-records) grew substantially
after this index was written, from a concurrently running session. It now also holds:

| topic | contents |
|---|---|
| **Lonely Runner, 13 effective speeds** | `lonely-runner/` — a 42-entry theorem bank from a 19-round campaign. **Court verdict: LRC(13) NOT CLOSED.** Strongest closed subproblem is the large-prime canonical class p > 2366. The file states its own authority boundary: the known proof through 12 effective speeds is an external input, later deductions are session mathematics whose historical novelty was **not certified**, and `LIVE-CERTIFIED` means a finite or computational certificate is attached, **not** proof-assistant formalization. |
| **Ramsey R(5,5)** | `ramsey-r55/` — a pure-mathematics deep dive |
| **Erdős 500** | `erdos500/` — a deletion-density and inheritance toolkit with ledgers |
| **C(13,6,3)** | `covering-designs/` and `covering/` — witnesses and target-20 cover structure |
| **Additive encodings** | `additive-encodings/` — an abstract theorem bank |
| **Automata** | `automata/` — finite transducer monoids, quotients and robust bounds, plus an abstract Lean identity index |
| **Witness vault** | `witness-vault/` — audited witnesses |

That session publishes under the same discipline: it names what is not closed, and refuses to
launder conditional steps into proofs.

## Earlier repositories

[erdos203](https://github.com/jaredwilder/erdos203) · [erdos411](https://github.com/jaredwilder/erdos411) · [erdos902](https://github.com/jaredwilder/erdos902) · [msl-ore-estate](https://github.com/jaredwilder/msl-ore-estate)

---

## What is claimed

**No Erdős problem is claimed closed anywhere in this release.**

One result improves a published bound. One is a candidate against a published record, labeled as
not kernel-sealed. Two extend published ranges. One corrects another group's metadata. Three are
new to Mathlib. The rest are bounds, formalizations, certificates, reductions, refutations, and
the working record.

Every repository states its own limits on its front page. Where a claim is conditional, the
condition is named. Where a computation did not finish, it says so. Where a verifier could not
decide, that is reported as undecided rather than as a pass.

## License

Apache-2.0 throughout, matching Mathlib. Upstream data retains its own terms.
