# DOC-003 ISMS Scope and Context

## Document Details
- **Document Classification**: Internal
- **Version**: 1
- **Date**: 3rd June 2025
- **Document Author**: Shahaan Umer
- **Document Owner**: MockProtect

---

## Version History

| Version | Date | Revision Author | Summary of Changes |
|---------|------|-----------------|--------------------|
|         |      |                 |                    |

---

## Distribution List

| Name             | Position | Summary of Changes |
|------------------|----------|--------------------|
| Jhon Doe         | CEO      |                    |
| Jane Doe         | CISO     |                    |
| Max Mustermann   | CTO      |                    |

---

## Approval

| Name             | Position | Approval Status            |
|------------------|----------|--------------------------|
| Jhon Doe         | CEO      | Signed: 03/06/2025       |
| Jane Doe         | CISO     | Signed: 03/06/2025       |
| Max Mustermann   | CTO      | Signed: 03/06/2025       |

---

## Table of Contents

1. [Introduction](#1-introduction)
2. [Organization Context](#2-organization-context)
    - [2.1 Company Profile](#21-company-profile)
    - [2.2 Functions](#22-functions)
    - [2.3 Products and Services](#23-products-and-services)
3. [Internal and External Issues](#3-internal-and-external-issues)
    - [3.1 Internal Issues](#31-internal-issues)
    - [3.2 External Issues](#32-external-issues)
4. [Interested Parties and Their Requirements](#4-interested-parties-and-their-requirements)
    - [4.1 Interested Parties](#41-interested-parties)
    - [4.2 Applicable Legal and Regulatory Requirements](#42-applicable-legal-and-regulatory-requirements)
5. [Purpose and Scope of ISMS](#5-purpose-and-scope-of-isms)
    - [5.1 Purpose](#51-purpose)
    - [5.2 Scope Definition](#52-this-purpose-applies-to-the-scope-of-the-isms-as-defined-below)
    - [5.3 Potential Impact of an Information Security Incident](#53-potential-impact-of-an-information-security-incident)
    - [5.4 Information Security Objectives](#54-information-security-objectives)
    - [5.5 Scope of ISMS](#55-scope-of-isms)
        - [5.5.1 Organizational](#551-organizational)
        - [5.5.2 Products and Services](#552-products-and-services)
        - [5.5.3 Exclusions](#553-exclusions)

---

## 1. Introduction

MockProtect is dedicated to safeguarding the security of its business information against incidents and unexpected events. To achieve this, the company has established an Information Security Management System (ISMS) in accordance with ISO/IEC 27001:2022.

This document outlines:
- Organizational context
- Internal and external issues
- Interested parties and their requirements
- Scope and applicability of ISMS

This document is reviewed annually or when significant changes occur.

---

## 2. Organization Context

### 2.1 Company Profile

- **Company Name**: MockProtect GmbH
- **Headquarters**: Frankfurt am Main, Germany
- **Established**: 2017
- **Company Type**: Private, SaaS (Software-as-a-Service)
- **Core Offering**: Mobile-integrated cybersecurity alert and response platform
- **Markets Served**: European Union, United Kingdom, and global clients in regulated sectors

**Strategic Drivers**:
- Regulatory demands (EU GDPR, UK GDPR, NIS2 Directive)
- Robust ISMS implementation for trust and compliance

---

### 2.2 Functions

| Department               | Function / Responsibility                                                                 |
|-------------------------|------------------------------------------------------------------------------------------|
| Product Development     | Develops MockProtect app, integrates SIEM, EDR, SOAR                                      |
| DevSecOps               | Embeds security in SDLC, manages CI/CD pipelines                                          |
| IT Operations           | Manages IT infrastructure, user access, endpoint security                                 |
| Sales & Business Dev.   | Market expansion, partnerships, pre-sales support                                         |
| Customer Success        | Technical support, onboarding                                                             |
| Legal & Compliance      | Contract review, GDPR compliance, regulator liaison                                       |
| Human Resources         | Onboarding, offboarding, security training                                                |
| Marketing & Communications | Brand visibility, market trust                                                         |
| Finance & Procurement   | Budgeting, procurement, secure vendor services                                            |
| Internal Audit          | Monitors ISMS, performs audits, maintains risk registers                                  |
| Information Security    | Cybersecurity department, policy development                                              |

---

### 2.3 Products and Services

**Products under ISMS Scope**:
1. MockProtect Mobile App
2. SIEM Integration Module
3. EDR Integration Service
4. SOAR Orchestration Engine
5. Analytics & Reporting Dashboard

---

## 3. Internal and External Issues

### 3.1 Internal Issues

| Category         | Internal Issue                                                               |
|------------------|----------------------------------------------------------------------------|
| Organizational   | Lack of centralized security policy documentation                          |
| People & Culture | Varying security awareness, existing Shadow IT                             |
| Processes        | Inconsistent incident response                                             |
| Technology       | Rapid CI/CD pipelines lack security integration                            |
| Information Assets | Unclear data classification and ownership                                 |
| Access Control   | Gaps in RBAC enforcement                                                  |
| Vendor Management | Incomplete security assessments and SLAs                                  |
| Compliance       | Partial GDPR process implementation                                       |
| Monitoring       | Inconsistent log retention policies                                        |
| Resource Allocation | Limited ISMS monitoring staff                                           |
| Internal Communication | Decentralized communication tools                                    |
| Training & Awareness | Lack of structured cybersecurity training plan                          |

---

### 3.2 External Issues

| Category         | External Issue                                                               |
|------------------|----------------------------------------------------------------------------|
| Regulatory       | Evolving privacy regulations (GDPR, NIS2)                                   |
| Legal            | Data residency and transfer laws                                           |
| Market Expectations | ISO 27001 certification demand                                          |
| Technological    | AI-driven threats, zero-day attacks                                       |
| Economic         | Budget constraints affecting client expectations                           |
| Social / Cultural | Public concern over data breaches                                         |
| Political        | Brexit-related divergence                                                 |
| Industry         | Competition in SaaS cybersecurity                                         |
| Supply Chain     | Third-party dependencies                                                  |
| Environmental    | Focus on green IT                                                        |

---

## 4. Interested Parties and Their Requirements

### 4.1 Interested Parties

| Interested Party      | Legal & Regulatory Requirement | Contractual Obligation | Specific Needs & Expectations             |
|----------------------|--------------------------------|-----------------------|--------------------------------------------|
| Customers (EU & UK)  | GDPR, NIS2, UK GDPR            | SLAs, DPAs            | Data protection, availability, incident notifications |
| Employees            | GDPR, German Labour Laws      | Employment Contracts  | Secure access, policies, data privacy      |
| Top Management       | NIS2, BaFin                   | ISMS Commitment       | ISMS performance, risk visibility          |
| Regulatory Authorities | GDPR Supervisory Authorities | Reporting Obligations | Audit readiness, breach reporting          |
| Vendors/Suppliers    | GDPR, NIS2                    | Contracts, SLAs       | Data protection, risk assessments          |
| Internal IT & DevOps | GDPR, ISO 27001               | Internal SOPs         | Secure configurations, privileged access   |
| ISMS & Security Team | ISO 27001 clauses             | Roles & Responsibilities | Risk management process                   |
| Data Protection Officer | GDPR                        | Formal Mandate        | DPIAs, access to ISMS reports              |
| Shareholders         | NIS2, ESG Reporting          | Governance Frameworks | Risk assurance, certification roadmap      |
| Clients’ Auditors    | GDPR, ISO 27001               | Right to Audit        | ISMS proof, internal audit reports         |
| Incident Response Partners | NIS2 Coordination        | Incident Contracts    | Rapid response collaboration               |
| Application End Users | GDPR, ePrivacy               | Terms of Use          | Trust, secure app functionality            |

---

### 4.2 Applicable Legal and Regulatory Requirements

| Regulation / Standard | Relevance to MockProtect                                         |
|----------------------|------------------------------------------------------------------|
| EU GDPR              | Data protection for EU clients and users                         |
| UK GDPR              | Post-Brexit data protection compliance                           |
| NIS2 Directive       | Cybersecurity obligations for essential services                 |
| BDSG                 | German federal data protection law                               |
| TTDSG                | Regulates cookie usage                                           |
| ePrivacy Directive   | Communication metadata handling                                  |
| ISO/IEC 27001:2022   | ISMS framework implementation                                   |
| Employment Law       | Handling employee data across jurisdictions                      |
| Export Control Regulations | Dual-use technology compliance                              |
| Cyber Resilience Act | Upcoming EU regulation                                           |

---

## 5. Purpose of ISMS

### 5.1 Purpose

- Establish information security policy and objectives
- Manage information security incidents
- Monitor ISMS performance
- Continually improve information security management

---

### 5.2 Potential Impact of an Information Security Incident

- Loss of client trust
- Regulatory penalties
- Data breach exposure
- Service disruption
- Financial loss
- Operational downtime
- Reputational damage
- Loss of certification
- Client churn
- Increased insurance premiums

---

### 5.3 Information Security Objectives

1. Ensure Confidentiality, Integrity, and Availability (CIA)
2. Protect sensitive app data
3. Maintain legal and contractual compliance
4. Achieve ISO/IEC 27001:2022 certification
5. Minimize risks through structured processes
6. Ensure business continuity
7. Promote security awareness
8. Secure remote work
9. Continuously improve ISMS
10. Enforce access controls
11. Secure software development pipelines
12. Regularly test security controls

---

### 5.4 Scope of ISMS

#### 5.4.1 Organizational

- Headquarters in Frankfurt
- All service-delivery departments
- Core SaaS offerings
- IT systems and infrastructure
- Remote workforce operations
- Third-party providers
- Client and third-party data
- Legal and regulatory domains
- Information assets
- Human resources involved in security
- Security controls and procedures

#### 5.4.2 Products and Services

**Products Under ISMS Scope**:
1. MockProtect Mobile App
2. SIEM Integration Module
3. EDR Integration Service
4. SOAR Orchestration Engine
5. Analytics & Reporting Dashboard

#### 5.4.3 Exclusions

- Subsidiaries not involved in information processing
- Non-IT physical locations
- Non-critical systems or personal devices
- Non-information security-related activities

