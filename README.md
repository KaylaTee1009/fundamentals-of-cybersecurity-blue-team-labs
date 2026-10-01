# Fundamentals of Cybersecurity: Blue Team Labs

Write-ups from hands-on labs completed as part of a Fundamentals of Cybersecurity
course. Each lab was run in an isolated virtual lab environment and covers a different
piece of practical security work — from social engineering and web-based attacks to
network intrusion detection and honeypot analysis.

## Labs

| Module | Topic | Description |
|---|---|---|
| [Module 8](Module_8_Writeup.pdf) | Website Cloning & Malicious File Delivery | Cloned a real organizational website and weaponized it to deliver a malicious file, demonstrating how spoofed sites and trojanized documents are used in social engineering attacks. |
| [Module 10](Module_10_Writeup) | SSH Honeypot Analysis with Kippo | Deployed a Kippo SSH honeypot and used Kippo-Graph to analyze attacker login attempts and replay a full attacker session, revealing real-world credential patterns and post-access behavior. |
| [Module 11](Module_11_Writeup) | Intrusion Detection with Snort | Wrote custom Snort IDS rules and generated matching traffic (recon, credential leakage, unauthorized file access, and a Netcat backdoor) to validate detection end-to-end. |

## Skills Demonstrated
- Web server administration and HTML editing (Apache, `/var/www/html`)
- Social engineering / phishing attack simulation
- Writing and validating custom Snort IDS signatures
- Network traffic analysis (ICMP, FTP, HTTP, TCP)
- Honeypot deployment and log/session analysis (Kippo, Kippo-Graph)
- Linux command-line fundamentals (`vi`, `nano`, user management, file permissions)

## Environment
All labs were performed in a self-contained virtual lab (VMware Workstation) using
Ubuntu-based target/sensor VMs and a Windows attacker machine, isolated from any
production network.

---
*These write-ups are for educational purposes, documenting coursework completed as
part of a cybersecurity fundamentals course.*
