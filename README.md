# Home Credit LAP AI Voice Agent

## Project Overview
This project is an AI voice agent built using Retell AI for Home Credit's Loan Against Property (LAP) qualification process.

The agent contacts customers, explains the pre-approved LAP offer of up to ₹75 lakhs, checks preliminary eligibility, and guides eligible customers to a senior loan expert.

## Objectives
- Verify the customer.
- Explain the Loan Against Property offer.
- Handle busy customers and callback requests.
- Identify existing property loans or EMI reduction requirements.
- Collect and evaluate eligibility details.
- Route eligible customers to a senior loan expert.

## Eligibility Criteria
1. **Property Type:** Residential, Commercial, and Industrial are eligible. Agricultural property is not eligible.
2. **Ownership:** Sole and Joint ownership are accepted.
3. **Original Documents:** Original property documents must be available.
4. **Loan Amount:** Maximum ₹75,00,000.
5. **Occupation and Income:** Salaried or Self-employed; income must be received through a bank account.
6. **Market Value:** Record the customer's estimated property market value.
7. **Tenure:** Minimum 3 years and maximum 15 years.

## Key Features
- Natural AI voice conversations
- Customer verification
- LAP offer presentation
- Eligibility qualification
- Out-of-order information handling
- Callback handling
- Loan-transfer specialist routing
- Post-call data extraction
- Final handoff for eligible customers

## Technology Used
- Retell AI
- AI voice agent
- Single-prompt agent configuration
- Post-call analysis and data extraction

## Testing
The agent was tested for:
- Successful eligibility qualification
- Agricultural property rejection
- Cash income rejection
- Existing loan transfer handling
- Loan amount above ₹75 lakhs
- Tenure outside the permitted range
- Out-of-order customer responses
- Busy customer and callback handling

## Expected Outcome
Eligible customers are directed to a senior loan expert to discuss the exact interest rate and next steps. Ineligible customers are informed politely, and existing loan or EMI-reduction cases are routed to a loan-transfer specialist.

## Note
This repository contains project documentation. The working voice agent is configured and published separately in Retell AI.
