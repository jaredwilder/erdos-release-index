# Publication audit — 2026-09-14

**Author:** Jared Wilder

This is a live publication-state audit of the September 2026 mathematics estate. Its purpose is narrow: distinguish mathematics that is already public, mathematics that needed routing/repair, and source artifacts that are still genuinely unavailable on the public tree.

It is **not** a theorem-authority upgrade. A public registry row is not automatically a theorem; a formal-looking source is not automatically kernel authority; a finite computation does not acquire a broader scope by being published.

## Published / repaired in this audit

### Global release routing

The main [`erdos-release-index`](https://github.com/jaredwilder/erdos-release-index) now routes the focused subject homes that had been easy to miss, including the recovered PrimeGap and sums-of-three-cubes programs.

The `C_k` headline was also corrected from the original 59-row release to the current **84 exact OPTIMAL values** published by [`ck-sequences`](https://github.com/jaredwilder/ck-sequences): 26 `C3`, 34 `C4`, and 24 `C5` values under the current repaired definition.

### Prime-gap admissibility

[`prime-gap-admissibility`](https://github.com/jaredwilder/prime-gap-admissibility) is public with the recovered historical Lean source and a pinned clean rebuild. The recovered project contains eleven source modules. This is a finite residue-admissibility formal program; it is **not** an asymptotic prime-gap theorem, and the universal first-cover permutation/bijection statement remains open.

### Sums of three cubes, k=114

[`sums-three-cubes-114`](https://github.com/jaredwilder/sums-three-cubes-114) is public with the recovered `S3C_Oracle_114.lean` source. The public formal core includes the mod-9/mod-7 ingredients and the exact mod-7 one-zero-coordinate theorem. The equation `a^3+b^3+c^3=114` remains open. Historical PARI scripts/raw search outputs have not been recovered.

### Ramsey construction-class eliminations

A direct routing page now exists at [`RAMSEY-CONSTRUCTION-CLASS-ELIMINATIONS.md`](RAMSEY-CONSTRUCTION-CLASS-ELIMINATIONS.md).

It points to two already-public exact negative programs:

1. [`combinatorial-records/ramsey/conference-switching-book-elimination.md`](https://github.com/jaredwilder/combinatorial-records/blob/main/ramsey/conference-switching-book-elimination.md): for every symmetric conference matrix of order `N=4m+2`, no diagonal `±1` switching simultaneously avoids `B_m` while the complement avoids `B_(m+1)`. The `N=398`, `B_99/B_100` case is a corollary. This eliminates a construction class, not arbitrary graphs.
2. [`combinatorial-records/findings/circulant-ramsey-family-elimination.md`](https://github.com/jaredwilder/combinatorial-records/blob/main/findings/circulant-ramsey-family-elimination.md): complete circulant-family exhaustions at `R(3,10), n=40` and `R(4,6), n=36`, covering 1,048,575 and 262,143 connection sets respectively, with zero survivors. These are family eliminations, not new unrestricted Ramsey-number bounds.

### RH finite-prefix / finite-spectrum reconstruction boundary

Round 23 contained a coherent theorem package that was present in the canonical forensic estate but not found on the live RH tree under its exact statements. It is now public at:

[`riemann-hypothesis/method-obstructions/finite-prefix-reconstruction-boundary-2026-09-14.md`](https://github.com/jaredwilder/riemann-hypothesis/blob/main/method-obstructions/finite-prefix-reconstruction-boundary-2026-09-14.md)

The exact scope is:

- the Bernoulli / Hausdorff / coefficient cross-representation identities;
- the fact that the two-dimensional `H_{n,q}` lattice contains no independent numerical information beyond the boundary row `H_{n,0}`;
- **finite-spectrum reconstruction:** for known spectrum size `m`, `H_{0,0},...,H_{m-1,0}` together with `a_0` determine all coefficients of `G` and hence every Toeplitz determinant;
- **arbitrary-depth no-go in both directions:** no fixed finite Hausdorff sign rectangle forces global determinant positivity, and no fixed finite determinant rectangle forces global Hausdorff positivity;
- no finite mixed `H/D` sign battery from these generic hierarchies characterizes the full positive-real spectral cone.

The surviving open bridge is **tail-controlled reconstruction** for the infinite architecture. This package is explicitly a method/reconstruction result: it does **not** prove anything new about the actual zeta zeros and does **not** prove RH.

### RH auxiliary theorem extraction

Two additional Round-26 auxiliary theorems are now reader-facing:

- [`top-k-angular-schur-positivity.md`](https://github.com/jaredwilder/riemann-hypothesis/blob/main/auxiliary-theorems/top-k-angular-schur-positivity.md) — a finite-variable rectangular Schur theorem: if `r` times the sum of the `k` largest absolute variable arguments is `< π/2`, then `s_(r^k)>0`; the Toeplitz determinant detector-delay bound is a corollary. The finite proof was explicitly rechecked by the final source court; historical novelty is plausible but unresolved.
- [`critical-value-squared-gap-monotonicity.md`](https://github.com/jaredwilder/riemann-hypothesis/blob/main/auxiliary-theorems/critical-value-squared-gap-monotonicity.md) — for the finite real-rooted backward-heat-flow polynomial model, `|H_t(c_j)|/(x_{j+1}-x_j)^2` is nondecreasing, with the symmetric two-zero equality case retained. The entire-function extension still requires convergence control.

Neither theorem is presented as an RH result.

### Erdős–Gyárfás structural spine

The existing 202-card public forge already contained DS05–DS18, but the strongest chain was effectively buried in machine-readable cards. It now has a human theorem surface:

[`erdos-gyarfas-power-of-two-cycles/STRUCTURAL-SPINE-DS05-DS18.md`](https://github.com/jaredwilder/erdos-gyarfas-power-of-two-cycles/blob/main/STRUCTURAL-SPINE-DS05-DS18.md)

The chain is: exact cubic-surplus identity → bounded `3S` cubic defect kernel → fixed-surplus `6t` exceptional core → quotient cycle doubling → exact elimination of the `|A|=2|B|` and `|A|=2|B|+1` branches. These are source-proved structural results; historical novelty is unrun and the Erdős–Gyárfás conjecture remains open.

### Caccetta–Häggkvist exact-boundary C4 chain

A human extraction now exposes the strongest source-supported exact-boundary fourth-moment theorem:

[`caccetta-haggkvist-triangles/EXACT-BOUNDARY-C4-CHAIN.md`](https://github.com/jaredwilder/caccetta-haggkvist-triangles/blob/main/EXACT-BOUNDARY-C4-CHAIN.md)

For the stated triangle-free oriented `3d`-vertex `d`-outregular kernel, the source chain gives

```text
C4(D) ≥ ceil(3d^3/2),
tr(A^4) ≥ 6d^3,
```

plus the exact skew-energy decomposition. The recovered packet labels the central result a supported terminal asset, but this publication does **not** claim a fresh independent checker/Lean replay; the flagship conjecture stays open.

### Erdős #271 Stanley-sequence correction and theorem map

The #271 front door incorrectly described the structural endpoint in terms of **maximum** reflection multiplicity. The final audited theorem is instead controlled by **mean oriented-reflection multiplicity**

```text
μ_k = binom(k,2)/|U_k|.
```

The README is corrected and the exact dictionary is now public at:

[`erdos271-stanley-sequences/REFLECTION-MULTIPLICITY-GROWTH.md`](https://github.com/jaredwilder/erdos271-stanley-sequences/blob/main/REFLECTION-MULTIPLICITY-GROWTH.md)

For fixed seed, the audited reduction is `a_k = Θ(k+k^2/μ_k)`; with the external superlinearity input this becomes `a_k = Θ(k^2/μ_k)`. The `A(4)` `k^2/log k` target becomes exactly a `μ_k = Θ(log k)` target. The asymptotic itself remains open.

### Lonely Runner front-door repair

The focused `lonely-runner-13` repository already contained the closed large-prime canonical residue theorem, but its root README did not surface it. The front door now leads with the exact closed subproblem and its proof architecture:

[`lonely-runner-13/LARGE-PRIME-CANONICAL-CLOSURE.md`](https://github.com/jaredwilder/lonely-runner-13/blob/main/LARGE-PRIME-CANONICAL-CLOSURE.md)

For every prime `p>2366`, a primitive 13-speed tuple satisfying `u_i ≡ i (mod p)` is not a counterexample. Full LRC(13) remains open.

## Older “unpublished” flags that are already resolved live

Recursive live-tree inspection confirms that several older debt flags were stale retrieval/index results rather than real publication gaps:

- Erdős #77: [`diagonal-ramsey-corridor`](https://github.com/jaredwilder/diagonal-ramsey-corridor)
- Erdős #738: [`erdos738-triangle-free-induced-trees`](https://github.com/jaredwilder/erdos738-triangle-free-induced-trees)
- RH Epoch-32 method obstructions: [`riemann-hypothesis`](https://github.com/jaredwilder/riemann-hypothesis)
- Erdős #655 historical regular-polygon close: [`erdos655-regular-polygon-counterexample`](https://github.com/jaredwilder/erdos655-regular-polygon-counterexample)
- Kirkman / Steiner triple systems: [`lean-contributions`](https://github.com/jaredwilder/lean-contributions), including the 1,473-line zero-`sorry` development at `mathlib-pr/Mathlib/Combinatorics/Design/SteinerTriple.lean`
- Erdős #251 and #1212 theorem-map deltas: linked from the release index
- Erdős #289, #477, #486 and #949 compact theorem routes: linked from the release index
- 617 local-`PROVED`, canonical-gold-56 and Pass-4-556 provenance surfaces: already public in `msl-ore-estate` with their authority warnings intact

## Genuine source-publication residue

The remaining high-confidence gaps are no longer mostly theorem statements. They are exact historical evidence artifacts.

### Erdős #1061 primitive-seed CSV — recovered exactly, public transport still pending

The exact recovered object is:

`ERDOS1061_PRIMITIVE_SEEDS_200K.csv`

with:

- **152,803 data rows**
- SHA-256 `343b12fceb642d15b898f1a4bbbd9018b4a4301c0e72ac46ba30f559358e1a68`
- approximately 17 MB of data

The public subject home and verifier/receipt are already available at [`erdos1061-aliquot-square`](https://github.com/jaredwilder/erdos1061-aliquot-square), but the exact CSV bytes are not yet in the public tree. The recovery doctrine forbids replacing this object with a regenerated byte-different table merely because the mathematics would be equivalent.

### AGI-ZETA-BOUNDED-CLOSE-2026-08-14 archive

A historical inventory points to a separate 32-file ZIP with preregistration, failed routes, A/B replication and `verify_zeta_packet.py`. The actual archive bytes are not present in the recovered public/source estate currently available to this audit. It must be recovered before its contents are interpreted or promoted.

### Erdős #1005 Farey packet

A public summary exists, but a load-bearing identity is truncated in the surviving source summary. The complete original packet remains a source-recovery item. It must not be reconstructed by guesswork and then mislabeled as the historical source.

### Historical replay artifacts

Still missing from their public theorem notes:

- original standalone verifier / receipts for the conference-switching Ramsey-book campaign;
- original CP-SAT / PySAT models, certificates and receipts for the Erdős–Selfridge odd seven-modulus obstruction.

These are tracked in [`open-math-frontier/SOURCE-RECOVERY-QUEUE.md`](https://github.com/jaredwilder/open-math-frontier/blob/main/SOURCE-RECOVERY-QUEUE.md).

## Provenance deliberately not bulk-published as theorem authority

The historical canonical V2 theorem-claim registry contains **816 rows**, but it mixes proposed claims, finite-checked claims, prose-proved claims, source-asserted material and research targets. The old source-bucket “public-safe” split was itself superseded by later claim-level IP/semantic court.

Therefore the exact V2 registry remains a provenance object pending claim-level release court. Bulk-publishing it as an “816 theorem” release would be false. Individual mathematical survivors are already being routed through subject homes and audited theorem/provenance surfaces.

## Publication doctrine

The release follows four invariants:

1. **Truth is not novelty.** Prior art can remove priority without erasing the mathematics.
2. **Scope is not importance.** A construction-class elimination, exact finite classification or child theorem stays at its exact scope.
3. **Publication is not authority.** A public file does not become a proof merely because it is visible.
4. **Exact-source recovery is byte-level.** When a historical artifact is hash-pinned, do not silently replace it with a regenerated equivalent.

The audit remains live: source archaeology can still expose under-routed theorem identities. The hard residue is increasingly concentrated in exact supporting bytes, specialist prior-art courts, and reader-facing extraction from already-public machine/provenance layers.
