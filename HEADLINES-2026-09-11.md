# Mathematics release — headline board — 2026-09-11

This is the **human-first** view of the release. It deliberately ignores raw file counts and asks one question: **what mathematics is most worth reading?**

Statuses are intentionally different. A full answer to a frozen statement, a strong theorem inside an open problem, an exact finite classification, a formalization, and a candidate-new result are not the same thing.

## Tier 1 — read these first

### 1. Integral octagons: `d(2,8) > 30000`

Public home: `jaredwilder/integral-point-sets`

The exhaustive exact-integer search pushes the hereditary lower bound for integral octagons in general position from 22,270 past 30,000. The public release includes the search/certificate estate and an independent release-day rerun of the documented computation.

**Status:** concrete published-number advance / exact computation.

### 2. Erdős #902: tournament program and `f(4)` frontier

Public homes: `jaredwilder/erdos902`, `jaredwilder/erdos902-tournament-f4`

The program contains the classical sandwich, exact small cases, large formal structural machinery, order-49 Cayley eliminations, DRT(23)/QR23 structure, capacity theorems and falsifiers. A finite computation yields a **candidate `f(4)>=49`** against the published lower bound 48, with the remaining authority dependency explicitly tied to completeness of the external tournament catalogue.

**Status:** major formal/computational program; candidate finite improvement with an external-catalogue dependency.

### 3. Erdős #949: sharp finite constant `5` + infinite IP structure

Public home: `jaredwilder/unpublished-math-papers/erdos949-sumfree-ip/`

For every sum-free `S⊆R`, some `q∈{1,...,5}` has both `q` and `2q` outside `S`, and 5 is sharp. The estate also proves a countably infinite finite-sums complement theorem and simultaneous avoidance under finitely many additive homomorphisms into an additive semigroup.

**Status:** paper-shaped exact theorem cluster. Targeted searches did not find the exact problem-specific formulations, but folklore/specialist-priority risk remains; no global novelty certificate is claimed.

### 4. `C(13,6,3)`: one-block exact-close frontier

Public home: `jaredwilder/combinatorial-records/covering-designs/C13-6-3/`

Two independently validated 21-block covers are public. A hypothetical 20-cover is forced into only three point-degree multisets, with sharp pair multiplicity laws, multiplicity-3 geometry, local triple-excess identities, at least 42 singleton triples around every degree-9 point, and global triple excess 114.

The frontier remains

`20 <= C(13,6,3) <= 21`.

A replayable proof that 20 is impossible would close the value at 21.

**Status:** exceptionally compressed exact-close program; **not closed yet**.

### 5. Erdős–Straus structured denominators: complete AP and GP classifications

Public home: `jaredwilder/erdos-straus-progressions`

The release contains iff parameterizations for Erdős–Straus solutions whose three denominators lie in arithmetic progression or geometric progression, with independent computational validation.

**Status:** complete structured-subfamily classifications.

### 6. Graham–Alspach sequenceability beyond the published general range

Public homes: `jaredwilder/graham-alspach-sequenceability`, `jaredwilder/graham-alspach-extended`

Verified sequenceability ranges extend beyond the general published range for `Z_29`, `Z_31` and additional prime cyclic groups, backed by a large certificate bank and independent implementations.

**Status:** exact finite-range advance / certificate-backed computation.

## Tier 2 — strong standalone mathematics

### Erdős #247 — exact-hypothesis irrationality milestone

If `a_1<a_2<...` and `limsup a_n/n=∞`, then for every integer base `b>=2`,

`sum b^(-a_n)`

is irrational. More generally, rationality of a `0/1` support expansion is equivalent to eventual periodicity of its support indicator.

**Status:** exact theorem at the canonical sparsity hypothesis; parent problem asks for transcendence. Targeted search found no exact tracker match; folklore risk remains high.

### Erdős #486 — summable forbidden mass gives ordinary density

For forbidden residue sets `X_n`, under the frozen activation semantics,

`sum |X_n|/n < infinity`

implies existence of ordinary natural density. The finite periodic truncations satisfy the explicit error estimate

`0 <= delta_N-d(B) <= sum_{n>N}|X_n|/n`,

and

`d(B) >= max(0,1-sum |X_n|/n)`.

**Status:** general theorem / strong parameter slice; specialist literature priority unresolved.

### Erdős #52 — a multiplicative box is almost maximally additive

For

`A_N={2^i 3^j : 0<=i,j<N}`,

valuation decoding gives

`|A_N+A_N| >= C(N,2)^2 = (1/4+o(1))|A_N|^2`.

The natural rank-two multiplicative box is therefore not a viable small-sum/small-product counterexample vehicle.

**Status:** exact structural theorem; conservative folklore-risk treatment.

### Rank-three graph kernels

Every finite simple 2-connected graph of cyclomatic number three reduces, after suppression of maximal degree-2 paths, to one of four loopless 2-connected multigraph kernels: `Q4`, `T221`, `D22`, or `K4`. The same packet develops exact K4-free fibre-realization and complexity consequences.

**Status:** standalone structural theorem packet; novelty search not completed for every component.

### Finite avoidance classifications in `F_31` and `F_73`

The release includes exact extrema and complete/extensive extremizer data for simultaneous additive/multiplicative avoidance constraints, with independent exact verifiers.

**Status:** finite exact classifications; novelty wording restricted to targeted-search results where applicable.

## Tier 3 — useful exact barriers and reductions

- **#655:** the literal frozen statement is false: regular `n`-gons satisfy its circle condition and have exactly `floor(n/2)` distances. Complete negative answer to that formulation; already-public/known mathematics, not claimed novel.
- **#145:** squarefree-gap moments exist for every fixed `0<=alpha<=1`; `alpha=1` has limit 1. Historically subsumed by stronger results; retained as a clean proof slice.
- **#727:** for every prime `p>=7`, `n=2p-2` gives `((n+2)!)^2 ∤ (2n)!`; infinite exact obstruction family.
- **#1212:** every `(2,3^k)`, `k>=2`, is isolated in the admissible subgraph; infinitely many exact dead ends.
- **#859:** for every fixed `t`, the distinct-divisor representation predicate is periodic modulo `lcm(1,...,t)`, hence `d_t` exists and is rational.
- **#406:** ternary `{0,1}` powers of two obey an exact 3-adic residue sieve with only `O(N^(log_3 2))` surviving exponents up to `N`.
- **#400:** elementary universal `O_k(log n)` control paired with explicit factorial-subsequence growth of order `log n/log log n`.
- **#51:** every totient preimage obeys `n <= a 2^R(a)` where `R(a)=max{r:r!<=a}`.
- **#243:** eventual divisibility plus exploding successive ratios forces an irrational reciprocal sum.

## Formal-mathematics headline

The public formal estate now includes, among other things:

- the `erdos902` tournament development;
- 218 standalone graph-theory Lean theorem files in `lean-forge-graph-theory`;
- the 27-file formal barrier tower in `erdos595-barrier-tower`;
- 79 declarations across 20 files / 15 problems in `erdos-theorems` at the current indexed snapshot;
- a 1,473-line zero-sorry Steiner/Kirkman development in `lean-contributions`;
- exact Roth-number values `rothNumberNat 14 = 8` and `rothNumberNat 15 = 8` in `erdos-close-campaigns`.

Formal scope is reported per artifact: a finite `decide` receipt is never silently upgraded into a universal theorem.

## What is *not* a headline

Raw `PROVED` workflow labels, theorem-count inflation, finite computations presented as asymptotic proofs, malformed generated Lean, and retracted routes are archive/provenance material rather than headline mathematics.

A useful example is Erdős #740: a recovered route tried to use `K_m` by asserting that every subgraph of a complete graph is complete. Under standard subgraph semantics that premise is false. It is therefore **not** promoted here as a close.

## Release status

This board is a snapshot, not a saturation claim. Large unreleased or incompletely reconciled surfaces remain, including contradiction histories, ORE-v1 payload bytes, semantic-review trees, formalizer obligations, historical proof archives and long-tail theorem packets.
