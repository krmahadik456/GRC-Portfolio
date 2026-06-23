# Data Protection Policy

| **Document Information** | |
|--------------------------|---|
| **Document Owner:** | CISO |
| **Version:** | 1.0 |
| **Effective Date:** | June 24, 2026 |
| **Review Date:** | June 24, 2027 |
| **Approved By:** | Board of Directors |
| **Classification:** | Internal |

---

## 1. Purpose

The purpose of this policy is to define the requirements for protecting data at SecurePay Technologies. This policy ensures that data is classified, handled, stored, transmitted, and disposed of in a manner that maintains its confidentiality, integrity, and availability, and complies with applicable legal and regulatory requirements.

---

## 2. Scope

This policy applies to:
- All data created, processed, stored, or transmitted by SecurePay Technologies
- All employees, contractors, and third parties
- All systems, applications, and devices
- All locations and business units
- All data throughout its lifecycle

---

## 3. Data Classification

### 3.1 Classification Levels

| Level | Description | Examples | Protection Required |
|-------|-------------|----------|---------------------|
| **Public** | Information that can be freely shared | Press releases, marketing materials, public financial reports | No restrictions |
| **Internal** | Information for internal use only | Policy documents, meeting minutes, employee directories | Access controls |
| **Confidential** | Sensitive information requiring protection | Employee records, financial data, internal reports | Encryption, access controls |
| **Restricted** | Highly sensitive information requiring highest protection | Customer PII, payment data, KYC documents, PHI, trade secrets | Encryption, strict access controls, monitoring |

### 3.2 Data Owners

Each data asset shall have an assigned owner responsible for:
- Classification of the data
- Approving access to the data
- Ensuring data is protected appropriately
- Reviewing data protection controls

---

## 4. Data Handling Guidelines

### 4.1 Data Creation

| Level | Handling Requirements |
|-------|----------------------|
| **Public** | Standard creation; no special handling |
| **Internal** | Store in authorized systems; apply access controls |
| **Confidential** | Store in authorized systems; apply encryption; restrict access |
| **Restricted** | Store in authorized systems; apply strong encryption; strict access controls; audit logging |

### 4.2 Data Storage

| Level | Storage Requirements |
|-------|----------------------|
| **Public** | Standard storage |
| **Internal** | Authorized systems only; access controls |
| **Confidential** | Encrypted storage; authorized systems only |
| **Restricted** | Strong encryption; authorized systems only; regular monitoring |

### 4.3 Data Transmission

| Level | Transmission Requirements |
|-------|--------------------------|
| **Public** | No restrictions |
| **Internal** | Secure transmission (VPN, encrypted connection) |
| **Confidential** | Strong encryption (TLS 1.2+) |
| **Restricted** | Strong encryption (TLS 1.2+), secure channels only |

### 4.4 Data Sharing

| Level | Sharing Requirements |
|-------|----------------------|
| **Public** | No restrictions |
| **Internal** | Approved channels only; internal recipients |
| **Confidential** | Approval required; authorized recipients only |
| **Restricted** | Strict approval; need-to-know basis; authorized recipients only |

---

## 5. Data Retention and Disposal

### 5.1 Retention Periods

| Data Type | Retention Period | Legal Basis |
|-----------|------------------|-------------|
| Financial records | 7 years | Indian Companies Act |
| HR records | 7 years | Indian Employment Law |
| Customer transaction data | 10 years | RBI guidelines |
| Customer PII | 10 years | RBI guidelines |
| KYC documents | 10 years | PMLA, RBI guidelines |
| Emails | 3 years | Business necessity |
| Audit logs | 1 year | Security best practice |

### 5.2 Data Disposal Methods

| Level | Disposal Method |
|-------|-----------------|
| **Public** | Standard deletion |
| **Internal** | Secure deletion (overwrite) |
| **Confidential** | Secure deletion (multiple overwrite) |
| **Restricted** | Physical destruction (degaussing, shredding) or certified secure deletion |

---

## 6. Data Security Controls

### 6.1 Encryption Requirements

| Scenario | Encryption Required |
|----------|---------------------|
| Data at rest (confidential/restricted) | ✅ AES-256 |
| Data in transit (confidential/restricted) | ✅ TLS 1.2+ |
| Data on portable devices | ✅ Full disk encryption |
| Data in backups | ✅ AES-256 |

### 6.2 Access Controls

| Control | Application |
|---------|-------------|
| Role-Based Access Control (RBAC) | All systems |
| Least Privilege | All users |
| Multi-Factor Authentication (MFA) | Confidential/restricted data |
| Quarterly Access Reviews | All data |

### 6.3 Monitoring

| Activity | Monitoring Required |
|----------|---------------------|
| Access to restricted data | ✅ |
| Data exfiltration attempts | ✅ |
| Privileged user activity | ✅ |
| Failed access attempts | ✅ |

---

## 7. Data Breach Notification

### 7.1 Internal Reporting

| Incident Type | Report To | Timeframe |
|---------------|-----------|-----------|
| Suspicious activity | Security Team | Immediately |
| Confirmed breach | CISO | Within 1 hour |

### 7.2 External Reporting

| Authority | Notification Requirement | Timeframe |
|-----------|--------------------------|-----------|
| Data Protection Board | If personal data involved | Within 72 hours |
| Law Enforcement | Criminal activity | Immediately |
| Affected Individuals | Personal data breach | Without undue delay |

---

## 8. Compliance Requirements

### 8.1 Regulatory Requirements

| Regulation | Applicable To | Key Requirements |
|------------|---------------|------------------|
| **GDPR** | EU customers | Data subject rights, breach notification |
| **PCI DSS** | Payment card data | Cardholder data protection |
| **IT Act, 2000** | Indian operations | Reasonable security practices |
| **RBI Guidelines** | Financial services | Data localization, KYC requirements |

### 8.2 Compliance Monitoring

- Regular compliance audits shall be conducted
- Compliance gaps shall be tracked and remediated
- Regulatory updates shall be monitored and incorporated

---

## 9. Roles and Responsibilities

| Role | Responsibility |
|------|----------------|
| **CISO** | Overall data protection program |
| **Data Owners** | Data classification, access approval |
| **Data Custodians** | Implementation of data protection controls |
| **All Employees** | Handle data according to classification |
| **Legal Team** | Regulatory compliance |
| **Privacy Officer** | Data subject rights, breach notification |

---

## 10. Review and Update Schedule

This policy shall be reviewed:
- At least annually
- When significant changes occur in:
  - Regulatory requirements
  - Business operations
  - Technology infrastructure

---

## 11. References

- ISO/IEC 27001:2022
- GDPR (General Data Protection Regulation)
- PCI DSS (Payment Card Industry Data Security Standard)
- Information Technology Act, 2000 (India)
- RBI Guidelines on Cybersecurity
- SecurePay Technologies' Information Security Policy

---

## 12. Definitions

| Term | Definition |
|------|------------|
| **PII** | Personally Identifiable Information |
| **PHI** | Protected Health Information |
| **KYC** | Know Your Customer |
| **Data at Rest** | Data stored on physical media |
| **Data in Transit** | Data being transmitted |
| **Data Subject** | Individual about whom data is held |
| **Data Breach** | Unauthorized access, alteration, or destruction of data |

---

## 13. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | June 24, 2026 | Kaustubh Mahadik | Initial creation |
