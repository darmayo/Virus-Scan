<div align="center">

# 🦠 Virus Scan & Malware Analysis Services

**Koleksi layanan online untuk scan file, URL, hash, domain, IP, dan malware sample menggunakan multi-engine antivirus, reputation database, sandbox analysis, dan threat intelligence.**

![Focus](https://img.shields.io/badge/focus-virus%20scan%20%7C%20malware%20analysis%20%7C%20file%20reputation-7F77DD?style=flat-square)
![Usage](https://img.shields.io/badge/usage-defensive%20analysis-D85A30?style=flat-square)
![Category](https://img.shields.io/badge/category-malware%20analysis%20%7C%20SOC%20%7C%20DFIR-1D9E75?style=flat-square)

</div>

---

> Repository ini fokus untuk **virus scan, malware triage, file reputation, URL reputation, hash lookup, dan threat intelligence enrichment**.  
> Jangan upload file sensitif, dokumen internal, source code private, credential, customer data, atau sample rahasia ke layanan publik.

---

## 📑 Daftar Isi

- [🎯 Purpose](#-purpose)
- [🦠 Multi-Engine Virus Scanners](#-multi-engine-virus-scanners)
- [🌐 URL, Domain & IP Reputation](#-url-domain--ip-reputation)
- [🧪 Malware Sandbox Analysis](#-malware-sandbox-analysis)
- [🔎 Hash Lookup & Threat Intelligence](#-hash-lookup--threat-intelligence)
- [🧭 Basic Malware Triage Workflow](#-basic-malware-triage-workflow)
- [⚠️ Upload Safety Notes](#️-upload-safety-notes)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🎯 Purpose

Virus scan services digunakan untuk membantu analisis awal terhadap file, URL, hash, domain, atau IP yang dicurigai berbahaya.

Use cases:

- SOC alert enrichment
- Malware triage
- Email attachment checking
- URL reputation checking
- Hash reputation lookup
- Incident response
- Threat intelligence
- DFIR investigation
- Safe lab analysis
- Checking suspicious downloads

---

## 🦠 Multi-Engine Virus Scanners

| Service | Link | Fungsi |
|---|---|---|
| Jotti's Malware Scan | https://virusscan.jotti.org/it-IT/scan-file | Layanan scan file dengan beberapa antivirus engine untuk pengecekan cepat file mencurigakan. |
| VirusTotal | https://www.virustotal.com/gui/home/upload | Multi-engine scanner untuk file, URL, domain, IP, dan hash reputation. |
| MetaDefender Cloud | https://metadefender.opswat.com/ | Multi-scanning, file sanitization, hash lookup, dan threat analysis dari OPSWAT. |
| Hybrid Analysis | https://www.hybrid-analysis.com/ | Malware analysis service dengan sandbox dan threat intelligence. |
| ANY.RUN | https://any.run/ | Interactive malware sandbox untuk analisis behavior file dan URL. |
| Joe Sandbox Cloud | https://www.joesandbox.com/ | Malware sandbox untuk file, URL, email, dan behavior analysis. |
| Intezer Analyze | https://analyze.intezer.com/ | Malware analysis dan code reuse/genetic malware analysis. |
| Triage | https://tria.ge/ | Malware sandbox dan automated behavioral analysis. |
| Kaspersky Threat Intelligence Portal | https://opentip.kaspersky.com/ | File, URL, hash, domain, dan IP reputation lookup. |
| FortiGuard Labs | https://www.fortiguard.com/ | Threat intelligence, file hash, URL, IP, dan CVE/security lookup. |

---

## 🌐 URL, Domain & IP Reputation

| Service | Link | Fungsi |
|---|---|---|
| VirusTotal URL Scan | https://www.virustotal.com/gui/home/url | Scan URL dan cek reputation dari banyak engine. |
| urlscan.io | https://urlscan.io/ | Analyze URL, screenshot, DOM, requests, redirects, dan infrastructure. |
| Google Safe Browsing Transparency Report | https://transparencyreport.google.com/safe-browsing/search | Cek status keamanan domain/URL menurut Google Safe Browsing. |
| Cisco Talos Intelligence | https://talosintelligence.com/reputation_center | IP/domain/email reputation lookup. |
| FortiGuard Web Filter Lookup | https://www.fortiguard.com/webfilter | URL category dan reputation lookup. |
| Kaspersky OpenTIP | https://opentip.kaspersky.com/ | URL, domain, IP, dan hash reputation lookup. |
| AbuseIPDB | https://www.abuseipdb.com/ | IP abuse reputation database. |
| URLhaus | https://urlhaus.abuse.ch/ | Database malware URLs dari abuse.ch. |
| PhishTank | https://phishtank.org/ | Database phishing URL community. |
| OpenPhish | https://openphish.com/ | Phishing intelligence dan URL feed. |

---

## 🧪 Malware Sandbox Analysis

| Service | Link | Fungsi |
|---|---|---|
| ANY.RUN | https://any.run/ | Interactive malware analysis sandbox. |
| Triage | https://tria.ge/ | Automated malware sandbox analysis. |
| Hybrid Analysis | https://www.hybrid-analysis.com/ | Sandbox analysis dan behavior report. |
| Joe Sandbox Cloud | https://www.joesandbox.com/ | Advanced malware sandbox analysis. |
| Intezer Analyze | https://analyze.intezer.com/ | Malware family/code reuse analysis. |
| MalwareBazaar | https://bazaar.abuse.ch/ | Malware sample repository dan intelligence dari abuse.ch. |
| CAPE Sandbox | https://github.com/kevoreilly/CAPEv2 | Open-source malware sandbox untuk lab lokal. |
| Cuckoo Sandbox | https://github.com/cuckoosandbox/cuckoo | Open-source automated malware analysis sandbox. |

---

## 🔎 Hash Lookup & Threat Intelligence

| Service | Link | Fungsi |
|---|---|---|
| VirusTotal Hash Search | https://www.virustotal.com/gui/home/search | Search file hash, URL, domain, dan IP. |
| MalwareBazaar | https://bazaar.abuse.ch/ | Malware hash/sample lookup dan intelligence. |
| Kaspersky OpenTIP | https://opentip.kaspersky.com/ | Hash/file reputation lookup. |
| MetaDefender Cloud | https://metadefender.opswat.com/ | Hash lookup dan multi-scanning. |
| ThreatFox | https://threatfox.abuse.ch/ | IOC database untuk malware indicators. |
| YARAify | https://yaraify.abuse.ch/ | YARA-based malware intelligence lookup. |
| MalShare | https://malshare.com/ | Malware repository dan hash lookup untuk researchers. |
| Cisco Talos File Reputation | https://talosintelligence.com/talos_file_reputation | File hash reputation lookup. |
| AlienVault OTX | https://otx.alienvault.com/ | Open threat intelligence community untuk IOC lookup. |
| MISP Project | https://www.misp-project.org/ | Threat intelligence sharing platform. |

---

## 🧭 Basic Malware Triage Workflow

```text
1. Collect suspicious artifact safely
   ↓
2. Calculate hash locally
   ↓
3. Search hash first before uploading file
   ↓
4. Check reputation from multiple sources
   ↓
5. Analyze URL/domain/IP reputation if related
   ↓
6. Use sandbox only for non-sensitive samples
   ↓
7. Review behavior, network IOC, dropped files, registry/process activity
   ↓
8. Document indicators and detection opportunities
```

### Useful Local Commands

```bash
# Linux/macOS
sha256sum suspicious_file
md5sum suspicious_file

# Windows PowerShell
Get-FileHash .\suspicious_file -Algorithm SHA256
Get-FileHash .\suspicious_file -Algorithm MD5
```

---

## ⚠️ Upload Safety Notes

Public scanning services may share uploaded samples, metadata, hash, filename, behavior report, or detection results with security vendors and researchers.

Before uploading, check:

- Is the file confidential?
- Does it contain credentials?
- Does it contain customer data?
- Does it contain internal documents?
- Does it contain source code?
- Does it contain private keys or tokens?
- Is it part of an active incident where disclosure could harm investigation?

Recommended safe flow:

```text
Hash lookup first
    ↓
URL/domain/IP lookup
    ↓
Upload only if non-sensitive
    ↓
Use private sandbox for confidential samples
```

For sensitive samples, use an isolated local lab or private enterprise sandbox instead of public upload services.

---

## ⚖️ Disclaimer

Gunakan resource ini hanya untuk:

- Defensive malware analysis
- SOC alert enrichment
- Incident response
- DFIR
- Threat intelligence
- Lab pribadi
- Security research legal
- File/URL reputation checking yang sah

Jangan menggunakan layanan ini untuk menyebarkan malware, menguji bypass antivirus secara ofensif, mengunggah data rahasia, atau melakukan aktivitas yang melanggar hukum.
