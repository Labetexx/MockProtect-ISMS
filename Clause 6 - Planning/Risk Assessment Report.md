# REC-004 Risk Assessment Report

**DOCUMENT CLASSIFICATION:** Internal  
**VERSION:** 1  
**DATE:** 10th June 2025  
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

| NAME            | POSITION | APPROVAL STATUS          |
|-----------------|----------|-------------------------|
| Jhon Doe        | CEO      | Signed: 03/06/2025      |
| Jane Doe        | CISO     | Signed: 03/06/2025      |
| Max Mustermann  | CTO      | Signed: 03/06/2025      |

---

## Table of Contents

1. Introduction  
2. Risk Assessment Context  
    2.1 Internal and External Context  
    2.2 Scope  
    2.3 Criteria for performing Information Security Risk Assessment  
    2.4 Risk Scoring  
    2.5 Risk Analysis Heatmap  
3. Risk Assessment Results Summary  
    3.1 Risk Assessment details  

---

## 1. Introduction

This report outlines the risk assessment conducted for MockProtect as a part of the ISO 27001:2022 compliance efforts. The purpose is to identify, analyse and prioritise information security risks that could impact the organisation’s assets, data and operations. This report would serve as foundation for development risk treatment plans.

---

## 2. Risk Assessment Context

### 2.1 Internal and External Context

#### Internal Context

- **Business Model & Core Assets:**  
MockProtect is a SaaS-based cybersecurity company headquartered in Frankfurt, Germany, with around 1,700 employees, of which approximately 70% work remotely. Its flagship product is a mobile app delivering real-time security alerts from SIEM, EDR, and SOAR systems, plus an analytics dashboard and response orchestration engine.

- **Organizational Structure & Governance:**  
    - Key leadership: CEO, CISO, CTO, ISMS Project Lead.  
    - Departments include Security Engineering, Product, DevOps, IT, HR, Compliance, and Client Services.  
    - ISMS initiative is aligned with ISO/IEC 27001:2022, spearheaded by top management.

- **Processes & Culture:**  
Agile product development and DevOps with on-premises DevOps infrastructure, strong emphasis on continuous delivery and innovation. Security is a guiding principle.

- **Technology & Operations:**  
    - Integration pipelines with SIEM, EDR, and SOAR platforms.  
    - Internal tooling for log ingestion, alert processing, and mobile notifications.  
    - Employee-owned and company-managed endpoints due to hybrid/remote work.

- **Internal Challenges:**  
    - Maintaining centralized visibility over distributed assets.  
    - Ensuring consistent security control and patching across remote devices.  
    - Bridging gaps in secure configuration and monitoring under ISO 27001 scope.

#### External Context

- **Regulatory & Compliance Landscape:**  
    - GDPR, UK-GDPR, NIS2 Directive, BDSG, TTDSG, ePrivacy  
    - Pursuing ISO 27001:2022 certification.

- **Customer Expectations:**  
    - Enterprise-grade security for financial, healthcare, and critical infrastructure clients.  
    - SLAs around uptime, alert accuracy, and compliance standards.

- **Threat Environment:**  
    - Targeted by APTs, zero-day exploits, supply-chain attacks.  
    - Exposure due to third-party service providers.

- **Market & Competitive Pressure:**  
    - Competing with global MSSPs and cloud-native services.  
    - Need for mobile-first incident response solutions.

---

### 2.2 Scope

This Risk Assessment applies to all assets, personnel, systems, and services within the ISMS scope of MockProtect, including products like the SIEM Integration Module, SOAR Orchestration Engine, and Analytics Dashboard.

---

### 2.3 Criteria for performing Information Security Risk Assessment

#### Likelihood

| Rating | Likelihood      | Description                              |
|--------|-----------------|------------------------------------------|
| 1      | Rare            | May occur only in exceptional circumstances |
| 2      | Unlikely        | Could happen, but not expected          |
| 3      | Possible        | Might occur at some point               |
| 4      | Likely          | Expected to occur in most cases         |
| 5      | Almost Certain  | Expected to occur frequently            |

#### Impact

| Rating | Impact Level    | Description                              |
|--------|-----------------|------------------------------------------|
| 1      | Insignificant   | Minimal impact, no data loss, negligible disruption |
| 2      | Minor           | Minor disruption, small data breach     |
| 3      | Moderate        | Noticeable impact, moderate data breach |
| 4      | Major           | Significant impact, customer data compromised |
| 5      | Critical        | Severe operational failure, legal penalties, reputational damage |

---

### 2.4 Risk Scoring

Risk Score = Likelihood × Impact

| Risk Score Range | Risk Level  | Action Required                                            |
|------------------|-------------|------------------------------------------------------------|
| 1–2              | Very Low    | Minimal risk. Monitor.                                     |
| 3–4              | Low         | Acceptable. Monitor periodically.                          |
| 5–9              | Medium      | Requires management attention. Plan mitigation or justify. |
| 10–15            | High        | Action required. Develop and monitor mitigation plan.      |
| 16–25            | Very High   | Immediate action required. Implement risk treatment ASAP.  |

---

### 2.5 Risk Analysis Heatmap

| Impact ↓ / Likelihood → | 1 (Rare) | 2 (Unlikely) | 3 (Possible) | 4 (Likely) | 5 (Almost Certain) |
|------------------------|----------|--------------|--------------|------------|--------------------|
| 1 (Insignificant)      | 1 Very Low | 2 Very Low  | 3 Low       | 4 Low      | 5 Medium           |
| 2 (Minor)              | 2 Very Low | 4 Low       | 6 Medium    | 8 Medium   | 10 High            |
| 3 (Moderate)           | 3 Low      | 6 Medium    | 9 Medium    | 12 High    | 15 High            |
| 4 (Major)              | 4 Low      | 8 Medium    | 12 High     | 16 Very High | 20 Very High      |
| 5 (Critical)           | 5 Medium   | 10 High     | 15 High     | 20 Very High | 25 Very High      |

---

## 3. Risk Assessment Results Summary

| Risk ID  | Risk Description | Asset | Risk Score | Risk Treatment | ISO 27001:2022 Ref | Residual Risk Score |
|----------|------------------|-------|------------|----------------|-------------------|---------------------|
| RSK-001  | Insecure public API exposure due to missing authentication and rate limiting | API Gateway, Backend Microservices, Customer Data, Authentication System | 12 (High) | Mitigate – Implement API authentication (OAuth 2.0), enforce rate limiting, use WAF | 8.23, 8.28, 8.25 | 6 (Medium - Accepted) |
| RSK-002  | Lack of security awareness leading to phishing and mishandling of sensitive data | Employees, Email System, Client Data, Workstations | 12 (High) | Mitigate – Conduct security awareness training, implement phishing simulation, restrict external email forwarding | 6.3, 8.9, 5.17 | 4 (Low) |

---

## 3.1 Risk Assessment details

### RSK-001 Insecure API Exposure

- **Risk ID:** RSK-001  
- **ISO 27001:2022 Ref:** A.8.25 (Secure Development), A.8.29 (Supplier Relationships)  
- **Date Identified:** 15/06/2025  
- **Clause/Control:** Secure Development, Supplier Relationships  
- **Risk Description:** Insecure public API exposure due to missing authentication and rate limiting  
- **Asset(s) Affected:** API Gateway, Backend Microservices, Customer Data, Authentication System  
- **Asset Type:** Technical  
- **Vulnerability:** No authentication, no rate limiting  
- **Threat:** Unauthorized access, Denial of Service (DoS)  
- **Outcome/Consequence:** Data leakage, impersonation  
- **CIA Impact:** Confidentiality, Availability  
- **Existing Control:** JWT tokens, IP filter  
- **Control Effectiveness:** Medium  
- **Impact Score:** 4  
- **Likelihood Score:** 3  
- **Risk Score:** 12  
- **Risk Level:** High  
- **Risk Owner:** Head of Engineering  
- **Treatment Option:** Mitigate  
- **Treatment Plan:** Implement OAuth2.0, WAF, and rate limiting  
- **Risk Treatment Owner:** DevOps Lead  
- **Target Date:** 15/07/2025  
- **Status:** In Progress  
- **Residual Impact:** 3  
- **Residual Likelihood:** 2  
- **Residual Risk Score:** 6  
- **Residual Risk Level:** Medium  
- **Accepted?:** Yes  
- **Last Updated:** 15/06/2025  
- **Notes:** Public APIs seeing probes  
- **Next Review Date:** 01/08/2025  

---

### RSK-002 Insider Awareness & Human Error

- **Risk ID:** RSK-002  
- **ISO 27001:2022 Ref:** A.6.3 (Security Awareness), A.6.4 (Disciplinary Process)  
- **Date Identified:** 15/06/2025  
- **Clause/Control:** Security Awareness, Disciplinary Process  
- **Risk Description:** Lack of security awareness leading to phishing and data mishandling  
- **Asset(s) Affected:** Employees (Staff Users), Email System, Client Data, Workstations  
- **Asset Type:** Human / Information / Technical  
- **Vulnerability:** No structured training program  
- **Threat:** Phishing, human error  
- **Outcome/Consequence:** Reputational loss, data breach  
- **CIA Impact:** Confidentiality, Integrity  
- **Existing Control:** Onboarding guidance only  
- **Control Effectiveness:** Low  
- **Impact Score:** 3  
- **Likelihood Score:** 4  
- **Risk Score:** 12  
- **Risk Level:** High  
- **Risk Owner:** HR Manager  
- **Treatment Option:** Mitigate  
- **Treatment Plan:** Conduct formal training and phishing simulations  
- **Risk Treatment Owner:** Compliance Officer  
- **Target Date:** 10/07/2025  
- **Status:** Not Started  
- **Residual Impact:** 2  
- **Residual Likelihood:** 2  
- **Residual Risk Score:** 4  
- **Residual Risk Level:** Low  
- **Accepted?:** Yes  
- **Last Updated:** 15/06/2025  
- **Notes:** Needs formal training policy  
- **Next Review Date:** 01/08/2025  
