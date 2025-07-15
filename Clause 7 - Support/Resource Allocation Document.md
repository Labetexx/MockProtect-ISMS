# DOC-008 Resource Allocation Document

**DOCUMENT CLASSIFICATION:** Internal  
**VERSION:** 1  
**DATE:** 3rd June 2025  
**DOCUMENT AUTHOR:** Shahaan Umer  
**DOCUMENT OWNER:** MockProtect  

---

## VERSION HISTORY

| VERSION | DATE | REVISION AUTHOR | SUMMARY OF CHANGES |
|---------|------|-----------------|--------------------|
|         |      |                 |                    |

---

## DISTRIBUTION LIST

| NAME            | POSITION | SUMMARY OF CHANGES |
|-----------------|----------|--------------------|
| Jhon Doe        | CEO      |                    |
| Jane Doe        | CISO     |                    |
| Max Mustermann  | CTO      |                    |

---

## APPROVAL

| NAME            | POSITION | APPROVAL STATUS         |
|-----------------|----------|------------------------|
| Jhon Doe        | CEO      | Signed: 03/06/2025     |
| Jane Doe        | CISO     | Signed: 03/06/2025     |
| Max Mustermann  | CTO      | Signed: 03/06/2025     |

---

## Table of Contents

1. [Purpose](#1-purpose)  
2. [Scope](#2-scope)  
3. [Identified Resource Requirements](#3-identified-resource-requirements)  
   - [Human Resources](#a-human-resources)  
   - [Technical Resources](#b-technical-resources)  
   - [Financial Resources](#c-financial-resources)  
4. [Resource Prioritization Based on Risk Assessment and SoA](#4-resource-prioritization-based-on-risk-assessment-and-soa)  
5. [Monitoring and Review](#5-monitoring-and-review)  

---

## 1. Purpose

This document ensures that adequate resources are allocated for the effective implementation, operation, maintenance, and continual improvement of the ISMS at MockProtect, in accordance with ISO/IEC 27001:2022 Clause 7 – Support.

---

## 2. Scope

This policy applies to:

1. All information assets managed by MockProtect, whether hosted on-premises or in the cloud.  
2. All employees, contractors, and third-party service providers who access or manage MockProtect’s systems and data.  
3. All platforms, including the MockProtect Mobile App, SIEM Integration Module, EDR Integration Service, SOAR Orchestration Engine, and Analytics Dashboard.  
4. All data types handled by MockProtect, including personal data, security incident metadata, analytics, and client configurations.

---

## 3. Identified Resource Requirements

### a. Human Resources

| Role                     | Description / Responsibility                       | Allocation Status |
|-------------------------|----------------------------------------------------|-------------------|
| Information Security Officer | Lead ISMS planning and implementation          | Assigned          |
| Risk Management Team    | Conduct risk identification and treatment planning | Assigned          |
| Compliance Officer      | Monitor regulatory and standards compliance        | Assigned          |
| IT Support Engineers    | Deploy, configure, and monitor security controls   | Assigned          |
| ISMS Trainers           | Deliver ISMS awareness and competency training     | Assigned          |

### b. Technical Resources

| Technology / Tool               | Purpose                                 | Allocation Status |
|---------------------------------|-----------------------------------------|-------------------|
| Access Control System (IAM/MFA) | Identity and access management          | Procured          |
| VPN & Firewall (e.g., Cisco ASA)| Secure remote access and network protection | Deployed       |
| Antivirus and EDR tools        | Endpoint protection and threat detection | Operational       |
| Document Management System      | Centralized ISMS policy/record control (e.g., SharePoint) | Operational |
| Backup & Recovery System       | Ensure data availability and resilience  | Operational       |

### c. Financial Resources

| Expense Area              | Purpose                                         | Estimated Budget (Annual) |
|--------------------------|-------------------------------------------------|---------------------------|
| Security Tool Subscriptions | Licensing for antivirus, VPN, firewall, EDR, etc. | $30,000                |
| Training & Awareness Programs | Annual awareness workshops, phishing simulations | $12,000              |
| External Audit Services  | Annual ISO 27001 certification or surveillance audits | $8,000               |
| Infrastructure Upgrades  | Firewalls, secure laptops, biometric locks, etc. | $20,000                |
| Professional Services    | Risk assessments, penetration testing, consulting | $10,000                |

---

## 4. Resource Prioritization Based on Risk Assessment and SoA

| Risk Area               | Priority | SoA Control Reference | Allocated Resources                           |
|------------------------|----------|----------------------|------------------------------------------------|
| Unauthorized Access    | High     | 5.15 Access Control  | MFA, IAM tools, access policies, regular audits |
| Phishing & User Error  | Medium   | 6.3 Awareness Training | Monthly awareness emails, LMS platform, phishing drills |
| Data Loss or Tampering | High     | 5.12 Data Integrity  | Backup systems, DLP tools, integrity checks    |
| System Downtime        | Medium   | 5.30 Redundancy      | Cloud failover systems, UPS, backup connectivity |
| Compliance Gaps        | High     | 5.1-5.4 Leadership   | Dedicated Compliance Officer, audit tracking systems |

---

## 5. Monitoring and Review

- Resource allocation is reviewed:
  - Annually during the ISMS Management Review.
  - Following any major change to systems, structure, or security posture.
  - Upon discovery of resource gaps in internal audits or incidents.
- Adjustments will be approved by the ISMS Committee and documented in the change control log.

