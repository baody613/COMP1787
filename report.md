# COMP1787 Requirements Management Coursework Report

**Participant ID:** [Nhập ID]
**Student ID:** [Nhập ID]

## Section A: Public Sector Projects Challenges and the Advantages of Agile

**Management Summary on Agile Methodology Completeness**
Public sector projects have historically struggled with high failure rates, often due to their reliance on traditional, rigid Waterfall methodologies. When developing systems for government or public services, requirements tend to change frequently due to new legislation or shifting public needs. Based on the case study provided, adopting an Agile-based approach would be highly appropriate for this development environment. Unlike linear models, Agile allows development teams to work in iterative cycles or 'sprints', delivering small, workable increments of the software securely and consistently. This is particularly crucial for public sector organisations that need to demonstrate value to taxpayers early on, rather than waiting years for a final product that might already be outdated upon release (Sommerville, 2015).

**Advantages and Drawbacks with Case Study Context**
There are several clear advantages to using Agile for this project. The most significant benefit is adaptability. For instance, in our scenario, if the government suddenly changes the policy regarding [thay bằng chi tiết trong đề bài - ví dụ: healthcare eligibility], an Agile team can easily pivot and include this new business rule in the next sprint. Furthermore, Agile actively involves stakeholders throughout the development process, ensuring that the final system actually meets the users' working needs rather than just ticking boxes on an initial specification sheet.

However, Agile methods do have notable drawbacks which must be managed. One major concern in the public sector is the lack of exhaustive upfront documentation. Government bodies usually require strict auditing trails and predictable budgetary forecasts before approving funds. Agile’s flexible scope can sometimes lead to 'scope creep', making it difficult to define the exact final cost of the project at the very beginning (Boehm and Turner, 2004). Moreover, the case study highlights a culture where senior management expects fixed deadlines; transitioning them to an Agile mindset where features are prioritized over fixed dates could cause initial friction and misunderstandings between the development team and the board.

## Section B: High-Level Requirements Analysis and MoSCoW Prioritisation

### B1: High-Level Functional Requirements
After analysing the situation described in the case study, the system will need several core functionalities to operate effectively. Below are eight high-level functional requirements outlined in a structured format:

| Req ID | Requirement Name | Description | Justification |
|:---|:---|:---|:---|
| **FR-01** | User Registration & Auth | The system must allow users to create an account and log in securely. | It is vital to verify the identity of the public users to prevent fraud and protect sensitive user profiles. |
| **FR-02** | Form Submission | Users must be able to fill out and submit their application forms digitally. | This addresses the key business problem of moving away from the slow, manual paper-based processes mentioned in the case. |
| **FR-03** | Document Upload | The application must allow users to upload supporting evidence (like PDFs or ID images). | Without this, administrators cannot verify the claims made in the digital forms, stalling the process. |
| **FR-04** | Application Dashboard | Users must be provided with a dashboard overviewing their current submissions and statuses. | This empowers the user to self-serve and significantly reduces the number of phone calls made to the support center. |
| **FR-05** | Admin Review Interface | Staff members must have access to a portal where they can read, approve, or reject submissions. | The core workflow of the organisation relies on staff processing these requests efficiently. |
| **FR-06** | Automated Communication| The system must automatically send an email or SMS confirmation when an application status changes. | Proactive communication keeps the public informed and builds trust in the new digital service. |
| **FR-07** | Search & Filter Tools | Administrators must be able to search for specific users by ID or name within the database. | Staff need to quickly locate records to handle physical inquiries or internal audits. |
| **FR-08** | Role-Based Access Control| The system must differentiate access rights between basic users, standard staff, and system administrators. | Not all staff should have the right to delete records or alter system configurations due to security risks. |

### B2: Non-Functional Requirements & Inaccurate Requirements

**Five Non-Functional Requirements (NFRs):**
To ensure the system is robust, it must meet the following non-functional constraints:

| NFR ID | Category | Requirement Description |
|:---|:---|:---|
| **NFR-01** | Security | All personally identifiable information must be encrypted in the database to comply with legal standards (AES-256). |
| **NFR-02** | Availability | The platform should ensure 99% uptime during standard working hours to guarantee uninterrupted public access. |
| **NFR-03** | Usability | The user interface must be accessible and comply with basic WCAG guidelines so that visually impaired citizens can still use the service. |
| **NFR-04** | Performance | The system needs to load pages within 3 seconds, even when hundreds of staff members are logged in simultaneously. |
| **NFR-05** | Reliability | Automated backups of the database must occur every 24 hours to prevent data loss in case of server failure. |

**Three Inaccurate or Unrealistic Requirements:**
During requirements gathering, some statements often turn out to be unfeasible or are simply observations.

| ID | Inaccurate Statement / Observation | Reason for Inaccuracy |
|:---|:---|:---|
| **IR-01** | *"The system must never ever crash."* | **Unrealistic:** All software has the potential for downtime due to unforeseen hardware or network issues. We should aim for high availability instead of impossible perfection. |
| **IR-02** | *"The interface needs to look very modern and cool."* | **Subjective Observation:** This is not a measurable requirement. What is 'modern' to one person might be confusing to an elderly user. It cannot be formally tested. |
| **IR-03** | *"Staff are currently taking too long to find files."* | **Observation statement:** This is a statement of the current business problem, not a technical requirement for the new system. It explains *why* we need a search function. |

### B4: MoSCoW Prioritisation Timebox
Applying the MoSCoW rules helps the team understand what to focus on during the initial development cycles.

| Priority | Assigned Requirements | Justification |
|:---|:---|:---|
| **Must Have** | User Registration <br> Form Submission <br> Admin Review Interface <br> Security (NFR) | These form the absolute core of the Minimum Viable Product (MVP). If the system is not secure or users cannot submit forms, the project is effectively useless. |
| **Should Have** | Document Upload <br> Search and Filter Tools <br> Usability (NFR) | These are highly important features that drastically improve the workflow. Without them, staff would have to rely on inefficient physical workarounds. |
| **Could Have**| Automated Communication <br> Application Dashboard <br> Performance optimization | These are desirable additions that enhance the user experience. However, they can be delayed to a later sprint if time runs short during development. |
| **Won't Have** *(for now)* | Complex reporting analytics <br> System integration with legacy software | While senior management might want fancy graphs, this does not help the immediate need of processing requests. It should be deferred to later phases. |

## Section C: LSEPi (Legal, Social, Ethical and Professional Issues)

### C1: The Data Controller and LSEPI considerations
**(a) The Role of the Data Controller:**
In any organisation handling information, the Data Controller plays a pivotal role. They are the entity (either an individual or a corporate body) that determines the ultimate purposes and the means of processing personal data. According to the Information Commissioner's Office (ICO, 2023), the Data Controller bears the highest level of accountability under the Data Protection Act 2018 (UK GDPR). They must ensure that data is collected fairly, kept secure, and only used for legitimate purposes.

**(b) Practical LSEPI Examples based on the Case Study:**
* **Legal:** The project is bound by strict privacy laws. *Practical example:* If the organisation builds a vulnerability in the administration portal and citizen records (such as [thay bằng dữ liệu nhạy cảm trong Case study, ví dụ: financial details]) are leaked to hackers, the organisation could face massive fines from the ICO and possible legal action from the public.
* **Social:** Developing digital-only platforms impacts society. *Practical example:* By moving the [tên dịch vụ trong bài] service entirely online, the organisation risks alienating elderly citizens or low-income families who may lack reliable internet access, thereby increasing social inequality.
* **Ethical:** This relates to doing what is morally right. *Practical example:* The organisation might decide to sell anonymous user data to third-party marketing companies to fund the IT project. While it might technically be anonymised, it is ethically questionable to monetize public sector data without explicit, informed consent.
* **Professional:** This involves the conduct of the project team. *Practical example:* The software developers might realise that the current timeline is too short to fully test the database structure. A professional issue arises if they choose to stay silent and deploy an unstable product rather than professionally warning management about the technical risks.

### C2: Professional Bodies and the BCS Code of Conduct
A professional body like the British Computer Society (BCS) exists to set and maintain high standards of competence, conduct, and ethical practice within the IT industry. By enforcing a Code of Conduct, the BCS ensures that its members act responsibly, protecting both the public and the reputation of the profession. To illustrate how this guides decision-making, we can look at the four main sections of the BCS Code:

1. **Public Interest:** IT professionals must safeguard public health, privacy, and safety. *Example:* A BCS member working on this project discovers a flaw that allows any user to view another person's submission. Following the code, they immediately halt the system rollout to fix it, putting the public's right to privacy ahead of the project's launch deadline.
2. **Professional Competence and Integrity:** Members should only undertake work they are qualified for. *Example:* If the project requires setting up a highly complex cloud security framework, a developer should honestly admit if they lack the specific cybersecurity training, rather than guessing and potentially compromising the system.
3. **Duty to Relevant Authority:** Members must respect the legitimate needs of their employers while avoiding conflicts of interest. *Example:* An IT manager on the project avoids hiring their best friend’s software company as a vendor, ensuring that contracts are awarded fairly and transparently based on merit.
4. **Duty to the Profession:** Professionals must uphold the reputation of the IT industry and support colleagues. *Example:* The senior agile scrum master actively mentors junior programmers on the team about secure coding practices, thereby raising the overall skill level and professionalism within the organisation.

## Conclusion and Assumptions
To summarise, the implementation of Agile methodologies presents a realistic and effective pathway for delivering this public sector project, allowing the team to adapt to changing requirements smoothly. By carefully filtering the functional and non-functional requirements and structuring them formally using MoSCoW rules, a clear roadmap for the initial software release has been established. Throughout this analysis, it is assumed that management is willing to embrace Agile culture and provide the necessary funding for proper cybersecurity measures. Ultimately, the success of the project does not just depend on writing code, but on strictly adhering to legal frameworks (like the DPA 2018) and maintaining the ethical standards championed by professional bodies such as the BCS.

## References
* Boehm, B. and Turner, R. (2004) *Balancing Agility and Discipline: A Guide for the Perplexed*. Boston: Addison-Wesley.
* Information Commissioner's Office (ICO) (2023) *Guide to the UK General Data Protection Regulation (UK GDPR)*. Available at: https://ico.org.uk/for-organisations/guide-to-data-protection/ (Accessed: 21 April 2026).
* Sommerville, I. (2015) *Software Engineering*. 10th edn. Pearson.
* The Chartered Institute for IT (BCS) (2022) *Code of Conduct*. Available at: https://www.bcs.org/membership-and-registrations/become-a-member/bcs-code-of-conduct/ (Accessed: 21 April 2026).
