# Release Day — 2026-09-11

**Author:** Jared Wilder

This file records the second-stage estate release begun after the initial public index. It is an anti-loss and scope-control ledger, not a theorem-count boast.

## Release rule

Pure mathematics, proofs, formalizations, exact computations, certificates, counterexamples, failed routes and provenance are publishable when they do not expose load-bearing product/patent/private IP.

Mixed biomedical, patient-state, treatment/control, commercial energy, patent, proprietary product, credential, infrastructure and private-corpus material remains behind the publication firewall. When mixed sources contain standalone mathematics, the mathematics is extracted rather than the raw mixed source being dumped.

## New public release surfaces

### MSL mathematical estate

[`jaredwilder/msl-ore-estate`](https://github.com/jaredwilder/msl-ore-estate) now contains a release-day forensic layer for a much larger mathematical estate than the original curated index exposed.

Publicly documented/reconstructible surfaces include:

- 10,726 raw route-registry events;
- 2,612 latest route/lemma states;
- 617 latest-local `PROVED` states across 171 problem families;
- 1,428 contradiction/status-changing histories;
- 6,882 frozen-vault identities;
- 606 live theorem-grade identities in the frozen snapshot;
- 238 exact-distinct promoted/curated mathematical rows;
- 303 canonical problem reconstructions;
- 2,858 closure obligations;
- 5,876 positive/certified claim occurrences;
- 21,146 formula/identity/inequality occurrences;
- 3,306 Lean declarations;
- 1,488 unfinished/load-bearing ore objects;
- 322,370 recursively recovered math-bearing structured-field occurrences;
- 65,834 problem-scoped unique normalized mathematical texts;
- 15,027 implication-stitch edges;
- 1,043 multi-hop candidate chains;
- 606 branch-level composite dossiers;
- a 35-shot kernel/formalizer firing line.

These counts are provenance surfaces. They do **not** mean that every object is a novel theorem or even a true claim.

### Exact 617-row provenance tranche

The complete latest-local `PROVED` tranche is now byte-reconstructible under `catalog/local-proved-617/`.

- rows: **617**
- exact CSV bytes: **246,477**
- exact CSV SHA-256: `4999693a7ad661344f8a05ae1c9dc00c9e2be91a6d1f9c842492e5b23047523a`
- compressed stream SHA-256: `f5bfd2d7a1cfc9b60b6d28421cc5418744ecc059a678ebb3b15be1eb58c271a8`
- transport: ten consecutive base64 slices of one `gzip -9` stream

`PROVED` in this tranche is a workflow-local status. Publication does not silently upgrade it to kernel-checked, literature-reconciled or globally true.

### ORE v1 migration

`msl-ore-estate/archive/2026-09-11/ore-v1-bootstrap/` exposes the frozen bootstrap report, exact hash manifest and format audit for the machine-scale provenance graph:

- **458,212** unique ORE-v1 mathematical objects;
- **1,133,352** relation/provenance edges;
- **26** referenced source files;
- **64,909** duplicate representation rows collapsed during identity migration.

The hash manifest records the canonical unreduced payload identities, including:

- `ore.jsonl`: `d45300265dc619701467fcd0a1046cc3f3e61a25359cbda37a3890c9180b2dbd`
- `edges.jsonl`: `44472dc8ecac3fe36a08027612a3cbc22d11ceb5c0f95bc4988f256f59c38f43`

The report/hash layer is public now; the release ledger must not be read as claiming the enormous payload bytes themselves have all been transported into GitHub yet.

### Historic theorem and witness vaults

The release-day archive also carries byte-reconstructible snapshots of:

- `00-DAY2-HISTORIC-MASTER-RELEASE.md` — SHA-256 `3b95a2f51df7b8a9829fb366986b5ef89306d8b354585b232bc9fabd9742e721`;
- `THEOREM_VAULT.csv` — SHA-256 `751fa7b59bffa6291f6c3df57bcbcaa35754bb5b0ca27f0b2c52f0edc16015f6`;
- `WITNESS_VAULT.json` — SHA-256 `20a8dea2d2ddd27d6f769661613fa508b4197dd4cfc28bae843fd271620dfdeb`.

### Public subject archive expansion

`jaredwilder/unpublished-math-papers` has been corrected from its obsolete “five mathematical writeups” description into a live release-day subject archive. Its public tree now contains focused homes for Caccetta–Häggkvist, EG203 analytic work, Erdős–Gyárfás power-cycle mathematics, Erdős 271, 500, 738 and 77, Lonely Runner, P6, RH reductions, fiber coherence/CSP theory, MathFire theorem outputs, structured Erdős–Straus denominator theorems, finite-field extremal classifications, prime-gap admissibility and related theorem banks.

The archive README is an index, not a global truth claim: each subdirectory retains its own authority boundary.

### Erdős–Straus arithmetic-progression classification

[`unpublished-math-papers/erdos-straus-progressions`](https://github.com/jaredwilder/unpublished-math-papers/tree/main/erdos-straus-progressions) publishes the complete AP-denominator classification:

> all positive solutions of `4/n = 1/x + 1/y + 1/z` whose strictly increasing denominators form an arithmetic progression are parameterized uniquely by coprime `a>d>0` and a positive scale `t`, with the exact parity split through `D=3a²-d²`; no primitive denominator triple occurs.

The independent regression sweep checked 76,115 coprime parameter pairs and 456,690 constructed solutions. Historical novelty is stated only as `apparently_new_after_systematic_search` (search date 2026-07-27), not as an absolute claim.

### Erdős–Straus geometric-progression classification

`unpublished-math-papers/erdos-straus-geometric-progressions` publishes the complete GP-denominator classification:

`x=tDa²`, `y=tDab`, `z=tDb²`, `n=4ta²b²`, where `D=a²+ab+b²`, `0<a<b`, `gcd(a,b)=1`, `t>=1`.

The parameters are unique and no primitive denominator triple occurs. Independent campaign verification checked tens of thousands of coprime parameter pairs and hundreds of thousands of constructed solutions/recoveries. Novelty remains qualified by the associated search dossier.

### Product/GP avoidance on [50]

`unpublished-math-papers/product-gp-free-50` publishes the exact finite classification for subsets of `{1,...,50}` that are simultaneously product-free and free of nontrivial three-term geometric progressions:

- exact maximum: **35**;
- exact minimum forbidden-edge transversal: **15**;
- exact extremizer count: **240**;
- independent C/Python verification and frozen extremizer digest.

### F_73 mixed avoidance

`unpublished-math-papers/f73-mixed-avoidance` publishes the exact simultaneous sum-free, product-free and nontrivial-3-AP-free classification in `F_73^×`:

- maximum: **12**;
- exactly **3** extremizers;
- minimum transversal: **60**;
- 7,422 forbidden edges;
- independent exhaustive verification.

### F_31 simultaneous sum/product avoidance — recovered release-day miss

A distinct MathFire final artifact contained a pure theorem that was absent from the public GitHub estate until this sweep. It is now released at `unpublished-math-papers/f31-sum-product-avoidance/` with README, exact C verifier, certificate and novelty dossier.

For `A subset F_31*`, if no `x,y,z in A` (repetitions allowed) satisfy `x+y=z` or `xy=z` modulo 31, then

`|A| <= 8`.

The bound is sharp, with exactly **9** extremizers. The independent verifier explores 8,421 valid search states and reproduces the complete size distribution, including zero valid 9-sets. Canonical extremizer digest:

`9e8335483eecaf3e5e7dcb747053613dabf848c24734126330551d5327901d17`.

This is exactly the kind of omission the saturation sweep is designed to catch. The novelty wording remains qualified: apparently new after systematic search, to the best of our knowledge.

### Rank-three kernel / K4-free fiber-coherence extraction

A focused public extraction is now at `unpublished-math-papers/rank-three-kernel/`.

The source packet contains **24 theorem/target cards**: **22 unconditional mathematical results/reductions** and **2 explicitly unproved rank-four targets**. The central classification is:

> every finite simple 2-connected graph of cyclomatic number three, after suppression of maximal degree-two paths, has loopless 2-connected kernel exactly one of `Q4`, `T221`, `D22`, or `K4`.

The packet then gives the exact relation/CSP mechanisms for those four kernels, a universal K4-free realization of finite binary relations and finite binary CSPs, an NP-completeness result for unbounded-rank K4-free fiber coherence, fixed-rank `O(d^r poly(N))` tractability, and exact K4 repair/deletion profiles.

Historical novelty and Lean formalization were both `UNRUN` in the source packet; the release does not upgrade either. Erdős #500, #595 and #738 remain open.

### Fourteen-runner wall / LRC(13) terminal estate

The `lonely-runner-13/` public home has now been expanded with the final reference-safe 14-runner-wall assets:

- `LRC14-THEOREM-BANK.json` — 18 live theorem statements plus the exact false dependency, downstream retractions, negative gold and open terminal-saturation obligations;
- `LRC14-ROUND22-TERMINAL-NORMAL-FORM.md` — strict deletion, primitive-deletion, exact gcd-budget, power-gcd, transition-cover and degree-two Riesz restrictions;
- `LRC14-FINAL-THEOREM-SUPPLEMENT.json` — quantitative finite/grid/gcd bounds and the exact remaining obligation.

The release explicitly says **LRC(13) is not closed**. Among the terminal restrictions, every hypothetical counterexample has a primitive non-tight 12-speed deletion, obeys the finite bound `91^12 = 322475487413604782665681`, and must admit a nonzero additive relation with coefficients in `{-2,-1,0,1,2}`. The remaining named throat is the **Primitive Non-Tight Extension Lemma**.

### Other large subject banks already public and now indexed correctly

The saturation pass verified that substantial subject extractions already existed but were underrepresented by the stale top-level README. These include:

- Erdős #738: 62 `PROVED_IN_PACKET` statements/schemas plus 12 explicit unproved targets, full split reconstruction and verifier;
- Erdős #500 / Turán (3,4): 76 theorem-forge cards;
- Erdős #271 Stanley sequences: 184 audited entries;
- graph/CSP fiber-coherence theorem bank: nine major theorem packets;
- Erdős–Gyárfás power-cycle theorem forge;
- P6 six-vertex-wall theorem/candidate/negative ledgers;
- Caccetta–Häggkvist CH3 theorem ledger;
- RH terminal encirclement reductions, with RH explicitly still open;
- Lonely Runner 13 effective-speed campaign and late theorem bank;
- prime-gap admissibility packet;
- MathFire Round 8 / Round 10 theorem outputs and verification receipts.

## Publication firewall

The following remain excluded from automatic raw release even when they contain equations or theorem-shaped statements:

- biomedical diagnosis/monitoring/prognosis/treatment/control embodiments;
- patient-state coupling/Jacobian/susceptibility inventions;
- digital-twin pharmacology machinery;
- patent claim language, continuations and unpublished embodiments;
- energy/grid/battery commercial implementations;
- proprietary game/product implementations;
- private corpora, credentials, infrastructure and business logic;
- mixed research-system architecture where raw publication would surrender load-bearing IP.

Pure standalone mathematics inside such sources may still be extracted to a public mathematical home.

## Status

**Release Day is active; estate saturation is not yet declared.**

A source is terminal only when it is explicitly one of:

- `PUBLIC_SUBJECT`
- `PUBLIC_MINE`
- `PUBLIC_HISTORICAL`
- `SUBSUMED`
- `QUARANTINED_MIXED_IP`

`PENDING_SOURCE_AUDIT` is temporary and must be driven to zero before the estate is called saturated.
