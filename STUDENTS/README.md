# Students — DISCOART

**Project:** DISCOART  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/jina-ai/discoart  
**Pinned commit:** `03946299dd2781215a01c690c86ccd13e0f65c80`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a3ba6ab0e4911883db32521c3e114fd01e8a401d1163177f879e061ec36590fe`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `03946299dd2781215a01c690c86ccd13e0f65c80`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `a3ba6ab0e4911883db32521c3e114fd01e8a401d1163177f879e061ec36590fe`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
