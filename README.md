# Cybersecurity Incident Response & Analysis

Documentation of real-world security incidents, remediation procedures, and analysis.
Maintained alongside CompTIA A+, Network+, and Security+ certification study.

---

## Incident Reports

### [Typo-Squatting and Scareware Encounter](typo-squatting-scareware.md)
*September 3–4, 2026*

A mistyped URL resolved to a typo-squatted domain serving fake Norton and McAfee security
alerts. Full write-up covering containment, malware scanning, browser remediation, Windows
system file repair, and post-repair verification — with screenshots at each step.

Includes analysis of why `DISM /restorehealth` must precede `sfc /scannow` when the
component store is damaged, and why the initial SFC failures were not attributable to
the incident.

---

## Skills Demonstrated

- Threat identification and classification
- Incident timeline reconstruction from system evidence
- Windows remediation: Defender full scan, `sfc /scannow`, `DISM /online /cleanup-image /restorehealth`
- Browser cleanup and permission review
- Root cause analysis and control recommendations
- Technical documentation

---

## Topics Covered

Social engineering · Scareware and other malware classes · Domain spoofing and
typo-squatting · System hardening and repair

---

**Cameron Salmon**
Marine Corps Telecommunications Veteran (MOS 2847) · CompTIA A+ and Network+ Certified
[LinkedIn](https://www.linkedin.com/in/cameron-salmon-) · [GitHub](https://github.com/CameronSalmon)
