# Educators — OPENMODELICA

**Project:** OPENMODELICA  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** https://github.com/OpenModelica/OpenModelica  
**Pinned commit:** `e3a6e9ed55db4e01168020cb96d571fed6c8fb05`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2826c4568d1bb1272404511b30e633c627bdedc443941b282189e5b643e15ea3`  
**Date:** October 2026

## Teaching with OPENMODELICA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `2826c4568d1bb1272404511b30e633c627bdedc443941b282189e5b643e15ea3` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
