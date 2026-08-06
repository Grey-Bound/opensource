# Bitcoin Product Security & Production Readiness Checklist

Practical checklist used by Greybound when reviewing Bitcoin products.

## 1. Wallet Architecture
- [ ] Key generation and storage approach
- [ ] Multisig / threshold scheme (if any)
- [ ] Recovery and backup flows
- [ ] Seed / key exposure risks
- [ ] Non-custodial vs hybrid model clarity

## 2. Payment & Settlement
- [ ] On-chain transaction flow
- [ ] Lightning integration (if present)
- [ ] Fee handling and bumping
- [ ] Reconciliation and accounting
- [ ] Failure and retry logic

## 3. Node Infrastructure
- [ ] Node configuration hardening
- [ ] Network exposure
- [ ] Monitoring and alerting
- [ ] Backup and recovery of node data
- [ ] Update and maintenance process

## 4. Backend & API
- [ ] Authentication and authorization
- [ ] Input validation
- [ ] Rate limiting
- [ ] Secrets management
- [ ] Logging and sensitive data exposure

## 5. Operational Security
- [ ] Access control
- [ ] Deployment process
- [ ] Incident response readiness
- [ ] Dependency management

## Priority Levels
- Critical
- High
- Medium
- Low

---
Used by Greybound in Bitcoin Product Security & Production Readiness Reviews.
