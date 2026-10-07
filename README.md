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
| **Total Reports** | 12,556 |
| **With Bounty** | 2,334 |
| **With CVE** | 1,978 |
| **Total Bounty Paid** | $3,959,599 |
| **Critical** | 1,003 |
| **High** | 1,961 |
| **Medium** | 3,573 |
| **Low** | 2,271 |

*Last Updated: October 07, 2026 at 01:04 PM EST*

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

- `reports.txt` — discovered URL + title list (12,427 unique reports)
- `index.json` — structured metadata (12,556 enriched reports)
- `reports/` — individual markdown page per report

