# Independent Insurance — CARAVEL

**Project:** CARAVEL  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `27cbe49c90ba5362ad52c9968dd98e035c30c74f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | CARAVEL with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
