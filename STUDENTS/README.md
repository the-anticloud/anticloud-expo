# Students — EXPO

**Project:** EXPO  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `53f6e12780bc746a3f0b9d12decd3cde22653073`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0aea881dfd12bb174c887a11374a59a09b38659b021302835bdf3b59837a17cb`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `53f6e12780bc746a3f0b9d12decd3cde22653073`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `0aea881dfd12bb174c887a11374a59a09b38659b021302835bdf3b59837a17cb`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
