<div align="center">

# 🦠 Virus Scan & Malware Analysis Services — Complete Edition

**Koleksi layanan online dan tools lokal untuk virus scan, file reputation, URL/domain/IP reputation, hash lookup, malware sandbox, YARA/Sigma detection, IOC enrichment, malware triage, DFIR, memory forensics, document malware analysis, dan private lab malware analysis.**

![Focus](https://img.shields.io/badge/focus-virus%20scan%20%7C%20malware%20analysis%20%7C%20DFIR-7F77DD?style=flat-square)
![Usage](https://img.shields.io/badge/usage-defensive%20analysis-D85A30?style=flat-square)
![Category](https://img.shields.io/badge/category-malware%20analysis%20%7C%20SOC%20%7C%20threat%20intel-1D9E75?style=flat-square)
![Resources](https://img.shields.io/badge/resources-116-58a6ff?style=flat-square)

</div>

---

## 📌 Tentang Repo Ini

Repo ini fokus untuk **virus scan, malware triage, file reputation, URL reputation, hash lookup, sandbox analysis, threat intelligence enrichment, local malware analysis, DFIR, dan detection engineering**.

Jangan upload file sensitif, dokumen internal, source code private, credential, customer data, private key, token, atau sample rahasia ke layanan publik.

Resource malware sample, evasion, dan high-risk research dipisahkan ke bagian **Restricted / High-Risk**.

---

## 📑 Daftar Isi

- [🦠 Multi-Engine Virus Scanners & File Reputation](#multi-engine-virus-scanners--file-reputation)
- [🌐 URL, Domain, IP Reputation & IOC Lookup](#url-domain-ip-reputation--ioc-lookup)
- [🧪 Malware Sandbox Analysis & Automated Triage](#malware-sandbox-analysis--automated-triage)
- [🔎 Hash Lookup, Malware Intelligence & Threat Intel](#hash-lookup-malware-intelligence--threat-intel)
- [🧬 YARA, Sigma, IOC Rules & Detection Engineering](#yara-sigma-ioc-rules--detection-engineering)
- [🧰 Local Static Malware Analysis Tools](#local-static-malware-analysis-tools)
- [🧪 Local Dynamic Analysis, DFIR & Memory Forensics](#local-dynamic-analysis-dfir--memory-forensics)
- [📚 Malware Analysis Learning, Labs & Reference](#malware-analysis-learning-labs--reference)
- [📧 Email, Document & Script Malware Triage](#email-document--script-malware-triage)
- [🧯 Private Lab, Safe Handling & Offline Analysis](#private-lab-safe-handling--offline-analysis)
- [🚫 Restricted / High-Risk Malware Samples & Evasion Research](#restricted--high-risk-malware-samples--evasion-research)

- [🧭 Basic Malware Triage Workflow](#-basic-malware-triage-workflow)
- [⚠️ Upload Safety Notes](#️-upload-safety-notes)
- [✅ Local Hash Commands](#-local-hash-commands)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🎯 Purpose

Virus scan dan malware analysis services digunakan untuk membantu analisis awal terhadap file, URL, hash, domain, IP, email attachment, dokumen, script, atau sample yang dicurigai berbahaya.

Use cases:

```text
SOC alert enrichment
Malware triage
Email attachment checking
URL reputation checking
Hash reputation lookup
Incident response
Threat intelligence
DFIR investigation
Safe lab analysis
Checking suspicious downloads
Detection engineering
YARA/Sigma rule creation
```

---

## 🦠 Multi-Engine Virus Scanners & File Reputation

| Resource | Link | Fungsi |
|---|---|---|
| VirusTotal | https://www.virustotal.com/gui/home/upload | Multi-engine scanner untuk file, URL, domain, IP, dan hash reputation. |
| Jotti's Malware Scan | https://virusscan.jotti.org/it-IT/scan-file | Layanan scan file dengan beberapa antivirus engine untuk pengecekan cepat file mencurigakan. |
| MetaDefender Cloud | https://metadefender.opswat.com/ | Multi-scanning, file sanitization, hash lookup, dan threat analysis dari OPSWAT. |
| Kaspersky OpenTIP | https://opentip.kaspersky.com/ | File, URL, hash, domain, dan IP reputation lookup. |
| FortiGuard Labs | https://www.fortiguard.com/ | Threat intelligence, file hash, URL, IP, dan CVE/security lookup. |
| Cisco Talos File Reputation | https://talosintelligence.com/talos_file_reputation | File hash reputation lookup dari Cisco Talos. |
| Intezer Analyze | https://analyze.intezer.com/ | Malware analysis dan code reuse/genetic malware analysis. |
| ReversingLabs TitaniumCloud | https://www.reversinglabs.com/products/file-reputation-service | File reputation dan threat intelligence service. |
| Triage | https://tria.ge/ | Malware sandbox dan automated behavioral analysis. |
| Hybrid Analysis | https://www.hybrid-analysis.com/ | Malware analysis service dengan sandbox dan threat intelligence. |

---

## 🌐 URL, Domain, IP Reputation & IOC Lookup

| Resource | Link | Fungsi |
|---|---|---|
| VirusTotal URL Scan | https://www.virustotal.com/gui/home/url | Scan URL dan cek reputation dari banyak engine. |
| urlscan.io | https://urlscan.io/ | Analyze URL, screenshot, DOM, requests, redirects, dan infrastructure. |
| Google Safe Browsing Transparency Report | https://transparencyreport.google.com/safe-browsing/search | Cek status keamanan domain/URL menurut Google Safe Browsing. |
| Cisco Talos Intelligence | https://talosintelligence.com/reputation_center | IP/domain/email reputation lookup. |
| FortiGuard Web Filter Lookup | https://www.fortiguard.com/webfilter | URL category dan reputation lookup. |
| AbuseIPDB | https://www.abuseipdb.com/ | IP abuse reputation database. |
| URLhaus | https://urlhaus.abuse.ch/ | Database malware URLs dari abuse.ch. |
| PhishTank | https://phishtank.org/ | Database phishing URL community. |
| OpenPhish | https://openphish.com/ | Phishing intelligence dan URL feed. |
| Pulsedive | https://pulsedive.com/ | Threat intelligence search untuk domain, IP, URL, dan IOC. |
| AlienVault OTX | https://otx.alienvault.com/ | Open threat intelligence community untuk IOC lookup. |
| ThreatFox | https://threatfox.abuse.ch/ | IOC database untuk malware indicators. |
| GreyNoise | https://www.greynoise.io/ | Internet noise dan IP reputation untuk scanning/threat activity. |
| Shodan | https://www.shodan.io/ | Exposure dan service intelligence untuk IP/domain terkait incident. |
| Censys | https://search.censys.io/ | Host, certificate, port, dan infrastructure intelligence. |

---

## 🧪 Malware Sandbox Analysis & Automated Triage

| Resource | Link | Fungsi |
|---|---|---|
| ANY.RUN | https://any.run/ | Interactive malware analysis sandbox. |
| Joe Sandbox Cloud | https://www.joesandbox.com/ | Advanced malware sandbox analysis. |
| CAPE Sandbox | https://github.com/kevoreilly/CAPEv2 | Open-source malware sandbox untuk lab lokal. |
| Cuckoo Sandbox | https://github.com/cuckoosandbox/cuckoo | Open-source automated malware analysis sandbox. |
| Assemblyline | https://github.com/CybercentreCanada/assemblyline-base | Malware analysis and file triage platform dari Canadian Centre for Cyber Security. |
| Viper | https://github.com/viper-framework/viper | Binary management dan malware analysis framework. |
| IRMA | https://github.com/quarkslab/irma | Incident Response & Malware Analysis platform untuk multi-scanning lokal. |
| Malice | https://github.com/maliceio/malice | Open-source malware analysis framework berbasis plugin/container. |

---

## 🔎 Hash Lookup, Malware Intelligence & Threat Intel

| Resource | Link | Fungsi |
|---|---|---|
| MalwareBazaar | https://bazaar.abuse.ch/ | Malware sample repository, hash lookup, dan intelligence dari abuse.ch. |
| YARAify | https://yaraify.abuse.ch/ | YARA-based malware intelligence lookup. |
| MalShare | https://malshare.com/ | Malware repository dan hash lookup untuk researchers. |
| MISP Project | https://www.misp-project.org/ | Threat intelligence sharing platform. |
| OpenCTI | https://github.com/OpenCTI-Platform/opencti | Open-source cyber threat intelligence platform. |
| IntelMQ | https://github.com/certtools/intelmq | Automation framework untuk collect dan process threat intelligence feeds. |
| Mandiant Blog | https://www.mandiant.com/resources/blog | Threat intelligence dan malware/incident research. |
| Unit 42 Threat Research | https://unit42.paloaltonetworks.com/ | Threat intelligence, malware, dan vulnerability exploitation analysis. |
| Cisco Talos Blog | https://blog.talosintelligence.com/ | Threat research, malware, vulnerabilities, dan exploitation trends. |
| Microsoft Security Blog | https://www.microsoft.com/en-us/security/blog/ | Security research, malware, threat intelligence, dan incident analysis. |
| Google TAG Blog | https://blog.google/threat-analysis-group/ | Threat actor activity dan exploitation reporting. |
| The DFIR Report | https://thedfirreport.com/ | Incident reports, malware behavior, intrusion timeline, dan detection opportunities. |

---

## 🧬 YARA, Sigma, IOC Rules & Detection Engineering

| Resource | Link | Fungsi |
|---|---|---|
| YARA | https://github.com/VirusTotal/yara | Pattern matching engine untuk malware detection dan rule-based scanning. |
| YARA Rules | https://github.com/Yara-Rules/rules | Community YARA rules untuk malware families dan detection. |
| Neo23x0 signature-base | https://github.com/Neo23x0/signature-base | YARA, Sigma, IOC, dan detection signature collection. |
| Sigma | https://github.com/SigmaHQ/sigma | Generic SIEM detection rule format. |
| Sigma CLI | https://github.com/SigmaHQ/sigma-cli | CLI untuk convert dan validate Sigma rules. |
| LOKI | https://github.com/Neo23x0/Loki | Simple IOC and YARA scanner untuk endpoint triage. |
| THOR Lite | https://www.nextron-systems.com/thor-lite/ | Free IOC/YARA scanner dari Nextron untuk compromise assessment. |
| Hayabusa | https://github.com/Yamato-Security/hayabusa | Windows event log threat hunting dan timeline tool. |
| Chainsaw | https://github.com/WithSecureLabs/chainsaw | Windows event log analysis dan Sigma-based hunting. |
| CAPA | https://github.com/mandiant/capa | Identify capabilities in executable files. |
| FLOSS | https://github.com/mandiant/flare-floss | Extract obfuscated strings dari malware/binary. |
| Capa Rules | https://github.com/mandiant/capa-rules | Rules untuk CAPA capability detection. |

---

## 🧰 Local Static Malware Analysis Tools

| Resource | Link | Fungsi |
|---|---|---|
| Detect It Easy | https://github.com/horsicq/Detect-It-Easy | File type, packer, compiler, dan signature detector. |
| PE-bear | https://github.com/hasherezade/pe-bear | PE file analysis dan malware static analysis GUI. |
| PEStudio | https://www.winitor.com/ | Windows executable static analysis untuk triage malware. |
| CFF Explorer | https://ntcore.com/?page_id=388 | Portable executable editor dan inspection tool. |
| Ghidra | https://github.com/NationalSecurityAgency/ghidra | Reverse engineering suite untuk binary analysis. |
| radare2 | https://github.com/radareorg/radare2 | Reverse engineering framework untuk binary analysis. |
| Cutter | https://github.com/rizinorg/cutter | GUI reverse engineering berbasis Rizin/radare2 ecosystem. |
| x64dbg | https://github.com/x64dbg/x64dbg | Windows debugger untuk reverse engineering dan malware analysis lab. |
| dnSpyEx | https://github.com/dnSpyEx/dnSpy | .NET debugger dan assembly editor/decompiler. |
| ILSpy | https://github.com/icsharpcode/ILSpy | .NET decompiler. |
| Bytecode Viewer | https://github.com/Konloch/bytecode-viewer | Java/Android bytecode viewer dan decompiler GUI. |
| jadx | https://github.com/skylot/jadx | Dex/APK decompiler untuk Android malware analysis. |
| apktool | https://github.com/iBotPeaches/Apktool | Decode/rebuild APK resources dan manifest untuk Android malware triage. |
| strings / binutils | https://github.com/bminor/binutils-gdb | Extract strings dari binary, APK, DEX, atau native library. |

---

## 🧪 Local Dynamic Analysis, DFIR & Memory Forensics

| Resource | Link | Fungsi |
|---|---|---|
| Process Monitor | https://learn.microsoft.com/en-us/sysinternals/downloads/procmon | Monitor filesystem, registry, process, dan thread activity di Windows lab. |
| Process Explorer | https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer | Process inspection dan handle/DLL analysis. |
| Autoruns | https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns | Persistence dan autorun entry analysis. |
| TCPView | https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview | Network connection monitoring. |
| Regshot | https://sourceforge.net/projects/regshot/ | Registry snapshot diff untuk melihat perubahan malware. |
| Wireshark | https://gitlab.com/wireshark/wireshark | Packet capture dan protocol analysis. |
| Zeek | https://github.com/zeek/zeek | Network security monitoring dan protocol logging. |
| Suricata | https://github.com/OISF/suricata | IDS/IPS/NSM engine untuk network detection. |
| Volatility 3 | https://github.com/volatilityfoundation/volatility3 | Memory forensics framework. |
| Velociraptor | https://github.com/Velocidex/velociraptor | Endpoint DFIR, collection, dan hunting platform. |
| KAPE | https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape | Artifact collection dan parsing tool untuk DFIR. |
| Eric Zimmerman's Tools | https://ericzimmerman.github.io/#!index.md | Windows forensic tools collection. |
| plaso/log2timeline | https://github.com/log2timeline/plaso | Timeline generation untuk forensic investigation. |
| MVT | https://github.com/mvt-project/mvt | Mobile Verification Toolkit untuk Android/iOS forensic analysis secara konsensual. |
| PCAPdroid | https://github.com/emanuele-f/PCAPdroid | Capture dan analisis traffic langsung dari Android device. |

---

## 📚 Malware Analysis Learning, Labs & Reference

| Resource | Link | Fungsi |
|---|---|---|
| awesome-malware-analysis | https://github.com/rshipp/awesome-malware-analysis | Awesome list malware analysis tools dan resources. |
| awesome-malware | https://github.com/fabacab/awesome-malware | Koleksi resource malware research dan analysis. |
| MalwareAnalysis101 | https://github.com/CYB3RMX/MalwareAnalysis101 | Materi dasar malware analysis untuk defensive research dan lab. |
| Malware-Analysis | https://github.com/kh4sh3i/Malware-Analysis | Resource malware analysis untuk learning dan lab defensif. |
| Practical Malware Analysis Labs | https://github.com/mikesiko/PracticalMalwareAnalysis-Labs | Lab files untuk buku Practical Malware Analysis; gunakan hanya di isolated lab. |
| Malware Unicorn | https://malwareunicorn.org/workshops/re101.html | Reverse engineering 101 workshop material. |
| FLARE VM | https://github.com/mandiant/flare-vm | Windows malware analysis and reverse engineering distribution. |
| REMnux | https://github.com/REMnux/remnux-distro | Linux toolkit untuk malware analysis dan reverse engineering. |
| SANS FOR610 Resources | https://www.sans.org/blog/what-is-malware-analysis/ | Referensi dasar malware analysis dari SANS. |
| TheZoo | https://github.com/ytisf/theZoo | Malware sample repository untuk researchers; handle hanya di lab terisolasi. |
| VX-Underground | https://vx-underground.org/ | Malware research archive; high-risk, hanya untuk research defensif legal. |

---

## 📧 Email, Document & Script Malware Triage

| Resource | Link | Fungsi |
|---|---|---|
| MXToolbox Header Analyzer | https://mxtoolbox.com/EmailHeaders.aspx | Email header analyzer untuk phishing/malspam triage. |
| Google Admin Toolbox Messageheader | https://toolbox.googleapps.com/apps/messageheader/ | Email message header analyzer. |
| PhishTool | https://www.phishtool.com/ | Phishing email analysis dan triage platform. |
| CyberChef | https://gchq.github.io/CyberChef/ | Encoding/decoding, deobfuscation, IOC extraction, dan data transformation. |
| oletools | https://github.com/decalage2/oletools | Analyze malicious Office documents, macros, OLE, and VBA. |
| olefile | https://github.com/decalage2/olefile | Python package untuk parse OLE files. |
| pdf-parser.py | https://github.com/DidierStevens/DidierStevensSuite | PDF analysis tools dari Didier Stevens. |
| OfficeMalScanner | https://www.reconstructer.org/code.html | Office document malware analysis helper. |
| ViperMonkey | https://github.com/decalage2/ViperMonkey | VBA macro emulation untuk malicious macro analysis. |
| Box-JS | https://github.com/CapacitorSet/box-js | JavaScript malware analysis sandbox. |

---

## 🧯 Private Lab, Safe Handling & Offline Analysis

| Resource | Link | Fungsi |
|---|---|---|
| INetSim | https://www.inetsim.org/ | Internet services simulation untuk malware analysis lab. |
| FakeNet-NG | https://github.com/mandiant/flare-fakenet-ng | Dynamic network simulation tool untuk malware analysis. |
| Noriben | https://github.com/Rurik/Noriben | Malware behavior analysis wrapper around Procmon. |
| Speakeasy | https://github.com/mandiant/speakeasy | Windows kernel/user mode emulation framework untuk malware analysis. |
| flare-emu | https://github.com/mandiant/flare-emu | Emulation helper untuk shellcode/malware reverse engineering. |

---

## 🚫 Restricted / High-Risk Malware Samples & Evasion Research

> Resource di bagian ini high-risk. Jangan download, upload ulang, menjalankan, atau membuka sample di host utama. Gunakan hanya untuk defensive research legal di isolated lab.

| Resource | Link | Catatan |
|---|---|---|
| Ransomware Database Topic | https://github.com/topics/ransomware | Ransomware-related resources; hanya untuk defensive research di lab aman. |
| Malware Samples Topic | https://github.com/topics/malware-samples | Malware sample-related resources; jangan jalankan di host utama. |
| Evasion/AV Bypass Topic | https://github.com/topics/av-bypass | AV bypass/evasion content; tidak untuk penggunaan ofensif. |
| Payload Obfuscator Topic | https://github.com/topics/payload-obfuscator | Obfuscation/evasion topic; simpan hanya untuk malware-analysis awareness. |

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
6. Extract strings, metadata, imports, and indicators locally
   ↓
7. Use sandbox only for non-sensitive samples
   ↓
8. For sensitive samples, use isolated local lab/private sandbox
   ↓
9. Review behavior, network IOC, dropped files, registry/process activity
   ↓
10. Create IOC, YARA/Sigma opportunities, and documentation
```

---

## ⚠️ Upload Safety Notes

Public scanning services may share uploaded samples, metadata, hash, filename, behavior report, or detection results with security vendors and researchers.

Before uploading, check:

```text
Is the file confidential?
Does it contain credentials?
Does it contain customer data?
Does it contain internal documents?
Does it contain source code?
Does it contain private keys or tokens?
Is it part of an active incident where disclosure could harm investigation?
```

Recommended safe flow:

```text
Hash lookup first
    ↓
URL/domain/IP lookup
    ↓
Local static triage
    ↓
Upload only if non-sensitive
    ↓
Use private sandbox for confidential samples
```

For sensitive samples, use an isolated local lab or private enterprise sandbox instead of public upload services.

---

## ✅ Local Hash Commands

```bash
# Linux/macOS
sha256sum suspicious_file
md5sum suspicious_file

# Windows PowerShell
Get-FileHash .\suspicious_file -Algorithm SHA256
Get-FileHash .\suspicious_file -Algorithm MD5
```

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
- Detection engineering

Jangan menggunakan layanan, tools, sample, rule, payload, atau teknik dari repository ini untuk menyebarkan malware, menguji bypass antivirus secara ofensif, mengunggah data rahasia, melakukan evasion testing terhadap pihak lain, atau aktivitas yang melanggar hukum.
