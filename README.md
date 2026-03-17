# cyart-soc-team

This repository contains the practical exercises completed during **Week 2 of SOC training**.
The project demonstrates the **Security Operations Center (SOC) workflow**, including alert management, incident response, alert triage, evidence preservation, and a full alert-to-response investigation.

## Tools Used

* Wazuh (SIEM)
* TheHive (Incident Response Platform)
* Metasploit
* CrowdSec
* Velociraptor
* VirusTotal
* AlienVault OTX
* Google Sheets
* Google Docs

## Practical Tasks

The following SOC activities were completed:

1. **Alert Management Practice**

   * Created an alert classification system
   * Prioritized alerts using CVSS scoring
   * Created a Wazuh alert dashboard
   * Generated an incident ticket in TheHive
   * Simulated alert escalation via email

2. **Response Documentation**

   * Prepared an incident response report
   * Documented investigation timeline and remediation steps

3. **Alert Triage Practice**

   * Investigated alerts detected in Wazuh
   * Validated indicators using VirusTotal and AlienVault OTX
   * Documented triage results

4. **Evidence Preservation**

   * Collected volatile network data using Velociraptor
   * Acquired memory artifacts
   * Verified evidence integrity using SHA256 hashing
   * Documented chain-of-custody

5. **Capstone Project – Full Alert-to-Response Cycle**

   * Simulated an attack using Metasploit
   * Detected activity in Wazuh
   * Performed alert triage
   * Blocked attacker IP using CrowdSec
   * Documented the incident and stakeholder briefing

## Repository Structure

```
Week2
│
├── 1_Alert_Management_Practice
├── 2_Response_Documentation
├── 3_Alert_Triage_Practice
├── 4_Evidence_Preservation
└── 5_Capstone_Project
```

Each folder contains the **documentation, screenshots, and reports** related to the practical tasks performed during the SOC investigation.

## Objective

The objective of this project is to simulate a real SOC analyst workflow and demonstrate the ability to:

* Investigate security alerts
* Validate threats using intelligence platforms
* Preserve forensic evidence
* Respond to security incidents
* Document findings and communicate results
