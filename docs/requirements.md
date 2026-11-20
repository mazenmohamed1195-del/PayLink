PayLink – Requirements Document

1. Project Overview

1.1 Problem Summary

PayLink is a digital bill payment and wallet management system.

The system allows customers to pay different utility bills, including electricity, water, mobile, and internet bills, using money stored in their digital wallets.

Customers can add money to their wallets, check their balances, view transaction history, and make bill payments.

The system also provides features for agents, administrators, and support employees to manage and monitor payment operations.

1.2 Project Objectives

The main objectives of PayLink are:

- Allow customers to pay bills using digital wallets.
- Provide secure wallet and transaction management.
- Support multiple biller companies.
- Prevent duplicate payments and incorrect balance updates.
- Provide payment notifications and transaction tracking.
- Allow administrators and support employees to manage the system.

2. Stakeholders

Stakeholder| Responsibility
Customer| Adds money, views wallet balance, and pays bills.
Agent| Adds money for customers and makes payments on their behalf.
Administrator| Manages billers, services, fees, and system settings.
Support Employee| Searches payments and helps customers with payment problems.
Biller Companies| Receive and process bill payment requests.
PayLink Management| Monitors the system and business operations.

3. Functional Requirements

This section will contain the system's user stories and their acceptance criteria.

3. Functional Requirements

US-01: Customer Registration

Priority: Must

User Story:

As a customer, I want to register for a PayLink account so that I can use the bill payment services.

Acceptance Criteria:

- Given I am a new customer.
- When I submit the required registration information.
- Then the system creates my account and assigns the basic verification level.

US-02: Customer Verification Upgrade

Priority: Should

User Story:

As a basic customer, I want to upgrade my verification level so that I can benefit from higher payment limits.

Acceptance Criteria:

- Given I have a basic PayLink account.
- When I complete the required verification process and it is approved.
- Then my account is upgraded to verified and receives the higher payment limits.

US-03: View Wallet Information

Priority: Must

User Story:

As a customer, I want to view my available balance, held balance, and transaction history so that I can track my money.

Acceptance Criteria:

- Given I have a PayLink account and wallet.
- When I request my wallet information.
- Then the system displays my available balance, held balance, and transaction history.

US-04: Wallet Top-Up

Priority: Must

User Story:

As a customer, I want to add money to my wallet using a simulated card payment or agent cash so that I can pay my bills.

Acceptance Criteria:

- Given I have an active PayLink wallet.
- When a valid top-up is completed through a simulated card or agent cash.
- Then the system adds the amount to my wallet.

US-05: Wallet Ledger Recording

Priority: Must

User Story:

As a PayLink system, I need to record every wallet balance change in the ledger so that wallet balances can be calculated accurately.

Acceptance Criteria:

- Given a wallet balance is changed by a transaction.
- When the transaction is successfully processed.
- Then the system creates a corresponding ledger entry and calculates the wallet balance from its ledger entries.



4. Non-Functional Requirements

This section will describe measurable quality requirements, such as performance, security, reliability, and testability.

5. Requirements Priorities

Requirements will be classified into:

- Must: Essential requirements.
- Should: Important requirements.
- Could: Optional requirements.

6. Questions, Ambiguities and Decisions

This section will record unclear requirements, questions raised, and the decisions made by the team.
