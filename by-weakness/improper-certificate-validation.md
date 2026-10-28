# Weakness: Improper Certificate Validation (66 reports)

*Sorted by bounty amount, then severity, then votes.*

| # | Report | Title | Program | Severity | Bounty | Votes |
|---|---|---|---|---|---|---|
| 1 | [2435482](../reports/2435482.md) | CVE-2024-2466: TLS certificate check bypass with mbedTLS (reward  | [Internet Bug Bounty](../by-program/ibb.md) | Medium — CVSS 5.3 | $2,580 | 48 |
| 2 | [1455411](../reports/1455411.md) | Invalid handling of X509_verify_cert() internal errors in libssl  | [Internet Bug Bounty](../by-program/ibb.md) | Medium | $1,200 | 3 |
| 3 | [1599063](../reports/1599063.md) | Undici ProxyAgent vulnerable to MITM  | [Internet Bug Bounty](../by-program/ibb.md) | High — CVSS 7.4 | $1,000 | 5 |
| 4 | [1679267](../reports/1679267.md) | Desktop client does not verify received singed certificate in end | [Nextcloud](../by-program/nextcloud.md) | Medium — CVSS 5.4 | $1,000 | 13 |
| 5 | [2437050](../reports/2437050.md) | CVE-2024-2379: QUIC certificate check bypass with wolfSSL | [Internet Bug Bounty](../by-program/ibb.md) | Low | $560 | 37 |
| 6 | [3253725](../reports/3253725.md) | SameSite restrictions are lifted, and SameSite:Strict cookie are  | [Brave Software](../by-program/brave.md) | High — CVSS 8.3 | $500 | 70 |
| 7 | [1056144](../reports/1056144.md) | Acronis True Image  (Windows) does not validate server certificat | [Acronis](../by-program/acronis.md) | High — CVSS 7.4 | $500 | 34 |
| 8 | [1070533](../reports/1070533.md) | Acronis True Image 2021 (windows) does not validate server hostna | [Acronis](../by-program/acronis.md) | High — CVSS 7.4 | $250 | 18 |
| 9 | [1278254](../reports/1278254.md) | Built-in TLS module unexpectedly treats "rejectUnauthorized: unde | [Node.js](../by-program/nodejs.md) | Low | $150 | 20 |
| 10 | [746733](../reports/746733.md) | Remotely trigger an assertion on a TLS server with a malformed ce | [Node.js](../by-program/nodejs.md) | Critical — CVSS 9.3 | — | 15 |
| 11 | [3418776](../reports/3418776.md) | Silent TLS Trust Model Hijacking via `CURL_CA_BUNDLE` Environment | [curl](../by-program/curl.md) | Critical | — | 11 |
| 12 | [293358](../reports/293358.md) | The Microsoft Store Uber App Does Not Implement Certificate Pinni | [Uber](../by-program/uber.md) | Critical | — | 7 |
| 13 | [329645](../reports/329645.md) | Silent omission of certificate hostname verification in LibreSSL  | [Internet Bug Bounty](../by-program/ibb.md) | Critical — CVSS 9.1 | — | 4 |
| 14 | [3374554](../reports/3374554.md) | Apple SecTrust legacy path accepts untrusted certificates on pre- | [curl](../by-program/curl.md) | High | — | 30 |
| 15 | [2961050](../reports/2961050.md) | curl allows SSH connection even if host is not in known_hosts | [curl](../by-program/curl.md) | High | — | 11 |
| 16 | [4038287](../reports/4038287.md) | TLS certificate hostname bypass when the IP is written fullwidth  | [Node.js](../by-program/nodejs.md) | High — CVSS 7.4 | — | 4 |
| 17 | [1583680](../reports/1583680.md) | Undici does not use CONNECT or otherwise validate upstream HTTPS  | [Node.js](../by-program/nodejs.md) | High — CVSS 7.4 | — | 4 |
| 18 | [4006744](../reports/4006744.md) | TLS certificate hostname bypass when the host loosely resolves to | [Node.js](../by-program/nodejs.md) | High — CVSS 7.4 | — | 3 |
| 19 | [3784125](../reports/3784125.md) | GnuTLS OCSP stapling accepts unrelated SingleResponse (no cert-ID | [curl](../by-program/curl.md) | High | — | 3 |
| 20 | [3686259](../reports/3686259.md) | `set_daemon` wallet-rpc silently ignores `ssl_allowed_fingerprint | [Monero](../by-program/monero.md) | High — CVSS 7.7 | — | 2 |
| 21 | [713975](../reports/713975.md) | Only OpenSSL handles a CRL when passed in via CApath  | [curl](../by-program/curl.md) | High | — | 0 |
| 22 | [3153497](../reports/3153497.md) | CVE-2025-5025: No QUIC certificate pinning with wolfSSL | [curl](../by-program/curl.md) | Medium | — | 54 |
| 23 | [1048457](../reports/1048457.md) | CVE-2020-8286: Inferior OCSP verification | [curl](../by-program/curl.md) | Medium — CVSS 6.6 | — | 51 |
| 24 | [2669852](../reports/2669852.md) | CVE-2024-8096: OCSP stapling bypass with GnuTLS | [curl](../by-program/curl.md) | Medium | — | 36 |
| 25 | [2597504](../reports/2597504.md) | X-E2EE-SIGNATURE verification can be bypassed, leading to loss of | [Nextcloud](../by-program/nextcloud.md) | Medium — CVSS 4.2 | — | 27 |
| 26 | [3694390](../reports/3694390.md) | CVE-2026-7009: OCSP stapling bypass with Apple SecTrust | [curl](../by-program/curl.md) | Medium | — | 23 |
| 27 | [3455037](../reports/3455037.md) | Certificate Hostname Validation Bypass via Leading Dot in Hostnam | [curl](../by-program/curl.md) | Medium | — | 17 |
| 28 | [387250](../reports/387250.md) | OpenSSL::X509::Name Equality Check Does Not Work, Patch included | [Ruby](../by-program/ruby.md) | Medium | — | 11 |
| 29 | [803734](../reports/803734.md) | Mail does not verify IMAP/SMTP host connected via TLS | [Nextcloud](../by-program/nextcloud.md) | Medium — CVSS 5.9 | — | 9 |
| 30 | [3468098](../reports/3468098.md) | Certificate Pinning Bypass with wolfSSL backend over HTTP/3 | [curl](../by-program/curl.md) | Medium | — | 7 |
| 31 | [3966955](../reports/3966955.md) | TLS session cache case-folds CA paths and bypasses the active tru | [curl](../by-program/curl.md) | Medium | — | 6 |
| 32 | [915585](../reports/915585.md) | Social App does not validate server certificates for outgoing con | [Nextcloud](../by-program/nextcloud.md) | Medium — CVSS 5.4 | — | 4 |
| 33 | [3633146](../reports/3633146.md) | Sandbox User Can Inject Rogue CA Certificate into OS Trust Store  | [AWS VDP](../by-program/aws_vdp.md) | Medium | — | 3 |
| 34 | [980249](../reports/980249.md) | Net::SMTP with tls allows forged certificates as long as the host | [Ruby](../by-program/ruby.md) | Medium | — | 3 |
| 35 | [285153](../reports/285153.md) | No Email Verification | [Infogram](../by-program/infogram.md) | Medium | — | 3 |
| 36 | [3752567](../reports/3752567.md) | curl GnuTLS backend accepts a clientAuth-only certificate for HTT | [curl](../by-program/curl.md) | Medium | — | 1 |
| 37 | [4128428](../reports/4128428.md) | CVE-2026-115528: wolfSSL TLS connect without cert | [curl](../by-program/curl.md) | Medium | — | 1 |
| 38 | [3989514](../reports/3989514.md) | CVE-2026-87866: wolfSSL public-key pinning bypass | [curl](../by-program/curl.md) | Medium | — | 1 |
| 39 | [813279](../reports/813279.md) | Lets Encrypt Certificates affected by CAA Rechecking Incident | [Endless Group](../by-program/endless_group.md) | Medium — CVSS 6.1 | — | 1 |
| 40 | [4127399](../reports/4127399.md) | wolfSSL Backend Silently Ignores --cert-status (OCSP Stapling Byp | [curl](../by-program/curl.md) | Medium | — | 0 |
| 41 | [4129642](../reports/4129642.md) | HSTS cache file: three trailing dots silently disable HSTS for th | [curl](../by-program/curl.md) | Medium | — | 0 |
| 42 | [4129638](../reports/4129638.md) | TLS session cache ignores CURLOPT_SSL_CTX_FUNCTION identity and r | [curl](../by-program/curl.md) | Medium | — | 0 |
| 43 | [3962304](../reports/3962304.md) | Improper certificate validation for non-canonical IPv4 hostnames  | [Node.js](../by-program/nodejs.md) | Medium — CVSS 6.7 | — | 0 |
| 44 | [4118610](../reports/4118610.md) | CVE-2026-111484: OpenSSL with SecTrust accepts bad OCSP staples | [curl](../by-program/curl.md) | Medium | — | 0 |
| 45 | [4124276](../reports/4124276.md) | GnuTLS + Apple SecTrust discards authenticated OCSP failure | [curl](../by-program/curl.md) | Medium | — | 0 |
| 46 | [3355218](../reports/3355218.md) | CVE-2025-10966: missing SFTP host verification with wolfSSH | [curl](../by-program/curl.md) | Low | — | 43 |
| 47 | [2410774](../reports/2410774.md) | CVE-2024-2379: QUIC certificate check bypass with wolfSSL | [curl](../by-program/curl.md) | Low | — | 11 |
| 48 | [1699740](../reports/1699740.md) | nextcloudcmd incorrectly trusts bad TLS certificates | [Nextcloud](../by-program/nextcloud.md) | Low — CVSS 2.8 | — | 10 |
| 49 | [1991427](../reports/1991427.md) | CVE-2023-28321: IDN wildcard match | [Internet Bug Bounty](../by-program/ibb.md) | Low | — | 4 |
| 50 | [1950627](../reports/1950627.md) | CVE-2023-28321: IDN wildcard match | [curl](../by-program/curl.md) | Low | — | 2 |
| 51 | [4122227](../reports/4122227.md) | wolfSSL TLS sessions retain native-CA trust after the application | [curl](../by-program/curl.md) | Low | — | 2 |
| 52 | [4128701](../reports/4128701.md) | Pinned public key check passes for a key the server does not hold | [curl](../by-program/curl.md) | Low | — | 2 |
| 53 | [3797526](../reports/3797526.md) | CVE-2026-12064: proto-default skips SSH verification | [curl](../by-program/curl.md) | Low | — | 2 |
| 54 | [3752888](../reports/3752888.md) | CVE-2026-9545: exposing HTTP/3 early data | [curl](../by-program/curl.md) | Low | — | 1 |
| 55 | [294891](../reports/294891.md) | Improper Certificate Validation | [PortSwigger Web Security](../by-program/portswigger.md) | Low — CVSS 2.6 | — | 0 |
| 56 | [4123304](../reports/4123304.md) | OpenSSL+Apple SecTrust: SecTrust accepts certificates that the ap | [curl](../by-program/curl.md) | Low | — | 0 |
| 57 | [4123646](../reports/4123646.md) | TLS session cache key omits native_ca_store: a session validated  | [curl](../by-program/curl.md) | Low | — | 0 |
| 58 | [4122300](../reports/4122300.md) | CVE-2026-111953: GnuTLS SecTrust OCSP staple bypass | [curl](../by-program/curl.md) | Low | — | 0 |
| 59 | [894922](../reports/894922.md) | [3DS][SSL] Improper certificate validation allows an attacker to  | [Nintendo](../by-program/nintendo.md) | None | — | 129 |
| 60 | [3739561](../reports/3739561.md) | SSL session-cache peer key omits signature_algorithms: strict-sig | [curl](../by-program/curl.md) | None | — | 4 |
| 61 | [3973111](../reports/3973111.md) | 08: CVE-2026-7009 fix incomplete for AWS-LC: `--cert-status` bypa | [curl](../by-program/curl.md) | None | — | 4 |
| 62 | [3973093](../reports/3973093.md) | 06: Incomplete fix for CVE-2026-7009: GCC/SecTrust builds silentl | [curl](../by-program/curl.md) | None | — | 4 |
| 63 | [3972323](../reports/3972323.md) | 10: CURLOPT_MAXLIFETIME_CONN bypass on active HTTP/2 connections | [curl](../by-program/curl.md) | None | — | 3 |
| 64 | [225540](../reports/225540.md) | Incorrect HTTPS Certificate | [Weblate](../by-program/weblate.md) | None | — | 2 |
| 65 | [3973090](../reports/3973090.md) | CVE-2026-82208: wolfSSL CA-cache hit overrides callback | [curl](../by-program/curl.md) | None | — | 1 |
| 66 | [715413](../reports/715413.md) | curl successfully matches IP address literal in URL against IP ad | [curl](../by-program/curl.md) | None | — | 0 |
