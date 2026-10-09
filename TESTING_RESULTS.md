# Testing Results — Home Credit LAP AI Voice Agent

## Test Cases

| Test Case | Expected Result | Status |
|---|---|---|
| Eligible customer | Complete eligibility checks and direct to senior loan expert | Passed |
| Agricultural property | Reject immediately | Passed |
| Cash income | Reject customer | Passed |
| Existing property loan or EMI reduction | Route to loan-transfer specialist | Passed |
| Loan amount above ₹75 lakhs | Offer maximum of ₹75 lakhs | Passed |
| Customer declines ₹75 lakhs | End the call politely | Passed |
| Tenure below 3 years | Reject customer | Passed |
| Information provided out of order | Remember details and avoid repeated questions | Passed |
| Busy customer | Ask for callback time and end the call | Passed |

## Conclusion
The Retell AI voice agent was tested against the main LAP qualification scenarios. The tests confirmed the expected handling of eligibility, rejection, callback, and specialist-transfer scenarios.
