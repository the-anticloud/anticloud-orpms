# Students — ORPMS

**Project:** ORPMS  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/orpms/orpms  
**Pinned commit:** `61da1571e7a79de5dbbdcd4c4672602c237110b6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bdb53e70688c3956c379422ae8ef77336070c13d058981bd897a660673d86b76`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `61da1571e7a79de5dbbdcd4c4672602c237110b6`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `bdb53e70688c3956c379422ae8ef77336070c13d058981bd897a660673d86b76`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
