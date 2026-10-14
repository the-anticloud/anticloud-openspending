# Independent Insurance — OPENSPENDING

**Project:** OPENSPENDING  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `aac0e3ae6b3aac7f07d462ec2bf30c9b393e97e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | OPENSPENDING with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
