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

### Erdős–Straus arithmetic-progression classification

[`unpublished-math-papers/erdos-straus-progressions`](https://github.com/jaredwilder/unpublished-math-papers/tree/main/erdos-straus-progressions) now publishes a standalone pure-mathematics extraction from the MathFire estate:

> all positive solutions of `4/n = 1/x + 1/y + 1/z` whose strictly increasing denominators form an arithmetic progression are parameterized uniquely by coprime `a>d>0` and a positive scale `t`, with the exact parity split through `D=3a²-d²`; no primitive denominator triple occurs.

The directory includes the symbolic derivation, an independent exact-arithmetic verifier, a machine-readable certificate and a qualified novelty dossier. The independent regression sweep checked 76,115 coprime parameter pairs and 456,690 constructed solutions. Historical novelty is stated only as `apparently_new_after_systematic_search` (search date 2026-07-27), not as an absolute claim.

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
