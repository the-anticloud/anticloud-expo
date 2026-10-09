# Educators — EXPO

**Project:** EXPO  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `53f6e12780bc746a3f0b9d12decd3cde22653073`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `0aea881dfd12bb174c887a11374a59a09b38659b021302835bdf3b59837a17cb`  
**Date:** October 2026

## Teaching with EXPO

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `0aea881dfd12bb174c887a11374a59a09b38659b021302835bdf3b59837a17cb` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
