# Cyber Threat Intelligence (CTI), OSINT & Threat Analysis

## Overview

This session focused on **Cyber Threat Intelligence (CTI)**, Open-Source Intelligence (OSINT), phishing analysis, cybercrime trends, threat intelligence frameworks, and modern defensive security concepts.

The primary objective was understanding how security professionals transform raw threat data into actionable intelligence that helps organizations defend against cyber threats.

---

# What is Cyber Threat Intelligence (CTI)?

Cyber Threat Intelligence (CTI) is the process of collecting, analyzing, and interpreting information about cyber threats, threat actors, vulnerabilities, and attack techniques.

The goal of CTI is to enable organizations to make informed security decisions and proactively defend against attacks.

## Intelligence Process

```text
Raw Data
    ↓
Information
    ↓
Analysis
    ↓
Actionable Intelligence
```

### Example

Finding a suspicious IP address is only data.

```text
185.xxx.xxx.xxx
```

After investigation, if security researchers discover that the IP belongs to a ransomware operator and has been reported in previous attacks, it becomes actionable intelligence.

Organizations can then:

* Block the IP
* Create SIEM detection rules
* Alert security teams
* Monitor related activity

---

# Indicators of Compromise (IoCs)

Indicators of Compromise are artifacts that indicate malicious activity within a system or network.

## Examples

* Malicious IP addresses
* Domains
* URLs
* Email addresses
* File hashes
* Registry modifications

### Sample IoCs

```text
Hash:
44d88612fea8a8f36de82e1278abb02f

Domain:
malicious-example.com

IP:
192.168.x.x
```

IoCs are commonly used in:

* Threat Hunting
* Incident Response
* Threat Intelligence Platforms
* SIEM Solutions

---

# Cyber Crime in India

The rapid adoption of digital services has significantly increased cybercrime activities.

## Common Cyber Crimes

### Financial Fraud

* UPI scams
* Banking fraud
* Credit card fraud

### Phishing

Fake emails and websites designed to steal credentials.

### Identity Theft

Attackers impersonate victims to commit fraud.

### Ransomware

Attackers encrypt files and demand payment.

### Social Engineering

Manipulating individuals into revealing sensitive information.

---

# Homographic Attacks

A Homographic Attack uses visually similar characters to deceive users.

## Example

Legitimate Domain:

```text
google.com
```

Malicious Domain:

```text
gооgle.com
```

The attacker replaces letters with Unicode characters that appear identical to legitimate ones.

## Risks

* Credential Theft
* Phishing
* Brand Impersonation
* Malware Distribution

## Prevention

* Carefully inspect URLs
* Use password managers
* Enable Multi-Factor Authentication (MFA)
* Use browser security protections

---

# Open Source Intelligence (OSINT)

OSINT refers to collecting intelligence from publicly available sources.

## Common Sources

* Search Engines
* Social Media Platforms
* WHOIS Records
* Public Databases
* News Sources
* Government Records

## Applications

* Threat Intelligence
* Cyber Investigations
* Brand Monitoring
* Security Research
* Attack Surface Analysis

---

# OSINT Investigation Workflow

## 1. Define Objectives

Determine what information is required.

Examples:

* Email Investigation
* Domain Investigation
* Person Investigation

---

## 2. Collect Data

Gather information from:

* Google
* LinkedIn
* WHOIS
* Social Media
* Public Records

---

## 3. Analyze Information

Identify:

* Patterns
* Relationships
* Connections

---

## 4. Validate Findings

Cross-reference information using multiple sources.

---

## 5. Report Results

Present findings in a structured and actionable format.

---

# Phishing Analysis

Phishing is a social engineering technique used to steal sensitive information.

## Analysis Process

### Email Header Analysis

Identify:

* Sender
* Return Path
* Originating Server

### URL Analysis

Check:

* Domain Reputation
* Domain Age
* Typosquatting Indicators

### Attachment Analysis

Inspect for:

* Macros
* Malware
* Suspicious Behavior

### Common Indicators

* Urgency
* Threatening Language
* Suspicious Links
* Poor Grammar

---

# Modern Threat Landscape

Organizations face threats from multiple adversaries.

## Nation-State Actors

Government-sponsored attackers.

## Cyber Criminals

Financially motivated groups.

## Insider Threats

Employees or contractors with malicious intent.

## Hacktivists

Attackers motivated by ideology or activism.

## Organized Crime Groups

Professional cybercriminal organizations.

---

# Attack Surface

The Attack Surface consists of all possible entry points an attacker can exploit.

## External Attack Surface

* Websites
* APIs
* Email Servers

## Internal Attack Surface

* Workstations
* Databases
* Internal Applications

## Human Attack Surface

* Employees
* Contractors
* Third Parties

---

# CIA Triad

The CIA Triad is the foundation of Information Security.

## Confidentiality

Protecting information from unauthorized access.

### Examples

* Encryption
* Access Controls
* Authentication

---

## Integrity

Ensuring information remains accurate and unaltered.

### Examples

* Hashing
* Digital Signatures

---

## Availability

Ensuring systems and data remain accessible when needed.

### Examples

* Backups
* Redundancy
* Disaster Recovery

---

# Cyber Kill Chain

The Cyber Kill Chain, developed by Lockheed Martin, describes the stages of a cyber attack.

## Seven Stages

### 1. Reconnaissance

Information gathering.

### 2. Weaponization

Creating malicious payloads.

### 3. Delivery

Sending the payload.

### 4. Exploitation

Triggering a vulnerability.

### 5. Installation

Installing malware.

### 6. Command & Control (C2)

Establishing communication with attacker infrastructure.

### 7. Actions on Objectives

Achieving the attacker's goals.

---

# CTI Lifecycle

The Cyber Threat Intelligence Lifecycle ensures intelligence is continuously improved.

## Stages

1. Direction
2. Collection
3. Processing
4. Analysis
5. Dissemination
6. Feedback

---

# MITRE ATT&CK Framework

MITRE ATT&CK is a globally recognized knowledge base of adversary tactics and techniques.

## Benefits

* Threat Hunting
* Attack Simulation
* Detection Engineering
* Incident Response

### Examples of ATT&CK Tactics

* Initial Access
* Execution
* Persistence
* Privilege Escalation
* Defense Evasion
* Credential Access
* Lateral Movement

---

# Endpoint Detection and Response (EDR)

EDR solutions continuously monitor endpoint devices for suspicious activity.

## Functions

* Threat Detection
* Threat Hunting
* Incident Investigation
* Automated Response

### Popular EDR Solutions

* CrowdStrike Falcon
* SentinelOne
* Microsoft Defender for Endpoint

---

# CERT-In

CERT-In stands for:

**Computer Emergency Response Team – India**

It is India's national cybersecurity incident response agency.

## Responsibilities

* Incident Response
* Vulnerability Advisories
* Threat Intelligence Sharing
* Security Alerts
* National Cyber Coordination

---

# Key Takeaways

* CTI transforms raw data into actionable intelligence.
* OSINT plays a critical role in investigations and threat hunting.
* MITRE ATT&CK helps understand attacker behavior.
* EDR improves endpoint visibility and response capabilities.
* CERT-In is a key component of India's cybersecurity ecosystem.
* The Cyber Kill Chain helps defenders understand attack progression.
