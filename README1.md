PCI DSS & HIPAA GRC Assessment – Nexus Health Services (Portfolio Project)
This project showcases how I approach Governance, Risk & Compliance (GRC) in a real-world healthcare scenario—bringing together business understanding, regulatory interpretation, risk analysis and practical remediation planning.

Nexus Health Services is a fictional multi-site healthcare organisation that processes both payment-card data and PHI/ePHI, creating a complex compliance landscape across hospitals, clinics, diagnostic systems, billing platforms and an online patient portal.

My goal in this project was to demonstrate how a GRC professional can translate regulatory requirements into clear scope, actionable risks and evidence-backed remediation.

🔍 Project Focus
I structured the assessment around a practical GRC workflow:

Business Scoping → Data Mapping → Compliance Scope → Risk Assessment → Evidence Planning → Remediation → Management Reporting

This mirrors how real organisations prepare for PCI DSS and HIPAA obligations while maintaining a risk-based mindset.

🏥 Business & Data Understanding
I began by mapping Nexus Health’s core processes and the sensitive data they handle:

Process	Data	System	Business Impact
Payment Processing	Cardholder data	Payment Platform	Financial loss, fraud, PCI exposure
Healthcare Billing	PHI/ePHI + billing	Billing System	Privacy breach, regulatory exposure
Customer Support	Customer information + PHI	CRM	Unauthorised disclosure
Account Management	Financial/account data	Account Platform	Fraud/account compromise
Vendor Management	Business/vendor data	Vendor Portal	Third-party risk


This mapping helped define what matters, where it lives, and what could go wrong — the foundation of any strong GRC assessment.

📜 Compliance Scope: PCI DSS & HIPAA
I assessed how PCI DSS and HIPAA apply across Nexus Health’s environment:

PCI DSS → Payment systems, CDE, online payment portal, connected controls

HIPAA → Billing systems, ePHI platforms, clinical systems, patient portal, BAAs

A key takeaway: PCI DSS and HIPAA overlap, but they are not the same scope.  
This distinction is essential for accurate compliance planning.

⚠️ Key Risk Scenarios Identified
1️⃣ Unnecessary Cardholder Data Storage
Risk of PCI DSS non-compliance and increased exposure.

2️⃣ Unsecured Online Payment Portal
Risk of web compromise, credential theft or card fraud.

3️⃣ Excessive PHI/ePHI Access
Risk of unauthorised disclosure or misuse of patient information.

4️⃣ Third-Party Weaknesses
Risk of vendor compromise affecting cardholder data or ePHI.

Each risk was investigated through structured questions around access, authentication, testing, contracts, evidence and system behaviour.

📁 Evidence Management
I designed an evidence plan to demonstrate both control design and control operation, including:

Data-flow diagrams

Vulnerability scans

Penetration-test results

Access reviews

MFA records

HIPAA risk analysis

Policies

Incident-response tests

This reflects a core GRC principle:
Controls mean nothing without evidence.

🚧 Risk-Based Remediation Roadmap
I prioritised remediation based on:

Severity

Regulatory exposure

Likelihood

Patient impact

Third-party dependencies

Critical priorities included:

Reducing cardholder-data exposure

Securing the online payment portal

Strengthening PHI/ePHI access governance

Improving third-party assurance

Medium priorities focused on formalising evidence management and centralising documentation.

📣 Executive Management Message
My final output summarised how leadership should treat PCI DSS and HIPAA as part of a broader enterprise risk-management programme, emphasising:

Risk-based decision-making

Clear ownership

Defined deadlines

Evidence requirements

Third-party assurance

Continuous monitoring

Success metrics included closure of high-risk findings, validated evidence, stronger access governance and improved monitoring.

🧩 Skills Demonstrated
Risk identification & assessment

PCI DSS scoping****/HIPAA Security Rule interpretation

Control mapping

Evidence planning & governance

Access governance (RBAC, MFA, reviews)

Vulnerability management & testing

Third-party assurance

Executive communication & reporting

📂 Suggested Repository Structure
text
PCI-DSS-HIPAA-Nexus-Health/
│
├── README.md
├── 01-Business-Scope/
├── 02-Compliance-Scope/
├── 03-Risk-Assessment/
├── 04-Control-Mapping/
├── 05-Evidence-Plan/
├── 06-Remediation/
├── 07-Management-Reporting/
└── docs/
💡 Key Takeaway
This project demonstrates that GRC is not just about asking:

“Are we compliant?”

It’s about understanding:

What matters, what threatens it, what controls reduce the risk, what evidence proves it, and what leadership should prioritise.

That’s the mindset I apply in my GRC work.
