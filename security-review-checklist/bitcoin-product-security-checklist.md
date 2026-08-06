# Bitcoin Product Security & Production Readiness Checklist

**Version:** 0.1  
**Maintained by:** GreyBound  
**Last updated:** August 2026

This checklist is used by GreyBound during Bitcoin Product Security & Production Readiness Reviews.  
It focuses on real-world production risks rather than theoretical issues.

---

## 1. Scope Definition
- [ ] Clear system boundaries defined
- [ ] Components in scope identified (wallet, payments, nodes, backend, etc.)
- [ ] Trust assumptions documented

## 2. Key Management & Wallet Architecture
- [ ] Key generation method reviewed
- [ ] Key storage and protection mechanisms
- [ ] Multisig / threshold signature design (if applicable)
- [ ] Recovery and backup procedures
- [ ] Exposure points for private keys or seeds
- [ ] Separation of duties (if multi-party)

## 3. Transaction & Payment Flows
- [ ] Transaction construction and signing flow
- [ ] Fee estimation and management
- [ ] RBF / CPFP handling
- [ ] Lightning-specific flows (if present)
- [ ] Failure handling and retries
- [ ] Reconciliation mechanisms

## 4. Node & Infrastructure
- [ ] Node configuration reviewed
- [ ] Network exposure and firewall rules
- [ ] Authentication to node interfaces
- [ ] Monitoring and alerting coverage
- [ ] Backup and restore procedures
- [ ] Update and patch management process

## 5. Backend & API Security
- [ ] Authentication and authorization model
- [ ] Input validation and sanitization
- [ ] Secrets management
- [ ] Rate limiting and abuse protection
- [ ] Logging practices (sensitive data exposure)
- [ ] Error handling

## 6. Operational Security
- [ ] Access control model
- [ ] Deployment pipeline security
- [ ] Dependency management and updates
- [ ] Incident response readiness
- [ ] Principle of least privilege applied

## 7. Risk Classification
For each finding use the following priority:
- **Critical** — Direct risk of fund loss or severe compromise
- **High** — Significant security or reliability risk
- **Medium** — Notable weakness
- **Low** — Best practice improvement

---

**Note:** This checklist is a living document and will evolve with GreyBound’s engineering practice.
