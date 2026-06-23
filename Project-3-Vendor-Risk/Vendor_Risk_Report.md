# Vendor Risk Assessment Report — CloudHost Solutions

| **Prepared By:** | Kaustubh Mahadik |
| **Date:** | June 24, 2026 |
| **Vendor:** | CloudHost Solutions Pvt. Ltd. |
| **Classification:** | Confidential |
| **Version:** | 1.0 |

---

## 1. Executive Summary

A comprehensive security assessment was conducted for CloudHost Solutions Pvt. Ltd., a cloud hosting and data storage vendor for SecurePay Technologies. The vendor was assessed against SOC 2 and ISO 27001 standards.

**Overall Risk Rating:** 🟡 Medium Risk (84.33/100)

| Metric | Value |
|--------|-------|
| **Total Findings** | 7 |
| **High Severity** | 1 |
| **Medium Severity** | 3 |
| **Low Severity** | 3 |

### Key Findings

| # | Finding | Severity | Action Required |
|---|---------|----------|-----------------|
| 1 | No MFA implementation | High | Implement MFA within 90 days |
| 2 | No quarterly access reviews | Medium | Implement quarterly reviews |
| 3 | Not GDPR compliant | Medium | Assess GDPR requirements |
| 4 | No DLP controls | Medium | Implement DLP controls |
| 5 | No cyber insurance | Low | Require cyber insurance |
| 6 | Incomplete data classification | Low | Complete classification policy |
| 7 | Limited IR exercises | Low | Conduct annual exercises |

---

## 2. Vendor Profile

| Detail | Information |
|--------|-------------|
| **Company Name** | CloudHost Solutions Pvt. Ltd. |
| **Years in Business** | 8 years |
| **Number of Employees** | 250 |
| **Services Provided** | Cloud hosting, data storage, managed infrastructure |
| **Data Accessed** | Customer PII, transaction data, KYC documents |
| **Data Storage Locations** | India (Mumbai, Bengaluru), Singapore |
| **Compliance Certifications** | ISO 27001 |

---

## 3. Assessment Summary

### Overall Scores

| Category | Score | Weight | Weighted Score |
|----------|-------|--------|----------------|
| Information Security | 93.75% | 20% | 18.75 |
| Access Control | 62.50% | 20% | 12.50 |
| Data Protection | 81.25% | 20% | 16.25 |
| Third-Party Management | 90.00% | 15% | 13.50 |
| Compliance | 83.33% | 10% | 8.33 |
| Incident History | 100.00% | 5% | 5.00 |
| Business Continuity | 100.00% | 10% | 10.00 |
| **Total** | | **100%** | **84.33** |

---

## 4. Detailed Findings

### Finding 1: No MFA Implementation

| Attribute | Detail |
|-----------|---------|
| **Severity** | High |
| **Category** | Access Control |
| **Description** | The vendor does not require Multi-Factor Authentication (MFA) for any systems, including administrative access. |
| **Risk** | Increased risk of unauthorized access through compromised credentials. |
| **Recommendation** | Require MFA for all administrative access and remote access. |
| **Timeline** | 90 days |
| **Status** | Open |

---

### Finding 2: No Quarterly Access Reviews

| Attribute | Detail |
|-----------|---------|
| **Severity** | Medium |
| **Category** | Access Control |
| **Description** | The vendor does not conduct regular access reviews to validate user permissions. |
| **Risk** | Overprivileged accounts may exist, increasing the risk of unauthorized access. |
| **Recommendation** | Implement quarterly access reviews for all systems. |
| **Timeline** | 90 days |
| **Status** | Open |

---

### Finding 3: Not GDPR Compliant

| Attribute | Detail |
|-----------|---------|
| **Severity** | Medium |
| **Category** | Compliance |
| **Description** | The vendor is not compliant with GDPR requirements for EU customer data. |
| **Risk** | Regulatory fines and legal liability if EU customer data is processed. |
| **Recommendation** | Assess GDPR requirements and implement necessary controls. |
| **Timeline** | 180 days |
| **Status** | Open |

---

### Finding 4: No DLP Controls

| Attribute | Detail |
|-----------|---------|
| **Severity** | Medium |
| **Category** | Data Protection |
| **Description** | The vendor does not have Data Loss Prevention (DLP) controls in place. |
| **Risk** | Increased risk of data exfiltration and data leakage. |
| **Recommendation** | Implement DLP controls for sensitive data. |
| **Timeline** | 180 days |
| **Status** | Open |

---

## 5. Risk Treatment Plan

| # | Finding | Treatment | Owner | Timeline |
|---|---------|-----------|-------|----------|
| 1 | No MFA | Implement MFA | Vendor CISO | 90 days |
| 2 | No access reviews | Quarterly reviews | Vendor CISO | 90 days |
| 3 | Not GDPR compliant | GDPR assessment | Vendor Legal | 180 days |
| 4 | No DLP controls | Implement DLP | Vendor CISO | 180 days |
| 5 | No cyber insurance | Obtain cyber insurance | Vendor CFO | 180 days |
| 6 | Incomplete classification | Complete policy | Vendor CISO | 90 days |
| 7 | Limited IR exercises | Conduct annual exercises | Vendor CISO | 120 days |

---

## 6. Recommendations

### Immediate Actions (0-90 Days)

| Priority | Action | Owner |
|----------|--------|-------|
| 1 | Implement MFA across all systems | Vendor CISO |
| 2 | Implement quarterly access reviews | Vendor CISO |
| 3 | Complete data classification policy | Vendor CISO |

### Short-Term Actions (90-180 Days)

| Priority | Action | Owner |
|----------|--------|-------|
| 4 | Assess GDPR requirements | Vendor Legal |
| 5 | Implement DLP controls | Vendor CISO |
| 6 | Obtain cyber insurance | Vendor CFO |
| 7 | Conduct annual IR exercises | Vendor CISO |

---

## 7. Conclusion

CloudHost Solutions Pvt. Ltd. is a medium-risk vendor with an overall score of 84.33/100. While the vendor has strong information security practices and business continuity controls, significant gaps exist in access control (MFA, access reviews) and compliance (GDPR).

The vendor should be required to address the high-severity finding (MFA implementation) within 90 days as a condition of continued engagement.

---

## 8. Appendices

### Appendix A: Scoring Methodology

| Score Range | Rating |
|-------------|--------|
| 90-100 | Low Risk |
| 70-89 | Medium Risk |
| 50-69 | High Risk |
| Below 50 | Critical Risk |

### Appendix B: Vendor Questionnaire Summary

| Section | Questions | Meets | Partial | Does Not Meet | N/A |
|---------|-----------|-------|---------|---------------|-----|
| Information Security | 8 | 6 | 1 | 1 | 0 |
| Access Control | 8 | 5 | 0 | 3 | 0 |
| Data Protection | 8 | 6 | 1 | 1 | 0 |
| Third-Party Management | 5 | 4 | 1 | 0 | 0 |
| Compliance | 6 | 4 | 0 | 1 | 1 |
| Incident History | 3 | 1 | 0 | 0 | 2 |
| Business Continuity | 5 | 5 | 0 | 0 | 0 |
| **Total** | **43** | **31** | **3** | **6** | **3** |

---

## Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | June 24, 2026 | Kaustubh Mahadik | Initial creation |
