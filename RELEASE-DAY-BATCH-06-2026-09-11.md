# RELEASE DAY — BATCH 06 — 2026-09-11

This batch is a **headline-and-integrity pass**: promote an under-advertised A+ structural reduction, while killing two seductive false closes before they can contaminate the public theorem layer.

## Headline promotion — Erdős #1093 / #890 divisor-window bridge

Public home: `jaredwilder/erdos-theorems/erdos1093-divisor-window/README.md`

For an admissible `(n,k)` in Erdős #1093, let

`L_k = lcm(1,...,k)`.

The release proves the exact equivalence

`n-i is k-smooth  <=>  n-i | L_k`

for every `0<=i<k`, and therefore the deficiency is exactly

`delta(n,k) = #{d | L_k : n-k < d <= n}`.

So for each fixed `k`, every positive-deficiency candidate is contained in the finite divisor geometry

`n = d+i`, `d | L_k`, `0<=i<k`.

The same packet contains an exact cross-problem identity for Erdős #890:

`sum_{i=0}^{k-1} omega_k(n+i) = omega_{>k}(C(n+k-1,k))`,

and, at an admissible #1093 window,

`S_k = k-d+E`, hence `S_k<=k <=> E<=d`,

where `d` counts k-smooth members and `E` counts excess distinct large-prime factors. In plain language: **#1093 deficiency pays for #890 excess.**

The estate ranked both the divisor-window theorem and the #890↔#1093 bridge `A+`. Neither parent problem is claimed closed, and historical priority for the exact formulation remains unresolved.

The exact divisor engine was also run through `k<=45`, reproducing all currently listed deficiency-`>1` examples in that range, including `delta(284,28)=9`, with no additional examples found in the stated finite frontier.

## Integrity correction — Erdős #891

Public correction: `jaredwilder/erdos-proved-lemmas/erdos891-omega-scope-correction.md`  
Commit: `0924db3a7bf9ba5a9297722b5a7b911ca312edba`

A historical close silently changed the canonical prime-factor count from distinct-prime `omega` to multiplicity-counting `Omega`.

The least-multiple argument is valid for the `Omega` variant:

`Omega(P_k ceil(n/P_k)) >= k+1`,

but **does not solve #891**, whose intended/current formulation counts distinct prime divisors. The canonical problem remains open even at `k=2`.

All archived #891 branch-close / `TARGET_CLOSED` language depending on the `Omega` reading is superseded.

## Integrity correction — Erdős #539

Public correction: `jaredwilder/erdos-proved-lemmas/erdos539-diagonal-close-retraction.md`  
Commit: `7bc8e041cc00bef55d119b160104c88f17e0f8b6`

A historical route claimed

`a/gcd(a,a)=a`.

The correct identity is

`a/gcd(a,a)=1`.

So the diagonal pairs do **not** inject `A` into the quotient set, and the archived claimed formula `h(n)=n` collapses. #539 remains open; the false diagonal route is now a permanent regression test rather than latent gold.

## Why this batch matters

Release Day is not a maximal-claim exercise. The same mining pass that discovers an A+ theorem can also encounter a one-symbol semantic drift that manufactures a fake solution. Both outcomes belong in the public record.

The rule remains:

- strong exact mathematics goes up;
- failed routes stay visible;
- semantic mismatches are killed before promotion;
- no workflow label outranks the mathematical statement.

## Saturation

**Not saturated.** The contradiction-history payload, ORE-v1 bytes, 556 formalizer obligations, historical proof archives, duplicate reconciliation, and the raw theorem-shaped candidate mine remain live.
