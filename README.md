 Project: Barclays – Open Banking API Enablement (PSD2 Compliance) 
�
� Project Overview 
Client: Barclays Bank PLC 
Initiative: Open Banking / PSD2 Compliance 
Timeline: November 2018 – May 2019 (6.5 months) 
Domain: Retail Banking, Regulatory Technology (RegTech), Digital APIs 
Regulation Basis: Revised EU Payment Services Directive (PSD2) 
�
� Project Objective 
To design and implement a secure, PSD2-compliant Open Banking platform allowing 
licensed third-party providers (TPPs) to access Barclays customer account and payment 
data with explicit customer consent. This included the creation of APIs for account access, 
consent management, and audit tracking. 
�
� Detailed BA Phase-wise Activities 
�
� Phase 1: Project Initiation & Stakeholder Alignment (3 weeks) 
Initiated discussions with cross-functional stakeholders: Product, Compliance, Legal, 
Security, and Architecture teams. Created stakeholder analysis matrix to determine 
influence and interest levels. Defined the project's scope and ensured strategic alignment 
with Barclays’ PSD2 roadmap. Established project Confluence space for documentation and 
JIRA epics for tracking. 
�
� Phase 2: Regulatory Requirements Elicitation (1 month) 
Worked closely with the Legal and Compliance departments to interpret PSD2 and EBA 
guidelines into actionable user stories and technical requirements. Created a compliance 
matrix and functional feature catalog. Ensured GDPR clauses were factored into account 
data sharing and consent protocols. 
�
� Phase 3: As-Is / To-Be Process Mapping & Gap Analysis (3 weeks) 
Mapped the existing digital banking data access processes (As-Is) and proposed the Open 
Banking architecture (To-Be) with BPMN 2.0 in Visio. Conducted a gap analysis identifying 
12 critical functional, security, and privacy gaps. Prioritized them using MoSCoW technique 
and refined requirements with architects. 
�
� Phase 4: Consent & Privacy (DPIA Phase) (4 weeks) 
Collaborated with the Data Protection Officer (DPO) to complete a comprehensive DPIA to 
identify and mitigate privacy risks. Documented risks around PII exposure, implemented 
mitigation via scoped access tokens and detailed consent logging. Designed Visio-based 
flowcharts for Consent Grant, Revocation, and Expiry. 
�
� Phase 5: Functional Requirements & API Design (1.5 months) 
Hosted requirement workshops with API architects and product owners. Defined OpenAPI 
specs for /accounts, /transactions, and /payments endpoints. Created detailed field-level 
mappings, error-handling logic, and authentication/authorization flows using OAuth2 + 
eIDAS certificates. 
�
� Phase 6: UAT Planning & Execution (1 month) 
Defined end-to-end test cases covering valid consent flows, invalid TPPs, expired tokens, 
and security breach scenarios. Managed UAT execution across 4 cycles. Logged and tracked 
over 40 defects in JIRA. Worked with developers to validate fixes and achieved test case 
success rate of 98% before sign-off. 
�
� Phase 7: Go-Live Support (2 weeks) 
Enabled early access to sandbox for top fintech partners like Yolt. Post-Go-Live, monitored 
API consumption metrics and consent revocations via Splunk dashboards. Facilitated 
onboarding documentation, FAQs, and API portal guides for external partners. Prepared 
production support checklist and change request register. 
�
� Post-Go-Live Performance & Data Highlights 
• API Uptime: 99.6% 
• TPPs Onboarded: 37 by launch 
• Avg Consent Validity: 89.2 days 
• API Call Success Rate: 97.6% 
• Consent Revocation Rate: ~4.2% monthly 
�
� Final BA Deliverables Summary 
• BRD – Confluence 
• RTM – Excel 
• DPIA – Word 
• Consent Flow Diagrams – Visio 
• As-Is / To-Be Maps – Visio 
• UAT Plan & Defect Log – Excel, JIRA 
