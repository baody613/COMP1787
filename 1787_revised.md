COMP1787 Requirements Management Coursework Report

---

# COVER PAGE

## COMP1787 Requirements Management Coursework

**Digital Service Delivery System for Public Sector Applications**

**Student:** Tong Bao Duy

**Student ID:** GCS210642

**Date of Submission:** June 2026

**Academic Year:** 2025–2026

---

# BUSINESS CASE DESCRIPTION

A UK public sector organisation currently operates a manual, paper-based system for processing citizen applications. The system involves multiple handoff points, prolonged processing times, and high administrative costs. Stakeholders include citizens (applicants), administrative staff, senior management, and external partners. The organisation seeks to implement a digital platform that standardises procedures, reduces processing times, and improves transparency. The proposed approach is to adopt Agile software development methodologies to allow for iterative delivery and stakeholder engagement throughout the implementation lifecycle.

---

# TABLE OF CONTENTS

1. Section A: Public Sector Projects, Business Context, and Agile Methodology
2. Section B: Requirements Analysis, Review, and Prioritisation
3. Section C: Legal, Social, Ethical, and Professional Considerations
4. Conclusion and Implementation Recommendations
5. References

---

# SECTION A: PUBLIC SECTOR PROJECTS, BUSINESS CONTEXT, AND AGILE METHODOLOGY

## A1: Executive Summary and Business Case Context

### Business Problem and Organisational Goals

The organisation currently faces significant operational inefficiencies stemming from its reliance on manual, paper-based application processing systems. These legacy processes introduce multiple challenges: extended processing timelines that can span weeks or months, inconsistent decision-making due to lack of standardisation, high operational costs attributable to labour-intensive administrative work, and limited transparency for citizens regarding application status. The case study organisation has identified the digital transformation of this application processing system as a strategic priority aligned with broader government digitisation initiatives and public sector modernisation mandates (as described in the Business Case Description provided at project initiation).

The business goals driving this initiative are multifaceted. Firstly, the organisation aims to reduce the time-to-decision for citizen applications by automating routine checks, validation, and communication workflows. Secondly, it seeks to improve data quality and consistency by implementing standardised digital forms and validation logic at the point of submission. Thirdly, the organisation intends to enhance citizen satisfaction through transparency, self-service capabilities, and proactive communication. Fourthly, senior management expects significant cost reductions through labour optimisation and process efficiency gains. These goals must be balanced against the constraints of the public sector environment, where budgetary certainty, compliance with regulatory frameworks, and public accountability are paramount considerations (UK Parliament, 2010).

### Appropriateness of Agile Methodology

Public sector projects have historically demonstrated elevated failure rates when adopting traditional Waterfall methodologies (Sommerville, 2015, p. 48). The primary reason is that requirements in government-facing applications are inherently volatile due to frequent legislative changes, shifting policy priorities, and evolving citizen expectations. Unlike commercial software where market conditions may shift gradually, public sector organisations must often respond rapidly to new legislation or policy directives that fundamentally alter system requirements.

Agile methodologies are particularly well-suited to this context for several evidence-based reasons. First, Agile operates through iterative cycles or "sprints" that typically last 2–4 weeks, allowing the development team to deliver functional software increments at regular intervals rather than attempting a "big bang" release after 18–24 months of development. This approach provides immediate value demonstration to taxpayers and stakeholders, a critical factor in public sector projects where accountability and transparency are essential (Sommerville, 2015, p. 52). Second, Agile methodologies facilitate continuous stakeholder engagement throughout development, ensuring that the delivered system reflects actual user needs rather than assumptions recorded in initial specification documents. Third, Agile accommodates requirement changes by treating them as normal and expected rather than as project failures, making it resilient to legislative or policy changes that may occur during the project lifecycle (Boehm and Turner, 2004, p. 31).

## A2: Advantages of Agile for This Project

The principal advantage is organisational adaptability. For instance, if government policy regarding benefit eligibility criteria changes mid-project, an Agile team can incorporate the new business rules into the next sprint cycle without requiring a comprehensive rework of project plans and budgets. This flexibility is critical in government applications where legislative change cycles are predictable and regular.

A second key advantage is stakeholder alignment. By conducting sprint reviews with administrators, citizens, and senior management at regular intervals, the team ensures that the final product actually solves the identified business problems rather than implementing a specification that has become outdated or misaligned with operational needs (Sommerville, 2015, p. 56). This continuous feedback mechanism significantly reduces the risk of a "surprise failure" at delivery where stakeholders discover that the system does not meet their expectations.

A third advantage is risk mitigation through incremental delivery. By delivering small, working software increments every 2–4 weeks, the organisation can identify technical or organisational impediments early and adjust course before significant budget or schedule commitments are made. For instance, if the team discovers that integrating with legacy back-office systems is more complex than anticipated, this knowledge is gained in week 6 of an 18-month project, allowing for course corrections, rather than week 70 of a traditional Waterfall approach.

Fourth, Agile promotes knowledge retention within the team. By working in iterative cycles with regular retrospectives, the team continuously learns from prior iterations and optimises its processes and delivery mechanisms, resulting in accelerating velocity and improving quality over time.

## A3: Challenges and Risk Mitigation in the Public Sector Context

Despite these advantages, Agile introduces challenges specific to the public sector environment that must be actively managed. The primary concern is the tension between Agile's flexible, emergent scope and the public sector's requirement for budgetary certainty and fixed funding approvals. Government bodies typically require detailed cost estimates and fixed delivery timelines before approving budget allocations. Agile's incremental, adaptive approach can result in scope creep—the progressive addition of features or requirements that were not originally costed, leading to budget overruns and schedule delays (Boehm and Turner, 2004, pp. 52-67).

To mitigate this risk, the organisation should establish a clear, fixed Minimum Viable Product (MVP) scope at project initiation, based on the prioritised requirements detailed in Section B. This MVP defines the boundary of features included in the initial release and provides the foundation for budgetary planning and stakeholder communication. Features beyond the MVP are explicitly classified as "Should Have" or "Could Have" under the MoSCoW framework and are scheduled for subsequent phases only if budget and capacity permit. This approach maintains budgetary discipline while preserving Agile's flexibility within a bounded scope.

A second challenge is the cultural resistance from senior management accustomed to traditional project governance. Government organisations often operate within hierarchical decision-making structures where executive approval gates are established based on anticipated milestones (e.g., design complete in month 4, development complete in month 12). Agile's emphasis on working software incrementally delivered rather than detailed upfront design documentation may conflict with established governance structures and create uncertainty among senior stakeholders about project progress (Boehm and Turner, 2004, pp. 78-89).

Mitigation requires executive sponsorship and change management. The organisation should invest in training and coaching for senior management on Agile principles and governance models suitable for public sector contexts. Establishing a steering committee that reviews sprint outcomes, backlog evolution, and product metrics at regular intervals (e.g., every 4 weeks) ensures visibility for senior stakeholders while respecting the Agile team's autonomy in determining how to achieve sprint goals.

A third challenge is the documentation gap. Unlike Waterfall approaches that produce comprehensive design documents, specification documents, and test plans at project initiation, Agile emphasises working software over comprehensive documentation. However, government organisations often face strict auditing requirements and must maintain detailed records of system design decisions, change justifications, and deployment configurations for compliance purposes (UK Parliament, 2010). Insufficient documentation can create post-implementation audit liabilities and operational risks.

Mitigation requires establishing documentation standards that balance Agile principles (minimal but sufficient) with regulatory requirements. The team should maintain a decision log capturing significant design decisions and their rationale, architecture diagrams documenting system structure and external integrations, a requirements traceability matrix linking user requirements to implemented features, and deployment runbooks documenting operational procedures. These artefacts are maintained incrementally throughout the project rather than created retrospectively, reducing overhead whilst ensuring compliance.

## A4: Financial Considerations and Return on Investment

Current operational costs of the manual system include personnel costs for administrative staff processing applications (estimated at 2.5 FTE staff at £35,000 per annum = £87,500 annually), costs associated with physical document storage and retrieval systems (estimated at £15,000 annually), and overhead costs for office space and equipment (estimated at £10,000 annually). Total annual operational cost of the manual system: approximately £112,500.

The proposed digital system requires initial capital investment for development, infrastructure, and deployment. Estimated development costs for an 18-month Agile project including product management, development team (4–5 developers), quality assurance, and infrastructure setup are approximately £450,000–£550,000 (including contingency). Infrastructure hosting, licensing, and operational support are estimated at £40,000–£50,000 annually.

Expected benefits from the digital system include personnel cost reductions through automation of routine tasks, with an estimated reduction of 1.5 FTE to 1.0 FTE following system implementation, generating annual savings of approximately £52,500. Reduction in document storage and retrieval overhead through elimination of physical document handling, estimated at £12,000 annually. Improvement in processing cycle time from an average of 28 days to 7 days, enabling processing of a higher volume of applications with existing capacity, with an estimated revenue impact of £80,000 annually from processing an additional 15% of applications without additional staffing. Reduction in support and inquiry costs through improved transparency and self-service capabilities, estimated at £20,000 annually. Total estimated annual benefits: approximately £164,500.

Break-even analysis indicates that the project achieves payback of its initial investment within 3.5–4 years. Net Present Value (NPV) over a 5-year evaluation period, assuming a discount rate of 3.5% (typical for public sector analyses), is estimated at £420,000–£480,000. Internal Rate of Return (IRR) is estimated at approximately 22–28%, substantially exceeding the public sector hurdle rate of 5–7%, indicating a strong business case for investment.

However, this analysis is subject to key risks: realisation of efficiency gains depends on adequate stakeholder change management and user adoption of digital processes; citizen adoption rates may be lower than projected, particularly for elderly or disadvantaged populations with limited digital literacy; legislative or policy changes may alter processing requirements, necessitating system modifications; and technical risks including system availability, security breaches, or integration failures with legacy systems could undermine benefits realisation.

## A5: Broader Business and Stakeholder Impacts

### Operations

Implementation of the digital system will fundamentally reshape operational workflows. Currently, applications enter a queue at reception, are distributed manually to available staff, and progress through multiple handoff points before final decision and communication. The digital system will introduce automated intake (validation of form completeness and mandatory fields), standardised workflow routing based on predefined rules, and automated communication triggered by status changes. These changes will require retraining of administrative staff, potentially creating short-term productivity dips during transition. The organisation should plan for a 4–6 week transition period during which processing capacity will be reduced whilst staff adapt to new workflows. Post-transition, operational efficiency should increase by 30–40%, but this realisation is contingent on effective change management and stakeholder engagement.

### Compliance

The organisation operates within multiple regulatory frameworks including the UK General Data Protection Regulation (GDPR) under the Data Protection Act 2018, the Public Sector Equality Act 2010 (requiring accessible services for disabled citizens), and potentially sector-specific legislation depending on the application domain. The digital system must be designed with compliance as a foundational requirement rather than an afterthought. Data protection by design, implementation of privacy impact assessments, accessibility compliance testing, and audit trail generation for regulatory reporting are essential components of the system. Failure to embed these requirements adequately could expose the organisation to significant compliance and reputational risks.

### Market Position and Strategic Implications

Digital service delivery is increasingly expected by citizens and is a key performance indicator in government modernisation assessments. The successful implementation of this platform positions the organisation as a forward-thinking public sector entity, enhancing its reputation and potentially attracting partnership opportunities with other government bodies facing similar challenges. Conversely, failure or significant delays in implementation could undermine the organisation's credibility and limit future digital initiatives.

### Key Stakeholders and Their Concerns

**Citizens (Applicants):** Primary concern is ease of use, assurance of data security and privacy, and visibility of application progress. Older citizens and those with limited digital literacy may require alternative channels (telephone support, in-person assistance) to access the service equitably.

**Administrative Staff:** Concerns include job security (will the system eliminate my position?), requirement for new technical skills, and potential for increased monitoring/performance metrics through system-generated data. Mitigation requires clear communication that automation is designed to eliminate routine, low-value tasks whilst creating opportunities for higher-value work such as exception handling and complex decision-making.

**Senior Management:** Concerns centre on costs, timeline certainty, risk mitigation, and visibility into project progress. Clear financial analysis (as provided in Section A4), transparent governance structures, and regular reporting of key performance indicators are essential to maintain executive support.

**External Partners:** If the system integrates with partner organisations' systems (e.g., verification services, payment systems), partners will have concerns regarding data sharing agreements, API stability and support, and change notification procedures.

## A6: Actionable Recommendations and Implementation Roadmap

### Immediate Actions (Months 1–2)

1. Establish a cross-functional steering committee including representatives from senior management, citizen services, IT operations, and an independent project management office. This committee meets bi-weekly to review progress, address impediments, and approve scope changes.

2. Conduct a detailed feasibility study addressing technical architecture options, integration requirements with legacy systems, and preliminary risk assessment. Estimated effort: 6–8 weeks.

3. Develop a comprehensive change management and stakeholder engagement plan. Identify key stakeholder groups, define engagement strategies for each group, and plan change impact assessments and communication campaigns for each phase of implementation.

4. Establish a clear, documented Agile governance model adapted for the public sector context. Define the roles and responsibilities of the Product Owner, Scrum Master, development team, and steering committee. Specify decision-making authorities, escalation paths, and reporting requirements.

### Phase 1: Foundation and MVP Development (Months 3–9)

1. Execute sprint planning with clear definition of the MVP scope based on the prioritised requirements detailed in Section B. The MVP includes all "Must Have" requirements and a subset of "Should Have" requirements. Estimated velocity: 40–60 story points per sprint, assuming 2-week sprints.

2. Establish development infrastructure including version control, continuous integration pipelines, automated testing frameworks, and deployment automation. Estimated effort: 3–4 weeks.

3. Implement the core functional features: user registration, form submission, administrative review interface, and role-based access control (FR-01, FR-02, FR-05, FR-08).

4. Implement foundational non-functional requirements: security (AES-256 encryption for PII), basic availability targets (99% uptime during working hours), and automated backup procedures.

5. Conduct user acceptance testing with administrative staff and a pilot group of citizens in week 8 of the phase, feeding back results to the development team for refinement.

6. Plan for deployment readiness including operational runbooks, support procedures, and contingency plans for rollback.

### Phase 2: Enhancements and Hardening (Months 9–15)

1. Implement remaining "Should Have" and "Could Have" features based on priority and stakeholder feedback: document upload (FR-03), application dashboard (FR-04), automated communication (FR-06), search and filtering (FR-07), usability enhancements, and performance optimisations.

2. Conduct comprehensive security testing and penetration testing to validate protection against external threats and ensure compliance with government security standards.

3. Execute extensive user training for administrative staff, including classroom instruction, on-the-job coaching, and development of user documentation and video guides.

4. Plan rollout to broader user population, potentially through a phased approach (pilot region first, then broader rollout) to manage risk and allow for refinement based on initial operational experience.

### Phase 3: Stabilisation and Transition to Operations (Months 15–18)

1. Conduct parallel running of digital and legacy systems for 2–4 weeks to validate system functionality under real operational load and allow staff to build confidence.

2. Transition to full production operation of the digital system, with legacy system run-off and archival of historical records.

3. Establish operational support structures including help desk procedures, incident response protocols, and change management processes for post-implementation modifications.

4. Plan for Phase 2 enhancements including advanced reporting, analytics capabilities, and integration with legacy back-office systems to be implemented following the initial stabilisation period.

---

# SECTION B: REQUIREMENTS ANALYSIS, REVIEW, AND PRIORITISATION

## B1: Requirements Gathering and Review Process

### Methodological Approach

Requirements for the digital system were gathered through a structured process involving multiple stakeholder groups. The approach employed semi-structured interviews with administrative staff members (n=8) to understand current workflows, pain points, and information needs. Focus groups with citizens (n=3 groups, 12 citizens total) were conducted to understand user needs, accessibility requirements, and preferences for communication and feedback. Executive interviews were conducted with senior management (n=3) to clarify strategic objectives, budget constraints, and key success metrics. Document analysis of current procedural manuals, forms, and process diagrams was conducted to identify existing requirements and constraints.

Requirements gathered from these sources were then synthesised and organised using affinity mapping—grouping similar requirements into logical categories (authentication, submission, review, communication, administration). This process resulted in an initial set of 42 potential requirements spanning functional, non-functional, and operational domains.

### Requirement Review and Filtering Process

The initial set of 42 requirements was then subjected to a rigorous review process designed to eliminate duplicates, identify conflicts, and ensure alignment with the prioritised business objectives outlined in Section A. The review process followed these steps:

**Step 1: Duplicate Identification and Consolidation**
Each requirement was checked against all others to identify statements that addressed identical functionality but were phrased differently or came from different stakeholder groups. For example, two requirements—"The system must provide users with visibility of their application status" and "Citizens should be able to track progress on their submitted applications"—were identified as duplicates and consolidated into a single, more precisely worded requirement.

**Step 2: Conflict Identification**
Requirements were screened for potential conflicts or contradictions. For instance, an initial requirement stated "The system must provide real-time updates of application status to citizens via SMS," whilst another stated "SMS communication should be optional and not imposed on all citizens." These were identified as conflicting. The conflict was resolved through stakeholder discussion, determining that SMS communication should be opt-in rather than mandatory, reducing unnecessary operational costs whilst preserving citizen choice.

**Step 3: Scope Boundary Analysis**
Requirements were evaluated against the defined project scope (digital intake and review process) to ensure they fell within project boundaries. For instance, a requirement to "integrate with the legacy financial system to automatically transfer approved applications for benefit payments" was identified as exceeding the initial scope and was deferred to a Phase 2 enhancement, documented for future reference but not included in the MVP.

**Step 4: Stakeholder Validation**
The consolidated and filtered requirement set was presented back to stakeholder groups (administrative staff, citizens, management) for validation. This step ensured that requirements accurately reflected stakeholder needs and that no critical requirements had been inadvertently excluded during consolidation. Stakeholder feedback resulted in the addition of two previously overlooked requirements related to accessibility and multi-language support.

Following this systematic review process, the initial set of 42 requirements was consolidated to 23 distinct, validated requirements without significant overlap or conflict. These 23 requirements form the basis for the detailed analysis in subsequent sections.

### Analysis and Rationale

The requirements are grounded in evidence from stakeholder interviews, analysis of existing operational data (e.g., current application processing times, error rates, citizen complaints), and reference to best practices in digital government service delivery (UK Government Digital Service standards, GOV.UK Design System guidance). The rationale for each requirement is documented in the requirements specification, linking the requirement to specific business objectives, user needs, or compliance obligations.

For example, the requirement for "role-based access control" is grounded in evidence from administrative staff interviews indicating variability in the scope of access granted to different roles, creating security risks and audit concerns. The business rationale is to ensure that system access privileges are aligned with job responsibilities and segregation of duty principles, reducing security risk and supporting compliance with audit requirements. This evidence-based linkage ensures that requirements are not merely "nice-to-have" features but are directly tied to the business case and strategic objectives outlined in Section A.

## B2: Functional Requirements Analysis

The system requires eight high-level functional requirements to support the core business processes of application submission and administrative review:

| Req ID | Requirement Name | Description | Business Justification | Source |
|--------|------------------|-------------|------------------------|--------|
| FR-01 | User Registration & Authentication | The system must allow users to create an account and log in securely using credentials (username and password or government digital identity verification). | Identity verification is essential to prevent fraud, ensure authenticity of claims, and protect sensitive personal information. Aligns with government identity verification standards. | Staff interviews, admin concerns, compliance requirements |
| FR-02 | Form Submission | Users must be able to fill out structured digital application forms, save incomplete submissions as drafts, and submit completed forms. The system must acknowledge receipt and provide a unique reference number. | Directly addresses the primary business problem: eliminating manual, paper-based submission processes. Reduces data entry errors and provides evidence of submission. | Stakeholder interviews, process analysis, citizens focus group |
| FR-03 | Document Upload | The application system must allow users to upload supporting evidence (PDFs, images) with file size limits and validation of acceptable formats. | Administrative staff require supporting documentation to verify claims made in the application form. Without this functionality, staff would revert to requesting physical documents, reverting to the manual process. | Staff interviews, workflow analysis |
| FR-04 | Application Dashboard | Authenticated users must have access to a personalised dashboard displaying all their submitted applications, current status, timeline of status changes, and estimated processing time. | Empowers self-service access to information, reducing phone calls to support centre and improving citizen satisfaction. Supports transparency in government service delivery. | Citizen focus groups, benefit realisation analysis |
| FR-05 | Administrative Review Interface | Staff members must access a dedicated portal where they can view submitted applications, review supporting documentation, add internal notes, and record approval/rejection decisions with justification. | Core operational requirement. Staff efficiency and consistency of decision-making depends on a structured review interface. | Staff interviews, workflow analysis, business case |
| FR-06 | Automated Communication | The system must automatically send notifications (email and/or SMS, citizen's choice) when application status changes (e.g., received, under review, approved, rejected). | Proactive communication builds trust in government services and reduces phone inquiries regarding application status. Supports accessibility requirement to ensure all citizens understand their application status. | Citizen focus group feedback, customer experience analysis |
| FR-07 | Search and Filtering | Administrative staff must be able to search for applications by citizen name, reference number, date of submission, or application status. System must support filtering to identify subsets of applications (e.g., "all approved applications from June 2026"). | Staff workflow efficiency depends on rapid location of application records. Supports audit requirements for identifying and reporting on application subsets. | Staff interviews, operational efficiency analysis |
| FR-08 | Role-Based Access Control | The system must implement granular access control, differentiating privileges between: (a) basic users (citizens) with access to their own applications only; (b) standard staff with access to applications in their assigned queue; (c) senior staff with access to applications and ability to override decisions; (d) system administrators with full system access. | Security requirement to prevent unauthorised access, data leakage, or inappropriate modification. Supports compliance with segregation of duty principles and audit requirements. | Information security assessment, staff roles analysis, compliance requirements |

## B3: Non-Functional Requirements Analysis and Completeness Assessment

Beyond functional requirements, the system must meet several non-functional requirements defining quality attributes and operational constraints:

| NFR ID | Category | Requirement | Detailed Description | Business Justification |
|--------|----------|-------------|----------------------|------------------------|
| NFR-01 | Security | Data Encryption | All personally identifiable information (PII) stored in the database must be encrypted using AES-256 standard. Encryption keys must be managed securely and rotated on a defined schedule (e.g., annually). | Legal requirement under UK GDPR. Protects citizens' privacy and sensitive government data. Reduces liability from potential data breach scenarios. |
| NFR-02 | Security | Authentication | All user access to the system must be authenticated using government-approved identity verification (e.g., UK Verify or equivalent). Passwords, if used, must comply with GCHQ password guidance (minimum 8 characters, no mandatory special characters). | Legal requirement under GDPR. Reduces fraud and identity theft risks for citizen applicants. |
| NFR-03 | Availability | System Uptime | The platform must maintain 99.0% uptime availability during standard working hours (08:00–18:00, Monday–Friday). This is measured over a rolling 30-day period. | Citizens and staff depend on system availability for daily operations. Downtime creates citizen frustration and forces staff to revert to manual processes. Target is achievable with standard cloud infrastructure and documented SLAs. |
| NFR-04 | Usability | Accessibility Compliance | The user interface must comply with Web Content Accessibility Guidelines (WCAG) 2.1 Level AA standards, ensuring usability for citizens with visual, auditory, mobility, or cognitive impairments. This includes keyboard navigation, screen reader compatibility, and colour contrast compliance. | Legal requirement under the Public Sector Equality Act 2010. Ensures equitable access to government services. Aligns with government accessibility standards (Government Accessibility Requirements). |
| NFR-05 | Usability | Multilingual Support | The system must support English and [language as specified for local region], with interface translations and support for document submission in both languages. | Ensures accessibility for diverse citizen populations, particularly recent immigrants or citizens with limited English proficiency. Reduces barriers to service access. |
| NFR-06 | Performance | Page Load Time | The system must load all application pages within 3 seconds under normal operating conditions (peak concurrent users: 150). This includes form pages, dashboard views, and administrative interfaces. | Slow page loads create user frustration, reduce adoption, and create perception of poor system quality. 3-second target aligns with government web performance guidance. |
| NFR-07 | Performance | Scalability | The system architecture must support scaling to accommodate up to 500 concurrent users without degradation of performance beyond the 3-second page load target. | Administrative staff may spike during peak application periods. Citizens may access the system simultaneously across regions. System must accommodate this demand variability. |
| NFR-08 | Reliability | Data Backup | Automated backups of the production database must occur every 24 hours, with backups retained for a minimum of 7 years (compliance requirement). Backup integrity must be verified through automated testing (restore validation). | Protects against data loss from hardware failures, corruption, or human error. 7-year retention aligns with government record retention policies. |
| NFR-09 | Reliability | Disaster Recovery | A documented disaster recovery plan must be established defining recovery time objective (RTO) of 4 hours and recovery point objective (RPO) of 1 hour (maximum data loss). Regular disaster recovery drills must be conducted quarterly. | Ensures business continuity in case of catastrophic failure (data centre outage, corrupted backup, etc.). 4-hour RTO ensures that extended outages cannot occur. |
| NFR-10 | Compliance | Audit Trail | The system must maintain an immutable audit trail capturing all significant events: user login/logout, form submission, status changes, administrative actions (approvals, rejections), system configuration changes. Audit trail entries must include timestamp, user identifier, action description, and result/outcome. | Required for government compliance audits and investigation of irregularities. Provides evidence of correct processing procedures and detection of unauthorized access or modification. |

## B4: Identification of Inaccurate and Problematic Requirements

During the requirement review process, several statements made by stakeholders were identified as not qualifying as formal system requirements. These are documented below to explain why they were filtered out:

| ID | Statement | Reason for Exclusion |
|----|-----------|----------------------|
| IR-01 | "The system must never crash." | Unrealistic: All software systems have potential for failure due to hardware failures, network issues, or unexpected operating conditions. Instead, we establish a realistic uptime target (NFR-03: 99.0% availability), acknowledge that occasional failures may occur, and establish recovery procedures to minimise impact and recovery time. |
| IR-02 | "The interface needs to look very modern and cool." | Subjective Observation: This is not a measurable, testable requirement. Visual aesthetics differ by user cohort—what appears "modern" to younger citizens may appear confusing to elderly users. Government service design guidance emphasises clarity and usability over trend-chasing aesthetics. Instead, requirement NFR-04 specifies adherence to accessibility standards and government design principles, which balance usability and professional presentation. |
| IR-03 | "Staff are currently taking too long to find files." | Observation Statement: This describes a current-state problem, not a system requirement. However, it justifies the inclusion of functional requirement FR-07 (search and filtering) as a solution. The business problem is documented to explain the rationale for the requirement, but the problem statement itself is not a requirement. |
| IR-04 | "The system should handle 10,000 concurrent users." | Unrealistic for Context: A focus group participant suggested this number without understanding typical usage patterns. Analysis of the organisation's application volume (approximately 200 applications per day, peaking during benefit eligibility period changes) and the ratio of citizen applicants to administrative staff processing applications indicates that peak concurrent users will likely be 150–200, not 10,000. The more realistic requirement (NFR-07) specifies 500 concurrent users as a prudent overestimate. |
| IR-05 | "The system must integrate with all legacy systems." | Out of Scope: Integration with legacy back-office systems (payroll, benefits administration) was identified as important but excluded from the MVP scope to maintain budget and schedule within defined limits. This is documented as a Phase 2 enhancement to be addressed in subsequent project phases. |

## B5: MoSCoW Prioritisation Framework and Process

The MoSCoW prioritisation framework categorises requirements into four categories: Must Have (essential for MVP delivery), Should Have (highly important but not essential for MVP), Could Have (desirable enhancements), and Won't Have (explicitly deferred to later phases). This framework provides structured guidance for development team planning and scope management.

### Prioritisation Methodology

The prioritisation process was conducted through a structured workshop involving representatives from each stakeholder group: senior management, administrative staff, citizen representatives, and the project sponsor. The process followed these steps:

**Step 1: Stakeholder Nomination of Priority Criteria**
Stakeholders identified the criteria by which requirements should be prioritised:
- Strategic importance to the business case and documented goals (Section A)
- Impact on key operational metrics (processing time, cost, citizen satisfaction)
- Dependencies (some requirements are prerequisites for others; for example, authentication is required before form submission)
- Risk exposure if the requirement is not delivered (security, compliance, operational impact)
- Effort estimation for implementation (relative complexity)

**Step 2: Risk Weighting Analysis**
Requirements were assessed for risk exposure using the framework: Risk = Business Impact × Probability of Failure. For instance, the security requirement (NFR-01) was assigned high business impact (consequences of a data breach are severe: financial penalties, reputational damage, citizen trust erosion) and moderate probability of failure if not implemented (security vulnerabilities in digital systems are common), resulting in a high-risk requirement that must be included in the MVP.

Conversely, the performance optimisation requirement (improving page load time below 2 seconds) was assigned moderate business impact (user experience degradation but system remains functional) and low probability of failure if not addressed in MVP (pages can be optimised in Phase 2), resulting in medium priority.

**Step 3: Pareto Analysis**
Requirements were ranked by their contribution to business value (the 80/20 principle). The analysis identified that 5 functional requirements (FR-01, FR-02, FR-05, FR-08 and FR-07) and 4 non-functional requirements (NFR-01, NFR-02, NFR-03, NFR-04) account for approximately 80% of the value delivered to stakeholders and achievement of the business case objectives. These requirements were designated as "Must Have" for MVP delivery.

**Step 4: Dependency Analysis**
Requirements were assessed for logical dependencies. For instance, FR-05 (administrative review interface) is dependent on FR-01 (user authentication) being implemented first; staff cannot log in and review applications without authentication. This dependency structure informed the recommended implementation sequence.

### MoSCoW Categorisation and Justification

| Priority Level | Assigned Requirements | Business Justification | Effort Estimate | Delivery Phase |
|----------------|----------------------|------------------------|-----------------|-----------------|
| **Must Have** | FR-01: User Registration & Authentication | System cannot function without authentication; enables all other security controls. | 2–3 weeks | Phase 1 |
| | FR-02: Form Submission | Primary business problem; without this, project is pointless. | 2–3 weeks | Phase 1 |
| | FR-05: Administrative Review Interface | Core operational requirement; enables staff to process applications. | 3–4 weeks | Phase 1 |
| | FR-08: Role-Based Access Control | Security and compliance requirement; mandated to prevent data breaches. | 2–3 weeks | Phase 1 |
| | NFR-01: Data Encryption | Legal requirement under GDPR; mandatory for government systems. | 1–2 weeks | Phase 1 |
| | NFR-02: Authentication Security | Legal requirement; mandated identity verification. | 2–3 weeks | Phase 1 |
| | NFR-04: Accessibility Compliance | Legal requirement under Equality Act 2010; mandated for public services. | 3–4 weeks | Phase 1 |
| | NFR-10: Audit Trail | Compliance and operational requirement; essential for government audits. | 2–3 weeks | Phase 1 |
| **Should Have** | FR-03: Document Upload | Highly important for reducing staff rejection of applications due to missing evidence. Improves first-time application quality. | 2–3 weeks | Phase 2a (early Priority) |
| | FR-04: Application Dashboard | High citizen satisfaction impact; reduces support calls. Self-service capability aligns with government digital strategy. | 2–3 weeks | Phase 2a |
| | FR-06: Automated Communication | High citizen satisfaction impact; proactive communication reduces inquiries. | 1–2 weeks | Phase 2a |
| | FR-07: Search and Filtering | Staff efficiency requirement; reduces time to locate applications from ~5 minutes to <30 seconds. | 1–2 weeks | Phase 2a |
| | NFR-03: System Uptime | Important for operational reliability; 99% uptime is achievable with standard cloud SLA. | 1–2 weeks | Phase 1 (foundational) |
| | NFR-05: Multilingual Support | Accessibility requirement for diverse citizen population; reduces barriers to access. | 2–3 weeks | Phase 2a |
| | NFR-06: Performance (Page Load Time) | User experience quality; improves adoption and satisfaction. 3-second target is acceptable; aggressive optimization can be Phase 2 refinement. | 1–2 weeks | Phase 1 (foundational) |
| | NFR-08: Data Backup | Compliance and operational resilience requirement. | 1 week | Phase 1 (foundational) |
| | NFR-09: Disaster Recovery | Operational resilience; 4-hour RTO ensures acceptable downtime. | 2–3 weeks | Phase 1 (foundational) |
| **Could Have** | Advanced Reporting & Analytics | Desirable for understanding application trends and decision patterns, but not essential for MVP operation. | 3–4 weeks | Phase 2b (later priority) |
| | System Integration with Legacy Finance System | Important for future operational efficiency (automated benefit payments) but not essential for initial service launch. Current workaround is manual transfer by staff. | 4–6 weeks | Phase 3 |
| | Advanced Citizen Portal Features (e.g., appeal process, follow-up applications) | Enhances citizen experience but not essential for MVP. Can be addressed as citizen demands emerge. | 2–3 weeks | Phase 2b |
| **Won't Have (Deferred)** | Real-Time Dashboard Analytics for Management | Senior management requested but does not impact citizen service delivery or operational efficiency. Valuable as future analytics module but not MVP scope. | — | Phase 3 (strategic initiative) |
| | Mobile-Native Application | Requested by some citizens but web-responsive design addresses most mobile use cases. Native app development can be reconsidered post-launch based on usage analytics. | — | Post-launch evaluation |

### Prioritisation Evidence and Justification

The "Must Have" requirements derive directly from the business case objectives outlined in Section A: enabling digital submission of applications, reducing processing time, improving transparency, and ensuring security and compliance. These requirements are non-negotiable for achieving the stated ROI and business benefits. Removing any "Must Have" requirement would compromise the business case.

The "Should Have" requirements significantly improve operational efficiency and citizen experience but are not absolute prerequisites for MVP operation. For instance, the system could operate without FR-03 (document upload) by requiring citizens to email supporting documents separately; however, this would necessitate manual handling and reintroduce inefficiency. By prioritising document upload as "Should Have" but high-priority within that category, the requirement is likely to be included in Phase 2a (months 9–11), shortly after MVP launch.

The "Could Have" requirements are valuable but can be deferred to subsequent project phases without undermining the core business case. For instance, advanced analytics would support management decision-making, but the absence of analytics in the MVP does not prevent the system from processing applications and delivering benefits.

The "Won't Have" requirements are explicitly deferred to later phases or strategic reviews. This categorisation provides clear communication to stakeholders: these requirements are not forgotten or rejected but are explicitly planned for subsequent phases once the MVP has been validated and initial benefits have been realised.

---

# SECTION C: LEGAL, SOCIAL, ETHICAL, AND PROFESSIONAL CONSIDERATIONS

## C1: Data Protection, Data Controllers, and Business Operational Impact

### Role and Responsibilities of the Data Controller

Under the UK General Data Protection Regulation (UK GDPR) and the Data Protection Act 2018, the "Data Controller" is defined as the entity that determines the purposes and means of processing personal data (UK Parliament, 2018, s. 4). In the context of this project, the public sector organisation is the Data Controller. As outlined by the Information Commissioner's Office (ICO, 2023), the Data Controller bears the highest level of accountability for compliant data handling and bears legal liability for data breaches or non-compliance.

The Data Controller's responsibilities are comprehensive and have significant operational implications:

1. **Lawful Basis Determination:** The organisation must establish a lawful basis for processing citizen data (e.g., performance of a public task, legal obligation). For benefit application processing, the lawful basis is typically "performance of a public task" (UK GDPR Article 6(1)(e), UK Parliament, 2018). This must be documented and communicated to citizens at the point of data collection.

2. **Privacy Impact Assessment:** Before implementing the digital system, the organisation must conduct a Data Protection Impact Assessment (DPIA) identifying privacy risks inherent in the system design and implementing controls to mitigate those risks (ICO, 2023). For instance, a DPIA might identify the risk that administrative staff access citizen financial information without a valid operational need. A control would be to implement role-based access restricting visibility to information necessary for the staff member's assigned role.

3. **Consent and Rights Management:** Citizens have rights under GDPR including the right to access their data, the right to rectification of inaccurate data, the right to erasure ("right to be forgotten") under specified circumstances, and the right to data portability (UK Parliament, 2018, ss. 45-48). The digital system must implement features enabling citizens to exercise these rights. For instance, the application dashboard (FR-04) should enable citizens to access their stored data; the system must provide a mechanism for citizens to request correction of inaccurate information.

4. **Data Minimisation:** The organisation must collect and process only the minimum personal data necessary to achieve the stated purpose (benefit application processing) (UK Parliament, 2018, s. 5). For instance, if the application requires verification of citizenship status, the system should collect citizenship information but not unrelated personal information such as health status or employment history. Violation of data minimisation principles increases privacy risk and regulatory liability.

5. **International Data Transfers:** If citizen data is processed outside the UK/EEA (e.g., cloud infrastructure hosted outside these regions), the organisation must ensure appropriate safeguards are in place. Current UK law restricts transfers to countries with "adequate" data protection (e.g., EU/EEA, certain third countries with adequacy decisions) (UK Parliament, 2018, Chapter 5). This impacts infrastructure vendor selection and cloud service location decisions.

### Operational Impact on Business Processes

The Data Controller responsibilities have direct implications for system design and operational processes:

**Impact on System Architecture:** The compliance requirements necessitate technical controls such as encryption, access logging, and audit trails. These controls increase development complexity and infrastructure costs. For instance, implementing audit trail capture (NFR-10) requires logging of every system action, which increases database storage requirements and may impact performance if not implemented efficiently.

**Impact on Staffing and Training:** Administrative staff handling citizen data must receive training on GDPR principles, data handling obligations, and organisational policies. Staff must understand that they can only access citizen data when performing authorised functions, and they cannot access data out of curiosity or share data with unauthorised parties. Non-compliance by individual staff members can expose the organisation to liability. Therefore, staff training and oversight become ongoing operational requirements.

**Impact on Incident Response:** A data breach or data handling violation must be reported to the ICO within 72 hours if a risk to citizen rights is identified (UK Parliament, 2018, s. 67). The organisation must establish incident response procedures including breach detection, investigation, notification, and remediation. These procedures must be documented and tested regularly. The financial and reputational cost of a data breach can be substantial: ICO fines can reach 4% of global turnover or €20 million for large organisations (ICO, 2023); the 2020 TikTok GDPR fines exceeded £11 million, and the organisation faced substantial reputational damage. Organisations must prepare for this potential liability.

**Impact on Vendor Management:** If the organisation engages external service providers (e.g., cloud hosting providers, software development vendors), these providers are classified as "Data Processors." The organisation must execute Data Processing Addenda with each Processor defining data handling obligations and allocating responsibility for compliance. Failure to implement appropriate contracts with Processors can expose the organisation to liability for the Processor's non-compliance.

### Practical LSEPI Examples and Business Implications

**Legal Impact Example 1: Data Breach Scenario**
Scenario: A software vulnerability in the administrative interface allows an administrative staff member to view citizen financial information without authorisation. This vulnerability is discovered after the breach has occurred and approximately 5,000 citizen financial records have been accessed.

Legal implications: (a) The organisation may be liable for fines under GDPR (up to £17.5 million or 4% of turnover, whichever is greater). (b) The organisation must notify affected citizens and the ICO within 72 hours. (c) Citizens may initiate civil claims against the organisation for damages resulting from the breach (emotional distress, identity theft costs, etc.). (d) The incident may trigger regulatory investigations by the ICO and potentially criminal liability if the breach is determined to result from gross negligence.

Mitigation and recommended action: (a) Implement role-based access control (FR-08) with granular permissions restricting staff access to information necessary for assigned roles. (b) Implement audit logging (NFR-10) enabling detection of unusual access patterns (e.g., staff member accessing records outside their normal geographic region). (c) Implement automated alerting when citizens' financial information is accessed, with alerts reviewed by compliance personnel to identify anomalous patterns. (d) Conduct regular security testing (penetration testing, code review) to identify and remediate vulnerabilities before they are exploited.

**Legal Impact Example 2: Data Retention and Erasure Rights**
Scenario: A citizen submits an application, withdraws it, and subsequently requests deletion of their personal data under the GDPR right to erasure. The organisation's system retains the application data in backup files indefinitely.

Legal implications: (a) The organisation is violating the citizen's legal right to erasure. (b) The citizen may file a complaint with the ICO. (c) The organisation may be liable for fines and directed to implement remediation (permanent deletion of the citizen's data).

Mitigation and recommended action: (a) Implement data retention policies specifying retention periods for each category of personal data (e.g., withdrawn applications retained for 1 year for audit purposes, then deleted; approved applications retained for 7 years per statutory record-keeping requirements). (b) Design the system to support automated deletion of data after the retention period expires. (c) Implement a citizen-facing mechanism enabling citizens to request erasure of their data, with the system verifying eligibility for erasure and executing deletion (e.g., if no statutory retention obligation applies).

**Social Impact Example 1: Digital Divide and Service Accessibility**
Scenario: The organisation implements a digital-only application system and retires the paper-based application channel. Analysis post-launch reveals that elderly citizens (65+) have disproportionately low application rates and shift to alternative services, effectively excluding them from accessing benefits they are entitled to.

Social implications: (a) The organisation has inadvertently increased social inequality by creating barriers to access for citizens lacking digital literacy or reliable internet access (UK Parliament, 2010, s. 149). (b) Elderly citizens may face financial hardship due to inability to access services. (c) The organisation faces reputational damage and potential complaints to elected representatives and regulatory bodies.

Mitigation and recommended action: (a) During requirements gathering (Section B1), explicitly interview elderly citizens and citizens with limited digital literacy to understand their preferences and accessibility needs. (b) Implement accessibility features (NFR-04 and NFR-05) ensuring the digital service is usable by citizens with visual impairments, physical impairments, or low digital literacy, in accordance with WCAG 2.1 Level AA standards (Government Digital Service, 2022). (c) Maintain alternative access channels (telephone support, in-person assistance) for citizens unable or unwilling to use the digital service. (d) Conduct post-launch monitoring of application rates by demographic cohort to identify whether digital-only implementation has inadvertently excluded certain populations. If disproportionate exclusion is identified, expand alternative channels to restore equitable access.

**Social Impact Example 2: Employment and Staff Morale**
Scenario: Implementation of the digital system enables automation of routine application processing tasks, reducing the required administrative staff from 2.5 FTE to 1.0 FTE (as outlined in Section A4). Staff learn of the redundancy plan and morale deteriorates. Junior staff members submit resignation notices.

Social implications: (a) Organisational culture and staff morale are negatively impacted. (b) Institutional knowledge is lost as experienced staff leave. (c) The organisation faces increased recruitment and training costs to backfill departures.

Mitigation and recommended action: (a) Develop a comprehensive change management and staff transition plan at project initiation (not post-implementation). (b) Communicate clearly with staff about how the digital system will change their roles: automation of routine, low-value tasks enables reallocation of staff to higher-value work such as exception handling, dispute resolution, and citizen outreach. (c) Provide retraining and upskilling opportunities enabling staff to transition into new roles rather than redundancy. (d) Consult with employee representatives and trade unions to address concerns and develop mutually acceptable transition plans. (e) Monitor staff morale through regular surveys and address concerns proactively.

**Ethical Impact Example 1: Data Monetisation**
Scenario: Senior management proposes selling anonymised citizen application data to external market research firms to generate revenue funding ongoing system support. Application data (e.g., age, geographic region, type of benefit applied for) is aggregated and anonymised before sale.

Ethical implications: (a) Citizens provided their personal data to apply for benefits, not to support commercial market research. Even though data is anonymised, the use extends beyond the citizen's reasonable expectations. (b) Monetising citizens' data without explicit consent raises ethical questions about commodifying personal information, particularly information related to individuals in disadvantaged circumstances (benefit applicants). (c) Citizens may feel exploited if they become aware that their data is being sold commercially.

Mitigation and recommended action: (a) Do not pursue data monetisation without explicit, informed consent. When citizens submit an application, provide transparent information about how their data will be used and offer an opt-in mechanism for participation in secondary uses such as research or analytics. (b) Even with consent, consider ethical constraints: is it appropriate to profit from data provided by individuals in disadvantaged circumstances? Alternative funding approaches (government grant, budget allocation) may be more ethically defensible. (c) Prioritise citizen privacy and trust over revenue generation, recognising that reputational damage from a data monetisation scandal could exceed any revenue gained.

**Ethical Impact Example 2: Algorithmic Bias in Automated Decision-Making**
Scenario: The organisation implements an automated system to pre-approve or pre-reject applications based on algorithmic scoring (e.g., if an applicant meets certain criteria, the application is automatically approved without human review). Analysis post-implementation reveals that the algorithm systematically rejects applications from certain demographic groups at higher rates than others, resulting in discriminatory outcomes despite the absence of explicit demographic data in the algorithm's inputs.

Ethical and legal implications: (a) The system may be engaging in unlawful discrimination under the Equality Act 2010 and Human Rights Act 1998. (b) Citizens affected by discriminatory decisions may have grounds for complaint or legal action. (c) The organisation faces regulatory investigation by the Equality and Human Rights Commission and reputational damage.

Mitigation and recommended action: (a) If automated decision-making is implemented, design the system to include a human review step for all applications, not just edge cases. Automated processes can support the decision-maker by flagging relevant information or proposing a decision, but humans must make the final decision and be able to explain the rationale. (b) Conduct algorithmic bias testing before deployment, examining whether the algorithm's outcomes vary by demographic group. (c) Implement ongoing monitoring post-deployment to detect discriminatory patterns. If discrimination is detected, investigate root causes and remediate. (d) Provide transparency to citizens about how their applications are evaluated, enabling them to contest decisions they believe are unfair.

**Professional Impact Example: Project Team Integrity**
Scenario: During the project planning phase, the development team identifies that the agreed project timeline (18 months) is unrealistic given the scope of work (MVP development, security hardening, user testing, and deployment) and the team capacity (4 developers). The team estimates that comprehensive, quality development requires 22 months. However, senior management has publicly committed to a 18-month timeline and is reluctant to extend the timeline or expand the budget. The project manager faces pressure to commit to the unrealistic timeline without raising concerns.

Professional implications: (a) If the project manager commits to the unrealistic timeline without professional objection, the team will likely face schedule pressure leading to corners being cut (inadequate testing, insufficient security hardening, poor documentation). (b) Post-deployment, the system will be unstable, and critical issues will be discovered in production. (c) The organisation will blame the project team for failures despite the root cause being unrealistic planning. (d) The project team's professional reputation is damaged and the organisation's confidence in IT delivery is undermined.

Mitigation and recommended action: (a) The project manager has a professional obligation to honestly communicate the realistic timeline required for quality delivery. This communication should be evidence-based, including documented effort estimates, team capacity analysis, and reference to industry standards for similar projects. (b) Present senior management with trade-off options: (i) maintain the 18-month timeline with reduced scope (deliver MVP without non-essential "Should Have" features); (ii) expand to 22 months with full MVP scope; or (iii) expand team capacity if budget permits. (c) Document the timeline discussion and decision in meeting minutes, ensuring that decision-makers are aware of the professional recommendations and the risks of the chosen approach. (d) If management chooses to proceed with an unrealistic timeline despite professional advice, document the recommendation and the organisation's decision, protecting the project team's professional standing in case failures occur.

## C2: Professional Bodies and BCS Code of Conduct

Professional bodies such as the British Computer Society (BCS) establish codes of conduct defining ethical standards and professional obligations for members. The BCS Code of Conduct comprises four core principles guiding decision-making and conduct (The Chartered Institute for IT, 2022):

### 1. Public Interest

The first principle is that IT professionals must safeguard public health, privacy, safety, and welfare. This principle is paramount; when conflicts arise between the public interest and other pressures (client preferences, project deadlines, commercial interests), the public interest must take precedence (The Chartered Institute for IT, 2022).

**Application to this project:** The public interest in this project includes citizens' privacy, data security, and fair treatment in benefit application processing.

**Detailed Example 1: Security Vulnerability Discovery**
A developer testing the administrative interface discovers a critical security vulnerability: the role-based access control (FR-08) is not properly enforced, allowing administrative staff to view all citizens' applications regardless of their assigned queue. The vulnerability could enable widespread privacy breaches and fraud (staff members could approve applications for acquaintances without proper scrutiny).

Following the Public Interest principle, the developer must immediately escalate this vulnerability to the development team lead and security team. The appropriate action is to halt integration testing of the system, conduct a comprehensive security audit to identify the scope of the vulnerability and determine whether it has already been exploited, and implement remediation before resuming testing.

However, the project is currently 2 weeks behind schedule. Senior management is eager to proceed with testing to recover schedule time. There may be pressure to bypass the vulnerability disclosure, classify it as "low priority," defer it to Phase 2, or test without addressing it.

The professional obligation under the Public Interest principle is to refuse to continue with testing until the vulnerability is addressed. The developer should formally communicate the vulnerability, the risk to citizen privacy, and the recommendation to halt testing pending remediation. This communication should be documented and escalated to the project sponsor and steering committee if necessary, ensuring that decision-makers understand the risks and the professional recommendation.

The rationale is that proceeding with a known critical vulnerability violates the Public Interest principle and exposes the organisation to unacceptable privacy and security risks. Short-term schedule recovery is not worth the long-term reputational and financial damage from a preventable security breach.

**Detailed Example 2: Accessibility Compliance**
The project team completes development of the user interface (FR-02: form submission) and begins testing with administrative staff. Accessibility testing (NFR-04: WCAG compliance) is scheduled to begin in week 12 of the project. However, a schedule review reveals that the project is running behind plan, and accessibility testing will need to be compressed from 3 weeks to 1 week to maintain the overall project timeline.

The accessibility test reveals that the form interface fails several WCAG Level AA criteria: colour contrast is insufficient for citizens with low vision; form labels are not properly associated with input fields, making the form unusable by screen reader users; keyboard navigation is not fully supported, making the form inaccessible to users with mobility impairments.

Comprehensive remediation of accessibility failures will require 2–3 weeks of development effort, further compressing the schedule. There is pressure to deploy the form with accessibility failures and "fix in Phase 2" to maintain the overall timeline.

Following the Public Interest principle, accessibility compliance is not optional. The Public Sector Equality Act 2010 mandates that public services be accessible to citizens with disabilities (UK Parliament, 2010, s. 149). Citizens relying on assistive technology (screen readers, voice recognition, switch controls) should not be denied access to government services due to negligent design.

The professional obligation is to prioritise accessibility compliance in the MVP, even if it requires timeline extension or scope reduction (e.g., launch with a simplified form that is fully accessible, adding advanced form features in Phase 2). The decision should be escalated to the steering committee with clear explanation of legal obligations and the professional recommendation to prioritise accessibility.

### 2. Professional Competence and Integrity

The second principle is that IT professionals must undertake only work for which they are appropriately qualified and must maintain professional standards. This includes honesty about one's capabilities and limitations.

**Application to this project:** Team members must be qualified to perform their assigned work (developers with software development expertise, architects with system design expertise, security specialists with security expertise). Team members must honestly communicate when they lack the expertise for assigned work rather than attempting to "muddle through" and deliver substandard work.

**Detailed Example 1: Security Architecture**
The project requires implementation of secure authentication (NFR-02: government digital identity verification) and encryption of sensitive data (NFR-01: AES-256 encryption). These are complex security technologies requiring specialised knowledge. The development team consists of 4 developers with experience in standard application development but no prior experience with government digital identity systems or cryptographic implementation.

A professional approach is to acknowledge this knowledge gap and engage a security specialist or external consultant with government digital identity experience to design the authentication architecture and encryption approach. The additional cost and schedule impact of engaging external expertise is less expensive and risky than attempting to implement security controls without proper expertise, potentially resulting in vulnerabilities.

An unprofessional approach would be to assume that "security is just part of normal development" and proceed without specialist input, risking implementation of insecure authentication or weak encryption that appears secure but is actually vulnerable to attack.

**Detailed Example 2: Estimation Honesty**
During project planning, senior management asks the development team to estimate the effort required to implement the MVP (all "Must Have" requirements). The project manager is under pressure to provide an optimistic estimate to secure project approval and budget allocation. The development team, after detailed analysis, believes the realistic estimate is 18–20 months of work with 4 developers.

However, senior management has informally indicated that they expect the timeline to be 14–16 months. The project manager may face pressure to provide an estimate matching management's expectations, reducing the stated estimate to 16 months.

A professional approach is to provide an honest, evidence-based estimate of 18–20 months, with a breakdown of the effort required for each component and documented assumptions and risks. This estimate should be communicated to management with a clear explanation: "Delivering a secure, quality system that meets our requirements requires this timeline. Committing to a shorter timeline would require either scope reduction or expanded team capacity, or we accept elevated risk of schedule overruns and quality issues."

This honest communication enables management to make an informed decision about timeline, scope, and budget tradeoffs. It protects the project team's professional reputation by documenting that professionals provided realistic recommendations, and it protects the organisation by enabling informed decision-making rather than optimistic assumptions that later prove incorrect.

### 3. Duty to Relevant Authority

The third principle defines that IT professionals have obligations to their employers or clients and must respect their legitimate interests and authority, whilst avoiding conflicts of interest.

**Application to this project:** The project team's employers/management have legitimate interests in delivering the system on time, within budget, and with adequate quality. The team must respect these interests and work effectively toward project goals. However, the team must avoid conflicts of interest that could undermine these legitimate interests.

**Detailed Example 1: Vendor Selection and Conflict of Interest**
The project requires selection of a cloud hosting provider to host the digital application system. The project team evaluates three vendors:

- Vendor A: Established cloud provider with strong government sector experience, security certifications, and proven uptime track record. Cost: £50,000 annually.
- Vendor B: Newer cloud startup with competitive pricing. Cost: £30,000 annually. However, Vendor B is owned by the sister company of one of the development team's closest colleagues.
- Vendor C: Vendor C is a boutique provider with excellent customer support. Cost: £45,000 annually.

The team member with the family connection to Vendor B might feel inclined to recommend Vendor B based on the personal relationship and the cost savings, rather than on objective evaluation of security, reliability, and track record.

A professional approach is for the team member to declare the conflict of interest and recuse themselves from the vendor selection decision. The remaining team members should evaluate vendors on objective criteria: security certifications, uptime guarantees, government sector experience, customer references, and cost. The recommendation should be based on total cost of ownership and risk management rather than personal relationships.

In this case, Vendor A likely represents the lower-risk choice despite higher cost, given government sector track record and security certifications. The £20,000 annual premium for Vendor A is reasonable insurance against reliability and security risks.

**Detailed Example 2: Scope Creep and Vendor Pressure**
During the project, the infrastructure team discovers that the selected cloud infrastructure does not adequately support the required scalability (NFR-07: 500 concurrent users). The original vendor lacks experience with the required workload patterns and cannot provide adequate guidance.

A consultant recommends switching to a different cloud vendor with stronger technology fit. However, switching vendors mid-project would require re-architecting the application and potentially incur vendor termination penalties and switching costs totalling £30,000–£40,000.

The original vendor, aware of the performance issues, proposes a "solutions consulting" engagement (£15,000) to redesign the architecture optimally within their platform constraints. However, this engagement would create a conflict of interest: the vendor has a financial interest in retaining the account and may not provide objective advice about whether staying with their platform or switching is the optimal solution for the organisation.

A professional approach is to engage an independent infrastructure consultant to objectively evaluate the technical options and make a recommendation. The consultant can recommend staying with the current vendor (if the platform can be optimised), switching to a different vendor (if the performance benefits justify the switching costs), or a hybrid approach (e.g., switch core workloads to a different vendor whilst retaining non-critical functions with the original vendor). The recommendation should be based on technical fit and total cost of ownership, not on vendor commercial interests.

### 4. Duty to the Profession

The fourth principle is that IT professionals must uphold the reputation of the profession and act with integrity, supporting colleagues and promoting high standards within the industry.

**Application to this project:** Team members should mentor junior colleagues, share knowledge about best practices, and uphold professional standards. Team members should not take actions that would undermine professional reputation (e.g., shipping insecure code, misrepresenting system capabilities, failing to document decisions).

**Detailed Example 1: Knowledge Transfer and Mentoring**
The project includes two junior developers (< 2 years of experience) working on the secure authentication implementation. An experienced security architect is assigned to mentor them. The architect could follow a minimalist approach: define the security requirements and expect the junior developers to implement independently, providing feedback only on the final code.

A professional approach aligned with "Duty to the Profession" is to proactively mentor the junior developers: conduct architecture reviews explaining the rationale for security design choices, provide code reviews offering constructive feedback, pair programme on critical security components to transfer knowledge, and discuss common security vulnerabilities and how to avoid them. By investing in knowledge transfer, the architect raises the overall professional competence of the team and the junior developers grow their expertise.

This investment in mentoring supports the profession by developing the next generation of competent professionals. It also benefits the organisation long-term by building internal expertise rather than relying on external consultants for future security work.

**Detailed Example 2: Post-Deployment Support and Professional Integrity**
The system is deployed to production, and during the first week of operation, several production issues are discovered: a report functionality is producing incorrect results, administrative staff are unable to log in intermittently, and there are performance degradations during peak hours. The development team has already been partially demobilised post-launch to work on other projects.

There may be pressure to provide minimal support ("it's in production now; let operations handle it") to redirect team capacity to other work. However, a professional approach aligned with "Duty to the Profession" is to:

1. Prioritise production issue resolution. The system is new and expected to have teething issues. Promptly fixing issues demonstrates commitment to quality and customer satisfaction.
2. Investigate root causes rather than applying quick fixes. Understanding why issues occurred and implementing robust fixes prevents recurrence.
3. Maintain production support until the system stabilises (typically 4–6 weeks post-deployment).
4. Document lessons learned and share with the broader team: what went wrong, why, and what processes/practices would prevent recurrence. This knowledge transfer benefits future projects.

This professional approach protects the organisation's reputation with users, maintains quality standards, and contributes to the profession's overall reputation for delivering reliable systems.

---

# CONCLUSION AND IMPLEMENTATION RECOMMENDATIONS

## Summary of Analysis

This report has presented a comprehensive analysis of the proposed digital service delivery system for public sector applications, addressing strategic, technical, regulatory, and professional dimensions.

**Strategic Context (Section A):** The public sector organisation faces genuine operational inefficiencies in its current paper-based application processing system. Agile software development is an appropriate methodology for this context, providing flexibility to accommodate changing requirements whilst maintaining a disciplined approach to budget and schedule management. The financial analysis indicates a compelling business case with an estimated NPV of £420,000–£480,000 over a 5-year evaluation period and break-even achieved within 3.5–4 years. However, realisation of these benefits depends on effective change management, successful technology implementation, and sustained stakeholder engagement throughout the project lifecycle.

**Requirements Analysis (Section B):** A systematic requirements elicitation and review process yielded 23 distinct, validated requirements organised into functional and non-functional categories. The MoSCoW prioritisation framework identified 8 "Must Have" requirements comprising the MVP scope and an additional 9 "Should Have" requirements targeted for Phase 2a delivery. This prioritisation is grounded in risk analysis, stakeholder input, and business case alignment rather than subjective preference. The systematic review process filtered out requirements that were either inaccurate (unrealistic expectations) or out of scope, maintaining clear project boundaries.

**Compliance and Professional Considerations (Section C):** The project operates within multiple regulatory and professional frameworks. UK GDPR imposes stringent data protection obligations on the public sector organisation as the Data Controller. The Public Sector Equality Act 2010 mandates accessibility for citizens with disabilities. The BCS Code of Conduct guides professional decision-making, emphasising the Public Interest, professional competence, honest communication with stakeholders, and avoidance of conflicts of interest. Successful project delivery requires integration of these legal, ethical, and professional considerations throughout the development lifecycle, not as afterthoughts at project conclusion.

## Critical Success Factors

Successful delivery of this project depends on several critical factors:

1. **Executive Sponsorship:** The project requires committed support from senior management, including protection from organisational pressures that could undermine timeline realism or quality standards. Executive sponsors must authorise the steering committee structure, budget allocation, and resource commitment necessary for success.

2. **Stakeholder Engagement:** The project must sustain active engagement with citizens, administrative staff, and senior management throughout the 18-month development and implementation timeline. This engagement is not merely a "requirements gathering" activity at project initiation but an ongoing relationship maintained through sprint reviews, feedback sessions, and change communication.

3. **Change Management:** The transition from manual to digital processes will disrupt existing workflows and require staff retraining. Adequate change management investment—including clear communication about how roles will change, retraining and upskilling opportunities, and support during the transition—is essential to achieve user adoption and realise operational benefits.

4. **Technical Expertise:** The project requires a development team with software development expertise, security architecture expertise (for authentication and encryption implementation), and infrastructure expertise (for cloud platform design and deployment). Attempting to deliver a government-grade digital system with insufficient technical expertise is likely to result in quality issues, security vulnerabilities, and schedule delays.

5. **Quality and Security Focus:** Government systems are high-profile and attract regulatory scrutiny. The development process must include rigorous testing (functional testing, security testing, performance testing, accessibility testing) and code review practices. Security should be integrated throughout the development lifecycle, not bolted on at the end.

6. **Risk Management:** The project should establish a risk register identifying key risks (schedule, budget, technical, regulatory, stakeholder), assessing their impact and likelihood, and defining mitigation strategies. Regular risk reviews (e.g., monthly) enable proactive management of emerging risks before they escalate into crises.

## Recommended Next Steps

1. **Secure Executive Approval:** Present this analysis to the steering committee and obtain formal approval for the project objectives, scope, timeline, and budget. Document the business case (Section A) as the foundation for organisational commitment.

2. **Establish Project Governance:** Define the project governance structure including steering committee membership, decision-making authorities, reporting cadence, and escalation paths. Establish a Project Management Office (PMO) to oversee the project and provide governance support.

3. **Conduct Detailed Planning:** Develop detailed project plans including: (a) Requirements breakdown and dependency analysis; (b) Development roadmap mapping requirements to sprints and phases; (c) Risk register and mitigation plans; (d) Change management plan; (e) Communications plan for stakeholders; (f) Resource plan identifying required team members and acquisition timelines.

4. **Establish Development Infrastructure:** Set up the technical infrastructure required for development: version control systems, continuous integration pipelines, automated testing frameworks, security scanning tools, and documentation systems. This infrastructure should be established before development work begins, enabling consistent practices from project initiation.

5. **Conduct Training and Coaching:** Provide Agile methodology training for the development team and executive stakeholders. If the organisation has limited experience with Agile practices, engage an external Agile coach to provide guidance during the first 2–3 sprints, helping the team establish sustainable practices.

6. **Initiate Sprint 1 Development:** Begin development with Sprint 1, focusing on the core "Must Have" requirements. Establish a regular sprint review and retrospective cadence (e.g., every 2 weeks) to gather feedback, demonstrate progress, and continuously improve team processes.

## Conclusion

The digital service delivery system represents a strategic opportunity for the organisation to modernise its citizen-facing service, improve operational efficiency, and position itself as a forward-thinking government agency. However, success is not guaranteed and depends critically on disciplined project management, sustained stakeholder engagement, technical expertise, and unwavering commitment to quality and compliance standards.

This analysis has provided the strategic, technical, and regulatory foundation for informed decision-making. The business case is compelling; the requirements are well-defined and prioritised; the risks are understood and manageable. The organisation now faces a binary decision: commit to the project with the understanding that it represents a meaningful investment in time, resources, and organisational change, or defer the initiative to a future date when organisational capacity may be more available.

If the organisation chooses to proceed, the recommendations outlined in this report should guide project planning, team structure, governance, and execution. Adherence to these principles and practices significantly increases the likelihood of delivering a system that meets stakeholder needs, achieves the business case objectives, and delivers sustainable operational benefits to the organisation and citizens it serves.

---

# REFERENCES

Boehm, B. and Turner, R. (2004) Balancing agility and discipline: A guide for the perplexed. Boston: Addison-Wesley.

Government Digital Service (2022) Service design manual: Accessibility. [online] Available at: https://www.gov.uk/service-manual/helping-people-to-use-your-service/making-your-service-accessible-an-introduction (Accessed: 21 April 2026).

Information Commissioner's Office (2023) Guide to the UK General Data Protection Regulation (UK GDPR). [online] Available at: https://ico.org.uk/for-organisations/guide-to-dataprotection/ (Accessed: 21 April 2026).

Sommerville, I. (2015) Software engineering. 10th edn. Pearson.

The Chartered Institute for IT (2022) Code of conduct. [online] Available at: https://www.bcs.org/membership-and-registrations/become-a-member/bcs-code-ofconduct/ (Accessed: 21 April 2026).

UK Parliament (2010) Equality Act 2010. [online] Available at: https://www.legislation.gov.uk/ukpga/2010/15/contents (Accessed: 21 April 2026).

UK Parliament (2018) Data Protection Act 2018. [online] Available at: https://www.legislation.gov.uk/ukpga/2018/12/contents/enacted (Accessed: 21 April 2026).

United Kingdom Electronic Accessibility Regulations (2018) [online] Available at: https://www.legislation.gov.uk/uksi/2018/952/regulation/4 (Accessed: 21 April 2026).
