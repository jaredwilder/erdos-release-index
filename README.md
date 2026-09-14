# September 2026 mathematics release — index

A living index to Jared Wilder's September 2026 public mathematics release: theorems, exact finite results, formal proofs, computational certificates, papers, open-problem corpora, research archives, and the evidence needed to check them.

**Start with the mathematics.** Each entry says what the result is and how it was established. Corrections and failed approaches remain public, but they do not replace the description of unrelated successful work.

Author: Jared Wilder. Release began 2026-09-10. This index is append-only while the release continues to expand.

For the broader cross-subject map and historical-scale comparison, see [`open-math-frontier`](https://github.com/jaredwilder/open-math-frontier).

---

## Added 2026-09-14

These were finished earlier but had never been published.

| where | what |
|---|---|
| [ramsey-r55-circulant-41/lean-proof](https://github.com/jaredwilder/ramsey-r55-circulant-41/tree/main/lean-proof) | One Lean file with no imports that proves **R(3,3)=6, R(3,4)=9, R(3,5)=14 and R(4,4)=18** exactly, plus 25 ≤ R(4,5) ≤ 31 and 42 ≤ R(5,5) ≤ 62. The values are classical; what's new is getting all of them from the definition with one method. |
| [erdos411/defect-calculus](https://github.com/jaredwilder/erdos411/tree/main/defect-calculus) | A kernel-checked **if-and-only-if description of every solution of 3φ(N) = 2N + 2**: each solution is a smaller number with a known defect times one prime, and that prime is determined exactly. It also includes the 2-adic balance law and the prime ladder. r=2 stays open. |
| [erdos902-tournament-f4/structural-proof](https://github.com/jaredwilder/erdos902-tournament-f4/tree/main/structural-proof) | The f(4) ≥ 49 argument as **one Lean theorem**: no S4 tournament on 4–48 vertices, given one named input about the two surviving DRT(23,11,5) classes. It comes with 35 certificates ruling out the other classes. |
| [riemann-hypothesis](https://github.com/jaredwilder/riemann-hypothesis) | The working records for **epochs 20–32**, **297 Lean theorems** from that stretch (215 accepted by the kernel, 82 not, all with receipts) and the first-rung interval certification. The highlight is a Lean restatement of RH, about Mathlib's actual `riemannZeta`, as the squared zero offsets summing to zero in every window. RH stays open. |
| [erdos-campaign-archive/…/erdos513-close-packet](https://github.com/jaredwilder/erdos-campaign-archive/tree/main/campaigns/erdos513-close-packet-2026-08-11) | Erdős 513: a candidate exact value **B = 1/A\* ≈ 0.58507882**, reduced to two unproved statements, with tests and Lean targets. |

---

## Focused subject homes

Use these repositories to follow a mathematical program and its current
proof, computation and correction record. The global routing was reconciled
with live public repository trees on 2026-09-13: the eighteen homes identified
in the Round-13 estate audit and ten other existing homes now have direct links
here. These are existing public programs, not newly claimed theorem closures.

### Graph theory and Ramsey programs

| Subject | Preferred home | Scope and evidence boundary |
|---|---|---|
| #20: sunflower families | [erdos20-sunflower](https://github.com/jaredwilder/erdos20-sunflower) | Formal supporting lemmas, constructions and finite counterexamples; the parent conjecture is not closed. |
| #146: degenerate Turán | [erdos146-degenerate-turan](https://github.com/jaredwilder/erdos146-degenerate-turan) | Minimum-degree extraction, sparsity and reductions, with 51 named historical Lean checks; embedding and extremal-bound assembly remain. |
| #500: Turán (3,4) | [erdos500-turan34](https://github.com/jaredwilder/erdos500-turan34) | Density staircases, plateau structure, theorem bank and explicitly unproved targets. |
| #592: ordinal Ramsey | [erdos592-ordinal-ramsey](https://github.com/jaredwilder/erdos592-ordinal-ramsey) | Formal ordinal framework and conditional reductions; imported literature hypotheses remain explicit. |
| #593: obligatory hypergraphs | [erdos593-obligatory-hypergraphs](https://github.com/jaredwilder/erdos593-obligatory-hypergraphs) | Finite witnesses, formal reductions and conditional separations; literature assumptions are not promoted to unconditional proofs. |
| #1066: unit distance | [erdos1066-unit-distance](https://github.com/jaredwilder/erdos1066-unit-distance) | Geometric/coloring lemmas, formal statement layer and obstruction program; parent problem not closed. |
| Caccetta–Häggkvist triangles | [caccetta-haggkvist-triangles](https://github.com/jaredwilder/caccetta-haggkvist-triangles) | Minimum-counterexample structure, boundary identities and inequalities, with correction history; conjecture not claimed solved. |
| P6 Erdős–Hajnal | [p6-erdos-hajnal](https://github.com/jaredwilder/p6-erdos-hajnal) | Structural theorem program, finite checks, retired routes and named closure obligations; flagship remains unproved. |
| 41-vertex (5,5)-Ramsey circulant | [ramsey-r55-circulant-41](https://github.com/jaredwilder/ramsey-r55-circulant-41) | Exact witness structure, symmetries and extension obstructions; not a new global Ramsey lower bound. |
| #738: induced trees | [erdos738-triangle-free-induced-trees](https://github.com/jaredwilder/erdos738-triangle-free-induced-trees) | Theorem bank, triangle-free graph structure, finite checks and explicitly labeled search targets. |
| Erdős–Gyárfás power-of-two cycles | [erdos-gyarfas-power-of-two-cycles](https://github.com/jaredwilder/erdos-gyarfas-power-of-two-cycles) | Cycle-spectrum results, finite classifications and construction barriers; general degree-three target remains unresolved. |
| Fiber coherence and cycle rank | [fiber-coherence-cycle-rank](https://github.com/jaredwilder/fiber-coherence-cycle-rank) | Coherence criteria, cycle-rank obstruction classifications, graph/CSP theory and mapped proof dependencies. |
| #77: diagonal Ramsey exponential limit | [diagonal-ramsey-corridor](https://github.com/jaredwilder/diagonal-ramsey-corridor) | 23-card program: unconditional thin-corridor equivalence, exact structural lemmas, conditional limit criterion and construction barriers; limit existence not proved. |
| #74: bipartite defect | [erdos74-bipartite-defect](https://github.com/jaredwilder/erdos74-bipartite-defect) | Bounded finite-subgraph defect implies a finite coloring bound; formal finite-vertex guard and explicit infinite-set calibration. |

### Additive and multiplicative number theory

| Subject | Preferred home | Scope and evidence boundary |
|---|---|---|
| #142: progression-free sets | [erdos142-progression-free](https://github.com/jaredwilder/erdos142-progression-free) | Behrend embedding, greedy ternary structure, carry/rigidity analysis and barriers; source claims retain their stated ranges. |
| #1192: representation energy | [erdos1192-representation-energy](https://github.com/jaredwilder/erdos1192-representation-energy) | Corrected Cauchy–Schwarz inequalities and basis-density constraints, including the r·2^k cutoff; general construction unresolved. |
| Lonely Runner: 13 effective speeds | [lonely-runner-13](https://github.com/jaredwilder/lonely-runner-13) | Exact finite statements, structural normal forms and source packets; restricted results separated from the general conjecture. |
| #271: Stanley sequences | [erdos271-stanley-sequences](https://github.com/jaredwilder/erdos271-stanley-sequences) | Independent-sequence structure, scaling/shift theory, spectra and theorem banks with open boundaries. |
| #949: finite-sum avoidance | [erdos949-finite-sums](https://github.com/jaredwilder/erdos949-finite-sums) | Finite and countable results with a Lean core; the continuum-sized sum-free-subset target remains separate. |
| #850: radical coincidences | [erdos850-radical-coincidences](https://github.com/jaredwilder/erdos850-radical-coincidences) | Structural pruning, verified controls and the recorded finite search frontier; the infinite three-term problem is not closed. |
| #273: covering systems | [erdos273-covering-systems](https://github.com/jaredwilder/erdos273-covering-systems) | Exact parity-split reduction, finite search/SAT ladder, controls and corrections; no full permitted-modulus covering established. |
| #39: Sidon density | [erdos39-sidon-density](https://github.com/jaredwilder/erdos39-sidon-density) | Formal finite bounds and an infinite greedy construction, with executable controls; no near-square-root-density solution. |
| #890 / #1093: divisor-window bridge | [erdos890-1093-divisor-window](https://github.com/jaredwilder/erdos890-1093-divisor-window) | Exact divisor-window coordinates, deficiency/excess identities and source evidence; parent problems and priority questions remain separate. |
| #1061: aliquot squares | [erdos1061-aliquot-square](https://github.com/jaredwilder/erdos1061-aliquot-square) | Explicit generator, primitive-ray scaling and certificate provenance; exact recovered CSV transport remains a separately tracked item. |
| Rado-equation avoidance atlas | [rado-equation-avoidance-atlas](https://github.com/jaredwilder/rado-equation-avoidance-atlas) | Reader-facing relation-family framework and provenance; inspect the source-recovery map for numerical-table availability. |

### Finite classifications, codes and transport

| Subject | Preferred home | Scope and evidence boundary |
|---|---|---|
| Finite-field extremal sets | [finite-field-extremal-sets](https://github.com/jaredwilder/finite-field-extremal-sets) | Three exact F31/Z31/F73 classifications, complete maximizing sets, recovered original verifiers and passing Python/C/C++ checks. |
| Constant-GC reverse-complement codes | [constant-gc-reverse-complement-codes](https://github.com/jaredwilder/constant-gc-reverse-complement-codes) | Exact finite code/witness lane and graph definition, with independent verification and the length-eight frontier explicitly separated. |
| Strongly regular graph transport | [strongly-regular-graph-transport-atlas](https://github.com/jaredwilder/strongly-regular-graph-transport-atlas) | 119-row source atlas and transport ledger, exact source hashes, typed relations and one-sided limits. |

### Compact theorem and correction routes

- [#251: finite dyadic-prefix denominators](https://github.com/jaredwilder/erdos-findings-ledger/blob/main/theorems/ERDOS-251-DYADIC-PREFIX-DENOMINATOR.md) — keep the origin-0 and origin-1 conventions separate; this does not prove irrationality of the infinite series.
- [#1212: fixed-row coprime-run coordinate](https://github.com/jaredwilder/erdos-findings-ledger/blob/main/theorems/ERDOS-1212-ROW-RUN-COORDINATE.md) — the campaign's dual run function is explicitly defined; this is separate from the isolated-vertex family and the global path problem.
- [#289: all-prime reciprocal-sum obstruction](https://github.com/jaredwilder/erdos-proved-lemmas/blob/master/erdos289-padic-reciprocal-obstructions.md) — written universal argument, with narrower formal/finite components identified separately.
- [#477: all integer quadratics](https://github.com/jaredwilder/erdos-proved-lemmas/blob/master/erdos477-all-quadratics.md) — complete written proof that no degree-2 image uniquely tiles Z; the square-case Lean layer is separate.
- [#486: quantitative summable-forbidden-mass theorem](https://github.com/jaredwilder/erdos-proved-lemmas/blob/master/erdos486-summable-forbidden-mass.md) — density, tail-error bound and positive-density corollary under the explicit activation rule n<m.
- [#949: complement cardinality](https://github.com/jaredwilder/erdos949-finite-sums/blob/main/human/complement-cardinality.md) — written doubling-injection proof; not a continuum-sized finite-sums construction, and no kernel-check claim for this child.
- [Corrections and quarantined claims](https://github.com/jaredwilder/msl-ore-estate/blob/main/MATH-QUARANTINE-AND-CORRECTIONS.md) — proposition-level corrections; historical route status is not proof authority.

## Results first

### Published-number and finite-range advances

| repository | result |
|---|---|
| [integral-point-sets](https://github.com/jaredwilder/integral-point-sets) | **`d(2,8) > 30000`** for integral octagons in general position, improving the hereditary lower bound 22270. Also includes **394 impossibility certificates** and exact values `d(2,4)=8`, `d(2,5)=73`, `d(2,6)=174`. |
| [erdos902-tournament-f4](https://github.com/jaredwilder/erdos902-tournament-f4) | A computational **candidate `f(4) >= 49`** against the published lower bound 48. The finite repair-capacity calculation reproduces exactly; the remaining dependency is completeness of the cited McKay–Spence tournament catalogue. The repository also contains roughly 150 sorry-free Lean theorems on the surrounding structure. |
| [graham-alspach-sequenceability](https://github.com/jaredwilder/graham-alspach-sequenceability) | Graham–Alspach sequenceability verified for subset sizes **21–28 in `Z_29` and 21–30 in `Z_31`**, extending beyond the published general range 20. |
| [graham-alspach-extended](https://github.com/jaredwilder/graham-alspach-extended) | Further verified ranges for **`Z_37`, `Z_41`, `Z_43`, and `Z_61`**, covering **22,082,109 subsets** with independent Go/Python verification. |
| [graham-alspach-z53-z71](https://github.com/jaredwilder/graham-alspach-z53-z71) | **104 sequenceability rows at size 21 or above**, against a published general result covering size at most 20. **20,001,879,972 orbit representatives covering 838,583,192,826 subsets, zero non-sequenceable.** `Z_53` (sizes 41-52) and `Z_71` (62-70) had never been attempted; `Z_37` and `Z_41` are now complete from 21 to `p-1`. Every row's orbit sizes sum to exactly `C(p-1,c)`. The compute wall is stated exactly, and a hand-checkable `Z_53` witness is included. |
| [erdos1084-harborth](https://github.com/jaredwilder/erdos1084-harborth) | A correction to formal-conjecture metadata: a variant marked research-open follows from Harborth 1974, together with Lean formalization work on the corresponding bound. |
| [erdos376-successor-frontier](https://github.com/jaredwilder/erdos376-successor-frontier) | An explicit **1,006-digit integer above `10^1000`** satisfying simultaneous base-3/base-5/base-7 digit restrictions, independently reproduced with matching SHA-256. |
| [ck-sequences](https://github.com/jaredwilder/ck-sequences) | **59 exact optimal values of `C_k(N)`** across `k=3,4,5`, each with solver proof of optimality and a directly checked witness. |
| [binary-sidon-f7](https://github.com/jaredwilder/binary-sidon-f7) | **`24 <= f(7) <= 30`** for binary Sidon sets in `{0,1}^7`, the first unpublished term of A309370. The upper bound is new: splitting by a coordinate makes each half Sidon in `{0,1}^6`, giving `f(d) <= 2 f(d-1)` and halving the `[24, 60]` interval previously on file. The 24-element witness is re-verified from the definition. At 25 the result is an honest **unresolved**, with the encoding calibrated on both sides at `d = 4, 5, 6` and the compute wall measured. |
| [covering-13-6-3](https://github.com/jaredwilder/covering-13-6-3) | `C(13,6,3)` stays open at 20 or 21, but the lower-bound argument is strengthened. **`C(12,5,2) = 9` proved exhaustively** (98,147,285 nodes) against a Schönheim bound of 8, raising the point-degree floor in any 20-block cover from 8 to 9 and **collapsing the slack from 16 to 3**. The bound then re-derives itself and the degree multiset is pinned to three possibilities. The bottleneck is measured, not guessed: the relaxation sits at 14.3 against a target of 20. |

### Exact finite mathematics and certificate-backed results

| repository | result |
|---|---|
| [erdos203](https://github.com/jaredwilder/erdos203) | Finite prime-fibre obstruction calculus for Erdős–Graham #203. **G29 proves the first common-period fibre family with raw density >1 cannot cover for any phase assignment**, with exact bound `823/840 < 1`; G30 checks all 2,880 phases of the `{5,7,11,13}` core with maximum union density `353/720`. |
| [additive-combinatorics-campaigns](https://github.com/jaredwilder/additive-combinatorics-campaigns) | First 13-element C3-free set has **minimum span exactly 60**; all 13-sets of span at most 63 are classified as 6 sets in 4 orbits; eight-element C5-free minimum span is **exactly 25**; a carry-free construction has exponent **`log_7(3) > 1/2`**; and a Lean theorem is backed by a shipped **447,254-addition LRAT proof**. |
| [combinatorial-records](https://github.com/jaredwilder/combinatorial-records) | Binary Sidon **`f(7) >= 24`**, 677 covering-number rows, exact finite-field classifications, circulant Ramsey-family exhaustions, Lonely Runner theorem material, `C(13,6,3)` witnesses/structure, automata, and additive-encoding theorems. |
| [zero-sum-theorem-closures](https://github.com/jaredwilder/zero-sum-theorem-closures) | A finite derivation system starting from **27 seeds** reaches a fixed point after 7 generations with **889 typed theorems**; independent replay checks **10,528,320 direct assignments**. |
| [erdos-straus-progressions](https://github.com/jaredwilder/erdos-straus-progressions) | Two complete iff classifications for Erdős–Straus solutions whose denominators lie in arithmetic or geometric progression, with independent computational checks. |
| [ck-gold-and-r3-envelope](https://github.com/jaredwilder/ck-gold-and-r3-envelope) | **380 verified finite `r_3` bounds** derived from explicit rules and witnesses, plus **36 finite `C_k` searches** with stated domains and witnesses. |
| [kreisel-kurz-heptagon-extension](https://github.com/jaredwilder/kreisel-kurz-heptagon-extension) | Exact Diophantine reduction of the integral-octagon extension question over `Q(sqrt(2002))`: master quartic, four square-linkage equations, genus-zero conic base, exact field localization, and millions of certified exact cells. |
| [erdos-proved-lemmas](https://github.com/jaredwilder/erdos-proved-lemmas) | Finished lemmas and reductions extracted from larger Erdős projects, including independently rechecked results for 978, 126, 1107, and 893 and structural results for 396, 373, 602, 774, 1142, and 289. |

### Formal mathematics

| repository | contents |
|---|---|
| [erdos902](https://github.com/jaredwilder/erdos902) | Kernel-checked tournament mathematics for Schütte/Erdős #902: the classical sandwich, exact small values, `48 <= f(4) <= 67`, exact order-49 Cayley eliminations, DRT(23) structure, QR23 symmetry, repair capacities, dominator cubes, private-cover barriers, and factorization falsifiers. |
| [erdos-theorems](https://github.com/jaredwilder/erdos-theorems) | **79 Lean declarations across 20 files and 15 Erdős problems**, all with clean axiom-footprint accounting. |
| [lean-forge-graph-theory](https://github.com/jaredwilder/lean-forge-graph-theory) | **218 standalone sorry-free Lean theorem files** on C4-free/K4-free and related graph structure, with verification records for 217. |
| [erdos595-barrier-tower](https://github.com/jaredwilder/erdos595-barrier-tower) | **27 sorry-free Lean files** proving a sharp coverability barrier: every graph on at most continuum many vertices is countably triangle-free-coverable, while non-coverability begins at the successor of the continuum; additional cofinality/component consequences are formalized. |
| [lean-contributions](https://github.com/jaredwilder/lean-contributions) | A **1,473-line zero-sorry Steiner triple-system/Kirkman development** in Mathlib style, plus a statement formalization/API for Erdős 1066, the ten-module HumuFinisher project, and standalone formal files. |
| [erdos-lean-remainder](https://github.com/jaredwilder/erdos-lean-remainder) | Two completed kernel-clean proof developments: Erdős 503 orthogonal joins/exact isosceles numbers and an Erdős 289 reciprocal-sum finite bound, alongside unfinished formalization records and SAT instances. |
| [erdos-close-campaigns](https://github.com/jaredwilder/erdos-close-campaigns) | **`rothNumberNat 14 = 8` and `rothNumberNat 15 = 8`**, the first exact values of Mathlib's canonical `rothNumberNat`, plus a supermultiplicativity lemma absent from Mathlib, a formalized classical lower bound, and additional structural lemmas. |

---

## Papers and theorem programs

| repository | contents |
|---|---|
| [eg203-kummer-papers](https://github.com/jaredwilder/eg203-kummer-papers) | **Nineteen LaTeX sources and eighteen compiled PDFs** from the EG203/Kummer program, including subgroup-obstruction mathematics, conductor/descent/Iwasawa structure, the sharp dichotomy at `l log l ~ log Q`, conditional distribution criteria, and a separate analysis of insufficient approaches. |
| [erdos203-obstruction-calculus](https://github.com/jaredwilder/erdos203-obstruction-calculus) | A **16-lemma finite subgroup-obstruction calculus** with exact local densities/moments, CRT synchronization, projective Kummer slopes, a density-zero framework, and a conditional Kummer-distribution criterion. |
| [unpublished-math-papers](https://github.com/jaredwilder/unpublished-math-papers) | A large public subject archive: Erdős/Kummer papers, Ramsey and finite-field classifications, exact structured-denominator theorems, theorem banks, formal packets, additive/fiber-coherence programs, integral-distance work, and dozens of focused problem extractions. |
| [erdos710-descent-and-1044](https://github.com/jaredwilder/erdos710-descent-and-1044) | An observed prime-descent law for Erdős 710 tested through `n<=114` with five held-out primes, five Lean Hall-matching theorems, and a closed form for the Erdős 1044 extremal family. |
| [eg203-eg411-corpus](https://github.com/jaredwilder/eg203-eg411-corpus) | A large working corpus containing 125 EG203 Lean files, large finite searches, arithmetic/formal results, additional obstruction theory, and 19 compiled papers, with historical corrections separated from current result descriptions. |

---

## Large research archives and formalization corpora

These repositories preserve large bodies of material with mixed internal evidence levels. Their counts describe archives, not synthetic theorem totals.

| repository | scale |
|---|---|
| [msl-ore-estate](https://github.com/jaredwilder/msl-ore-estate) | **322,370 math-bearing recovered fields**, **65,834 problem-scoped distinct normalized mathematical texts**, **21,146 formula/identity/inequality occurrences**, **3,306 Lean declarations**, **2,858 proof/closure obligations**, and a **238-entry curated mathematical catalog**. Selected results are extracted into subject repositories. |
| [erdos-campaign-archive](https://github.com/jaredwilder/erdos-campaign-archive) | **266 automated proof-search runs across 241 distinct Erdős problems**, 2,979 files and 215 Lean files, preserving proofs, bounds, refutations, failed approaches, prior-art findings, and null results. |
| [erdos-cable-corpus](https://github.com/jaredwilder/erdos-cable-corpus) | **914 Lean files across 152 problems** with 937 receipts: 211 clean-footprint compiled files, 266 textually sorry-free files without a clean-footprint verdict, 267 compile failures, 23 files containing `sorry`, and 147 files with no joined receipt. |
| [erdos152](https://github.com/jaredwilder/erdos152) | **160 Lean formalizations of Erdős problem statements**: one proved main statement, 159 main statements left as `sorry`, and a semantic audit detecting all 58 independently known-bad examples. |
| [oracle-math-honest-inventory](https://github.com/jaredwilder/oracle-math-honest-inventory) | **725 public mathematical records**: 494 proposed, 163 finite-checked, 46 proved in prose, and 22 source-asserted/unclassified, with evidence level attached to each entry. |
| [erdos-ore-findings](https://github.com/jaredwilder/erdos-ore-findings) | Mathematics recovered from a 30,438-object historical archive, including independently recomputed composite-run, Pell-family, and binomial-prime-factor results; a larger extraction found 97 mathematical families missing from an earlier theorem index. |

---

## Open-problem data, verification, and formalization audits

| repository | contents |
|---|---|
| [open-math-frontier](https://github.com/jaredwilder/open-math-frontier) | **9,926 source-attributed open mathematical targets**, **8,501 with executable checkers**, plus release maps, formalization status, published-bound metadata, and the historical-scale comparison. |
| [frontier-math-target-data](https://github.com/jaredwilder/frontier-math-target-data) | Open-problem registries, structural problem classifications, a normalized catalog of published techniques, and the Erdős database. |
| [lean-semantic-blades](https://github.com/jaredwilder/lean-semantic-blades) | **33 deterministic semantic checks** for Lean formalizations, run over the 160-file companion corpus; the suite detects all 58 examples independently known to be semantically defective. |
| [graham-alspach-certificates](https://github.com/jaredwilder/graham-alspach-certificates) | Certificate bank behind the sequenceability results, including **60,134 `Z_29` certificate rows**, independent Go/Python checkers, deliberately corrupted controls, and deterministic regeneration. |
| [erdos-computational-searches](https://github.com/jaredwilder/erdos-computational-searches) | A **`4.646 × 10^11` Erdős 850 search frontier** and an exact Erdős 273 parity-split reduction, with source, receipts, and prior-art reconciliation. |
| [erdos835-lean-audit](https://github.com/jaredwilder/erdos835-lean-audit) | A formal dependency audit showing that the proposed Erdős 835 lower-bound proof inherits upstream `sorryAx`, while identifying the smaller claims that use `native_decide` and those with clean footprints. |
| [erdos-counterexample-queue](https://github.com/jaredwilder/erdos-counterexample-queue) | **504 counterexamples that appear in campaign transcripts and reached no findings document**, worked and re-verified. Four new results, including the refutation of `r(N) <= tau(N)` (first failure `N=123`) and a Ramsey-type threshold that is **7, not the filed 33**; twelve filed receipts that fail re-derivation; and one case of a **true lemma retired on a counterexample that cannot exist**. Standalone verifier, 27 checks. |
| [erdos-archive-seam](https://github.com/jaredwilder/erdos-archive-seam) | Mathematics recovered from 297 archives, two tarballs and a search store outside the searchable tree. **Settles a contradiction between two of this estate's own audits: `F(42) = 34`, not 30**, so the flagship result is false. Also a complete negative result on Sidon digit alphabets, exact Erdős–Hajnal and Caccetta–Häggkvist classifications, and a measured account of what 1,360 Lean files contain (348 verified of 1,360; four distinct ways an axiom footprint and an exit code disagree). |
| [erdos930-consecutive-block-square](https://github.com/jaredwilder/erdos930-consecutive-block-square) | **Two disjoint blocks of four consecutive integers whose product is a perfect square**: `33·34·35·36 · 1680·1681·1682·1683 = 3361826160²`, found inside a search box an internal source declared empty, and unique for `a ≤ 200, b ≤ 30000`. Plus six refuted research dossiers, two of which claimed to close open problems. Standalone verifier, 38 checks. |
| [mathematics-under-the-wrong-filename](https://github.com/jaredwilder/mathematics-under-the-wrong-filename) | **93 archives carrying project, product or opaque names hold real mathematics** — the measured size of a filename-based blind spot. Includes an eight-round Erdős 595 program (four rank-three branch kernels and no fifth, no finite Helly bound, NP-completeness at domain size three) whose filenames contain no mathematical word. **Paley(17) recomputed: K4-free with triangle cover number exactly 2**, with the explicit 36/32 partition. |
| [pascal-relation-extremal-atlas](https://github.com/jaredwilder/pascal-relation-extremal-atlas) | Mathematics from primary stores that reached neither ledger summary. **A five-species gap law** reducing C3 membership from a 24-permutation search to five linear tests (0 mismatches in 12,650 quadruples); **the published base rule `2^r+1` is exponentially far from least** and the true value is non-monotone in `r`, settled through `r = 9`; and a **density bound of 1/5** available from two halves that sat in different directories. |
| [formalizer-kernel-audit](https://github.com/jaredwilder/formalizer-kernel-audit) | **213 kernel-clean theorems** from 939 formalizer receipts under a six-part gate, of which **73 are unique Erdős 595 statements** — the coverability-iff-colouring reduction, a continuum blindness result, and a compactness → finite obstruction → countable core arc. Also the specimen: a file with **exit 0 and a clean axiom footprint whose conclusion is `RiemannHyp`**, where `RiemannHyp` is a bound `Prop` variable and the proof is `not_lt.mp`. |
| [nested-archive-mathematics](https://github.com/jaredwilder/nested-archive-mathematics) | **253 archives nested inside other archives, opened for the first time; 134 held mathematics.** Recomputed here: four points with all six pairwise distances integral, no three collinear and not concyclic; the regular `n`-gon has exactly `floor(n/2)` distinct distances; `n!+1` is powerful exactly at `n = 4, 5, 7`; and `n(n-1)(n-2)` divides `C(2n,n)` at `n = 2480` and `3478`. Also a three-way error on Mian-Chowla `a(13)`: the estate held 155 and 134, an audit chose 134, and the value is **128**. |
| [session-transcript-mathematics](https://github.com/jaredwilder/session-transcript-mathematics) | 600 raw session logs (741 MB) mined for mathematics stated once and never filed. **A uniform periodicity law**: the greedy sum-avoiding sequence from seed `{k}` is exactly `{n >= k : n mod (3k-1) in [k, 2k-1]}`, verified for `k = 1..10` over 300 terms with zero mismatches and a two-line proof. Three refutations recomputed, including a named extremizer that is not a least preimage and an exhaustive enumeration whose own maximum is 6, not the filed 12. |
| [lean-corpus-audit](https://github.com/jaredwilder/lean-corpus-audit) | **Four thousand Lean files, six compile receipts.** Audited on receipts rather than on the absence of the word `sorry`. Zero of 1,172 research-open statements are proved; exactly one file closes its statement and it is an 11-vertex refutation, recomputed here. Also 59 self-declared axioms, 35 nameplate theorems whose statements are `(7 : Nat) <= 8` and the like, and a corruption that overwrote the tactic in 77 files. |
| [divergent-mirror-mathematics](https://github.com/jaredwilder/divergent-mirror-mathematics) | A 32,081-file tree the search index excludes by construction. **A `Z_73` sequenceability witness found by simulated annealing in 33 minutes over 1.8 billion steps is an instance of a one-line theorem** (`g^1..g^(p-1)` sequences `Z_p` minus zero), verified for all 61 odd primes below 300 — so every size-`(p-1)` row across nine certificates is redundant, and both the generator and the main tree's own note on that closure missed it. Also Graham certificate coverage re-verified against exact binomials, and an exact DNA-code value with its graph rebuilt. |
| [relation-family-atlas](https://github.com/jaredwilder/relation-family-atlas) | **One symbol names two different sequences**, found independently by two sweeps: `C_k` read over any ordering versus sorted order. They agree to `N=5` and diverge at `N=6`. Both correct; the OEIS and novelty checks ran against one of them. Plus a Rado-equation atlas of 839 values with ten absent from OEIS, `R(5,5) >= 42` by an explicit ladder, and a 12-sigma anomaly that was the asymptotic's error, not the arithmetic's. The covering arm improved nothing, and its own receipts show why: 40 cross-references against 7,419 open entries. |

---

## Corrections, retractions, and research history

These repositories are intentionally about mistakes, dead ends, or historical claim changes. They support the positive mathematics without becoming its headline.

| repository | record |
|---|---|
| [erdos-findings-ledger](https://github.com/jaredwilder/erdos-findings-ledger) | **52 mathematical result records** linking statements to evidence, verification methods, and later corrections. |
| [erdos-attack-logs](https://github.com/jaredwilder/erdos-attack-logs) | Research logs, computations, refutations, and prior-art findings across multiple Erdős problems. |
| [eg411-superseded-closure-claims](https://github.com/jaredwilder/eg411-superseded-closure-claims) | Superseded closure claims preserved in their original form with the later correction record. |
| [erdos411-retraction-record](https://github.com/jaredwilder/erdos411-retraction-record) | Historical research packets and their associated retraction record. |

The rule throughout the release is simple: **the mathematical statement says what was established; the evidence tells you how it is supported; the correction record tells you what changed.**

---

## Reproduction status

A release-day sweep reran 14 documented executable verifiers from committed source; all 14 completed successfully after two missing command-line arguments were corrected in the documentation.

The exhaustive exact-integer computation behind **`d(2,8) > 30000`** was also rerun and reproduced its committed receipt in every field except wall-clock time: **136,801,313 cells, 6 solutions, 0 non-trivial extensions, all six correctness checks passed, and exact-coordinate records matched byte for byte**.

The point of this material is practical: important claims should be independently checkable from what is public.

---

## Reading rule

Do not infer a theorem count from repository count, file count, historical workflow labels, or raw archive size. The release contains different mathematical objects: theorems, exact finite computations, candidate bounds, classifications, formalizations, certificate rows, papers, research routes, counterexamples, and retractions.

Read the statement first. Then inspect the proof, certificate, computation, or formal file appropriate to that statement. Historical novelty is a separate literature question.

## License

Apache-2.0 throughout where repository-authored, with upstream material retaining its own terms.