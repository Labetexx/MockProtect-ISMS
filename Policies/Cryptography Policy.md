# PL-006 Cryptography Policy

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
3. [Policy Statement](#3-policy-statement)  
4. [Roles and Responsibilities](#4-roles-and-responsibilities)  
5. [Compliance and Exceptions](#5-compliance-and-exceptions)  
6. [Related Documents](#6-related-documents)  
7. [Review and Maintenance](#7-review-and-maintenance)  

---

## 1. Purpose

The purpose of this Cryptographic Policy is to establish requirements for the proper use, management, and protection of cryptographic controls to ensure the confidentiality, integrity, and authenticity of data within MockProtect’s information systems and services. This policy supports compliance with ISO/IEC 27001:2022 controls 8.24, 8.25, and 8.26.

---

## 2. Scope

This policy applies to:

i. All information assets managed by MockProtect, whether hosted on-premises or in the cloud.  
ii. All employees, contractors, and third-party service providers who access or manage MockProtect’s systems and data.  
iii. All platforms, including:  
  – MockProtect Mobile App  
  – SIEM Integration Module  
  – EDR Integration Service  
  – SOAR Orchestration Engine  
  – Analytics Dashboard  
iv. All data types handled by MockProtect, including:  
  – Personal data  
  – Security incident metadata  
  – Analytics  
  – Client configurations  

---

## 3. Policy Statement

i. All sensitive data must be encrypted at rest and in transit using approved cryptographic algorithms and protocols (e.g., AES-256, RSA-2048, TLS 1.3).  
ii. MockProtect shall maintain a list of approved cryptographic standards aligned with industry best practices and regulatory requirements.  
iii. Cryptographic keys must be generated, distributed, stored, rotated, and destroyed securely and in accordance with the key management lifecycle.  
iv. Private keys must not be shared and shall be protected using hardware security modules (HSMs) or equivalent secure key storage mechanisms.  
v. Symmetric encryption should be used where appropriate for performance, but only with secure key exchange mechanisms (e.g., Diffie-Hellman, ECDH).  
vi. All public key certificates used for server authentication must be issued by a trusted Certificate Authority (CA) and monitored for expiry and revocation.  
vii. The use of deprecated or weak algorithms (e.g., MD5, SHA-1, DES) is prohibited.  
viii. All cryptographic implementations (libraries, APIs, etc.) must be vetted and approved by the Security team before use in production environments.  
ix. End-to-end encryption (E2EE) should be implemented for customer-facing communication channels.  
x. MockProtect shall periodically review and update cryptographic practices to reflect emerging threats and advancements in technology.  

---

## 4. Roles and Responsibilities

| Role                    | Responsibility                                                                 |
|------------------------|-------------------------------------------------------------------------------|
| Chief Information Security Officer (CISO) | Approves and oversees cryptographic strategy and compliance.             |
| Security Architect     | Defines cryptographic standards and reviews cryptographic architecture.       |
| DevOps & Engineering Teams | Implement and maintain cryptographic controls within applications and infrastructure. |
| IT Operations          | Manages encryption for data at rest and secure communication protocols.       |
| Compliance Officer     | Ensures alignment with regulatory requirements and ISO standards.             |

---

## 5. Compliance and Exceptions

All employees, contractors, and third-party service providers must comply with the requirements defined in this Cryptography Policy. Failure to adhere to the policy may result in disciplinary action, including but not limited to access revocation, termination of contract, or legal consequences, depending on the severity of the violation.

Exceptions to this policy shall only be granted through formal approval by the Information Security Officer (ISO) and must be documented, justified, and reviewed annually. Any deviation without prior approval shall be considered a policy violation.

---

## 6. Related Documents

The following documents support and are referenced by this Cryptography Policy:

i. Information Security Policy  
ii. Access Control Policy  
iii. Risk Management Policy  
iv. Data Classification & Handling Policy  
v. Secure Development & Change Management Policy  
vi. Cloud Security Policy  
vii. Incident Management Policy  
viii. Key Management Standard (if separate)  
ix. Acceptable Use Policy  

---

## 7. Review and Maintenance

This policy shall be reviewed annually or upon significant changes to cryptographic practices, regulatory requirements, or the threat landscape. Updates must be approved by the CISO and communicated to all relevant stakeholders.
