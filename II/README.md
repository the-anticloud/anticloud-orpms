# Independent Insurance — ORPMS

**Project:** ORPMS  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/orpms/orpms  
**Pinned commit:** `61da1571e7a79de5dbbdcd4c4672602c237110b6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `bdb53e70688c3956c379422ae8ef77336070c13d058981bd897a660673d86b76`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | ORPMS with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `bdb53e70688c3956c379422ae8ef77336070c13d058981bd897a660673d86b76`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
