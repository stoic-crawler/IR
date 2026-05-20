<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║          INCIDENT RESPONSE PLAYBOOKS – stoic‑crawler         ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

# 🛡️ IR Playbooks

**A visual, tactical guide to handling cyber incidents – one phase at a time.**

[![GitHub last commit](https://img.shields.io/github/last-commit/stoic-crawler/IR?color=blue&style=flat-square)](https://github.com/stoic-crawler/IR/commits/main)
[![License](https://img.shields.io/badge/license-Unlicense-lightgrey?style=flat-square)](./LICENSE)
[![Made with Markdown](https://img.shields.io/badge/made%20with-markdown-1f425f?style=flat-square)](https://www.markdownguide.org)

</div>

---

## 📖 What is this?

This repository contains **Incident Response playbooks** mapped directly to the
[MITRE ATT&CK®](https://attack.mitre.org/) framework. Each playbook is a
**high‑resolution visual flowchart** that guides analysts through detection,
containment, eradication, and recovery – ensuring no step is missed under
pressure.

Whether you’re triaging a ransomware outbreak, hunting lateral movement, or
investigating an insider threat, these playbooks offer a **repeatable,
standardised, and rapid response plan**.

> **Key features:**
> - ✅ Covers **15+** MITRE ATT&CK tactics
> - ✅ Playbook includes **Ransomware** & **Insider Threat** scenarios
> - ✅ Visual flowcharts – easy to follow even at 3 AM
> - ✅ Designed for SOC analysts, incident responders, and security engineers
> - ✅ Ready to print, embed in wikis, or integrate into SOAR platforms

---

## 🗂️ Playbook Catalog

All playbooks are located under the [`playbooks/`](./playbooks/) directory.
Click any name below to jump to the image, or right‑click and “Save link as…”
to download.

| # | Playbook | MITRE Tactic | Description |
|---|----------|--------------|-------------|
| 1 | [Collection](./playbooks/Collection.png) | Collection | Identify and stop data staging |
| 2 | [Command & Control](./playbooks/Command_and_Control.png) | Command and Control | Detect and sever C2 channels |
| 3 | [Credential Access](./playbooks/Credential_Access.png) | Credential Access | Respond to password/credential theft |
| 4 | [Defense Evasion](./playbooks/Defense_Evasion.png) | Defense Evasion | Uncover tampering with security tools |
| 5 | [Discovery](./playbooks/Discovery.png) | Discovery | Investigate network/enumeration activities |
| 6 | [Execution](./playbooks/Execution.png) | Execution | Contain malicious code execution |
| 7 | [Exfiltration](./playbooks/Exfiltration.png) | Exfiltration | Stop data leakage in progress |
| 8 | [Impact](./playbooks/Impact.png) | Impact | Respond to destructive attacks |
| 9 | [Initial Access](./playbooks/Initial_Access.png) | Initial Access | Trace and close the entry point |
|10 | [Insider Threat](./playbooks/Insider_Threat.png) | Insider Threat | Investigate malicious insiders |
|11 | [Lateral Movement](./playbooks/Lateral_Movement.png) | Lateral Movement | Break the attacker’s movement chain |
|12 | [Persistence](./playbooks/Persistence.png) | Persistence | Remove long‑term footholds |
|13 | [Ransomware](./playbooks/Ransomware.png) | Impact | Survive and recover from ransomware |
|14 | [Reconnaissance](./playbooks/Reconnaissance.png) | Reconnaissance | Detect pre‑attack scanning |
|15 | [Resource Development](./playbooks/Resource_Development.png) | Resource Development | Respond to infrastructure preparation |
|16 | [Resource Development (Alt)](./playbooks/Resource_Development%201.png) | Resource Development | Alternative workflow for ResDev |



