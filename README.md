# P.E.S.T
PEST – Portable Enumeration &amp; Security Toolkit

## Architecture

```text
pest/
├── pest.py                # Entry point / CLI interface
├── core/
│   ├── preflight.py       # Environment validation + safety checks
│   ├── parse_nmap.py      # XML parsing logic
│   ├── findings.py        # Structured findings generation
├── modules/
│   ├── nmap_scan.py       # Recon execution module
├── reporting/
│   ├── markdown.py        # Report generation engine
└── output/                # Target-specific artifacts (excluded from git)
