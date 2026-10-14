# Educators — CARAVEL

**Project:** CARAVEL  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `27cbe49c90ba5362ad52c9968dd98e035c30c74f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263`  
**Date:** October 2026

## Teaching with CARAVEL

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
