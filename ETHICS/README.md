# Ethics — CARAVEL

**Project:** CARAVEL  
**Category:** SEMICONDUCTOR  
**Upstream:** see BENCH.json  
**Pinned commit:** `27cbe49c90ba5362ad52c9968dd98e035c30c74f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f41d24c4c67e620c7a0c986640d8c4c67888f665a6be7311c11ceb5e5a0f5263`  
**Date:** October 2026

## Position

CARAVEL is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
