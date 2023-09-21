### Scenario 1
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist. 

### Scenario 2
Botium Toys’ IT manager asked you to conduct an internal audit of the company’s assets, controls, and adherence to compliance regulations and standards. Then, based on the company’s current goals and level of risk, she requested that you complete a controls assessment and compliance checklist to identify and explain ways that the company can improve its security posture. 

Your task is to clearly and concisely communicate your findings and recommendations to the IT manager and other stakeholders, so they can implement the necessary controls and create appropriate documentation, processes, and procedures to ensure business continuity, the safety of critical assets, and compliance.

### Current assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Vendor access management
- Data center hosting services  
- Data retention and storage
- Badge readers
- Legacy system maintenance: end-of-life systems that require human monitoring

### Controls Assessment

![image](https://github.com/olabode-famobio/security-audit/assets/128502810/ca4200ee-6c5f-4983-a61d-ef8e888ae281)

![image](https://github.com/olabode-famobio/security-audit/assets/128502810/a51b2812-7efb-467b-ba72-ef5f3853c2d9)

![image](https://github.com/olabode-famobio/security-audit/assets/128502810/c34cfec0-deb9-4dc5-a00a-7088b905d5ca)


### Compliance checklist
- [ ] **The Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)**

  The FERC-NERC regulation applies to organizations that work with electricity or that are involved with the U.S. and North American power grid. Organizations have an obligation to prepare for, mitigate, and report any potential security incident that can negatively affect the power grid. Organizations are legally required to adhere to the Critical Infrastructure Protection Reliability Standards (CIP) defined by the FERC. 

  **Explanation**: NA
- [x] **General Data Protection Regulation (GDPR)**

  GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.

  **Explanation**: Botium Toys needs to adhere to GDPR because they conduct business and collect personal information from people worldwide, including the E.U.
- [x] **Payment Card Industry Data Security Standard (PCI DSS)**

  PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

  **Explanation**: Botium Toys needs to adhere to PCI DSS because they store, accept, process, and transmit credit card information in person and online.
- [ ] **The Health Insurance Portability and Accountability Act (HIPAA)**

  HIPAA is a federal law established in 1996 to protect U.S. patients' health information. This law prohibits patient information from being shared without their consent. Organizations have a legal obligation to inform patients of a breach. 

  **Explanation**: NA
- [x] **System and Organizations Controls (SOC type 1, SOC type 2)**

  The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.
  
  **Explanation**: Botium Toys needs to establish and enforce appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.

### Stakeholder memorandum 
TO: IT Manager, stakeholders

FROM: Olabode Famobio

DATE: 21/09/2023

SUBJECT: Internal IT audit findings and recommendations

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.


**Scope:**
- The following systems are in scope: accounting, end point detection, firewalls, intrusion detection system, SIEM tool. The systems will be evaluated for:
  - Current user permissions 
  - Current implemented controls
  - Current procedures and protocols
- Ensure current user permissions, controls, procedures, and protocols in place align with PCI DSS and GDPR compliance requirements.
- Ensure current technology is accounted for both hardware and system access.


**Goals:**
- Adhere to the NIST CSF.
- Establish a better process for their systems to ensure they are compliant. 
- Fortify system controls.
- Adapt to the concept of least permissions when it comes to user credential management. 
- Establish their policies and procedures, which includes their playbooks. 
- Ensure they are meeting compliance requirements.



**Critical findings (must be addressed immediately):**
- Multiple controls need to be developed and implemented to meet the audit goals, including:
  - Control of Least Privilege and Separation of Duties
  - Disaster recovery plans
  - Password, access control, and account management policies, including the implementation of a password management system
  - Encryption (for secure website transactions)
  - IDS
  - Backups
  - AV software
  - CCTV
  - Locks
  - Manual monitoring, maintenance, and intervention for legacy systems
  - Fire detection and prevention systems
- Policies need to be developed and implemented to meet PCI DSS and GDPR compliance requirements.
- Policies need to be developed and implemented to align to SOC1 and SOC2 guidance related to user access policies and overall data safety. 

**Findings (should be addressed, but no immediate need):** 
- The following controls should be implemented when possible:
  - Time-controlled safe
  - Adequate lighting
  - Locking cabinets
  - Signage indicating alarm service provider

**Summary/Recommendations:** It is recommended that critical findings relating to compliance with PCI DSS and GDPR be promptly addressed since Botium Toys accepts online payments from customers worldwide, including the E.U. Additionally, since one of the goals of the audit is to adapt to the concept of least permissions, SOC1 and SOC2 guidance related to user access policies and overall data safety should be used to develop appropriate policies and procedures. Having disaster recovery plans and backups is also critical because they support business continuity in the event of an incident. Integrating an IDS and AV software into the current systems will support our ability to identify and mitigate potential risks, and could help with intrusion detection, since existing legacy systems require manual monitoring and intervention. To further secure assets housed at Botium Toys’ single physical location, locks and CCTV should be used to secure physical assets (including equipment) and to monitor and investigate potential threats. While not necessary immediately, using encryption and having a time-controlled safe, adequate lighting, locking cabinets, fire detection and prevention systems, and signage indicating alarm service provider will further improve Botium Toys’ security posture.
