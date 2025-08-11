# 🛡️ Cybersecurity Portfolio

> *Hands-on projects, clear writeups, and a track record of learning from the Google Cybersecurity Certificate.*

---

&#x20;
# Note: This is a template README file. It will be updated as I keep adding projects.
## About me

I’m building a focused cybersecurity portfolio to showcase projects from the **Google Cybersecurity Certificate** and related home labs. This repo demonstrates practical skills in incident response, system hardening, network analysis, forensics, and secure configuration — with clean writeups, reproducible labs, and documented learning outcomes.

**Goals:**

- Show real, runnable projects with clear instructions.
- Include threat-model notes & adversary assumptions.
- Demonstrate tool proficiency (Wireshark, tcpdump, Linux hardening, Splunk/ELK-style logs, etc.).
- Make each project reproducible in a VM or Docker container where possible.

---

## Projects

> Each project directory includes: `README.md`, `writeup.md`, `artifacts/` (pcaps, logs, exports), and `reproduce.sh` or `Dockerfile` if applicable.

### 1) Incident Response — Suspicious Login Investigation

**Folder:** `projects/incident-response-suspicious-login`

- Short: Investigated a set of suspicious login events, performed timeline analysis, and produced containment & recovery recommendations.
- Key artifacts: authentication logs, timeline (`timeline.csv`), analyst writeup.
- Skills: log triage, timeline building, containment steps, mitigation.

### 2) Network Traffic Analysis — Malicious Exfiltration Demo

**Folder:** `projects/network-exfiltration`

- Short: Analyzed PCAP files to detect data exfil patterns and extract suspicious payloads.
- Key artifacts: `capture.pcap`, extraction scripts, YARA rules.
- Skills: Wireshark, tshark, scripting to automate extraction, YARA.

### 3) Host Hardening — Secure Baseline for Ubuntu Server

**Folder:** `projects/host-hardening-ubuntu`

- Short: Hardened an Ubuntu VM using CIS-inspired controls, automated with an Ansible playbook.
- Key artifacts: `ansible/playbook.yml`, before/after audit reports.
- Skills: system hardening, Ansible, auditd, SSH hardening.

### 4) Log Analysis & Detection — Simple SIEM Rules

**Folder:** `projects/log-detection`

- Short: Built detection rules and dashboards against simulated logs; evaluated false positives.
- Key artifacts: detection rules, synthetic logs, dashboard screenshots.
- Skills: log parsing, regex, detection tuning, basic dashboarding.

### 5) Forensics — Disk Image Artifact Recovery

**Folder:** `projects/forensics-disk-recovery`

- Short: Carved files from a disk image and documented user activity relevant to an investigation.
- Key artifacts: `image.dd`, carved files, forensic timeline.
- Skills: sleuthkit, bulk\_extractor, volatile memory overview.

### 6) Capture The Flag (CTF) Writeups

**Folder:** `projects/ctf-writeups`

- Short: Selected writeups demonstrating applied skills and problem solving.
- Key artifacts: solutions, commands, hints, lessons learned.

---

## How to use this portfolio

1. Clone the repo:

```bash
git clone https://github.com/<your-username>/<this-repo>.git
cd <this-repo>
```

2. Explore any project folder and read `README.md` inside it. Each project will include a `reproduce.sh` or a Dockerfile when the environment is reproducible.

3. Running labs (general guidance):

- Prefer using an isolated VM (VirtualBox / VMware) or a container sandbox.
- Read the project-level instructions carefully before executing scripts.

---

## Tech / Tools showcased

- Operating systems: Linux (Ubuntu), Windows (analysis notes)
- Networking: Wireshark, tcpdump, tshark
- Forensics: sleuthkit, bulk\_extractor
- Automation / infra: Ansible, Docker
- Logging / detection: grep/awk/sed, basic ELK/Splunk-style rules
- Scripting: Bash, Python (small helpers for parsing/extraction)

---

## Project template (use this when adding new projects)

```
projects/<project-name>/
├─ README.md            # short overview + TL;DR
├─ writeup.md           # detailed analysis, steps, findings
├─ artifacts/           # pcaps, logs, images, exports (don’t store secrets)
├─ reproduce.sh         # optional script to reproduce the lab
├─ Dockerfile | Vagrantfile  # optional environment setup
└─ LICENSE
```

Use `writeup.md` to include: problem statement, scope & assumptions, tools used, step-by-step analysis, findings, mitigations, and lessons learned.

---
## Contact & Links

- GitHub: `https://github.com/Rak256`
- LinkedIn: `www.linkedin.com/in/rakshit-nair-125667291`
- Email: `rakshit.nair.12@gmail.com`

(Replace with your real links / contact.)

---


