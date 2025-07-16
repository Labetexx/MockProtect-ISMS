# REC-026 Nonconformity Report

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

| NAME            | POSITION | APPROVAL STATUS       |
|-----------------|----------|----------------------|
| Jhon Doe        | CEO      | Signed: 03/06/2025   |
| Jane Doe        | CISO     | Signed: 03/06/2025   |
| Max Mustermann  | CTO      | Signed: 03/06/2025   |

---

## Table of Contents
1. Purpose  
2. Scope  
3. Nonconformity Summary  
4. Immediate Containment Actions  
5. Root Cause Analysis  
6. Corrective Actions  
7. Verification of Effectiveness  
8. Preventive Measures  
9. Closure Record  

---

## 1. Purpose

To document and address nonconformities identified within the ISMS, determine the root causes, define corrective actions, and ensure implementation to maintain compliance with ISO/IEC 27001:2022.

---

## 2. Scope

Covers all nonconformities identified via internal audits, security incidents, or observations within MockProtect's ISMS scope.

---

## 3. Nonconformity Summary

| NC ID        | Source           | Description                                     | Date Identified | Severity |
|--------------|------------------|-------------------------------------------------|-----------------|----------|
| NC-2025-04   | Internal Audit   | Access review records were not maintained for Q1 2025 | 15/05/2025      | Major    |
| NC-2025-05   | Security Incident| Unauthorized access to confidential payroll folder | 20/05/2025      | Major    |

---

## 4. Immediate Containment Actions

| NC ID        | Action Taken                                     | Date         | Responsible        |
|--------------|--------------------------------------------------|--------------|--------------------|
| NC-2025-04   | Notified IT Security and Compliance Teams. Access review initiated. | 16/05/2025    | Compliance Officer |
| NC-2025-05   | Revoked unauthorized access and started investigation.              | 21/05/2025    | SOC Manager        |

---

## 5. Root Cause Analysis

### NC-2025-04
**Method Used:** 5 Whys  
- Ownership for access reviews was not clearly assigned.  
- No automated workflow or reminders existed in the ITSM platform.  
- No training or compliance awareness for quarterly access reviews.  

### NC-2025-05
**Method Used:** RCA Template  
- Inadequate review of user privileges.  
- Lack of timely revocation of terminated user access.  
- Weak configuration of folder-level access permissions.  

---

## 6. Corrective Actions

| NC ID        | Corrective Action                                           | Due Date      | Responsible          | Status        |
|--------------|------------------------------------------------------------|---------------|---------------------|---------------|
| NC-2025-04   | Assign access review responsibility to Security Lead       | 01/06/2025    | IT Security Lead     | In Progress   |
| NC-2025-04   | Update SOP and integrate access review workflow in ticketing tool | 10/06/2025    | ISMS Manager         | Planned       |
| NC-2025-05   | Perform privilege audit of sensitive folders               | 05/06/2025    | SOC Manager          | In Progress   |
| NC-2025-05   | Implement stricter folder access controls and update Access Control Policy | 12/06/2025    | Compliance Officer   | Planned       |
| NC-2025-05   | Conduct refresher training on secure access protocols      | 15/06/2025    | HR / ISO             | Planned       |

---

## 7. Verification of Effectiveness

| Corrective Action                                | Verification Method               | Verifier           | Due Date      | Status        |
|--------------------------------------------------|-----------------------------------|--------------------|---------------|---------------|
| Access reviews performed for Q2                  | Sample audit and system check     | Internal Auditor   | 30/06/2025    | Pending       |
| Unauthorized access blocked and folder permissions corrected | System access logs review          | SOC Analyst        | 30/06/2025    | Pending       |
| Updated SOP and training material circulated     | Policy review and employee sign-off | Compliance Officer | 25/06/2025    | Pending       |

---

## 8. Preventive Measures

- Automate quarterly access review alerts via ITSM.  
- Add access review metrics to monthly ISMS dashboard.  
- Enforce review sign-offs for privileged accounts.  
- Mandatory annual secure access refresher training for all users.  

---

## 9. Closure Record

| NC ID        | Closure Date | Closure Approved By | Remarks                          |
|--------------|--------------|--------------------|----------------------------------|
| NC-2025-04   | TBD          | ISMS Manager       | Awaiting workflow integration    |
| NC-2025-05   | TBD          | ISMS Manager       | To be validated via audit review |

---

