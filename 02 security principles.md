# Security Principles

## Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relate security principles to real-world cyber incidents.

## CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element | Description | Example |
|----------|--------------|----------|
| Confidentiality | Ensures data is accessible only to authorized users. | Encrypting files, using passwords, access control lists. |
| Integrity | Ensures data is accurate, consistent, and not tampered with. | Using hashing, digital signatures, checksums. |
| Availability | Ensures systems and data are available when needed. | Redundant servers, backups, DDoS protection. |

![download](https://github.com/user-attachments/assets/a5e41e38-9763-44f2-892b-bf54c030f44a)

##examples
- Confidentiality violation:Unaouthorized access to customer data(e.g, Favebook-Cambridge Analytic case).
- Integrity Violation:Tampered medical data in hospitals leading to misdiagnosis
- Availability violation: DDos attack on banking websites preventing service access


# Risk,Privacy and Accountability
## Risk
- Defenition: probability of a threat exploiting a vulnerability to cause harm
*components*
  - Threat-->something that can cause damage
  -  Vulnerability--> weakness that can be exploited
  -  Impact--> damage if threat is realized
*Formula*
  - Risk=Threat x Vulnerability x Impact
 
## examples
- Threat: phishing
- Vulnerability: Employee lack of awareness
-  Impact:Credential theft,financial loss
   
  ![download](https://github.com/user-attachments/assets/0fd18b16-8da0-4ae5-95bb-bf165c80d84a)




# Privacy
- protecting personal and sensitive information of individuals
- Governed by Laws lik GDPR,DPDP Act (India),HIPAA.
 
  ![download](https://github.com/user-attachments/assets/a192c0be-415d-4098-a3fb-82187f573d22)


## key practices:
- Data minimization
- Informed consent
- Data anonymization

Example: A healthcare app must not share user health data without consent

# Accountability
Ensuring every action in an IT system can be traced back to an induvidual.

## Achieved through:
- Logging & auditing
- Using access tracking
- Non-repudiation mechanisms


Example:Audit logs in firewalls to trace malicious user actions.


|        Case                  |           Description                           |           Violated Principle |
| ------------------ | ----------------------------------------------------- | ---------------------------------------------------- |
|WannaCry (2017)               | Ransomware disabled hospital systems worldwide  | Availability                 |
|Equifax Breach (2017)         | Personal data of  143M users leaked             | Confidentiality & Integrity|
|Twiter Hack (2020)            | Insider access to admin tools                   | Confidentiality & Accountability|
