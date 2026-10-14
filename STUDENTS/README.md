# Students — CARAVEL

**Project:** CARAVEL  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `27cbe49c90ba5362ad52c9968dd98e035c30c74f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `27cbe49c90ba5362ad52c9968dd98e035c30c74f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
