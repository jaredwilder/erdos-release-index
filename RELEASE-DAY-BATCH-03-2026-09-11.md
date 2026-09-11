# RELEASE DAY — BATCH 03 — 2026-09-11

This batch records the next public extraction wave from the mathematics estate. It is an execution ledger, not a saturation declaration.

## Canonical-gold transport completed

The recovered 56-result canonical gold registry is now public in three parts under `jaredwilder/msl-ore-estate/catalog/canonical-gold-56/`:

- Part 1 — commit `e2c163b119bb26f0242138fb077ed364ce72ec2f`
- Part 2 — commit `b62fb013fdb4c11ac3d3646c434c35a70015ca78`
- Part 3 — commit `53d68587d0ab5487992ba89329c34796309b8a99`

Recovered source SHA-256: `a5eada56610ec5c8fbb6a2146cb9d56813dbd4d1900d9f8079a33a0c0b90b7f4`.

Historical source statuses and formal-scope warnings are preserved rather than normalized into one blanket authority level.

## Day-2 provenance / correction layer

Public under `jaredwilder/msl-ore-estate/archive/2026-09-11/day2-historic-haul/`:

- shortened operator-facing master/provenance surface — `5c68505eac1f0c0b3f818513d19f9678a896ddaf`
- correction/authority layer — `196c427c13e4d3235120cddfbddb7950274e6275`
- exact witness vault — `fd8c085bb869a3765410276c10033869b5a602bd`

The original recovered 99,230-byte Day-2 master remains pinned by SHA-256 `3b95a2f51df7b8a9829fb366986b5ef89306d8b354585b232bc9fabd9742e721`.

The correction layer publicly quarantines historical row #126: the unrestricted integer statement is false (`{-1,3,5}` has pairwise sums `2,4,8`); the recovered proof requires a missing positivity/domain hypothesis.

## New focused subject extractions

### Cross-problem bridge / forensic packet

- Erdős #890 ↔ #1093 deficiency/excess bridge — `de2f6fc74cf2a0e321763feea124b36c90a977a8`
- Erdős #1093 forensic problem card — `47d97c64557847d68f8a219916e703264a0b1d5e`

The bridge releases the exact large-prime binomial identity, admissible LCM divisor-window reduction, and accounting formula `S_k=(k-d)+E`, so `S_k<=k` iff `E<=d`. Neither parent problem is claimed closed.

### Number theory / arithmetic

- Erdős #930 Pell square-product family and `k>=4` obstruction — `1569d92d9ae57c590b02d5c330ea645192c07525`
- Erdős #276 recurrence common-divisor theorem — `7489853d17465bde1c2fe70aa7b641ac8c2fc0e0`
- Erdős #1052 two-prime unitary-perfect classification — `1285392bdea21d94dbb6f023b637fb73c133338b`
- Erdős #826 divisor-tail elimination — `d9c782887a65a1657a108ec1c14d32101c2e554c`
- Erdős #1073 factorial-plus-one divisor shape — `569dc304f07fe4e34da78f5f1814d328a30d0647`
- Erdős #479 infinite power-congruence family — `059329ca5dfcbab6e913484c20748278acf884a4`
- Erdős #885 factor-difference/square duality — `b28479e9a47759801c5de19dfbf43827fb3be747`
- Erdős #985 Fermat-prime primitive-root subfamily — `d91365bf7c032cf90351801bf948b913f079dc1c`
- Erdős #376 Kummer carry criterion for `gcd(C(2n,n),105)` — `9eba669ed9cab6a143c852c8b759c8b5ba691991`
- Erdős #821 odd totient targets have no preimages — `1a46a6f0de5be50b09b14ecd78ecfe59201302c0`
- Erdős #406 ternary-digit exponent sieve — `5413e3cd490c0b98d4b151558c9450ea6a9c8b00`
- Erdős #371 consecutive largest-prime-factor ties impossible — `db49e30de9aad888391d451b36ba57b36867f8a8`
- Erdős #412 sigma-orbit strict monotonicity — `80b7eac3a17b5714824471a8e66ef4f0c14f2f26`
- Erdős #51 totient-preimage size bound — `e76c03c8dd144b857e6d3dcecf935364e11c6b4a`
- Erdős #936 powerful-number square-cube/mod-8 packet — `5410b40f397d986a075a0189d82bb75af841109e`

### Combinatorics / measure / group reductions

- Erdős #120 unbounded affine-copy subcase — `02fddd3a690a19f31a8a15c067ce0a0567abbe30`
- Erdős #168 two-thirds `{n,2n,3n}` avoidance construction — `23d767c8fb0d446b5b8be21fb7aeffaff7927c61`
- Erdős #241 exact 3-multiset-sum counting bound — `0104c70b9f5c70573e0fc26ae78597d0ddc17bd2`
- Erdős #153 Sidon sumset bookkeeping / gap inequality — `b283f847082feb8003c4042048f986bf8ed6e29f`
- Erdős #274 infinite-group exact-coset-cover reduction — `deb4ff316f2a7be749ee15f4e43423374c73dc8f`

### Archive index

`jaredwilder/unpublished-math-papers/README.md` was refreshed to surface these Release-Day standalone packets while preserving its role as provenance/intake rather than pretending every directory is the permanent canonical home: commit `47a7944e99bd29873f763c2197c41eda33405cd2`.

## Exact historical ledger transport

The Day-2 theorem and quarantine ledgers are now byte-reconstructable from public gzip/base64 transport files:

- theorem vault transport — commit `dc8c2c0817cc3238a91d6ecdaa77bcc3eb3dc992`
  - reconstructed CSV bytes: `26341`
  - SHA-256: `751fa7b59bffa6291f6c3df57bcbcaa35754bb5b0ca27f0b2c52f0edc16015f6`
- quarantine-expanded transport — commit `68db210150d20d08ddf8a8ac603a406d6f953218`
  - reconstructed CSV bytes: `23060`
  - SHA-256: `a0ff8dc7e3dc7b3231bba6cc4b359fefec804ec98a9d2b79ce2799a70172d3df`
- reconstruction/hash manifest — commit `e0685a937c119de4367210e7bce1d6e08f08572f`

Together with the directly readable witness vault, the core Day-2 theorem/witness/quarantine triad is now publicly reconstructable with exact hashes.

## Authority boundary

- finite remains finite;
- single-instance kernel receipts remain single-instance;
- historically source-labeled `PROVED` rows do not outrank concrete later counterexamples;
- novelty is not inferred from absence of an obvious collision;
- mixed biomedical/patent/product/system material remains behind the release firewall.

## Saturation status

**NOT SATURATED.** Remaining estate work includes the 1,428 contradiction-history transport, ORE-v1 payload bytes, the 556 formalizer-obligation queue, duplicate-family reconciliation, EG203 historical-source reconciliation, Erdős #738 Lean semantic reconciliation, and the still-unprocessed MSL Estate Engine packet queue.
