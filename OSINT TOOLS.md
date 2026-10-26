# OSINT Tools

Different OSINT tools used to conduct security threat assessments and investigations.

## urlscan.io: scanning malicious URLs

[urlscan.io](https://urlscan.io/) is a free service that helps scan and analyse websites. It automates browsing and crawling through websites to record activities and interactions.

When a URL is submitted, the information recorded includes:

- domains and IP addresses contacted
- resources requested from those domains
- a snapshot of the web page
- technologies used and other metadata about the website

## abuse.ch: tracking malware and botnet indicators

[abuse.ch](https://abuse.ch/) is a research project hosted by the Institute for Cybersecurity and Engineering at the Bern University of Applied Sciences in Switzerland. It was developed to identify and track malware and botnets through several operational platforms:

| Platform | Purpose |
|----------|---------|
| **MalwareBazaar** | Sharing malware samples |
| **Feodo Tracker** | Tracking botnet command and control (C2) infrastructure linked with Emotet, Dridex and TrickBot |
| **SSL Blacklist** | Blocklist of malicious SSL certificates and JA3/JA3S fingerprints |
| **URLhaus** | Sharing malware distribution sites |
| **ThreatFox** | Sharing indicators of compromise (IOCs) |

## PhishTool: investigating phishing emails

PhishTool aims to treat phishing as a serious form of attack and provide a responsive means of email security. Through email analysis, security analysts can uncover email IOCs, prevent breaches and produce forensic reports for phishing containment and training.

It comes in two versions: **Community** and **Enterprise**. These notes focus on the Community version.

**Core features**

- **Email analysis**: retrieves metadata from phishing emails and helps analysts follow the email's actions, attachments and URLs to triage the situation.
- **Heuristic intelligence**: built-in OSINT helps analysts stay ahead of persistent attacks and understand which TTPs were used to evade security controls and social engineer a target.
- **Classification and reporting**: classifies phishing emails so analysts can act quickly, and generates reports as a shareable forensic record.

**Enterprise extras**

- Manage user-reported phishing events
- Report findings back to users and keep them engaged in the process
- Email stack integration with Microsoft 365 and Google Workspace

## Cisco Talos Intelligence: intel gathering

_Notes to be added._
