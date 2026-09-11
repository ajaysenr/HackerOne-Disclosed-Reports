# Weakness: Out-of-bounds Read (41 reports)

*Sorted by bounty amount, then severity, then votes.*

| # | Report | Title | Program | Severity | Bounty | Votes |
|---|---|---|---|---|---|---|
| 1 | [584603](../reports/584603.md) | RCE on CS:GO client using unsanitized entity ID in EntityMsg mess | [Valve](../by-program/valve.md) | Critical — CVSS 9.6 | $9,000 | 208 |
| 2 | [807772](../reports/807772.md) | OOB reads in network message handlers leads to RCE | [Valve](../by-program/valve.md) | Critical — CVSS 9.9 | $7,500 | 217 |
| 3 | [1070835](../reports/1070835.md) | CS:GO Server -> Client RCE through OOB access in CSVCMsg_SplitScr | [Valve](../by-program/valve.md) | Critical — CVSS 9.6 | $7,500 | 66 |
| 4 | [675578](../reports/675578.md) | Out of Bounds Memory Read in exif_scan_thumbnail | [Internet Bug Bounty](../by-program/ibb.md) | High — CVSS 8.8 | $1,500 | 20 |
| 5 | [675580](../reports/675580.md) | Out of Bounds Memory Read in exif_process_user_comment | [Internet Bug Bounty](../by-program/ibb.md) | High — CVSS 8.8 | $1,500 | 3 |
| 6 | [633607](../reports/633607.md) | Invalid read in `str_replace_partial` | [shopify-scripts](../by-program/shopify-scripts.md) | None | $1,000 | 7 |
| 7 | [295680](../reports/295680.md) | Invalid read leading to a segfault | [shopify-scripts](../by-program/shopify-scripts.md) | Low | $800 | 5 |
| 8 | [724253](../reports/724253.md) | Tcpdump before 4.9.3 has a buffer over-read in print-dccp.c:dccp_ | [Internet Bug Bounty](../by-program/ibb.md) | Critical — CVSS 9.8 | $500 | 3 |
| 9 | [724243](../reports/724243.md) | Tcpdump before 4.9.3 has a buffer over-read in print-802_11.c (CV | [Internet Bug Bounty](../by-program/ibb.md) | Critical — CVSS 9.8 | $500 | 3 |
| 10 | [200909](../reports/200909.md) | Out of bounds memory read in unserialize() | [Internet Bug Bounty](../by-program/ibb.md) | Medium | $500 | 6 |
| 11 | [1217702](../reports/1217702.md) | Adam and the  Deadly  Injections | [h1-ctf](../by-program/h1-ctf.md) | Critical | — | 13 |
| 12 | [3470095](../reports/3470095.md) | Heap Buffer Over-Read via Malicious SMB Server READ_ANDX Response | [curl](../by-program/curl.md) | High | — | 17 |
| 13 | [456727](../reports/456727.md) | null pointer dereference in imap_mail | [Internet Bug Bounty](../by-program/ibb.md) | High — CVSS 7.5 | — | 13 |
| 14 | [3897914](../reports/3897914.md) | Out-of-bounds read in MariaDB .frm parsing enables RCE via vtable | [MariaDB](../by-program/mariadb.md) | High — CVSS 8.8 | — | 12 |
| 15 | [321692](../reports/321692.md) | `base64-url` below 2.0 allocates uninitialized Buffers when numbe | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | High — CVSS 8.6 | — | 5 |
| 16 | [3506159](../reports/3506159.md) | Heap Out-of-Bounds Read in lib/http2.c via Malformed PUSH_PROMISE | [curl](../by-program/curl.md) | High | — | 5 |
| 17 | [3684614](../reports/3684614.md) | Heap-buffer-overflow in `Curl_ssl_push_certinfo_len()` — sole bou | [curl](../by-program/curl.md) | High | — | 4 |
| 18 | [321687](../reports/321687.md) | `base64url` allocates uninitialized Buffers when number is passed | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | High — CVSS 7.1 | — | 4 |
| 19 | [320269](../reports/320269.md) | `npmconf` (and `npm` js api) allocate and write to disk uninitial | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | High — CVSS 7.4 | — | 3 |
| 20 | [3470073](../reports/3470073.md) | Heap Buffer Over-Read via Malicious SMB Server READ_ANDX Response | [curl](../by-program/curl.md) | Medium | — | 9 |
| 21 | [321686](../reports/321686.md) | `atob` allocates uninitialized Buffers when number is passed in i | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Medium — CVSS 6.5 | — | 5 |
| 22 | [323017](../reports/323017.md) | Two vulnerability in GNU binutils | [Internet Bug Bounty](../by-program/ibb.md) | Medium | — | 4 |
| 23 | [3709605](../reports/3709605.md) | Conflux-queued zero-length RELAY_END triggers heap out-of-bounds  | [Tor](../by-program/torproject.md) | Medium — CVSS 5.9 | — | 4 |
| 24 | [330351](../reports/330351.md) | `byte` allocates uninitialized buffers and reads data from them p | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Medium — CVSS 5.2 | — | 4 |
| 25 | [852103](../reports/852103.md) | Out-of-Bound Read in urldecode() [CVE-2020-7067] | [Internet Bug Bounty](../by-program/ibb.md) | Medium | — | 2 |
| 26 | [321670](../reports/321670.md) | `stringstream` allocates uninitialized Buffers when number is pas | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Medium — CVSS 5.2 | — | 2 |
| 27 | [320166](../reports/320166.md) | `concat-with-sourcemaps` allocates uninitialized Buffers when num | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Medium — CVSS 6.5 | — | 2 |
| 28 | [781325](../reports/781325.md) | Out-of-bounds Read in php_strip_tags_ex | [Internet Bug Bounty](../by-program/ibb.md) | Medium | — | 1 |
| 29 | [1721098](../reports/1721098.md) | CVE-2022-35260: .netrc parser out-of-bounds access | [curl](../by-program/curl.md) | Low | — | 7 |
| 30 | [284951](../reports/284951.md) | Out-of-bounds read when importing corrupt blockchain with monero- | [Monero](../by-program/monero.md) | Low | — | 6 |
| 31 | [321704](../reports/321704.md) | `njwt` allocates uninitialized Buffers when number is passed in b | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Low — CVSS 1.8 | — | 5 |
| 32 | [221790](../reports/221790.md) | Certificate message OOB reads (CVE-2016-6306) | [Internet Bug Bounty](../by-program/ibb.md) | Low | — | 5 |
| 33 | [221789](../reports/221789.md) | OOB read in TS_OBJ_print_bio() (CVE-2016-2180) | [Internet Bug Bounty](../by-program/ibb.md) | Low | — | 5 |
| 34 | [321702](../reports/321702.md) | `put` allocates uninitialized Buffers when non-round numbers are  | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Low — CVSS 1.8 | — | 4 |
| 35 | [321701](../reports/321701.md) | `utile` allocates uninitialized Buffers when number is passed in  | [Node.js third-party modules](../by-program/nodejs-ecosystem.md) | Low — CVSS 1.8 | — | 3 |
| 36 | [3324190](../reports/3324190.md) | Heap-buffer-overflow (Out-of-Bounds Read) in DoH hostname encodin | [curl](../by-program/curl.md) | None | — | 24 |
| 37 | [3617719](../reports/3617719.md) | Function `do_pubkey()` can have out-of-bound read issue | [curl](../by-program/curl.md) | None | — | 13 |
| 38 | [2509402](../reports/2509402.md) | Out-Of-Bounds Memory Read on ███ | [U.S. Dept Of Defense](../by-program/deptofdefense.md) | None | — | 7 |
| 39 | [3738654](../reports/3738654.md) |  Firecracker Out-of-bounds Read/Write Local Privilege Escalation  | [AWS VDP](../by-program/aws_vdp.md) | None | — | 4 |
| 40 | [3973219](../reports/3973219.md) | 57: Heap out-of-bounds read in `curl_easy_escape_ccsid()` / `curl | [curl](../by-program/curl.md) | None | — | 2 |
| 41 | [3973245](../reports/3973245.md) | 55: Heap-buffer-overflow read in `curl_formadd_ccsid()` with bina | [curl](../by-program/curl.md) | None | — | 0 |
