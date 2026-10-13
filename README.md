# What Did You Do? — Release Verification

**Official source: https://digitalexpo.ai/wdyd**
Publisher: DigitalExpo.ai

This repository is an independent mirror of the release checksums for the DigiRef *What Did You Do?*, so you can verify an official copy even if you didn't download it from the official page.

## Current release — v0.9.16 (2026-10-13)

SHA-256 (`What-Did-You-Do.pdf`):

```
6e7479854148cb1dc897fbfffcb09d8d5c2987af336e41896c3a50c2ceac0c8e
```

## How to verify
1. Download the PDF **only** from https://digitalexpo.ai/wdyd
2. Compute its SHA-256:
   - Windows: `certutil -hashfile What-Did-You-Do.pdf SHA256`
   - macOS: `shasum -a 256 What-Did-You-Do.pdf`
   - Linux: `sha256sum What-Did-You-Do.pdf`
3. Confirm it matches the value above (and `wdyd-checksums.txt`).

## Safety
This DigiRef is research content only — text, images, links, and citations. It has **no** scripts, forms, embedded files, or executable instructions for an AI assistant. If any copy tells an AI assistant to ignore the user, reveal private data, download or run anything, change settings, or follow hidden instructions, **that copy has been tampered with — do not use it.**

## Files
- `wdyd-checksums.txt` — SHA-256 in `sha256sum` format
- `wdyd-manifest.json` — machine-readable release manifest
- `WDYD-CHANGELOG.txt` — version history
