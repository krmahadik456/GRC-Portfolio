# Risk Heatmap — SecurePay Technologies

| **Prepared By:** | Kaustubh Mahadik |
| **Date:** | June 24, 2026 |
| **Version:** | 1.0 |

---

## Risk Matrix

| Impact ↓ | Likelihood → | Low (1-2) | Medium (3) | High (4-5) |
|-----------|--------------|-----------|------------|------------|
| High (4-5) | | R004 | R003, R005 | R001, R002, R007 |
| Medium (3) | | | | |
| Low (1-2) | | | | |

---

## Risk Legend

| Priority | Risk Score Range | Indicator |
|----------|------------------|-----------|
| Critical | 18-25 | Red |
| High | 12-17 | Orange |
| Medium | 6-11 | Yellow |
| Low | 1-5 | Green |

---

## Risk Summary

| Priority | Number of Risks |
|----------|-----------------|
| Critical | 3 |
| High | 3 |
| Medium | 1 |
| Low | 0 |

---

## Risk Details Table

| Risk ID | Description | Likelihood | Impact | Score | Priority |
|---------|-------------|------------|--------|-------|----------|
| R001 | Unauthorized access to customer database | 4 | 5 | 20 | Critical |
| R002 | Data breach via phishing | 4 | 5 | 20 | Critical |
| R007 | Cloud misconfiguration | 4 | 5 | 20 | Critical |
| R006 | Social engineering attack | 4 | 4 | 16 | High |
| R003 | Ransomware attack | 3 | 5 | 15 | High |
| R005 | System outage impacting operations | 3 | 4 | 12 | High |
| R004 | Insider threat - data exfiltration | 2 | 5 | 10 | Medium |

---

## Risk Distribution

```
           Impact
             ^
    High      |   R004        R003, R005   R001, R002, R007
    Medium    |
    Low       |
              +---------------------------------------->
                 Low          Medium         High
                               Likelihood
```

---

## Key Takeaways

1. 43% of risks are Critical - Immediate action required
2. 43% of risks are High - Action required within 90 days
3. 14% of risks are Medium - Action required within 180 days

---

## Priority Actions

| Priority | Action | Timeline |
|----------|--------|----------|
| 1 | Implement MFA across all systems | 60 days |
| 2 | Secure cloud configurations | 60 days |
| 3 | Conduct phishing simulations | 60 days |
| 4 | Implement endpoint protection (EDR) | 90 days |
| 5 | Implement CSPM tool | 90 days |

---

## Risk by Asset

| Asset | Critical | High | Medium | Low | Total |
|-------|----------|------|--------|-----|-------|
| A001 - Customer Database | 2 | 0 | 1 | 0 | 3 |
| A002 - Employee Records | 1 | 0 | 1 | 0 | 2 |
| A003 - Financial Systems | 0 | 2 | 0 | 0 | 2 |
| A004 - Website/Applications | 1 | 0 | 0 | 0 | 1 |
| A005 - Email System | 0 | 0 | 0 | 0 | 0 |
| A006 - Cloud Infrastructure | 1 | 2 | 0 | 0 | 3 |

---

## Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | June 24, 2026 | Kaustubh Mahadik | Initial creation |
