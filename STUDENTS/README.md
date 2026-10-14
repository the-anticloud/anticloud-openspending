# Students — OPENSPENDING

**Project:** OPENSPENDING  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `aac0e3ae6b3aac7f07d462ec2bf30c9b393e97e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `aac0e3ae6b3aac7f07d462ec2bf30c9b393e97e1`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
