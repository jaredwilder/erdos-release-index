# Release Day — Batch 03 — 2026-09-11

This note records another public wave from the September 2026 mathematics release. It is a release log: what became public, what was corrected, and where a human reader should now look for the mathematics.

## 56-result reviewed registry

A reviewed cross-estate registry of **56 mathematical results** is public in three historical source files under

`jaredwilder/msl-ore-estate/catalog/canonical-gold-56/`.

The source parts were published in commits:

- `e2c163b119bb26f0242138fb077ed364ce72ec2f`
- `b62fb013fdb4c11ac3d3646c434c35a70015ca78`
- `53d68587d0ab5487992ba89329c34796309b8a99`

Recovered source SHA-256:

`a5eada56610ec5c8fbb6a2146cb9d56813dbd4d1900d9f8079a33a0c0b90b7f4`.

For human reading, start with `catalog/canonical-gold-56/README.md`, which translates the historical internal status labels into ordinary questions: what is the statement, what proves or checks it, what has been formalized, and what corrections or literature dependencies remain?

## Day-2 historical archive and corrections

The historical Day-2 material is preserved under

`jaredwilder/msl-ore-estate/archive/2026-09-11/day2-historic-haul/`.

It now has a human reading guide, an explicit correction file, and an exact witness table. The original 99,230-byte historical master remains pinned by SHA-256

`3b95a2f51df7b8a9829fb366986b5ef89306d8b354585b232bc9fabd9742e721`.

One important correction concerns Erdős #126: the unrestricted integer statement is false, since `{-1,3,5}` has pairwise sums `2,4,8`; the recovered proof requires a positivity/domain hypothesis. The historical record remains intact and the correction is placed in front of it.

The witness table contains independently checked finite objects including Sidon sets, 3-AP-free sets, two independent 21-block `C(13,6,3)` covers, finite Erdős witnesses, a four-point planar integer-distance configuration, and a finite prefix of the exact Erdős #930 Pell family. Each row states its domain so a finite witness is not confused with a universal theorem.

## Mathematics promoted into clearer public homes

The intake archive preserves the original extraction chronology, but the preferred reading surfaces are now organized by subject.

### Compact Erdős theorem bank

`jaredwilder/erdos-proved-lemmas` is the compact home for finished child theorems that do not yet need a repository of their own. Batch-03 results routed there include, among others:

- Erdős #120 — unbounded affine-copy avoidance;
- #168 — the exact `ceil(2N/3)` construction avoiding `{n,2n,3n}`;
- #274 — reduction of distinct-cardinality finite exact coset covers to finite groups;
- #371 — consecutive integers have different largest prime factors;
- #406 — exact ternary `{0,1}` exponent sieve;
- #412 — strict increase of forward sigma-orbits above 1;
- #479 — an infinite power-congruence family;
- #821 — odd totient targets greater than 1 have no preimages;
- #885 — factor-difference / square duality;
- #890↔#1093 — large-prime/deficiency bridge and admissible LCM divisor-window reduction;
- #930 — infinite Pell square-product family and the `k>=4` threshold obstruction;
- #936 — square-cube and mod-8 structure for odd powerful numbers;
- #985 — 3 is primitive modulo every Fermat prime at least 5;
- #1052 — classification of unitary-perfect integers with at most two distinct prime factors;
- #1073 — divisor shape of `n!+1`.

Parallel release work has also added further compact results directly to that theorem bank. The bank is a catalog, not a replacement for richer subject repositories when those exist.

### Additive combinatorics

`jaredwilder/additive-combinatorics-campaigns` now carries:

- Erdős #52 — for `A_N={2^i3^j}`, the exact product-set size `(2N-1)^2` and the lower bound `|A_N+A_N|>=C(N,2)^2`;
- Erdős #153 — Sidon sumset cardinality `n(n+1)/2` and the associated squared-gap inequality;
- Erdős #241 — `C(m+2,3)<=3N-2` for distinct unordered 3-multiset sums, hence `m^3<18N`.

These sit beside the repository's existing exact C3/C5-free results, additive encodings, zero-sum constructions, and LRAT-backed theorem.

### Erdős #376

`jaredwilder/erdos376-successor-frontier` now unifies the exact Kummer criterion

`gcd(C(2n,n),105)=1`

with the equivalent base-3/base-5/base-7 digit restrictions and the repository's independently reproduced **1,006-digit witness above `10^1000`**.

### Erdős #503

`jaredwilder/erdos-lean-remainder` is now the focused public home for the #503 formal/geometry material: the kernel-clean orthogonal-join development, exact values in selected dimensions, exact `f(1)=3`, and the regular-simplex midpoint lower bound `f(d)>=C(d+1,2)+1`.

### Combinatorial records

`jaredwilder/combinatorial-records` now carries the complete rank-2 hereditary Chvátal theorem alongside the existing Sidon, covering-design, Ramsey, finite-field, automata, and witness material.

## A subject that has outgrown the theorem bank

The Erdős #890↔#1093 material already consists of a large-prime binomial identity, deficiency/excess accounting, an admissible LCM divisor-window reduction, a finite deficiency engine, and a substantial forensic problem history.

It is therefore listed in the repository-topology queue as a **standalone subject-repository candidate**. Until repository creation is available through the release tooling, `erdos-proved-lemmas/erdos890-1093-bridge.md` is the compact human reading surface and the intake archive preserves the full chronology.

## Exact historical ledger transport

The Day-2 theorem and correction/quarantine ledgers are publicly reconstructable from gzip/base64 transport files:

- theorem-vault transport — commit `dc8c2c0817cc3238a91d6ecdaa77bcc3eb3dc992`
  - reconstructed bytes: **26,341**
  - SHA-256: `751fa7b59bffa6291f6c3df57bcbcaa35754bb5b0ca27f0b2c52f0edc16015f6`
- correction/quarantine transport — commit `68db210150d20d08ddf8a8ac603a406d6f953218`
  - reconstructed bytes: **23,060**
  - SHA-256: `a0ff8dc7e3dc7b3231bba6cc4b359fefec804ec98a9d2b79ce2799a70172d3df`
- reconstruction/hash manifest — commit `e0685a937c119de4367210e7bce1d6e08f08572f`.

Together with the readable witness table, these preserve the historical theorem/witness/correction layer exactly while the subject repositories provide cleaner mathematical reading surfaces.

## Evidence and publication rules

- finite statements remain finite;
- a proof-assistant check of one concrete instance remains evidence for that instance;
- historical `PROVED` and `FALSE` labels are both subordinate to direct mathematical checking;
- historical novelty is separate from correctness;
- corrections attach to the result they correct rather than becoming a warning label for unrelated work;
- coherent theorem families and formalization corpora should have coherent public homes;
- mixed biomedical, patent, product, private-data, and proprietary-system material remains behind the publication firewall.

## Release status

The public mathematics archive is still expanding. Remaining work includes additional historical-ledger transport, contradiction-history reconstruction, formalization-obligation review, duplicate-family reconciliation, source/literature reconciliation, and further subject routing.

The current architecture is intentionally layered: **focused subject repository > compact theorem bank > provenance archive**.
