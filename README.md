# Blue Team Write-Ups

Hands-on SOC and blue-team lab write-ups by **Anshio Renin** — alert triage, phishing, malware and DFIR analysis, each mapped to MITRE ATT&CK.

MSc Cybersecurity · CompTIA Security+ · Dublin, Ireland
[Portfolio](https://anshio-renin.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/anshio-renin-ms/) · [GitHub](https://github.com/AnshioRenin)

---

## Lab write-ups

| Lab | Platform | Focus | MITRE ATT&CK |
|---|---|---|---|
| [GrabThePhisher](labs/grabthephisher/) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/grabthephisher/) | Phishing-kit reverse engineering, Telegram exfiltration, IOC + actor attribution | T1566, T1567 |

## DFIR report notes

_Coming soon — weekly analyses of real intrusions from [The DFIR Report](https://thedfirreport.com/reports/): attack chain plus how a SOC would detect each stage._

---

## Repo structure

- `labs/<lab-name>/` — one folder per lab: the `README.md` write-up plus an `images/` folder
- `dfir-reports/<report-name>/` — DFIR report reading notes (same format)

## About

I am an MSc Cybersecurity graduate and CompTIA Security+ certified analyst focused on security operations and detection. These write-ups document my own hands-on analysis: the method, the findings, the ATT&CK mapping, and how I would detect and respond to each attack.

---

*Written for learning purposes. All indicators shown are from retired public lab samples, not live infrastructure.*
