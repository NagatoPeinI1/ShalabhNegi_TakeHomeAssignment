# feature/1-implementing-a-loan-approval-workflow

1. [Easy] Question: Implementing a Loan Approval Workflow

-- LoanSystem is the name specified in daml.yaml

```bash
daml build

daml test --files Main/Test/TestCases.daml

daml sandbox --wall-clock-time --log-level DEBUG --ledgerid LoanSystem ./.daml\dist\LoanSystem-0.0.1.dar

daml json-api --ledger-host localhost --ledger-port 6865 --http-port 7575

```
