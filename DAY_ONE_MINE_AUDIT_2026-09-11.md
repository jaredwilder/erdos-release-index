# Day-One release architecture — what this mathematics release actually is

**Author:** Jared Wilder  
**Date:** 2026-09-11  
**Status:** living release-day audit  
**Scope:** public pure mathematics only; the publication firewall remains controlling.

## Executive view

The September 2026 release is not one paper, one theorem claim, or one corpus dump. It is a **layered public mathematical archive** designed to release substantial mathematics quickly while preserving provenance, finite scope, formal trust boundaries, failed routes, and later corrections.

The recovered research corpus contains theorems, exact computations, formalizations, structural reductions, finite certificates, conjectural routes, rediscoveries, semantic mistakes, and historical workflow labels of uneven reliability. Those objects need different public homes and different kinds of checking.

The release therefore separates six functions:

1. **Open-problem index** — which problems are currently open, and what finite/formal checks exist?
2. **Research archive** — which mathematical objects were recovered from the historical estate?
3. **Subject extraction** — which coherent results deserve focused theorem, paper, or corpus repositories?
4. **Formal and computational evidence** — what was kernel-checked, exhaustively searched, or independently reproduced?
5. **Literature reconciliation** — is a true statement new, known, weaker than known, or already implicit in classical work?
6. **Correction record** — what was false, superseded, semantically mismatched, or valid only on a narrower domain?

These functions should not be collapsed into a single theorem count or a single mega-repository.

---

## The public layers

### 1. Open-problem index

[`open-math-frontier`](https://github.com/jaredwilder/open-math-frontier) exposes **9,926** structured open mathematical targets, **8,501** with executable checking procedures. Open status comes from cited external sources rather than from local research labels.

### 2. Research archive and provenance

[`msl-ore-estate`](https://github.com/jaredwilder/msl-ore-estate) preserves the larger recovered research record. Its release-day reconstruction includes:

- **322,370** math-bearing structured-field occurrences;
- **65,834** problem-scoped distinct normalized mathematical texts;
- **21,146** formula / identity / inequality occurrences;
- **3,306** recovered Lean declarations;
- **2,858** explicit proof/closure obligations;
- **1,428** contradiction / status-changing histories;
- a **238-entry broader curated catalog**;
- **617** latest workflow states labelled `PROVED` across **171** problem families;
- a newer **56-result reviewed registry** collecting particularly reusable mathematical results.

The 617 historical labels are not 617 adjudicated theorems. They are research records whose underlying statements and evidence must be checked individually.

### 3. Focused subject repositories

Standalone repositories carry coherent mathematics that should be readable without reconstructing the entire historical research process. Examples include:

- `integral-point-sets`;
- `erdos902` and `erdos902-tournament-f4`;
- the Graham–Alspach sequenceability repositories;
- `additive-combinatorics-campaigns`;
- `combinatorial-records`;
- `erdos-theorems`;
- `erdos-proved-lemmas`;
- `erdos595-barrier-tower`;
- `lean-contributions`;
- focused number-theory, Ramsey, covering, sequenceability, and formalization repositories.

The large `unpublished-math-papers` repository now serves as a provenance/intake archive rather than the preferred final home for every subject. Its routing rules are recorded in `SUBJECT-ROUTING.md`.

### 4. Semantic and correction audits

The release keeps false and mis-scoped claims visible so they are less likely to be repeated.

`erdos-ore-findings` currently records **25 distinct semantic contamination cases** across four numbered audits. Historical filenames use `SEMANTIC_COURT_*`; the public index [`SEMANTIC-AUDITS.md`](https://github.com/jaredwilder/erdos-ore-findings/blob/master/SEMANTIC-AUDITS.md) presents them as ordinary mathematical audits.

The failures include:

- max/min and quantifier inversion;
- existential statements promoted to universal ones;
- additive and multiplicative convolution confused;
- finite constructions extended to infinite ones without proof;
- norm mismatches such as using an `L²` theorem as `L∞`;
- dropped hypotheses from literature results;
- reversed asymptotic inequalities;
- source-text corruption changing the intended problem;
- endpoint data promoted to asymptotic laws;
- interval membership confused with divisibility;
- domain transfer without justification;
- bounded computations or local formal checks promoted beyond their range.

Where practical, regression scripts are committed beside the correction.

---

## Mathematics already recovered and independently checked

Examples from the release-day extraction include:

- a sharp `q<=5` forcing lemma for sum-free subsets of `R`;
- sparse-position irrationality theorems;
- exact semiprime/binomial structure;
- exact Erdős #85 values `f(5)=f(6)=f(7)=3`;
- the all-prime p-adic reciprocal-sum obstruction for Erdős #289;
- the corrected leading-`p` harmonic criterion for Erdős #291;
- fixed-`k` finiteness for Erdős #313;
- the `2^i3^j` multiplicative-box sumset theorem;
- the rank-2 hereditary Chvátal theorem;
- exact one-dimensional and quadratic construction results for Erdős #503.

Several attractive stronger claims were rejected after direct checking. Those corrections remain public beside the surviving mathematics.

The rule is simple: **release-day urgency does not upgrade evidence.**

---

## Why chronology is preserved

The archive is best understood as a mathematical research history, not a flat list of green/red labels. Preserving chronology makes it possible to see cases where:

- a correct theorem was later falsely refuted;
- a false theorem was repaired into a valid scoped lemma;
- a computation remained correct while its universal interpretation failed;
- a formal proof was technically valid but formalized the wrong statement;
- a known theorem was independently rediscovered and therefore useful as validation but not as a novelty claim;
- a modest historical record contained stronger mathematics than a later, more confident one.

That information would disappear in a single undifferentiated “best results” export.

---

## Publication standard

### Mathematical truth

- Re-derive proofs where practical.
- Recompute exact arithmetic independently.
- Check endpoints, quantifiers, denominator conventions, and operation semantics.
- For formal results, inspect the theorem that actually elaborated and its dependency footprint.

### Source fidelity

- Compare the claim to the intended mathematical statement.
- Do not let a stronger or weaker proxy inherit the status of the original problem.
- Treat suspiciously vacuous hypotheses as possible source corruption until reconciled.

### Literature boundary

- Mathematical truth and historical novelty are separate questions.
- A known theorem may still deserve release as a formalization, recovered provenance record, or useful corollary.
- A result that appears to resolve a problem still listed open requires an especially careful literature comparison.

### Reproducibility

- Exact finite results should ship their verifier or certificate where feasible.
- State the exact range/domain of the check.
- Do not promote a finite certificate into a universal theorem.

### Corrections

- False and superseded routes remain visible.
- Corrections append rather than silently rewriting history.
- A later researcher should be able to discover quickly that a tempting route has already failed.

### Repository hygiene

- A coherent theorem family, corpus, paper program, or substantial formalization should have a focused subject repository.
- Large archives are for provenance and intake, not permanent editorial centralization.
- Historical filenames may remain strange for provenance; public summaries should translate them into ordinary mathematical language.

---

## Publication boundary

The mathematics release is not permission to publish the broader applied research estate.

The controlling rule remains [`open-math-frontier/PUBLICATION-FIREWALL.md`](https://github.com/jaredwilder/open-math-frontier/blob/main/PUBLICATION-FIREWALL.md): pure mathematics may be released after review, while unpublished biomedical, pharmacology, patient-specific, industrial, product, patent-family, private-data, and commercially sensitive embodiments remain held unless separately cleared.

Mixed artifacts are split: publish the standalone mathematics; retain the application-specific implementation privately.

---

## What this release is doing

> **Recover the mathematical estate; preserve its chronology; check every result at the level its statement requires; place coherent mathematics in focused subject repositories; publish reproducible evidence; publish corrections locally; and keep unrelated applied IP outside the release.**

That combination—large-scale recovery, theorem extraction, focused repositories, reproducible verification, and permanent correction records—is the Day-One release architecture.
