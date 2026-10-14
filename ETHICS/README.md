# Ethics — DISCOART

**Project:** DISCOART  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/jina-ai/discoart  
**Pinned commit:** `03946299dd2781215a01c690c86ccd13e0f65c80`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a3ba6ab0e4911883db32521c3e114fd01e8a401d1163177f879e061ec36590fe`  
**Date:** October 2026

## Position

DISCOART is packaged for offline deployment with a verifiable audit trail. The
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
