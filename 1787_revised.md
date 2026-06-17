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

Agile is particularly well-suited to this context: it operates through iterative 2–4 week sprints allowing functional software delivery at regular intervals rather than a single 18-month "big bang" release; it facilitates continuous stakeholder engagement ensuring delivered systems reflect actual user needs; and it accommodates requirement changes naturally (Sommerville, 2015, p. 52; Boehm and Turner, 2004, p. 31).

**Key Advantages:** (1) Organisational adaptability—legislative changes can be incorporated in the next sprint without comprehensive replanning; (2) Stakeholder alignment—bi-weekly sprint reviews reduce risk of delivering misaligned systems; (3) Risk mitigation through early identification of technical impediments; (4) Team learning through iterative retrospectives and accelerating velocity.

**Key Challenges and Mitigation:** (1) Public sector requires budgetary certainty; mitigated by establishing fixed MVP scope with "Should Have" and "Could Have" features deferred to Phase 2–3; (2) Senior management expects traditional governance milestones; mitigated by establishing steering committee reviewing sprint outcomes and product metrics every 4 weeks; (3) Government requires compliance documentation; mitigated by maintaining decision logs, architecture diagrams, requirements traceability matrix, and deployment runbooks throughout development (UK Parliament, 2010).

## A4: Financial Considerations and Business Impact

Current operational costs (£112,500 annually) include staff (2.5 FTE at £87,500), document storage (£15,000), and overhead (£10,000). The digital system requires development investment of £450,000–£550,000 with ongoing operational costs of £40,000–£50,000 annually.

Expected annual benefits total approximately £164,500: staff cost reduction to 1.0 FTE (£52,500 savings), storage elimination (£12,000), processing efficiency gains from 28-day to 7-day cycle enabling 15% additional applications (£80,000 revenue), and reduced support inquiries (£20,000).

Break-even occurs within 3.5–4 years. Net Present Value over 5 years: £420,000–£480,000; Internal Rate of Return: 22–28% (exceeding public sector hurdle of 5–7%), indicating a strong business case. Key risks include change management effectiveness, citizen adoption (particularly elderly/disadvantaged populations), legislative changes, and technical failures.

## A5: Key Stakeholder Impacts

**Operations:** Digital system introduces automated intake, standardised workflow routing, and status-change notifications. Transition requires 4–6 weeks staff retraining with potential 30–40% efficiency gains post-transition.

**Compliance:** System must meet UK GDPR, Public Sector Equality Act 2010, and sector-specific regulations. Data protection by design, privacy impact assessments, accessibility testing, and audit trails are essential; non-compliance risks significant penalties.

**Strategic Position:** Digital service delivery is a key government modernisation indicator. Successful implementation enhances organisational reputation and partnership opportunities; failure undermines credibility.

Digital service delivery is increasingly expected by citizens and is a key performance indicator in government modernisation assessments. The successful implementation of this platform positions the organisation as a forward-thinking public sector entity, enhancing its reputation and potentially attracting partnership opportunities with other government bodies facing similar challenges. Conversely, failure or significant delays in implementation could undermine the organisation's credibility and limit future digital initiatives.

### Key Stakeholders and Their Concerns

**Citizens (Applicants):** Primary concern is ease of use, assurance of data security and privacy, and visibility of application progress. Older citizens and those with limited digital literacy may require alternative channels (telephone support, in-person assistance) to access the service equitably.

**Administrative Staff:** Concerns include job security (will the system eliminate my position?), requirement for new technical skills, and potential for increased monitoring/performance metrics through system-generated data. Mitigation requires clear communication that automation is designed to eliminate routine, low-value tasks whilst creating opportunities for higher-value work such as exception handling and complex decision-making.

**Senior Management:** Concerns centre on costs, timeline certainty, risk mitigation, and visibility into project progress. Clear financial analysis (as provided in Section A4), transparent governance structures, and regular reporting of key performance indicators are essential to maintain executive support.

**External Partners:** If the system integrates with partner organisations' systems (e.g., verification services, payment systems), partners will have concerns regarding data sharing agreements, API stability and support, and change notification procedures.

## A6: Implementation Approach

The project will be delivered over 18 months across three phases: (1) Months 1–2 establish governance (steering committee, feasibility study, change management plan, Agile governance model); (2) Months 3–9 develop the MVP including all "Must Have" requirements and foundational non-functional requirements (security, uptime, backup); (3) Months 9–15 add "Should Have" features (document upload, dashboards, communication, search); (4) Months 15–18 conduct parallel system testing and transition to full production.

# SECTION B: REQUIREMENTS ANALYSIS, REVIEW, AND PRIORITISATION

## B1: Requirements Analysis

A systematic requirements elicitation process involving staff interviews (n=8), citizen focus groups (n=12), executive interviews (n=3), and document analysis identified 42 potential requirements. After consolidating duplicates, identifying conflicts, and validating scope boundaries with stakeholders, 23 distinct requirements were retained.

**Functional Requirements (8):** FR-01: User authentication; FR-02: Form submission; FR-03: Document upload; FR-04: Application dashboard; FR-05: Administrative review interface; FR-06: Automated communication; FR-07: Search and filtering; FR-08: Role-based access control.

**Non-Functional Requirements (10):** NFR-01: AES-256 encryption; NFR-02: Government identity verification; NFR-03: 99% uptime; NFR-04: WCAG 2.1 Level AA accessibility; NFR-05: Multilingual support; NFR-06: 3-second page load; NFR-07: 500 concurrent user scalability; NFR-08: 24-hour backups (7-year retention); NFR-09: Disaster recovery (4-hour RTO); NFR-10: Immutable audit trail.

## B2: Inaccurate Requirements Filtered Out

Five problematic statements were identified and excluded: (1) "System must never crash" (unrealistic; specified 99% uptime instead); (2) "Interface must look modern and cool" (subjective; replaced with WCAG compliance); (3) "Staff take too long to find files" (problem statement; justified FR-07); (4) "System should handle 10,000 concurrent users" (unrealistic; specified 500); (5) "System must integrate with all legacy systems" (out of scope for MVP; deferred to Phase 2).

## B3: MoSCoW Prioritisation and Rationale

**Must Have (8 requirements):** FR-01, FR-02, FR-05, FR-08, NFR-01, NFR-02, NFR-04, NFR-10. Essential for MVP and directly support business case objectives.

**Should Have (9 requirements):** FR-03, FR-04, FR-06, FR-07, NFR-03, NFR-05, NFR-06, NFR-08, NFR-09. Improve efficiency and citizen experience; high-priority but deliverable in Phase 2a if necessary.

**Could Have:** Advanced reporting, legacy system integration, advanced citizen portal features (Phase 2b/3).

**Won't Have (deferred):** Real-time management analytics, mobile-native application (post-launch evaluation).

Prioritisation methodology: Risk analysis (business impact × probability of failure), Pareto analysis (80/20 principle), dependency mapping, and stakeholder input. The 8 "Must Have" requirements are non-negotiable for achieving project ROI and business case objectives. Removal of any Would compromise value delivery.

---

# SECTION C: LEGAL, SOCIAL, ETHICAL, AND PROFESSIONAL CONSIDERATIONS

## C1: Data Protection and Operational Impact

Under the UK GDPR and Data Protection Act 2018, the organisation is the Data Controller determining purposes and means of personal data processing (UK Parliament, 2018, s. 4). The Data Controller bears accountability for compliant data handling and liability for breaches (ICO, 2023).

**Data Controller Responsibilities:** (1) Establish lawful basis for processing and communicate to citizens; (2) Conduct Data Protection Impact Assessments identifying privacy risks; (3) Implement citizen rights mechanisms (access, rectification, erasure, data portability); (4) Adhere to data minimisation principles; (5) Ensure secure international data transfers if applicable (UK Parliament, 2018).

**Operational Impact:** Compliance necessitates technical controls (encryption, access logging, audit trails) increasing development complexity and cost. Staff must understand GDPR principles; non-compliance exposes organisations to liability. Data breaches must be reported to ICO within 72 hours (UK Parliament, 2018, s. 67); ICO fines reach 4% of global turnover or €20 million. External service providers require Data Processing Addenda defining obligations and responsibility allocation.

**Practical Examples:**

*Legal—Data Breach:* Unauthorised role-based access control (FR-08) vulnerability exposing 5,000 citizen financial records results in GDPR fines (up to £17.5M or 4% turnover), mandatory citizen and ICO notification within 72 hours, potential civil claims, and criminal liability. Mitigation: granular access control, audit logging for unusual patterns, automated alerting, regular security testing.

*Social—Digital Divide:* Digital-only implementation excludes elderly citizens (65+) and digitally illiterate populations, increasing social inequality (UK Parliament, 2010, s. 149). Mitigation: gather accessibility requirements from marginalised populations, implement WCAG 2.1 Level AA, maintain alternative channels (telephone, in-person), monitor demographic application rates.

*Ethical—Algorithmic Bias:* Automated decision-making may systematically discriminate against demographic groups (Equality Act 2010, Human Rights Act 1998). Professional obligation: include human review steps, conduct algorithmic bias testing pre-deployment, monitor for discriminatory patterns, provide transparency to citizens about evaluation criteria.

*Professional—Timeline Integrity:* Communicate realistic timelines based on evidence (effort estimates, team capacity, industry standards) rather than optimistic assumptions. Present trade-off options enabling informed decision-making. Document discussions protecting team reputation if failures occur.

## C2: Professional Bodies and BCS Code of Conduct

The BCS Code of Conduct comprises four principles guiding IT professional decision-making (The Chartered Institute for IT, 2022):

**1. Public Interest:** IT professionals must safeguard public health, privacy, safety, and welfare; public interest takes precedence over deadlines or commercial pressures (The Chartered Institute for IT, 2022). *Application:* Security vulnerabilities must be remediated immediately, even if behind schedule; accessibility compliance is non-negotiable.

**2. Professional Competence and Integrity:** Undertake only work for which qualified; communicate limitations honestly (The Chartered Institute for IT, 2022). *Application:* Engage security specialists for complex implementations; project managers must provide evidence-based estimates; resist pressure for optimistic timelines.

**3. Duty to Relevant Authority:** Respect employers' legitimate interests whilst avoiding conflicts of interest (The Chartered Institute for IT, 2022). *Application:* Base vendor selection on objective criteria (security certifications, uptime guarantees, cost); use independent consultants to evaluate conflicted technical decisions.

**4. Duty to the Profession:** Uphold professional reputation through integrity, mentoring, and quality commitment (The Chartered Institute for IT, 2022). *Application:* Mentor junior colleagues on security and best practices; prioritise production issues for investigation; document lessons learned to improve future projects; protect organisational reputation through quality commitment.

---

# CONCLUSION AND IMPLEMENTATION RECOMMENDATIONS

# CONCLUSION AND IMPLEMENTATION RECOMMENDATIONS

The digital service delivery system represents a strategic opportunity to modernise citizen-facing services, improve operational efficiency, and enhance the organisation's reputation as a forward-thinking government agency. Success depends critically on disciplined project management, sustained stakeholder engagement, technical expertise, and commitment to quality and compliance standards.

**Critical Success Factors:** (1) Executive sponsorship protecting the project from organisational pressures undermining timelines or quality; (2) Stakeholder engagement throughout the 18-month lifecycle; (3) Change management investment for staff transition; (4) Technical expertise in software development, security, and infrastructure; (5) Quality and security focus throughout development; (6) Proactive risk management.

**Immediate Next Steps:** (1) Secure executive approval for project objectives, scope, timeline, and budget; (2) Establish project governance including steering committee and PMO; (3) Develop detailed project plans; (4) Establish development infrastructure; (5) Provide Agile training for teams and stakeholders; (6) Initiate Sprint 1 development focusing on "Must Have" requirements.

The business case is compelling (NPV £420–480K, IRR 22–28%, payback 3.5–4 years); requirements are well-defined and prioritised; risks are understood and manageable. Successful delivery will provide sustainable operational benefits to the organisation and improved service quality for citizens.

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
