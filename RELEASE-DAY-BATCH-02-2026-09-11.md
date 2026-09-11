# Release Day — Batch 02

**Date:** 2026-09-11  
**Author:** Jared Wilder  
**Status:** active excavation; **not saturated**

This batch exists because the public repository list was materially smaller than the recoverable mathematics in the Library/atlas estate.

## Newly released subject mathematics

### 1. Rank-three kernel / K4-free fiber coherence

Public home: `jaredwilder/unpublished-math-papers/rank-three-kernel/`

Recovered source: 24 theorem/target cards, with 22 unconditional mathematical results/reductions and two explicitly unproved rank-four targets. The release includes the four-kernel classification `Q4/T221/D22/K4`, exact kernel-relation reductions, K4-free realization of arbitrary finite binary relations/CSPs, the fixed-rank tractability versus unbounded-rank NP-completeness boundary, and exact K4 deletion/repair profiles.

Commits:
- `d17a16e6077d4a35ce65fe0cc6b680e1321aebd3`
- `e35aa1848a9bbd97df091ffb42ff2524922cc9ce`

Historical novelty and Lean status remain unupgraded; the two rank-four targets remain open.

### 2. F_31 simultaneous sum/product avoidance

Public home: `jaredwilder/unpublished-math-papers/f31-sum-product-avoidance/`

Recovered from a distinct MathFire final artifact that had no proper public subject home.

Exact theorem: if `A subset F_31*` contains no `x,y,z` (repetitions allowed) with either `x+y=z` or `xy=z` modulo 31, then `|A|<=8`. The bound is sharp with exactly nine extremizers. The independent C verifier reproduces the complete size distribution and zero size-nine sets.

Commits:
- `3543cc7ce51222935c3e22e0c9017f21bb4d473f`
- `1b58bcfcc026ca48cf79519cc2fc573910fd8ec2`
- `d4054ff435acd0a8c5e51813ee774deb3da6a225`
- `782f7f3988aca4db9e336352c25caae46f89cda0`

Novelty remains qualified as apparently new after systematic search, to the best of our knowledge.

### 3. Fourteen-runner-wall terminal estate

Public home: `jaredwilder/unpublished-math-papers/lonely-runner-13/`

Newly surfaced files:
- `LRC14-THEOREM-BANK.json`
- `LRC14-ROUND22-TERMINAL-NORMAL-FORM.md`
- `LRC14-FINAL-THEOREM-SUPPLEMENT.json`

The release preserves the Round-14 false-reference dependency and downstream retractions. The full LRC(13) target remains open. The terminal normal form records strict deletion, primitive-deletion, exact gcd-budget, majority-gcd, transition-cover and Riesz/additive-dependence restrictions. The remaining named throat is the Primitive Non-Tight Extension Lemma.

Commits:
- `ba246a7e0444a7b5ce85cb041e55ca30a538d08b`
- `7eac4588b7c1520eb790468c0be42faa4dbd1ff3`
- `900fcc396edd371809bac912e9faed4cbd864160`

### 4. Signed sparse exact encoding theorem patch

Public home: `jaredwilder/additive-combinatorics-campaigns/signed-sparse-encodings/`

Recovered and released:
- shifted `B_s` exact encoding of ternary signed support-`s` vectors;
- optimal ternary signed sparse scale `Theta_s(m^s)`;
- support-three corollary `Theta(m^3)`;
- bounded coefficient constructive upper bound `O_{A,s}(m^(As))`.

Commits:
- `0db45534837d501b2928ca33a2e435a30b012ce4`
- `3710f816440d5cf7efdf000d7ad14bb4ca92740c`
- README index update `d1fd2b57dde105e66b74d100eaa6518153b48ddc`

Classical `B_s` inputs are disclosed. Historical novelty of the exact signed formulations is not claimed. The stronger exponent conjecture for general coefficient magnitude `A>=2` remains open.

### 5. Carry-free / sparse additive encoding mathematics extracted from mixed systems source

Public home: `jaredwilder/additive-combinatorics-campaigns/carry-free-encoding/`

This is a firewall-aware extraction: the standalone mathematics was published while verifier/authentication/worker/deployment architecture was intentionally not copied.

The 22-result ledger includes:
- sharp bounded-residue zero detection and balanced-cube injectivity thresholds;
- adjacent-carry generation of the full positional integer kernel;
- sharp relation localization and integer-polynomial evaluation thresholds;
- full-box output-span lower bounds, positional optimality/rigidity and heterogeneous mixed-radix extremality;
- sparse moment uniqueness and carry-free sparse moment encoding;
- finite-field sparse syndrome injectivity plus the corrected scope of the `2s` measurement lower bound;
- binary sparse additive counting, shifted `B_s` encoding and `Theta_s(m^s)` optimal exponent;
- signed support-two counting, shifted Sidon encoding and `Theta(m^2)` optimal exponent.

Commits:
- `aea211c86e5b7eda310960c4f656a066ed04f305`
- `2bd5c0b7d5b95538e1a91ebfdb3505f0e631637b`
- root README index update `631ada53fa298170f7cfc7c487e3803a52f97803`

The source itself labels most of these as classical/elementary/near-classical; the release preserves that and makes no automatic novelty claim.

## Repository hygiene repaired

The top-level `unpublished-math-papers/README.md` was stale and still described the repository as five writeups despite the release tree containing a large subject archive. It has been replaced with an actual subject index and authority-boundary statement.

Commit: `766dc0fe2edeec7d6fa2c5d77e8b727d3df895ab`

## Why saturation is still not declared

The estate atlas alone contains 1,770 theorem/negative-theorem nodes distributed across dozens of source domains. Many large pure-math domains are already publicly represented, while mixed domains remain behind the publication firewall. The remaining work is not just counting rows: every recoverable source must be mapped to `PUBLIC_SUBJECT`, `PUBLIC_MINE`, `PUBLIC_HISTORICAL`, `SUBSUMED`, or `QUARANTINED_MIXED_IP` without losing stronger scope variants or publishing protected application architecture.

Current high-value audit queue includes the remaining long-tail source domains, historical/retraction packages, source-level formalizer ore, and any theorem-bank artifact whose mathematics is present in the Library but not yet represented in a public subject tree.
