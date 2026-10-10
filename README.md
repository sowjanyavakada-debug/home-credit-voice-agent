Home Credit AI Voice Agent – Loan Against Property (LAP)

1. Project Overview

This project is about creating an AI Voice Agent for Home Credit to talk to existing customers about a Loan Against Property (LAP) offer.

The agent explains the loan offer, asks customers questions about their property and income, and checks whether they meet the basic eligibility requirements.

The maximum loan amount under this offer is ₹75 lakh.

The agent acts as the first point of contact. Customers who meet all the required conditions are informed that a senior loan expert will call them to explain the next steps and exact interest rates.

2. Main Objective

The main objective of this project is to make the initial loan qualification process easier through an AI-powered voice conversation.

The agent is designed to:

1.Speak to customers in a natural and professional manner.
2.Explain the Loan Against Property offer.
3.Collect the information needed to check eligibility.
4.Identify customers who do not meet the required conditions.
5.Handle customer answers even when they are given in a different order.
6.Direct existing-loan and EMI-reduction requests to a loan-transfer specialist.
7.Inform eligible customers about the next steps.

3. How Does the Voice Agent Work?

The agent follows these steps during a customer call.

Step 1: Greeting and Customer Verification

The agent greets the customer and checks whether it is speaking to the correct person. If the customer is busy, it asks for a convenient callback time.

Step 2: Explain the Loan Offer

After confirming the customer's identity, the agent explains the Loan Against Property offer of up to ₹75 lakh.

Step 3: Ask Eligibility Questions

The agent asks questions about the customer's property, ownership, documents, loan amount, occupation, income, property value, and repayment period.

Step 4: Check Eligibility

The agent compares the customer's answers with the eligibility rules provided in the assignment.

Step 5: Handle Special Cases

If the customer does not meet a required condition, the agent politely explains the reason and ends the qualification call. If the customer already has a loan against the property or wants to reduce their EMI, the agent directs them to a loan-transfer specialist.

Step 6: Arrange the Next Step

If the customer meets all the required conditions, the agent informs them that a senior loan expert will call them to discuss the next steps and exact interest rates.

 4. Customer Eligibility Rules

The agent collects the following information to check the customer's preliminary eligibility.

Property Type:Residential, commercial, and industrial properties are eligible. Agricultural property is not eligible.

Ownership: Both sole and joint ownership are eligible.

Original Documents: The customer must have the original property documents available.

Loan Amount:The requested loan amount must be ₹75 lakh or less.

Occupation: Both salaried and self-employed customers are eligible.

Income Source:The customer's income must be received through a bank account. Customers who receive income only in cash are not eligible.

Property Market Value: The agent asks the customer for the estimated current market value of the property.

Repayment Period:The requested loan repayment period must be between 3 and 15 years.

5. Important Business Rules

Immediate Disqualification

If the customer has agricultural property or receives income in cash, the agent politely explains that the customer does not meet the criteria for this offer and ends the qualification call.

The agent also checks the other eligibility conditions, including original document availability and repayment tenure.

Loan Amount Above ₹75 Lakh

If a customer requests more than ₹75 lakh, the agent explains the maximum limit and asks whether the customer would like to continue with the maximum allowed amount.

Existing Loan or EMI Reduction

If the customer already has a loan against the property or wants to reduce their current EMI, the agent directs the customer to a loan-transfer specialist instead of continuing the standard new-loan process.

Senior Expert Callback

The agent offers the next step to customers who have answered all required questions and meet the eligibility criteria. Final approval and loan terms remain subject to the lender's review.

6. Handling Natural Conversations

Customers may not always answer questions in the order expected.

For example, a customer might say:

"I'm salaried, my property is worth ₹80 lakh, and I need ₹50 lakh for ten years."

The agent should identify the information already provided and record those answers. It should ask only for the missing details instead of repeating questions unnecessarily.

The agent should also handle interruptions, conversational language, and unrelated questions politely before returning to the qualification process.

7. Technology Used

Voice AI Platform: Retell AI

System Prompt: A set of instructions that guides the agent's role, speaking style, questions, eligibility checks, and responses.

Testing Method: Test conversations based on different customer situations.

The agent is configured through the voice AI platform using the system prompt. The basic demonstration does not require a separate custom application unless additional features are needed.

8. Testing Scenarios

The agent should be tested with different customer situations to check whether it follows the required rules.

1. An eligible customer requesting ₹50 lakh with a 10-year repayment period.
2. A customer with agricultural property.
3. A customer who does not have the original property documents.
4. A customer requesting more than ₹75 lakh.
5. A self-employed customer receiving income in cash.
6. A customer who already has a loan and wants to reduce their EMI.
7. A customer requesting a repayment period outside the permitted range.
8. A customer who provides answers in a different order.
9. A customer who is busy and requests a callback.
10. An eligible customer who completes the entire qualification conversation.

The actual results of these tests should be recorded in the "test-scenarios.md" file after testing the agent.

9. Project Files

This GitHub repository contains the documentation for the project.

- README.md: Explains the project, objectives, workflow, eligibility rules, and testing approach.
- system-prompt.txt: Contains the instructions used to configure the AI voice agent.
- test-scenarios.md: Describes the test cases, expected behavior, and actual test results.

10. Project Status

Current Status: In Progress

The project is in progress until the voice agent has been configured, tested, and the required recordings and submission evidence have been collected.

The status can be updated to Completed once the implementation and testing are finished.

11. Expected Outcome

The expected outcome is a professional AI voice agent that can conduct preliminary Loan Against Property qualification conversations, collect the required information, follow the specified business rules, handle different customer responses, and direct customers to the appropriate next step.

The project demonstrates how conversational AI can support the initial stage of a customer qualification process while leaving final loan decisions to the human loan expert.

12. Assignment Deliverables

- Project documentation in GitHub.
- Complete system prompt used by the voice agent.
- Test scenarios and actual test results.
- Public link to the call recordings and call logs, including audio and transcript.
- Screen recording or published demo link if requested by the submission form.

Project Name: Home Credit AI Voice Agent – Loan Against Property Qualification

Purpose: Preliminary customer qualification using conversational AI.

Platform: Retell AI
