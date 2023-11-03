<p align="center">
  <img src="https://i.imgur.com/ElWjENc.png" alt="Google Logo" width="200" height="200" />
</p>

# Incident Handler's Journal

> **Disclaimer**: This repository contains my Incident Handler's Journal entries as part of the Google Cybersecurity Professional Certification Program.


## Date: July 23, 2024

### Entry #1: Ransomware Attack on Small U.S. Health Care Clinic


| Attribute           | Details                                                                     |
|---------------------|-----------------------------------------------------------------------------|
| **Date**            | July 24, 2024                                                               |
| **Overview**        | Examination of a ransomware attack that crippled a primary-care health clinic. |

### Description
A small health care clinic in the U.S., known for its primary-care services, suffered a security incident, which caused significant disruptions in its operations. Employees couldn't access essential files like medical records, and a ransom note appeared on their screens. The note clarified that the company's files were encrypted and demanded a ransom for decryption.

### The 5 W's Breakdown

| Keyword  | Description                                                                                          |
|----------|------------------------------------------------------------------------------------------------------|
| **Who**  | An organized syndicate of cybercriminals, notorious for targeting healthcare and transportation sectors.|
| **What** | A ransomware attack encrypted essential files, causing operations to halt.                             |
| **When** | Tuesday morning, approximately at 9:00 a.m.                                                          |
| **Where**| A primary-care health clinic in the U.S.                                                             |
| **Why**  | The attackers exploited a phishing campaign targeted at the company's employees. Once an employee downloaded the malicious attachment, malware was installed, granting the attackers unauthorized access. |

### Reflection & Key Questions
- **Prevention**: How could the health care company prevent an incident like this from occurring again?
- **Resilience**: What strategies can the clinic adopt to ensure rapid recovery from such incidents, minimizing operational downtime?


### Date: July 25, 2024

#### Entry: #2

**Description**: Analyzing a packet capture file

**Tool(s) used**: For this activity, I used Wireshark to analyze a packet capture file. Wireshark is a network protocol analyzer that uses a graphical user interface. The value of Wireshark in cybersecurity is that it allows security analysts to capture and analyze network traffic. This can help in detecting and investigating malicious activity.

**The 5 W's**:
- **Who**: N/A
- **What**: N/A
- **Where**: N/A
- **When**: N/A
- **Why**: N/A

---

### Date: July 25, 2024

#### Entry: #3

**Description**: Capturing a packet

**Tool(s) used**: For this activity, I used tcpdump to capture and analyze network traffic. Tcpdump is a network protocol analyzer that's accessed using the command-line interface. Similar to Wireshark, the value of tcpdump in cybersecurity is that it allows security analysts to capture, filter, and analyze network traffic.

**The 5 W's**:
- **Who**: N/A
- **What**: N/A
- **Where**: N/A
- **When**: N/A
- **Why**: N/A

---

### Date: July 27, 2024

#### Entry: #4

**Description**: Investigate a suspicious file hash

**Tool(s) used**: For this activity, I used VirusTotal, which is an investigative tool that analyzes files and URLs for malicious content such as viruses, worms, trojans, and more. It's a very helpful tool to use if you want to quickly check if an indicator of compromise like a website or file has been reported as malicious by others in the cybersecurity community. For this activity, I used VirusTotal to analyze a file hash, which was reported as malicious. This incident occurred in the Detection and Analysis phase. The scenario put me in the place of a security analyst at a SOC investigating a suspicious file hash. After the suspicious file was detected by the security systems in place, I had to perform deeper analysis and investigation to determine if the alert signified a real threat.

**The 5 W's**:
- **Who**: An unknown malicious actor
- **What**: An email sent to an employee contained a malicious file attachment with the SHA-256 file hash of `54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b`
- **Where**: An employee's computer at a financial services company
- **When**: At 1:20 p.m., an alert was sent to the organization's SOC after the intrusion detection system detected the file
- **Why**: An employee was able to download and execute a malicious file attachment via e-mail.

**Additional notes**: How can this incident be prevented in the future? Should we consider improving security awareness training so that employees are careful with what they click on?

---


