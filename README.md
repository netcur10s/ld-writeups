# LetsDefend Writeups
**SOC Alert Investigations | Blue Team Exercises | Incident Analysis**

## About

LetsDefend simulates the SOC analyst workflow — triaging real alerts, investigating suspicious activity, and making true positive or false positive determinations with documented justification. Unlike CTF platforms, the focus is on the defensive analysis process rather than exploitation.

These writeups document my investigation methodology, triage decisions, and conclusions written the way findings would be communicated in a professional SOC environment.

## Investigations

Writeups are added as investigations are completed. Each entry links directly to the full writeup.

| Case | Category | Severity | Verdict |
|---|---|---|---|
| *Investigations in progress* | | | |

## Investigation Format

Every writeup follows this structure to mirror professional SOC documentation standards:

**Alert Info** — Alert name, type, severity, and timestamp

**Initial Triage** — First impressions and priority assessment based on available context

**Investigation** — Step by step analysis, tools used, and findings at each stage

**IOCs** — Indicators of Compromise identified during the investigation

**Verdict** — True positive or false positive determination with full justification

**Response Actions** — Containment or escalation steps taken or recommended

**Lessons Learned** — Key takeaways and detection improvements identified

## Tools Used

| Tool | Purpose |
|---|---|
| LetsDefend SIEM | Alert triage and log analysis |
| VirusTotal | File and URL reputation checking |
| AbuseIPDB | IP reputation and threat intelligence |
| MXToolbox | Email header and DNS analysis |
| CyberChef | Data decoding and artifact analysis |
| Wireshark | Packet capture analysis |
| Any.run | Dynamic malware analysis sandbox |

## Related

This repository is part of a broader security portfolio. For hands-on detection lab work using Splunk, Active Directory, and MITRE ATT&CK attack simulation see the [Cyber Detection Home Lab](https://github.com/netcur10s/cyber-detection-lab).

*Part of the [netcur10s](https://github.com/netcur10s) security portfolio*