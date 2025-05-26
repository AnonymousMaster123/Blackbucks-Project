# 🕵️ Footprinting

## Overview

Footprinting is the first and most crucial phase of ethical hacking and penetration testing. It involves gathering information about a target system, network, or organization to identify potential vulnerabilities. The goal is to collect as much data as possible without interacting directly with the target, thus remaining undetected.

---

## 🧠 Objectives

- Understand the importance and goals of footprinting.
- Learn various techniques and tools used in the process.
- Differentiate between passive and active footprinting methods.
- Recognize how attackers gather information to plan exploits.
- Explore defensive measures to mitigate information leakage.

---

## 🛠️ Techniques of Footprinting

### 1. Passive Footprinting
Gathering information without directly engaging the target system.

- WHOIS Lookups  
- DNS Interrogation  
- Website Footprinting  
- Social Media Profiling  
- Public Records & Document Metadata  

### 2. Active Footprinting
Interacting with the target to extract information.

- Network Scanning  
- Traceroute  
- Banner Grabbing  
- Ping Sweeps  

---

## 🔍 Tools Commonly Used

| Tool              | Purpose                                |
|-------------------|----------------------------------------|
| **Nmap**          | Network mapping and port scanning      |
| **Maltego**       | Relationship and entity mapping        |
| **Recon-ng**      | Web reconnaissance framework           |
| **theHarvester**  | Email and domain info harvesting       |
| **Shodan**        | Internet of Things (IoT) search engine |
| **NSLookup/Dig**  | DNS query tools                        |
| **Google Dorks**  | Advanced search techniques             |

---

## 🛡️ Defensive Strategies

- Minimize public exposure of sensitive data.
- Regularly audit DNS and WHOIS records.
- Restrict metadata in publicly shared documents.
- Use firewalls and IDS/IPS to detect active scanning.
- Implement security awareness training for employees.

---

## ✅ Use Cases

- **Red Teaming:** Understanding target surface before an attack simulation.
- **Blue Teaming:** Identifying exposed information to strengthen defenses.
- **Bug Bounty Hunting:** Collecting details to find vulnerabilities in scope.
- **Cybersecurity Training:** Practicing reconnaissance in ethical ways.

---

## ⚠️ Disclaimer

This project is intended for **educational purposes** and **authorized security assessments only**. Unauthorized use of these techniques may be illegal and unethical. Always obtain proper permission before testing any network or system.

---

## 📚 Further Reading

- [OWASP Information Gathering Guide](https://owasp.org/www-project-web-security-testing-guide/stable/4-Web_Application_Security_Testing/01-Information_Gathering.html)
- *Hacking: The Art of Exploitation* by Jon Erickson
- *The Hacker Playbook* by Peter Kim
