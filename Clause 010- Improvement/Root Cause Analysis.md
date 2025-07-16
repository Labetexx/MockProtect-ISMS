# REC-027 Root Cause Analysis Report

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
1. Incident Summary  
2. Description of the Incident  
3. Impact Assessment  
4. Investigation Timeline  
5. Root Cause Identification  
6. Contributing Factors  
7. Corrective Actions  
8. Preventive Actions  
9. Verification of Effectiveness  
10. Conclusion  

---

## 1. Incident Summary

| Incident Title                | Unauthorized Access to Confidential Folder |
|-------------------------------|--------------------------------------------|
| Date Detected                 | 20/05/2025                                 |
| Reported By                   | SOC Analyst                                |
| Location/Department          | Finance / Shared Drive                     |
| Category                     | Access Control Violation                   |
| Severity                     | Medium                                     |

---

## 2. Description of the Incident

An unauthorized user (non-Finance staff) accessed a folder marked “Confidential – Payroll” on the organization’s shared drive. The access was detected during a routine access log review conducted by the SOC team.

---

## 3. Impact Assessment

- **Confidentiality Breach:** Potential exposure of payroll and employee compensation data.  
- **Reputational Risk:** Internal trust impact and HR concerns.  
- **Compliance Risk:** Breach of internal ISMS controls (A.9 – Access Control).  

---

## 4. Investigation Timeline

| Date         | Activity                                      |
|--------------|-----------------------------------------------|
| 20/05/2025   | Incident reported and ticket raised.         |
| 21/05/2025   | Access logs analyzed, scope of exposure identified. |
| 22/05/2025   | User access rights reviewed.                 |
| 23/05/2025   | RCA meeting conducted.                       |
| 24/05/2025   | Control failures and root cause documented.  |

---

## 5. Root Cause Identification

### Immediate Cause:
- Shared folder permissions were not restricted to Finance-only access.

### Root Cause(s) (5 Whys Method):

1. **Why was a non-Finance user able to access the folder?**  
   ➤ Because the shared drive folder had open permissions.

2. **Why were the permissions not limited to Finance users?**  
   ➤ Because access permissions were not reviewed after folder creation.

3. **Why was there no review of folder permissions?**  
   ➤ Because the quarterly access review did not include subfolders on shared drives.

4. **Why were subfolders excluded from the review?**  
   ➤ The access review process did not include a control for recursive permission checks.

5. **Why was that control missing?**  
   ➤ The Access Control SOP lacked detailed guidance on folder hierarchy checks.

---

## 6. Contributing Factors

- Incomplete Access Control SOP.  
- Lack of awareness among folder owners on permission setup.  
- Absence of automated folder-level access monitoring.  

---

## 7. Corrective Actions

| Action ID | Action Description                                | Responsible                | Target Date  | Status        |
|-----------|---------------------------------------------------|--------------------------|--------------|---------------|
| CA-001    | Update Access Control SOP to include subfolder reviews | ISO Team                 | 15/06/2025   | In Progress   |
| CA-002    | Conduct full audit of shared drive permissions    | IT Security Lead         | 10/06/2025   | Planned       |
| CA-003    | Provide training to data owners on access setup and risks | HR / InfoSec Awareness | 20/06/2025   | Planned       |

---

## 8. Preventive Actions

- Automate periodic access audits with recursive checks.  
- Integrate shared drive permissions with IAM policy alerts.  
- Include shared folder controls in internal audit checklist.  

---

## 9. Verification of Effectiveness

Follow-up scheduled for **01/07/2025** to:

- Validate SOP update has been adopted.  
- Confirm full permissions audit is complete.  
- Test automated alerts functionality.  

---

## 10. Conclusion

This incident underscores the need for more granular access control oversight and updated procedures. Improvements will enhance the confidentiality controls per ISO/IEC 27001 Clause A.9.

---
