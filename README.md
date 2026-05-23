# incubyte-qa-assignment

**Incubyte QA Assignment – Gmail Compose**
This repo contains my test case submission for the QA Craftsperson role at Incubyte.
**What I've tested**
The scope is Gmail's Compose feature — writing and sending an email with subject Incubyte and body QA test for Incubyte.
**What's inside**
Gmail_Compose_Test_Cases.xlsx has three sheets:

Traditional Test Cases — 20 test cases in standard QA format (10 positive, 10 negative)
BDD Test Cases — same coverage written in Gherkin style (Given / When / Then)
Summary — quick snapshot of overall test coverage

**Areas covered**

Compose window loading and field validation
Subject and body input handling
Sending email and verifying delivery
Empty field and invalid email address scenarios
Basic XSS check on the subject field
Draft save, reopen, and send flow
Offline behaviour and attachment size limit
