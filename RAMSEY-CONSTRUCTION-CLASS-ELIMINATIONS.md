# Ramsey construction-class eliminations

Author: Jared Wilder  
Release routing note: 2026-09-14

This page routes two exact negative Ramsey-construction results that were easy to miss in broad repository search. They are **construction-class eliminations**, not new unrestricted Ramsey-number bounds.

## 1. Symmetric conference switching cannot realize the target book-Ramsey family

Canonical result:

- [`combinatorial-records/ramsey/conference-switching-book-elimination.md`](https://github.com/jaredwilder/combinatorial-records/blob/main/ramsey/conference-switching-book-elimination.md)

For every symmetric conference matrix of order

\[
N=4m+2\ge 6,
\]

no diagonal \(\pm1\) switching yields a graph simultaneously avoiding the book \(B_m\) while its complement avoids \(B_{m+1}\).

For \(N=398=4\cdot 99+2\), this eliminates the entire switched symmetric-conference construction class from the attempted \(B_{99}/B_{100}\) search.

The public note contains the complete row-sum contradiction. Historical novelty remains a separate literature question. This theorem does **not** prove nonexistence of arbitrary graphs meeting the book-avoidance target.

## 2. Exact circulant-family eliminations at two Ramsey targets

Canonical result:

- [`combinatorial-records/findings/circulant-ramsey-family-elimination.md`](https://github.com/jaredwilder/combinatorial-records/blob/main/findings/circulant-ramsey-family-elimination.md)

The complete circulant families were exhaustively checked at two orders:

- no circulant graph on 40 vertices witnesses \(R(3,10)>40\); all **1,048,575** connection sets were tested;
- no circulant graph on 36 vertices witnesses \(R(4,6)>36\); all **262,143** connection sets were tested.

A first run had incorrectly omitted the self-inverse \(n/2\) shift for even \(n\), searched only half the family, and was retracted. The corrected exhaustions cover the full families, and a standalone checker independently rebuilds adjacency and exactly tests cliques/independent sets. A positive/negative control at \(R(3,3)\) demonstrates that the checker can both accept and reject candidates.

These results do **not** determine \(R(3,10)\) or \(R(4,6)\), and historical novelty is not cleared.

## Evidence boundary

The theorem statements are public. The source-recovery queue still tracks historical replay artifacts that have not yet reached the public tree, including the original standalone verifier/receipt files for the conference-switching campaign.

See [`open-math-frontier/SOURCE-RECOVERY-QUEUE.md`](https://github.com/jaredwilder/open-math-frontier/blob/main/SOURCE-RECOVERY-QUEUE.md).
