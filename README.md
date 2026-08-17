# Goodfellas

A Python CLI tool for IOC (Indicator of Compromise) enrichment using the VirusTotal API. Built as part of my SOC analyst portfolio.

## What it does

Takes an indicator (starting with IP addresses in v1) and queries VirusTotal for reputation data, returning a clear, color-coded verdict in the terminal — no need to manually check each IOC on the VirusTotal website.

## Status

🚧 In active development — v1 in progress.

## Roadmap

- [ ] v1: Single IP lookup via VirusTotal v3 API, color-coded verdict output (malicious / suspicious / clean)
- [ ] v2: Support for domains, URLs, and file hashes
- [ ] v3: Bulk scanning from a file (CSV/TXT list of IOCs)
- [ ] v4: Export results (CSV/JSON report)

## Tech Stack

- Python 3
- `requests` — VirusTotal API calls
- `argparse` — CLI interface
- `colorama` (or ANSI codes) — terminal color output

## Usage (planned)

```bash
python goodfellas.py --ip 8.8.8.8
```

## Why "Goodfellas"

Because good IOC triage means knowing exactly who the bad guys are before they cause damage.

## Author

Aditya — BSc IT student, aspiring SOC Analyst.
[LinkedIn](https://linkedin.com/in/aditya-kumar-tripathi28/) · [TryHackMe](https://tryhackme.com/p/Aditya.Tripathi)
