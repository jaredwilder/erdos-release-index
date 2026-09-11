# erdos-release-index

A living index to Jared Wilder's September 2026 public mathematics release: theorems, exact finite
results, formal proofs, computational certificates, papers, open-problem corpora, research ledgers,
and the provenance needed to audit them.

**Start with the mathematics.** Evidence tier and scope travel with every result; retractions and
failed routes are preserved as integrity records rather than used as the headline for unrelated
work.

Author: Jared Wilder. Release began 2026-09-10. This index is append-only while the release is
still expanding.

For the broader cross-subject map and historical-scale audit, see
[`open-math-frontier`](https://github.com/jaredwilder/open-math-frontier).

---

## Results first

### Published-number and finite-range advances

| repository | result |
|---|---|
| [integral-point-sets](https://github.com/jaredwilder/integral-point-sets) | **d(2,8) > 30000** for integral octagons in general position, improving the hereditary lower bound 22270. The same repo carries **394 impossibility certificates** and exact values d(2,4)=8, d(2,5)=73, d(2,6)=174. |
| [erdos902-tournament-f4](https://github.com/jaredwilder/erdos902-tournament-f4) | A computational **candidate f(4) >= 49** against the published lower bound 48, Python-replicated with a stated McKay-Spence completeness dependency. The repo also carries roughly 150 zero-sorry Lean theorems on the surrounding tournament structure. |
| [graham-alspach-sequenceability](https://github.com/jaredwilder/graham-alspach-sequenceability) | Graham/Alspach certified for subset sizes **21-28 in Z_29 and 21-30 in Z_31**, extending beyond the published general range 20. |
| [graham-alspach-extended](https://github.com/jaredwilder/graham-alspach-extended) | Further verified ranges for **Z_37, Z_41, Z_43 and Z_61**, covering **22,082,109 subsets** with independent Go/Python verification. |
| [erdos1084-harborth](https://github.com/jaredwilder/erdos1084-harborth) | A correction to the DeepMind formal-conjectures metadata: a variant marked research-open follows from Harborth 1974, together with a sealed lower-bound formalization. |
| [erdos376-successor-frontier](https://github.com/jaredwilder/erdos376-successor-frontier) | An explicit **1,006-digit integer above 10^1000** satisfying the simultaneous base-3/base-5/base-7 digit restrictions, independently reproduced with matching SHA-256. |
| [ck-sequences](https://github.com/jaredwilder/ck-sequences) | **59 exact optimal values of C_k(N)** across k=3,4,5, each with a solver witness and proved optimality. |

### Exact finite mathematics and certificate-backed results

| repository | result |
|---|---|
| [erdos203](https://github.com/jaredwilder/erdos203) | Finite prime-fibre obstruction calculus for Erdős–Graham #203. **G29 proves the first common-period shell with raw fibre mass >1 is impossible for every phase assignment**, with exact bound `823/840 < 1`; G30 exhausts all 2,880 phases of the `{5,7,11,13}` core with maximum union density `353/720`. |
| [additive-combinatorics-campaigns](https://github.com/jaredwilder/additive-combinatorics-campaigns) | First 13-element C3-free set has **minimum span exactly 60**; all 13-sets of span <=63 classified as 6 sets in 4 orbits; eight-element C5-free minimum span **exactly 25**; a carry-free construction with exponent **log_7(3) > 1/2**; and a kernel-checked theorem backed by a **447,254-addition LRAT proof** shipped in full. |
| [combinatorial-records](https://github.com/jaredwilder/combinatorial-records) | Binary Sidon **f(7) >= 24**, 677 covering-number rows, exact finite-field classifications, Ramsey exhaustions, Lonely Runner theorem-bank material, C(13,6,3) witnesses/structure, automata and additive-encoding theorem banks. |
| [zero-sum-theorem-closures](https://github.com/jaredwilder/zero-sum-theorem-closures) | A deterministic derivation system saturating at **889 typed theorems** from 27 seeds over 7 generations, independently re-executed with **10,528,320 direct assignments and modelCalls: 0**. |
| [erdos-straus-progressions](https://github.com/jaredwilder/erdos-straus-progressions) | Two complete iff classifications for Erdős-Straus solutions whose denominators lie in arithmetic or geometric progression, with independent verifier runs. |
| [ck-gold-and-r3-envelope](https://github.com/jaredwilder/ck-gold-and-r3-envelope) | **380 machine-derived and verified r_3 bounds**, each carrying its witness, derivation family and superseded weaker bound, plus bounded C_k campaign evidence. |
| [kreisel-kurz-heptagon-extension](https://github.com/jaredwilder/kreisel-kurz-heptagon-extension) | Exact Diophantine reduction of the integral-octagon extension question over Q(sqrt(2002)): master quartic, four square-linkage equations, genus-zero conic base, exact field localization and millions of certified exact cells. |
| [erdos-proved-lemmas](https://github.com/jaredwilder/erdos-proved-lemmas) | A newly extracted bank of finished lemmas/reductions from open-problem campaigns, including independently re-checked results for Erdős 978, 126, 1107 and 893 and structural results for 396, 373, 602, 774, 1142 and 289. |

### Formal mathematics

| repository | scale |
|---|---|
| [erdos902](https://github.com/jaredwilder/erdos902) | Kernel-checked tournament mathematics for Schütte/Erdős #902: the classical sandwich `(n+2)2^(n-1)-1 <= f(n) <= n+3n^2 2^n`, exact small values, the finite window `48 <= f(4) <= 67`, exact order-49 Cayley eliminations, DRT(23) structure, QR23 symmetry, repair capacities, dominator cubes, private-cover barriers and factorization falsifiers. |
| [erdos-theorems](https://github.com/jaredwilder/erdos-theorems) | **79 Lean declarations across 20 files and 15 Erdős problems**, with clean axiom-footprint accounting. |
| [lean-forge-graph-theory](https://github.com/jaredwilder/lean-forge-graph-theory) | **218 standalone Lean theorem files**, all textually sorry-free, on C4-free/K4-free and related graph structure. |
| [erdos595-barrier-tower](https://github.com/jaredwilder/erdos595-barrier-tower) | **27 sorry-free Lean files** proving a sharp coverability barrier: every graph on at most continuum many vertices is countably triangle-free-coverable, while non-coverability begins at the successor of the continuum; additional cofinality/component consequences are formalized. |
| [lean-contributions](https://github.com/jaredwilder/lean-contributions) | A **1,473-line zero-sorry Steiner triple-system/Kirkman development** in Mathlib style, plus a first statement formalization/API for Erdős 1066, the ten-module HumuFinisher project and standalone formal files. |
| [erdos-lean-remainder](https://github.com/jaredwilder/erdos-lean-remainder) | Two finished kernel-clean proof packets, including the Erdős 503 orthogonal-join/isoceles-number development and an Erdős 289 reciprocal-sum bound, alongside the unfinished formalizer tail. |
| [erdos-close-campaigns](https://github.com/jaredwilder/erdos-close-campaigns) | **rothNumberNat 14 = 8 and rothNumberNat 15 = 8**, the first exact values of Mathlib's canonical `rothNumberNat`, plus a supermultiplicativity lemma absent from Mathlib and other sealed lemmas. |

---

## Papers and theorem programs

| repository | contents |
|---|---|
| [eg203-kummer-papers](https://github.com/jaredwilder/eg203-kummer-papers) | **Nineteen LaTeX sources and eighteen compiled PDFs** from the EG203/Kummer program, including the Sharp Dichotomy at `l log l ~ log Q` and the surrounding conductor/descent/Iwasawa/Kummer work. |
| [erdos203-obstruction-calculus](https://github.com/jaredwilder/erdos203-obstruction-calculus) | A **16-lemma finite subgroup-obstruction calculus** with exact local densities/moments, CRT synchronization, projective Kummer slopes, a density-zero schema and a conditional Kummer-distribution criterion. |
| [unpublished-math-papers](https://github.com/jaredwilder/unpublished-math-papers) | A large release-day subject archive recovered from the estate: Erdős/Kummer papers, Ramsey and finite-field classifications, exact structured-denominator theorems, theorem banks, formal packets, additive/fiber-coherence programs, integral-distance work, and dozens of focused problem extractions with authority classes preserved. |
| [erdos710-descent-and-1044](https://github.com/jaredwilder/erdos710-descent-and-1044) | An observed prime-descent law for Erdős 710 with five held-out primes, five sealed Hall-matching theorems, and a closed form for the Erdős 1044 extremal family. |

---

## Large corpora and release mines

These repositories are corpora, not single theorem claims. Their internal authority classes matter.

| repository | scale |
|---|---|
| [msl-ore-estate](https://github.com/jaredwilder/msl-ore-estate) | The public mine/provenance layer: **322,370 math-bearing structured-field occurrences**, **65,834 problem-scoped unique normalized mathematical texts**, **21,146 formula/identity/inequality occurrences**, **3,306 recovered Lean declarations**, **2,858 explicit closure obligations**, a **238-row promoted catalog**, and release-day theorem/witness/local-PROVED transports. These are estate counts, with authority attached object by object. |
| [erdos-campaign-archive](https://github.com/jaredwilder/erdos-campaign-archive) | **266 campaigns across 241 distinct Erdős problems**, 2,979 files and 215 Lean files, with successful, refuted and null routes preserved together. |
| [erdos-cable-corpus](https://github.com/jaredwilder/erdos-cable-corpus) | **914 Lean files across 152 problems** with 937 receipts. The completed receipt join distinguishes 211 clean-footprint compiled files, 267 compile failures, 23 files containing `sorry`, 266 textually sorry-free files without a clean-footprint verdict, and 147 unjoined files. |
| [erdos152](https://github.com/jaredwilder/erdos152) | **160 Lean statement formalizations of open Erdős problems** with a full 33-blade semantic defect audit attached. |
| [oracle-math-honest-inventory](https://github.com/jaredwilder/oracle-math-honest-inventory) | **725 public mathematical registry rows** with original authority classes preserved: 494 proposed, 163 finite-checked, 46 prose-proved, 22 source-asserted/unclassified. |
| [erdos-ore-findings](https://github.com/jaredwilder/erdos-ore-findings) | Results re-mined from a 30,438-object ore ledger, including a longest-composite-run computation, an infinite Pell family, binomial-prime-factor counterexamples, and a much larger Pass-3 extraction surface. |

---

## Open-problem data, verification and audit tooling

| repository | contents |
|---|---|
| [open-math-frontier](https://github.com/jaredwilder/open-math-frontier) | **9,926 source-attributed open mathematical targets**, **8,501 with callable mechanical verifiers**, plus release maps, claim ceilings and the historical-scale benchmark. |
| [frontier-math-target-data](https://github.com/jaredwilder/frontier-math-target-data) | Target registries, problem-shape data, a normalized technique catalog and the Erdős database; the private strategy layer is explicitly separated. |
| [lean-semantic-blades](https://github.com/jaredwilder/lean-semantic-blades) | A 33-blade deterministic semantic gate for autoformalized mathematics, published with its full run over the 160-file companion corpus. |
| [graham-alspach-certificates](https://github.com/jaredwilder/graham-alspach-certificates) | The certificate bank behind the sequenceability results, including **60,134 Z_29 certificate rows**, independent Go/Python checkers, deliberate corruptions and deterministic regeneration. |
| [erdos-computational-searches](https://github.com/jaredwilder/erdos-computational-searches) | A **4.646 x 10^11 Erdős 850 frontier** and an exact Erdős 273 parity-split reduction, with source, receipts and prior-art reconciliation. |
| [erdos835-lean-audit](https://github.com/jaredwilder/erdos835-lean-audit) | A focused axiom audit showing exactly which apparently-green Erdős 835 Lean claims depend on `native_decide` or upstream `sorryAx`, and which small claims are clean. |

---

## Integrity and provenance records

These repositories are intentionally about mistakes, retractions, route failures or claim ceilings.
They are not the front door to the positive mathematics, but they are part of the reason the
positive claims are auditable.

| repository | record |
|---|---|
| [erdos-findings-ledger](https://github.com/jaredwilder/erdos-findings-ledger) | **52 scope-pinned mathematical verdicts** with evidence paths and claim ceilings; includes caught provenance and computation failures as integrity controls. |
| [erdos-attack-logs](https://github.com/jaredwilder/erdos-attack-logs) | Attack logs, computations, route selection and prior-art verdicts across multiple Erdős campaigns. |
| [eg411-superseded-closure-claims](https://github.com/jaredwilder/eg411-superseded-closure-claims) | Superseded closure claims preserved under their original form with the later correction record. |
| [erdos411-retraction-record](https://github.com/jaredwilder/erdos411-retraction-record) | The research packets and retraction history preserved together rather than silently rewritten. |

The release doctrine is simple: **the theorem statement says what the theorem says; the evidence
class says how strongly it is established; the audit record says what failed. None of those should
be substituted for the others.**

---

## Reproduction status

A release-day verifier sweep re-ran the documented executable verifiers from committed source. The
14 verifiers in that sweep exited 0 after two undocumented invocation arguments were corrected in
the documentation.

The exhaustive exact-integer computation behind **d(2,8) > 30000** was also re-run and reproduced
its committed receipt in every field except wall clock: 136,801,313 cells, 6 solutions, 0
non-trivial extensions, correctness gate 6/6, and byte-identical exact-coordinate records.

The point of the reproduction layer is not to add rhetorical confidence. It is to make the
load-bearing claims attackable.

---

## Reading rule

Do not infer a theorem count from repository count, file count, `PROVED` workflow labels, or raw
corpus size. The release contains different kinds of mathematical objects: theorems, finite
computations, candidate bounds, exact classifications, formalizations, certificate rows, papers,
research routes, negative results and retractions.

Read each result at its stated scope. Where novelty matters, check the literature record. Where a
claim is computational, run the verifier. Where a Lean footprint matters, inspect the shipped
axiom receipt.

That is rigor. It does **not** require leading every result with an apology for a stronger claim
that was never made.

## License

Apache-2.0 throughout, matching Mathlib where relevant. Upstream data retains its own terms.