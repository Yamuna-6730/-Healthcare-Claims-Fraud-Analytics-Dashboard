# Data Dictionary

## Dataset Overview

This dataset contains healthcare insurance claim records used for claims analysis, fraud detection, and business intelligence reporting. Each row represents an individual healthcare claim submitted by a provider.

| Column | Data Type | Description |
|---------|----------|-------------|
| Claim_ID | String | Unique identifier assigned to each healthcare claim. |
| Provider_ID | String | Unique identifier of the healthcare provider submitting the claim. |
| Patient_ID | String | Randomly generated identifier representing the patient. |
| Date_of_Service | Date | Date on which the healthcare service was provided. |
| Procedure_Code | String | CPT/HCPCS code representing the performed medical procedure. |
| Diagnosis_Code | String | ICD-10 diagnosis code associated with the patient's condition. |
| Charge_Amount | Float | Total amount billed by the provider for the healthcare service. |
| Paid_Amount | Float | Amount reimbursed by the insurer or paid by the patient. |
| Insurance_Type | Category | Insurance coverage type (Private, Medicare, Medicaid, etc.). |
| Claim_Status | Category | Current processing status of the claim (Paid, Denied, Partially Paid). |
| Reason_Code | String | Code indicating the reason for denial or payment adjustment. |
| Follow_up_Required | Boolean | Indicates whether additional action is required to process the claim. |
| AR_Status | Category | Accounts Receivable status of the claim (Open, Closed). |
| Outcome | Category | Final outcome of the claim (Paid, Denied, Partial). |

---

## Potential Business Questions

- What percentage of claims are denied?
- Which providers generate the highest billing amounts?
- Which diagnosis codes are most frequently denied?
- Which insurance type experiences the highest denial rate?
- What is the average reimbursement amount?
- Which providers require the highest number of follow-ups?
- How do claim amounts change over time?
- What factors are associated with claim denial?

---

## Target Variables

Business KPIs analyzed:

- Total Claims
- Total Charge Amount
- Total Paid Amount
- Claim Approval Rate
- Denial Rate
- Average Claim Amount
- Provider-wise Claims
- Insurance-wise Claims
- Diagnosis-wise Claims
- Monthly Claim Trends