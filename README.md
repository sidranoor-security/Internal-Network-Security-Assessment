# 🛡️ Internal Network Security Assessment

## 📌 Project Overview

The **Internal Network Security Assessment** is a practical cybersecurity project focused on identifying, analyzing, and documenting security weaknesses within an internal network environment.

The assessment covers network reconnaissance, host discovery, port scanning, service enumeration, network traffic analysis, vulnerability assessment, security monitoring, risk analysis, and security recommendations.

The project was developed and tested in a controlled laboratory environment using **VMware Workstation and Kali Linux**, with security analysis supported by **Nmap, Wireshark, and Wazuh**.

---

## 🎯 Project Objectives

- Identify active hosts within an internal network.
- Discover open ports and exposed services.
- Perform service enumeration and network reconnaissance.
- Analyze network traffic for suspicious or unusual activity.
- Identify potential vulnerabilities and security weaknesses.
- Monitor security events and logs using Wazuh.
- Assess security risks associated with identified findings.
- Provide practical recommendations for improving internal network security.

---

## 🔍 Project Scope

The assessment focuses on:

- Internal network reconnaissance
- Host discovery
- Port scanning
- Service enumeration
- Network traffic analysis
- Vulnerability assessment
- Security monitoring
- Log analysis
- Risk identification
- Security recommendations

All testing was performed within an authorized and controlled laboratory environment.

---

## 🏗️ Lab Environment

The project was implemented in a virtualized laboratory environment using:

- **VMware Workstation** — Virtualization platform
- **Kali Linux** — Security testing and assessment platform
- **Nmap** — Network discovery and port scanning
- **Wireshark** — Network traffic analysis
- **Wazuh** — Security monitoring and log analysis

### 📸 Lab Environment

> Add VMware + Kali Linux screenshot here.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Kali Linux** | Security assessment and testing environment |
| **Nmap** | Host discovery, port scanning, and service enumeration |
| **Wireshark** | Network packet capture and traffic analysis |
| **Wazuh** | Security monitoring, event detection, and log analysis |
| **VMware Workstation** | Virtualized laboratory environment |

---

# 🔄 Assessment Methodology

## 1. Network Reconnaissance

The first stage focused on understanding the internal network environment and identifying available hosts.

Activities included:

- Identifying the network range
- Checking network configuration
- Determining the local IP address
- Identifying potential target hosts

### 📸 Network Configuration

> Add screenshot of network/IP configuration here.

---

## 2. Host Discovery

Nmap was used to identify active hosts within the authorized laboratory network.

The purpose of this stage was to determine which systems were reachable and available for further assessment.

### 📸 Nmap Host Discovery

> Add Nmap host discovery screenshot here.

---

## 3. Port Scanning

After identifying active hosts, Nmap was used to examine open ports and identify exposed network services.

This helped determine the attack surface of the assessed systems.

### 📸 Nmap Port Scan

> Add Nmap open ports screenshot here.

---

## 4. Service Enumeration

The discovered ports were further analyzed to identify the services and versions associated with them.

Service enumeration helps security analysts understand what applications are exposed and require additional security review.

### 📸 Service Enumeration

> Add Nmap service/version detection screenshot here.

---

## 5. Network Traffic Analysis

Wireshark was used to capture and analyze network traffic within the laboratory environment.

The analysis focused on understanding network communication and identifying potentially suspicious or unusual traffic patterns.

### 📸 Wireshark Analysis

> Add Wireshark packet analysis screenshot here.

---

## 6. Vulnerability Assessment

The identified hosts, ports, and services were reviewed to identify potential vulnerabilities, insecure configurations, and unnecessary exposure.

The findings were analyzed according to their potential security impact.

### 📸 Vulnerability Assessment

> Add relevant vulnerability assessment screenshot here.

---

## 7. Security Monitoring with Wazuh

Wazuh was used for security monitoring and log analysis.

The platform provided visibility into security events, system activity, and potentially suspicious behavior within the monitored environment.

### 📸 Wazuh Dashboard

> Add Wazuh dashboard screenshot here.

### 📸 Wazuh Security Event

> Add relevant Wazuh alert/event screenshot here.

---

# 📊 Security Findings

The assessment findings were documented based on observed network configuration, exposed services, traffic analysis, and security monitoring results.

| Finding | Category | Risk | Recommendation |
|---------|----------|------|----------------|
| Open network ports | Network Exposure | Medium | Restrict unnecessary ports and services |
| Exposed services | Attack Surface | Medium | Disable unnecessary services and apply security controls |
| Potentially insecure configuration | Configuration | Medium | Review and harden system configuration |
| Suspicious or abnormal traffic | Network Activity | Depends on finding | Investigate and monitor related traffic |
| Security monitoring events | Monitoring | Depends on event | Investigate alerts and strengthen monitoring |

> Replace these example findings with the actual findings identified during the assessment.

---

# ⚠️ Risk Analysis

Security findings were considered based on their potential impact on:

- Confidentiality
- Integrity
- Availability
- Network exposure
- Unauthorized access
- System security

Risk prioritization helps determine which security issues should be addressed first.

---

# 🛡️ Security Recommendations

Based on the assessment, the following security improvements are recommended:

- Disable unnecessary network services.
- Restrict unnecessary open ports.
- Apply appropriate firewall rules.
- Keep operating systems and services updated.
- Use strong authentication and access controls.
- Monitor network activity for suspicious behavior.
- Regularly review security logs and alerts.
- Implement continuous security monitoring.
- Perform periodic vulnerability assessments.
- Maintain proper network segmentation where appropriate.

---

# 📈 Expected Outcomes

The project provides practical experience in:

- Internal network reconnaissance
- Network mapping
- Host discovery
- Port scanning
- Service enumeration
- Packet analysis
- Vulnerability assessment
- Security monitoring
- Log analysis
- Risk assessment
- Security documentation

The assessment demonstrates how different cybersecurity tools can be combined to improve visibility and identify weaknesses within an internal network.

---

# 🧪 Practical Evidence

The following evidence is maintained as part of the project documentation:

- Network configuration screenshots
- Nmap scanning results
- Open port and service results
- Wireshark packet analysis
- Wazuh monitoring dashboard
- Wazuh security alerts
- Vulnerability assessment results
- Security findings and recommendations

---

# 📁 Project Structure

```text
Internal-Network-Security-Assessment/
│
├── README.md
│
├── screenshots/
│   ├── lab-environment/
│   ├── network-discovery/
│   ├── nmap/
│   ├── wireshark/
│   ├── wazuh/
│   └── findings/
│
├── reports/
│   └── final-report.pdf
│
└── documentation/
    └── methodology.md
