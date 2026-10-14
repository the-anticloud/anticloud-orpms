# Educators — ORPMS

**Project:** ORPMS  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/orpms/orpms  
**Pinned commit:** `61da1571e7a79de5dbbdcd4c4672602c237110b6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bdb53e70688c3956c379422ae8ef77336070c13d058981bd897a660673d86b76`  
**Date:** October 2026

## Teaching with ORPMS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `bdb53e70688c3956c379422ae8ef77336070c13d058981bd897a660673d86b76` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
