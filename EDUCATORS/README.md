# Educators — DISCOART

**Project:** DISCOART  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/jina-ai/discoart  
**Pinned commit:** `03946299dd2781215a01c690c86ccd13e0f65c80`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a3ba6ab0e4911883db32521c3e114fd01e8a401d1163177f879e061ec36590fe`  
**Date:** October 2026

## Teaching with DISCOART

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a3ba6ab0e4911883db32521c3e114fd01e8a401d1163177f879e061ec36590fe` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
