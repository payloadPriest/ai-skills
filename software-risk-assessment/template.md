## Security Risk Assessment
_Fill in application details and determine risk level after analysis._

---

### Basic Information
| Field              | Details                         |
|--------------------|---------------------------------|
| Application Name   | {{issue.customfield_10958}}     |
| Assessment Date    |                                 |
| Reviewer           |                                 |
| Risk Level         | (Low = 1 / Medium = 2 / High = 3 based on overall score) |
| Verdict            | (Approved / Rejected)           |
| Acceptance Criteria|                                 |

---

### General Information
_Provide objective facts about the software. Remove any assumptions or unknowns._

| Field                         | Details |
|------------------------------|---------|
| Developer Reputation         |         |
| Required Permissions         |         |
| Additional Notes             |         |
| Covered by Contract          | (Yes / No) |
| Privacy Policy               | (Link or summary) |
| Data Stored Outside Endpoint | (Yes / No / Unknown) |
| Data Residency               | (EU / Non-EU / Unknown) |
| Known Vulnerabilities        | (List CVEs or link to vulnerability database) |
| Patch Management             |         |
| • ManageEngine Supported Apps| (Yes / No / Unknown) |
| • Jamf Patch Titles          | (Yes / No / Unknown) |
| • Heimdal Monitored Apps     | (Yes / No / Unknown) |

---

### Risk Matrix (Weighted by Category Importance)
_Score each risk as Low (1), Medium (2) or High (3) based on context and controls._

**Formula:**  
Weighted Score = (Likelihood × Impact) × (Weight % / 100)

| Category          | Risk Description                                         | Likelihood (1–3) | Impact (1–3) | Weight (%) | Weighted Risk Score |
|-------------------|-----------------------------------------------------------|------------------|--------------|-----------:|---------------------|
| Security          | Potential for data breaches or unauthorised access        |                  |              | 30%        |                     |
| Compliance        | Alignment with EU financial sector regulations. 		|            	   |              | 20%        |                     |
| Privacy           | Exposure of confidential or personally identifiable information.|            |              | 20%        |                     |
| Patch Management  | Timeliness and reliability of security updates.           |                  |              | 10%        |                     |
| Vendor Stability  | Risk of vendor discontinuation or support gaps.           |                  |              | 10%        |                     |
| Software Stability| Likelihood of malfunction or performance issues.          |                  |              | 5%         |                     |
| Integration       | Compatibility with existing systems and controls.         |                  |              | 5%        |                     |


---

### Overall Weighted Risk Score

**Formula:**  
Overall Risk Score = Sum of all Weighted Risk Scores

**Risk Level Thresholds:**  
- Low Risk: Score ≤ 2.5  
- Medium Risk: Score > 2.5 and ≤ 5  
- High Risk: Score > 5

---

### Verdict

_Summarise the result of the assessment and state whether the tool is **Approved** (with conditions) or **Rejected**._

---

### Acceptance Criteria
_Define the conditions required before the tool can be deployed._
