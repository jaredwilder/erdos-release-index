# Day-One Mine Audit — what this release actually is

**Author:** Jared Wilder  
**Date:** 2026-09-11  
**Status:** living release-day audit  
**Scope:** public pure mathematics only; the publication firewall remains controlling.

## Executive view

The September 2026 release is not one paper, one theorem claim, or one corpus dump. It is a **layered public mathematical estate** built so that positive mathematics can be released quickly without erasing provenance, failed routes, finite scope, formal trust boundaries, or later corrections.

That architecture matters because the recovered research corpus is high-entropy. It contains real theorems, exact computations, formalizations, barriers, finite certificates, conjectural routes, rediscoveries, semantic drift, contradicted claims, and occasionally a late workflow label that is less reliable than an earlier line of mathematics.

The release therefore separates six jobs that are often collapsed into one:

1. **Frontier:** what is actually open, and what finite/formal interfaces exist?
2. **Mine:** what mathematical objects were recovered from the historical research estate?
3. **Promotion:** which recovered objects survive proof replay and deserve standalone mathematical release?
4. **Formal / computational evidence:** what exactly was kernel-checked, exhaustively searched, or independently reproduced?
5. **Literature reconciliation:** is a true statement new, known, weaker than known, or already implicit in a classical result?
6. **Integrity record:** what was false, superseded, semantically mismatched, or merely finite when the source rhetoric was universal?

The result is intentionally not a single undifferentiated theorem count.

---

## The public layers

### 1. Open-frontier layer

[`open-math-frontier`](https://github.com/jaredwilder/open-math-frontier) currently exposes **9,926** structured open mathematical targets, **8,501** with executable checking procedures. Open status comes from cited external sources rather than from whether a local campaign happened to say `PROVED` or `FALSE`.

This is the target map, not the result ledger.

### 2. Ore / provenance layer

[`msl-ore-estate`](https://github.com/jaredwilder/msl-ore-estate) is the public mine. Its release-day reconstruction records, among other surfaces:

- **322,370** math-bearing structured-field occurrences;
- **65,834** problem-scoped unique normalized mathematical texts;
- **21,146** formula / identity / inequality occurrences;
- **3,306** recovered Lean declarations;
- **2,858** explicit closure obligations;
- **1,428** contradiction / status-changing histories;
- a **238-row promoted/curated catalog**;
- a lossless surface of **617 latest-local `PROVED` rows across 171 problem families**.

The last number is deliberately *not* called 617 theorems. A local campaign status is a lead that must still survive canonical-statement, contradiction, proof, and literature review.

### 3. Focused theorem / certificate layer

Standalone repositories now carry results that are useful to read without reconstructing the full campaign history: exact finite classifications, theorem packages, Lean developments, search certificates, structural barriers, and focused Erdős-problem extractions.

Examples include:

- `integral-point-sets`;
- `erdos902` and `erdos902-tournament-f4`;
- `graham-alspach-sequenceability`, `graham-alspach-extended`, and the certificate bank;
- `additive-combinatorics-campaigns`;
- `combinatorial-records`;
- `erdos-theorems`;
- `erdos595-barrier-tower`;
- `lean-contributions`;
- `unpublished-math-papers`;
- focused number-theory, Ramsey, Sidon, covering, sequenceability, and formalization repositories.

The release index remains the map; the focused repository is the authority for the result it actually states.

### 4. Correction / semantic-court layer

A mass mathematical release is only credible if false late-stage claims are made harder—not easier—to resurrect.

The `erdos-ore-findings` court records now document **25 separate contamination cases** across `SEMANTIC_COURT_02.md` through `SEMANTIC_COURT_05.md`, in addition to the earlier Day-One forensic correction ledger.

The failures are not one generic model-error category. They include:

- max/min quantifier inversion;
- existential/universal witness slips;
- additive-vs-multiplicative convolution confusion;
- finite-to-infinite gluing without a bridge theorem;
- using an `L²` result as if it were `L∞`;
- losing a fixed-bound hypothesis from a literature theorem;
- reciprocal/asymptotic inequality reversal;
- source-text corruption turning an intended problem into a vacuous one;
- endpoint facts promoted to asymptotic laws;
- interval membership confused with divisibility;
- domain transfer from integer-base expansions to rational bases;
- bounded-computation or local formal receipts promoted beyond their certified scope.

Where the correction is cheaply executable, a regression script is committed beside it.

This is not a side project. It is part of the publication machinery.

---

## What the Day-One mine already yielded under independent attack

The current mining pass has promoted mathematics only when the statement could be independently reconstructed or recomputed.

Examples released from the ore include:

- a sharp `q<=5` forcing lemma for sum-free subsets of `R`, with sharpness witness;
- infinite congruence, factorial-divisibility, nearby-divisor, and divisor-sum identity families;
- a sparse-position irrationality theorem and related exact arithmetic packages;
- corrected semiprime/binomial structure whose later internal “counterexample” was itself arithmetically wrong;
- exact Erdős #85 values
  
  `f(5)=f(6)=f(7)=3`,
  
  with a self-contained `C4`-free common-neighborhood proof and exhaustive verification of every labeled graph through seven vertices.

Equally important, several attractive “closes” were rejected rather than released:

- Erdős #396 `k=2` impossibility, refuted by the exact known witness `n=2480`;
- Erdős #943 prime-exponent product formulas, which solve multiplicative rather than additive convolution;
- Erdős #749 use of Ruzsa's square-mean theorem as a pointwise bounded-representation theorem;
- Erdős #406 application of Senge–Straus after dropping the fixed digit-sum bound;
- Erdős #317 use of an `1/lcm(1,...,n)` granularity bound in the wrong asymptotic direction;
- multiple purported closes whose proposed witness did not satisfy the frozen definition at all.

The governing rule is simple: **release-day urgency does not upgrade evidence.**

---

## A useful observation about the estate

The Day-One archive is not best understood as a bag of 710/617/etc. green rows waiting to be uploaded. It is closer to a **mathematical event log**.

That is more valuable.

Because chronology was preserved, it is possible to observe patterns such as:

- a correct theorem later being falsely refuted;
- a false theorem later being repaired into a valid scoped lemma;
- a computation remaining correct while its universal interpretation fails;
- a formal proof being kernel-clean but proving the wrong semantic statement;
- a genuine known theorem being rediscovered independently and therefore useful as a validation event but not a novelty claim;
- a low-ranked row containing a clean theorem while a high-ranked row contains a seductive false close.

A flat “best results” export would destroy that information.

---

## Publication standard

For the rest of release day, promotion should continue to require the following gates.

### Mathematical truth

- Re-derive the proof where practical.
- Recompute exact arithmetic independently.
- Attack endpoints, quantifiers, denominator conventions, and operation semantics.
- For formal results, inspect what theorem actually elaborated and its dependency footprint.

### Canonical fidelity

- Compare the claim to the current canonical problem statement.
- Do not let a strengthened or weakened formal proxy inherit the status of the original problem.
- Treat suspiciously vacuous hypotheses as possible source corruption until reconciled.

### Literature boundary

- Truth and novelty are separate verdicts.
- A known theorem may still deserve release as recovered provenance, formalization, or a useful corollary.
- A theorem that appears to solve a problem still listed open requires an especially aggressive collision check before publication.

### Reproducibility

- Exact finite results should ship their verifier/certificate where feasible.
- The verifier's scope should be stated explicitly.
- A finite certificate must never be rhetorically promoted into a universal theorem.

### Correction permanence

- False and superseded routes remain visible.
- Corrections append; they do not silently rewrite history.
- A later miner should be able to discover that a tempting route is dead before spending another week on it.

---

## Publication firewall

The mathematics release is not permission to dump the broader research estate.

The controlling rule remains [`open-math-frontier/PUBLICATION-FIREWALL.md`](https://github.com/jaredwilder/open-math-frontier/blob/main/PUBLICATION-FIREWALL.md):

- standalone pure mathematics, proofs, formalizations, and non-sensitive verification infrastructure are presumptively publishable after claim review;
- unpublished biomedical, pharmacology, patient-specific, energy/grid/battery, industrial, game-engine, product, deployment, business, patent-family, and commercially load-bearing embodiments remain held unless already deliberately released;
- mixed artifacts are split: publish the standalone mathematics, retain the application-specific embodiment.

This audit publishes no such retained applied material.

---

## What we are doing

The project is not “upload everything models ever said.”

It is:

> **Recover the mathematical estate; preserve its chronology; attack every promotion; publish the surviving mathematics at its exact scope; publish the evidence that makes it reproducible; publish the corrections that make it falsifiable; and keep unrelated applied IP behind the firewall.**

That combination—large-scale recovery *plus* theorem extraction *plus* adversarial correction *plus* reproducible certificates—is the real Day-One object.

The mine is still open.
