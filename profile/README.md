<h1 align="center">Cognis Digital</h1>
<p align="center"><b>Verifiable, self-hostable defense &amp; security intelligence.</b><br>
<i>Built and proven, not promised — every tool public, CI-verified, and honest about its limits.</i></p>

<p align="center">
<img alt="repos" src="https://img.shields.io/badge/tools-open%20%26%20verified-6D28D9">
<img alt="license" src="https://img.shields.io/badge/license-COCL%20v1.0-6D28D9">
<img alt="deps" src="https://img.shields.io/badge/dependencies-none%20(stdlib)-6D28D9">
<img alt="ci" src="https://img.shields.io/badge/CI-green%20·%20Python%203.9–3.13-3FB950">
</p>

---

We build single-purpose intelligence tools you can **run yourself** — offline, air-gapped, zero-dependency — with **reproducible metrics gated in CI**. No cloud lock-in, no data egress, no black boxes. Each repo ships a CLI, structured output, tests, and a `bench/run_all.py` that regenerates the numbers in its `RESULTS.md`.

### 🔴 Watch a detector work — live, in your browser
**[CA-CFAR small-target detection demo →](https://claude.ai/code/artifact/c38c3d70-3f90-4993-ada7-f3a129d2d3a7)** — hide a one-pixel target in clutter, then watch it get found; stack frames to recover it when it's buried below the noise. Runs entirely client-side.

## The suite

| Tool | Mission | Verified highlights |
|---|---|---|
| **[cognis-lattice](https://github.com/cognis-digital/cognis-lattice)** | Counter-threat-finance attribution & fusion | 61 intel sources · **17 blockchains** traced live · STIX + MISP · F1 1.00 (clean) |
| **[cognis-vanguard](https://github.com/cognis-digital/cognis-vanguard)** | Self-hosted multi-INT fusion for the edge | 14 live feeds · provenance graph · LLM + vision backends |
| **[cognis-vigil](https://github.com/cognis-digital/cognis-vigil)** | Multi-domain ISR + **search & rescue** *(non-kinetic)* | dark-contact cross-cue · **1-px swimmer detection** · SNR stacking · ROC |
| **[cognis-lookout](https://github.com/cognis-digital/cognis-lookout)** | Geospatial change & **wide-area search** *(non-kinetic)* | change F1 1.00 · **lost-hiker detection** · georeferenced heatmaps |
| **[cognis-harvest](https://github.com/cognis-digital/cognis-harvest)** | Illicit-crop detection & yield estimation | spectral + SAR fallback · area CIs · yield modeling |
| **[cognis-relay](https://github.com/cognis-digital/cognis-relay)** | BLOS PACE communications resilience | PACE validation · failover sim · no-pLEO enforcement |

## What we stand for

- **Self-hostable & offline.** Air-gap capable, zero third-party dependencies. Your data never leaves your enclave.
- **Verifiable.** Reproducible ground-truth metrics, gated in continuous integration across Python 3.9–3.13.
- **Honest scope.** Detection, monitoring, OSINT, counter-threat-finance, communications — explicitly **non-kinetic**. We publish what our tools *don't* do and what formal military acceptance still requires (see each repo's `docs/COMPLIANCE.md`). We do not build weapons, targeting, or autonomous drone guidance.
- **Standards-native.** STIX 2.1, MISP, GeoJSON, SARIF, OSCAL — outputs drop into the systems teams already run.

<p align="center"><sub>Cognis Digital LLC · Wyoming · Source-available under COCL v1.0 · <a href="https://cognis.digital">cognis.digital</a> · admin@cognis.digital</sub></p>
