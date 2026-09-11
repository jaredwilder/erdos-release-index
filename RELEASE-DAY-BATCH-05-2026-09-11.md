# RELEASE DAY — BATCH 05 — 2026-09-11

This batch promotes another theorem wave out of the audited estate and, more importantly, separates **headline mathematical content** from merely large archive volume.

## New public theorem packets

### Erdős #655 — literal frozen statement closed negatively

Public home: `jaredwilder/erdos-proved-lemmas/erdos655-regular-polygon-counterfamily.md`  
Commit: `f2962c55e64614a2f3fd281c66a534363fae5773`

For every `n>=3`, a regular `n`-gon satisfies the stated circle condition and has exactly `floor(n/2)` distinct distances. Therefore no fixed `c>0` can force `(1+c)n/2` distinct distances for every sufficiently large configuration under the literal frozen statement.

**Authority boundary:** this is a complete mathematical negative answer to the literal frozen formulation. The archived green Lean receipt was only a finite proxy and is not represented as universal certification. The estate audit also says the counterfamily is already public/known; this is a correction/statement-scope headline, not a novelty claim.

### Erdős #145 — complete `0<=alpha<=1` moment slice

Public home: `jaredwilder/erdos-proved-lemmas/erdos145-squarefree-gap-moments-alpha-le1.md`  
Commit: `782524235f575dfb266080dcfe74be45afc4c797`

Using standard fixed-gap squarefree-correlation densities plus a telescoping tail estimate, the normalized squarefree-gap moment has a limit for every fixed `0<=alpha<=1`; the `alpha=1` limit is exactly `1`, and `alpha=0` is `6/pi^2`.

**Authority boundary:** citation-dependent partial theorem. The novelty audit says stronger historical squarefree-gap-moment results exist, so this is preserved mathematics rather than a frontier novelty claim.

### Erdős #727 — infinite exact `k=2` obstruction family

Public home: `jaredwilder/erdos-proved-lemmas/erdos727-k2-prime-obstruction-family.md`  
Commit: `dc122bd4565e146e49732bc72840adf2d57d7d7b`

For every prime `p>=7`, with `n=2p-2`,

`((n+2)!)^2 ∤ (2n)!`.

The proof is a one-prime valuation mismatch: the proposed divisor carries `p`-adic valuation `4`, while `(4p-4)!` carries only `3`.

**Authority boundary:** infinite obstruction family, not a negative answer to the parent infinitude question.

### Erdős #1212 — infinitely many admissible dead ends

Public home: `jaredwilder/erdos-proved-lemmas/erdos1212-infinite-dead-end-family.md`  
Commit: `7f6722b7322129bcc5dcd4d097555d83af863be6`

For every `k>=2`, `(2,3^k)` has unique full-graph neighbor `(1,3^k)`, which lies outside the `min(x,y)>1` admissible region. Hence the admissible subgraph contains infinitely many explicit isolated vertices.

**Authority boundary:** global structural obstruction family; the existence of some other infinite admissible path remains open.

### Erdős #859 — density existence is automatic and rational

Public home: `jaredwilder/erdos-proved-lemmas/erdos859-periodic-density.md`  
Commit: `3b33d9a9c54330e4b434027908171a13942f8962`

For fixed `t`, the predicate that `t` is a sum of distinct divisors of `n` depends only on `n mod lcm(1,...,t)`. Thus `d_t` always exists and is rational. The packet also preserves the corrected exact table for `t<=12`.

**Authority boundary:** elementary structural theorem. The parent asymptotic `d_t ~ c_1/(log t)^c_2` is untouched.

## Existing headline assets this batch sits beside

These were already public before Batch 05 and are not duplicated here:

- Erdős #949: sharp finite constant `5`, countable complement theorem, finite-real-dilate IP theorem, and finite-homomorphism semigroup envelope.
- `C(13,6,3)`: two validated 21-covers plus a heavily compressed hypothetical-20 structure; the exact value remains `20<=C(13,6,3)<=21` until a replayable 20-cover UNSAT certificate exists.
- Erdős #486: summable forbidden residue mass implies ordinary density, with quantitative tail error and a positive-density criterion.
- Erdős #247: exact-hypothesis irrationality in every integer base and eventual-periodicity characterization; folklore risk remains.
- Erdős #52: the natural multiplicative box `{2^i3^j}` has `|A+A| >= C(N,2)^2`, so it is nearly maximally additive.
- Erdős #406: quantitative 3-adic exponent sieve with `O(N^(log_3 2))` surviving exponents.
- Erdős #400: universal logarithmic upper control paired with an explicit factorial subsequence lower growth of order `log n/log log n`.
- exact finite extremal/certificate results including the F31/F73 avoidance packets, rank-three kernel theorem packet, and the Release-Day Erdős–Straus structured classifications.

## Anti-hype rule

A release-day headline may mean one of several things: complete answer to an exact frozen statement, strong theorem inside an open parent problem, exact finite classification, structural obstruction, formal certification, or candidate-new theorem after targeted search. Those statuses are not interchangeable.

In particular:

- #655 is a complete negative answer to the **literal frozen formulation**, but is not claimed new;
- #145 is mathematically useful but historically subsumed;
- #727/#1212/#859 are strong exact structural statements, not parent closes;
- `C(13,6,3)` is a close program, not yet a close;
- #949/#247 retain explicit specialist-priority / folklore-risk language.

## Saturation

Release saturation is **not declared**. The contradiction-history payload, ORE-v1 payload bytes, semantic-review/formalizer queues, and long-tail theorem estate remain live release surfaces.
