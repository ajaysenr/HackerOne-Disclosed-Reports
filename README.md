# HackerOne Disclosed Reports

A structured, auto-updated database of publicly disclosed HackerOne vulnerability reports.

## 🌐 Web Dashboard

Use the interactive dashboard to search reports and filter them by severity, year, program, bounty, CVE, weakness, or disclosure date.

**[Open the HackerOne Disclosed Reports dashboard →](https://h1.ajaysenr.com/)**

### Dashboard overview

[![HackerOne Disclosed Reports dashboard overview](assets/dashboard-overview.png)](https://h1.ajaysenr.com/)

### Report explorer

[![HackerOne Disclosed Reports report explorer](assets/report-explorer.png)](https://h1.ajaysenr.com/)

## 📊 Statistics

| Metric | Count |
|---|---|
| **Total Reports** | 12,638 |
| **With Bounty** | 2,337 |
| **With CVE** | 2,015 |
| **Total Bounty Paid** | $3,963,799 |
| **Critical** | 1,008 |
| **High** | 1,973 |
| **Medium** | 3,593 |
| **Low** | 2,288 |

*Last Updated: October 19, 2026 at 11:50 PM EST*

## 📁 Browse

| Category | Description |
|---|---|
| [By Severity](by-severity/) | critical / high / medium / low / none |
| [By Weakness](by-weakness/) | CWE-based vulnerability categories |
| [By Program](by-program/) | One page per bug bounty program |
| [By Asset Type](by-asset-type/) | URL / Source Code / Android / iOS / Hardware / ... |
| [By Year](by-year/) | Chronological disclosure timeline |
| [Top Reports](top-reports/) | Ranked by votes, bounty, CVSS, CVE |
| [Top Researchers](top-researchers/) | Leaderboards by count, bounty, votes |
| [Curated](curated/) | Perfect CVSS 10.0 / Hall of Fame / High-sev no bounty |

## 📄 Data

- `reports.txt` — discovered URL + title list (12,509 unique reports)
- `index.json` — structured metadata (12,638 enriched reports)
- `reports/` — individual markdown page per report

