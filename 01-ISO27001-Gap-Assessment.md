# Cartex Technologies Ltd.
## ISO/IEC 27001:2022 | Information Security Gap Assessment

**Prepared by:** Concord Ekwonna  
**Assessment Type:** Preliminary ISMS Readiness Assessment  
**Framework:** ISO/IEC 27001:2022  

---

## 1. Executive Summary

Cartex Technologies Ltd. operates a digital platform supporting sales, inventory, customer information, and payments, with approximately 120 employees working on-site and remotely.

The organization has established foundational security measures, including an approved information security policy, password requirements, antivirus protection, regular backups, onboarding security awareness training, and MFA on selected cloud applications. However, Cartex has not established a formal Information Security Management System (ISMS).

This assessment identifies **five information security control gaps and one ISMS governance gap**, evaluates their potential risks, maps findings to ISO/IEC 27001:2022 requirements, and proposes corrective actions and evidence requirements to support ISMS readiness.

## 2. Assessment Scope and Approach

The assessment covers the information security practices described in the Cartex case study, focusing on asset management, security awareness, physical entry, access rights, secure authentication, and ISMS scope definition.

**Assessment approach:**
1. Review documented security practices and identified weaknesses.
2. Map findings to applicable ISO/IEC 27001:2022 requirements and Annex A controls.
3. Evaluate potential security and business consequences.
4. Propose remediation actions, accountable functions, and expected evidence.
5. Establish preliminary remediation priorities and verification criteria.

Findings were evaluated through a qualitative, risk-informed approach. Because system configurations, threat exposure, asset criticality, and operational evidence were unavailable, formal likelihood and impact scores were not assigned.

## 3. Security Gap Assessment

| ID | Identified Gap | ISO 27001:2022 Mapping | Potential Risk | Recommended Corrective Action |
|---|---|---|---|---|
| G-01 | No centralized information asset inventory; departments maintain separate records. | **A.5.9** - Inventory of Information and Other Associated Assets (Organizational) | Unidentified assets may lack appropriate ownership, monitoring, and protection. | Establish a centralized asset register, assign owners, and implement periodic inventory reviews. |
| G-02 | Security awareness training is provided during onboarding without recurring refreshers. | **A.6.3** - Information Security Awareness, Education and Training (People) | Employees may become less prepared to recognize evolving security threats. | Introduce periodic refresher training, targeted awareness campaigns, and completion tracking. |
| G-03 | No formal access authorization and review process for sensitive physical areas. | **A.7.2** - Physical Entry (Physical) | Unauthorized individuals may gain access to sensitive facilities, equipment, or information. | Document physical access authorization, maintain access records, and conduct periodic reviews. |
| G-04 | System access rights are not consistently reviewed following employee role changes. | **A.5.18** - Access Rights (Organizational) | Excessive or outdated privileges may enable unauthorized access to sensitive information. | Implement a formal joiner-mover-leaver process and require timely access adjustments following role changes. |
| G-05 | MFA is implemented on some cloud applications but not consistently across relevant systems. | **A.8.5** - Secure Authentication (Technological) | Accounts without appropriate authentication protection may be more susceptible to credential compromise. | Assess authentication coverage, implement risk-based MFA requirements, and document approved exceptions. |

### Additional Governance Finding - G-06

**Requirement:** ISO/IEC 27001:2022 Clause 4.3 - Determining the Scope of the ISMS.

**Observation:** Cartex has not formally defined its ISMS scope.

**Risk:** Unclear organizational boundaries and dependencies may result in inconsistent ISMS implementation and gaps in security accountability.

**Recommendation:** Define, document, and obtain management approval for an ISMS scope that considers business activities, relevant stakeholders, internal and external issues, and interfaces with other organizations.

**Expected Evidence:** Approved ISMS scope statement and documented scope determination.

This is a management-system requirement, not an Annex A control.

## 4. Preliminary Risk-Based Remediation Priorities

The following priorities represent proposed remediation sequencing based on potential exposure and implementation dependencies. They are not formal risk ratings.

| Priority | Finding | Rationale |
|---|---|---|
| Immediate assessment | G-04 - Access Rights | Unnecessary privileges could expose sensitive systems and information. |
| Immediate assessment | G-05 - MFA Coverage | Authentication gaps may increase the risk of unauthorized account access. |
| Foundational | G-06 - ISMS Scope | Defining the scope establishes boundaries for systematic ISMS implementation. |
| Foundational | G-01 - Asset Inventory | Asset visibility supports ownership, risk assessment, and appropriate control selection. |
| Planned remediation | G-03 - Physical Entry | Formal access governance reduces unauthorized physical access exposure. |
| Planned remediation | G-02 - Security Awareness | Recurring training supports sustained employee security awareness. |

**Priority Validation:** Management should confirm final priorities following an assessment of asset criticality, existing compensating controls, likelihood, business impact, and risk appetite.

## 5. Proposed Remediation and Verification Plan

| Finding | Proposed Accountable Function | Target Timeline* | Expected Evidence | Verification Method |
|---|---|---|---|---|
| G-01 | IT / Asset Management | 30–60 days | Centralized asset register and assigned ownership records | Sample asset records and reconcile them with departmental inventories. |
| G-02 | HR / Information Security | 60–90 days | Approved training schedule and completion reports | Review training records and completion tracking. |
| G-03 | Facilities / Security | 30–60 days | Authorized access list, access procedures, and review records | Inspect documented approvals and sample physical access records. |
| G-04 | IT / Identity and Access Management | 0–30 days | Access review reports, role-change tickets, and approval records | Sample employee role changes and confirm corresponding access adjustments. |
| G-05 | IT Security | 0–30 days | MFA configuration reports, coverage records, and exception approvals | Review authentication settings for a sample of in-scope systems. |
| G-06 | ISMS Lead / Senior Management | 0–30 days | Documented and approved ISMS scope | Verify that scope boundaries, interfaces, and dependencies are defined and approved. |

*Timelines are illustrative targets proposed for the simulated engagement. They have not been agreed with Cartex management.

**Closure Criteria:** A finding should only be considered remediated when corrective actions are implemented, supporting evidence is available, and appropriate verification confirms that the identified weakness has been addressed.

## 6. Proposed ISMS Scope Statement

The proposed ISMS scope covers the people, processes, information assets, and technology systems supporting Cartex Technologies Ltd.'s digital platform for sales, inventory management, customer information, and payment services.

It includes relevant on-site and remote working arrangements and supporting information security activities. Organizational boundaries, external dependencies, interfaces, and any proposed exclusions require validation before management approval.

## 7. Conclusion

Cartex has implemented several foundational security measures but requires more consistent governance, access management, asset visibility, authentication controls, and security awareness practices to support a structured ISMS.

The proposed remediation plan provides a starting point for assigning accountability, addressing control weaknesses, and collecting evidence to demonstrate implementation.
