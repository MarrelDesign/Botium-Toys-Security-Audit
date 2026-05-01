# 🛡️ Comprehensive IT Security & Compliance Audit: Botium Toys

## 📌 Executive Summary
This project represents a complete IT security audit and risk assessment for **Botium Toys**, a fictional e-commerce and retail company. The audit was conducted to evaluate the company's current security posture against industry standards, identify critical vulnerabilities, and provide a prioritized, low-cost remediation strategy.

The assessment revealed an unacceptable risk score of **8/10** due to systemic failures in asset management, access controls, and compliance adherence. 

## 🎯 Scope and Goals
* **Scope:** The entire security program at Botium Toys, including employee equipment, internal networks, legacy systems, and customer data handling (on-site and online).
* **Goals:** Complete a controls and compliance assessment, identify gaps using the **NIST Cybersecurity Framework (CSF)**, and implement security best practices to avoid catastrophic data loss and regulatory penalties.

## 🚨 Key Findings & Vulnerabilities
During the assessment, critical infrastructure flaws were identified across multiple domains:

* **Access Control:** No implementation of the Principle of Least Privilege (PoLP) or Separation of Duties. Employees have inappropriate access to cardholder data and internal databases.
* **Network Security:** Lack of an Intrusion Detection System (IDS) and insufficient monitoring of vulnerable legacy systems.
* **Business Continuity:** Total absence of automated backups for critical data and no Disaster Recovery Plan (DRP).
* **Authentication:** Non-compliant password policies with no centralized password management system or Multi-Factor Authentication (MFA).

## ⚖️ Compliance Gaps
The current infrastructure severely violates key international regulations, risking immense financial penalties:
* **PCI DSS:** Customer credit card transactions and data are not properly encrypted in transit or at rest.
* **GDPR:** Insufficient privacy policies and lack of encryption for E.U. customers' Personally Identifiable Information (PII).

## 🛠️ Prioritized Remediation Plan (Zero/Low-Cost Focus)
To mitigate the threat of business collapse without requiring immediate massive capital expenditure, the following action plan was developed for stakeholders:

### Phase 1: Immediate Survival (Zero Cost)
1. **Access Revocation:** Instantly enforce PoLP and Separation of Duties. Revoke broad access to PII and payment gateways.
2. **Backups & DRP:** Implement automated scripts for offline database backups and document a clear Disaster Recovery Plan.

### Phase 2: Authentication & Compliance (Open-Source Solutions)
1. **Password Enforcement:** Deploy an enterprise-grade, open-source password manager (e.g., Bitwarden) and enforce mandatory MFA for all administrative and internal access.
2. **Encryption:** Configure end-to-end encryption for all customer credit card data and PII to immediately align with PCI DSS and GDPR minimal standards.

### Phase 3: Active Defense
1. **Intrusion Detection:** Deploy an open-source IDS (Suricata or Snort) at the network perimeter to monitor malicious internal traffic.
2. **Legacy Isolation:** Establish strict VLAN isolation for unpatchable legacy systems and enforce mandatory manual monitoring schedules.

---
*Disclaimer: This portfolio project is a simulation based on real-world auditing scenarios and frameworks (NIST, PCI DSS, GDPR) designed to demonstrate practical risk assessment and mitigation planning.*
