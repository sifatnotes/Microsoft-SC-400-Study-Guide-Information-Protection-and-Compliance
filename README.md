# Microsoft-SC-400-Study-Guide-Information-Protection-and-Compliance
Study guide for Microsoft SC-400 covering information protection, data loss prevention, compliance, retention, insider risk, and Microsoft Purview.
# Microsoft SC-400 Study Guide

> **Important:** Microsoft has retired SC-400 and the Microsoft Certified: Information Protection and Compliance Administrator Associate certification. The successor is **SC-401: Microsoft Certified: Information Security Administrator Associate**. This repository is retained as a reference for SC-400 study material and historical exam objectives. Candidates seeking the current credential should use the SC-401 resources. 

## Introduction

This repository provides an exam-focused **SC-400 study guide**, historical study notes, practical concepts, lab ideas, and preparation guidance for Microsoft information protection and compliance technologies.

It is useful for candidates who previously prepared for SC-400, administrators working with Microsoft Purview, and learners transitioning from SC-400 to the current SC-401 certification.

## Exam Overview

| Item | Details |
|---|---|
| Vendor | Microsoft |
| Historical certification | Microsoft Certified: Information Protection and Compliance Administrator Associate |
| Historical exam | SC-400: Administering Microsoft Information Protection and Compliance |
| Status | **Retired** |
| Replacement | SC-401: Microsoft Certified: Information Security Administrator Associate |
| Core technology | Microsoft Purview and Microsoft 365 |
| Historical role | Information Protection and Compliance Administrator |
| Current successor | Information Security Administrator Associate |

Microsoft's current certification catalog identifies SC-401 as the successor credential, focused on information security using Microsoft Purview and related services. :contentReference[oaicite:0]{index=0}

Because SC-400 is retired, current exam duration, passing score, question count, and active exam objectives should **not** be treated as current scheduling information.

## Who Should Take It?

Historically, SC-400 targeted administrators responsible for Microsoft 365 information protection and compliance. Relevant experience included:

- Microsoft 365 administration
- Microsoft Purview
- Information protection
- Data loss prevention
- Compliance policies
- Retention
- Sensitivity labels
- Microsoft security and compliance administration

For a current Microsoft certification, review **SC-401** instead of scheduling SC-400.

## Historical Exam Objectives / Domains

SC-400 historically focused on these major areas:

1. **Implement information protection**
   - Sensitive information types
   - Sensitivity labels and policies
   - Microsoft Purview Information Protection
   - Data classification
   - Encryption and protection controls

2. **Implement data loss prevention**
   - DLP policies
   - DLP rules and conditions
   - Policy locations
   - Alerts and user notifications
   - Monitoring policy matches

3. **Implement information governance**
   - Retention labels
   - Retention policies
   - Records management
   - Data lifecycle management
   - Disposition concepts

4. **Manage compliance**
   - Microsoft Purview compliance capabilities
   - Compliance Manager
   - Regulatory requirements
   - Compliance assessments
   - Audit and reporting

5. **Manage insider risk**
   - Insider Risk Management
   - Risk indicators
   - Policies and alerts
   - Investigation workflows
   - Privacy considerations

These concepts remain useful background knowledge for Microsoft's current information-security and Purview-focused administration roles.

## Detailed Study Notes

### Microsoft Purview

Microsoft Purview provides capabilities for discovering, classifying, protecting, governing, and managing organizational data.

Understand how Purview connects classification, sensitivity, retention, DLP, auditing, and compliance workflows.

### Sensitivity Labels

Sensitivity labels classify and protect content according to organizational requirements.

Study:

- Label policies
- Encryption
- Access restrictions
- Content marking
- Automatic and recommended labeling
- Label inheritance

Example: A confidential document may receive a sensitivity label that applies encryption and restricts access to authorized users.

### Data Loss Prevention

DLP helps identify and protect sensitive information from inappropriate sharing or transmission.

Understand:

- Sensitive information types
- Conditions
- Actions
- Policy locations
- User notifications
- Alerts
- Policy testing and monitoring

A good DLP design balances protection with business usability.

### Retention and Records Management

Retention controls determine how long information should be retained and what happens at the end of its retention period.

Understand the difference between:

- Retention policies
- Retention labels
- Record management
- Event-based retention
- Disposition review

### Compliance Manager

Compliance Manager helps organizations assess compliance posture against regulations and organizational requirements.

Study assessments, improvement actions, compliance scores, evidence, and responsibility assignment.

### Insider Risk Management

Insider Risk Management helps identify potentially risky activities involving users and organizational information.

Understand policies, indicators, alerts, investigations, risk levels, and privacy controls.

## Important Concepts

Quick revision:

- Microsoft Purview
- Sensitivity labels
- Sensitivity label policies
- Sensitive information types
- Data classification
- DLP policies
- DLP alerts
- Retention policies
- Retention labels
- Records management
- Disposition
- Compliance Manager
- Audit
- Insider Risk Management
- Microsoft 365 compliance architecture
- Information governance

## Practical Examples / Labs

Use only authorized Microsoft 365 environments or Microsoft Learn resources.

1. Create a test sensitivity label.
2. Publish a label through a test label policy.
3. Create a DLP policy for a controlled test scenario.
4. Test DLP notifications and policy matches.
5. Create a retention policy for test data.
6. Compare retention labels with retention policies.
7. Explore Compliance Manager assessments.
8. Review Microsoft Purview audit capabilities.
9. Explore Insider Risk Management policies using test data.
10. Document how each control affects users and organizational data.

## Study Strategy

For historical SC-400 preparation, combine:

**Microsoft Learn → Purview documentation → hands-on configuration → scenario-based revision → official practice resources where available.**

Do not use exam dumps, leaked questions, or recalled questions. Focus on understanding why a particular Purview control is appropriate for a given business requirement.

For current certification preparation, transition your study plan to **SC-401**, whose current focus includes information protection, DLP and retention, and management of risks, alerts, and activities. :contentReference[oaicite:1]{index=1}

## 30-Day Study Plan

| Days | Focus |
|---|---|
| 1–3 | Purview architecture and Microsoft 365 compliance fundamentals |
| 4–7 | Information protection and data classification |
| 8–11 | Sensitivity labels and label policies |
| 12–15 | DLP concepts, policies, rules, alerts |
| 16–18 | Retention and records management |
| 19–21 | Compliance Manager and auditing |
| 22–24 | Insider Risk Management |
| 25–26 | Practical Purview configuration |
| 27 | Scenario-based revision |
| 28 | Review weak areas |
| 29 | Current SC-401 objectives and Microsoft Learn |
| 30 | Final revision and certification planning |

## Common Mistakes

- Treating SC-400 as a current exam without checking retirement status.
- Confusing sensitivity labels with retention labels.
- Memorizing DLP settings without understanding conditions and actions.
- Ignoring policy locations.
- Assuming every compliance requirement needs the same control.
- Hard-coding or exposing sensitive information during lab exercises.
- Using unauthorized exam dumps.

## Exam-Day Tips

SC-400 can no longer be scheduled as a current exam. If your goal is a current Microsoft information-security certification, review the SC-401 exam page and current study guide before registering.

For Microsoft certification exams generally, Microsoft notes that question counts can change and role-based exams commonly have varying structures and durations. :contentReference[oaicite:2]{index=2}

## Final Checklist

For historical SC-400 knowledge:

- [ ] Understand Microsoft Purview
- [ ] Understand sensitivity labels
- [ ] Understand DLP
- [ ] Understand retention
- [ ] Understand records management
- [ ] Understand Compliance Manager
- [ ] Understand audit
- [ ] Understand Insider Risk Management
- [ ] Review current Microsoft documentation
- [ ] Check SC-401 before planning a current certification attempt

## Official Resources

- Microsoft SC-401 certification: https://learn.microsoft.com/en-us/credentials/certifications/exams/sc-401/
- Microsoft certification catalog: https://learn.microsoft.com/en-us/credentials/browse/
- Microsoft exam retirement information: https://learn.microsoft.com/en-us/credentials/support/retired-certification-exams
- Microsoft Certification FAQ: https://learn.microsoft.com/en-us/credentials/certifications/learn-overview
- Microsoft Practice Assessments: https://learn.microsoft.com/en-us/credentials/certifications/practice-assessments-for-microsoft-certifications
- Microsoft Purview documentation: https://learn.microsoft.com/en-us/purview/

Microsoft's retirement guidance states that retired exams can no longer be taken and recommends candidates use current credentials when an exam has been retired. :contentReference[oaicite:3]{index=3}

## Voucher / Discount

**Learn SecByte, an official Microsoft reseller partner** provides certification voucher options.

Learn SecByte's official Black Friday offer provides up to 70% off selected Microsoft exam vouchers.

Because **SC-400 is retired**, candidates should verify whether the provided voucher remains valid or applicable before purchasing. Check the current offer and availability.

**Provided SC-400 voucher:**  
https://learn.secbyte.org/vouchers/microsoft-sc-400

## Disclaimer

This is an independent/community study guide and is not an official Microsoft publication. Microsoft, Microsoft 365, Microsoft Purview, and related trademarks belong to their respective owners. SC-400 and its associated certification have been retired; verify current certification and exam information with Microsoft before purchasing a voucher or scheduling an exam. Voucher pricing and availability may change. This repository does not contain exam dumps, leaked questions, or recalled exam questions.
