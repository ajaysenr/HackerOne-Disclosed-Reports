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
| **Total Reports** | 12,517 |
| **With Bounty** | 2,325 |
| **With CVE** | 1,971 |
| **Total Bounty Paid** | $3,941,499 |
| **Critical** | 1,002 |
| **High** | 1,951 |
| **Medium** | 3,556 |
| **Low** | 2,267 |

*Last Updated: September 19, 2026 at 01:26 AM EST*

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

- `reports.txt` — discovered URL + title list (12,404 unique reports)
- `index.json` — structured metadata (12,517 enriched reports)
- `reports/` — individual markdown page per report

