# Educators — OPENSPENDING

**Project:** OPENSPENDING  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `aac0e3ae6b3aac7f07d462ec2bf30c9b393e97e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2`  
**Date:** October 2026

## Teaching with OPENSPENDING

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
