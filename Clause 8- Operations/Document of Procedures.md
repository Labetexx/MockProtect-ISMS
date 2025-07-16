# SOP-001 Document of Procedures

**DOCUMENT CLASSIFICATION**: Internal  
**VERSION**: 1  
**DATE**: 3rd June 2025  
**DOCUMENT AUTHOR**: Shahaan Umer  
**DOCUMENT OWNER**: MockProtect  

---

## VERSION HISTORY

| VERSION | DATE | REVISION AUTHOR | SUMMARY OF CHANGES |
|---------|------|-----------------|--------------------|
|         |      |                 |                    |

---

## DISTRIBUTION LIST

| NAME           | POSITION | SUMMARY OF CHANGES |
|----------------|----------|--------------------|
| Jhon Doe       | CEO      |                    |
| Jane Doe       | CISO     |                    |
| Max Mustermann | CTO      |                    |

---

## APPROVAL

| NAME           | POSITION | APPROVAL STATUS       |
|----------------|----------|----------------------|
| Jhon Doe       | CEO      | Signed: 03/06/2025   |
| Jane Doe       | CISO     | Signed: 03/06/2025   |
| Max Mustermann | CTO      | Signed: 03/06/2025   |

---

## Table of Contents

- [Access Control Procedure (SOP-001)](#access-control-procedure-sop-001)
- [Incident Response Procedure (SOP-002)](#incident-response-procedure-sop-002)
- [Change Management Procedure (SOP-003)](#change-management-procedure-sop-003)

---

## Access Control Procedure (SOP-001)

### 1. Purpose

Define criteria and procedures for managing access to MockProtect’s information systems, ensuring only authorized users have access.

### 2. Scope

Applies to all systems, applications, cloud services, and infrastructure owned or managed by MockProtect.

### 3. Definitions

- **Access Control**: Selective restriction of access to systems or data.
- **Least Privilege**: Ensuring users have only necessary access.
- **Role-Based Access Control (RBAC)**: Access permissions assigned by job role.

### 4. Operational Criteria

| Control Area           | Criteria                                                         |
|-----------------------|------------------------------------------------------------------|
| Access Approval       | Formal request via ticketing, approved by Department Head & ISO. |
| Access Rights Review  | Quarterly review, remediated in 5 business days.                |
| Authentication        | MFA for critical systems, strong password policies.              |
| Termination of Access | Revoked within 24 hours of employee exit or role change.         |
| Privileged Access     | Business justification required, monitored regularly.            |

### 5. Responsibilities

| Role             | Responsibility                                               |
|------------------|-------------------------------------------------------------|
| ISO              | Policy alignment, monitoring, approval of critical access.  |
| HR               | Notify IT of onboarding, exits, role changes.               |
| IT Team          | Implement, revoke, review access rights, maintain logs.     |
| Department Heads | Approve access requests relevant to their department.       |

### 6. Procedure Steps

#### Step 1: Access Request

- Submit via IT Service Management Ticketing System.
- Include:
  - Full name, department, job title.
  - Business justification.
  - System/application name.
  - Access type.
  - Duration (if temporary).

#### Step 2: Approval Workflow

- **Manager Review**: Aligns request with role.
- **ISO Review**: Evaluates access sensitivity, risk analysis.
- Approvals logged.

#### Step 3: Provisioning Access

- IT Admin provisions access per role.
- User notified automatically.
- Verification by user and IT.

#### Step 4: Access Review and Validation

- Quarterly and monthly reviews (privileged access).
- Validation criteria:
  - Is access needed?
  - Is it appropriate to the current role?
  - Any unusual activity?

#### Step 5: Access Modification

- Triggered by role change, system upgrade, scope adjustment.
- Follows ticketing and approval process.

#### Step 6: Access Revocation

- Triggers: Employee exit, contract completion, role change.
- Line manager notifies HR & IT within 24 hours.
- IT revokes access in 1 business day.
- ISO validation and closure.

### 7. Protocol Based Overview

#### a. Privileged Access Management

- Justified and approved by ISO.
- Logged and monitored via SIEM.
- Monthly reviews.
- No shared/admin accounts unless justified.

#### b. Temporary Access

- Granted for specific tasks.
- Predefined duration.
- Automatically revoked.
- Audited post-task.

#### c. Emergency Access

- Break-glass procedure.
- Secure credential storage.
- Logged and reviewed.

#### d. Access Documentation and Audit Trail

- Logs retained for 3 years.
- Includes requestor, approver, date/time, action taken.

### 8. Control Mechanisms

- Access Logs Monitoring.
- Segregation of Duties.
- Automated Alerts.

### 9. Non-Conformance and Exceptions

- Documented and approved by ISO.
- Escalated to ISMS Management Review Committee.

### 10. Review and Continuous Improvement

- Reviewed annually.
- Updated based on audits, incidents, organizational changes.

---

## Incident Response Procedure (SOP-002)

### 1. Purpose

Establish a consistent process for managing information security incidents.

### 2. Scope

Applies to all information systems and employees involved in or affected by incidents.

### 3. Definitions

- **Security Incident**: Compromise of confidentiality, integrity, or availability.
- **CSIRT**: Computer Security Incident Response Team.
- **Impact Level**: Severity of damage.

### 4. Roles and Responsibilities

| Role             | Responsibilities                                   |
|------------------|---------------------------------------------------|
| ISO              | Oversees process, ensures compliance.             |
| CSIRT Members    | Containment, eradication, recovery.               |
| IT Support       | System-level support.                             |
| Department Heads | Support classification, user communication.      |
| Employees        | Report incidents immediately.                     |

### 5. Operational Criteria

| Criteria               | Standard                                  |
|-----------------------|-------------------------------------------|
| Incident Detection    | ≤ 2 hours                                 |
| Initial Response      | ≤ 4 hours                                 |
| Full Containment      | ≤ 24 hours (high-impact incidents)        |
| Resolution and Recovery| ≤ 3 business days                         |
| Root Cause Analysis   | Mandatory for medium/high-impact incidents |
| Reporting             | All incidents logged                       |

### 8. Procedure Steps

#### Step 1: Incident Identification

- Detected by employee, system, monitoring tool.
- Report via Incident Reporting System.

#### Step 2: Incident Logging

- Logged in Incident Register.
- Details: ID, date/time, reporter, system affected, description.

#### Step 3: Initial Assessment and Triage

- ISO/CSIRT Lead assesses within 2 hours.
- Scope, urgency, impact classified.

#### Step 4: Containment

- Short-term: Isolate endpoints, disable accounts.
- Long-term: Temporary solutions, preserve evidence.

#### Step 5: Eradication and Recovery

- Identify root cause.
- Remove malware, reset credentials.
- Restore systems from backups.

#### Step 6: Post-Incident Analysis

- Root Cause Analysis (RCA).
- Meeting with CSIRT, IT, affected departments.
- Generate Incident Report.

#### Step 7: Reporting and Closure

- Final report submitted to management.
- Logs/artifacts archived.
- Incident formally closed.

#### Step 8: Communication

- Internal: Inform affected users/departments.
- External: Regulatory bodies, third parties (if required).

#### Step 9: Lessons Learned and Preventive Action

- Corrective and Preventive Action Plan (CAPA).
- Update policies, train users.

#### Step 10: Review and Continuous Improvement

- Quarterly review of incident records.
- Feed into ISMS continual improvement.

### 7. Control Mechanisms

- Incident Metrics and KPIs.
- Tooling: SIEM, ticketing, SOAR.
- Auditing: Quarterly internal audits.
- Access Controls: Role-based, MFA.

### 8. Non-Conformance and Exceptions

- Documented in Non-Conformance Register.
- Exceptions approved by ISO/CISO.

### 9. Review and Continuous Improvement

- Annual review.
- Post-incident Lessons Learned sessions.
- Table-top simulations, awareness programs.

---

## Change Management Procedure (SOP-003)

### 1. Purpose

Ensure all changes to information systems are managed in a controlled manner.

### 2. Scope

Applies to all planned, emergency, and standard changes.

### 3. Definitions

- **Change**: Addition, modification, removal of systems/configurations.
- **Standard Change**: Pre-approved, low-risk.
- **Emergency Change**: Urgent change to resolve incidents.
- **Change Request (CR)**: Formal request for change.
- **Change Advisory Board (CAB)**: Stakeholder review group.

### 4. Roles and Responsibilities

| Role              | Responsibilities                                          |
|-------------------|----------------------------------------------------------|
| Change Initiator  | Raises CR, provides rationale.                           |
| Change Manager    | Coordinates reviews, documentation, approvals.           |
| CAB               | Reviews and authorizes high-risk changes.                |
| ISO/ISMS Owner    | Ensures ISMS compliance.                                 |
| Implementation Team | Executes approved change.                              |
| QA/Testing Lead   | Validates post-implementation.                           |

### 5. Associated Documents

- Risk Assessment Report (REC-004)
- Statement of Applicability (REC-007)
- Configuration Management Policy
- Change Control Log (REC-012)
- Incident Response Procedure (SOP-002)

### 6. Change Management Process

#### Step 1: Identify and Initiate Change

- Complete Change Request Form.

#### Step 2: Classification of Change

- Standard, Normal, Emergency.

#### Step 3: Impact and Risk Assessment

- Downtime, users affected, security risks.

#### Step 4: Approval Process

- Standard: Auto-approved.
- Normal: CAB and ISO review.
- Emergency: Expedited approval.

#### Step 5: Planning and Communication

- Implementation plan, communication plan, rollback plan.

#### Step 6: Implementation

- Execute change within approved window.
- Capture evidence.

#### Step 7: Post-Implementation Review

- Validate change.
- Mark as closed in Change Control Log.

### 7. Control Mechanisms

- Change Control Log.
- Audit Trail.
- Review Metrics.
- CAB Meetings.

### 8. Exceptions and Non-Conformance

- Unauthorized changes recorded as non-conformance.
- Exceptions documented and approved.

---

