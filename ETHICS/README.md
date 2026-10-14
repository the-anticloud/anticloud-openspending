# Ethics — OPENSPENDING

**Project:** OPENSPENDING  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `aac0e3ae6b3aac7f07d462ec2bf30c9b393e97e1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `41bd316746f33a726eb06f252c9e4dd15ef8da4805101137567f0be25825abf2`  
**Date:** October 2026

## Position

OPENSPENDING is packaged for offline deployment with a verifiable audit trail. The
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
