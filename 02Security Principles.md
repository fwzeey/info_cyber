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


![download](https://github.com/user-attachments/assets/8eb4580f-18f5-4392-87a2-ee0c48c3bb54)


## Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key — too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).

## Examples 
- **Confidentiality Violation:** Unauthorized access to customer data (e.g., Facebook-Cambridge Analytics case).
- **Integrity Violation:** Tampered medical date in hospitals leading to misdiagnosis.
- **Avialability Violation** DDos attack on banking websites preventing service access.

# Risk, Privacy, and Accountability
# Risk
- Defintion: Probability of a threat exploiting a vulnerability to cause harm.

## Components:
- Threat -> something that can cause damage.
- Vulnerability -> weakness that can be exploited.
- Impact -> damage if threat is realized

## Formula:
- Risk = Threat x vulnerability x Impact

## Example: 
*Threat:* Phishing 
*Vulnerability:* Employee lack of awareness 
*Impact:* Credential theft, financial loss 


![OIP](https://github.com/user-attachments/assets/477a2708-10dd-43b5-8e0d-3cf0e49b7391)


# Privacy 
- Protecting personel and sensitive information of individuals. 
- Governed by laws like GDPR, DPDP Act (India), HIPAA

  
![OIP](https://github.com/user-attachments/assets/0e8a9225-4930-4b03-ad28-be557b9c0488)


## Key Practices:
- Data minimization 
- Informed consent 
- Data anonymization
  
Example: A healthcare app must not share user health data without consent.

# Accountability
Ensuring every action in an IT system can be traced back to an individual.
## Achieved through:
- Logging & auditing
- User access tracking
- Non-repudiation mechanisms
  
Example: Audit logs in firewalls to trace malicious user actions. 


## Real-Morld Case Studies

| Case                  | Description                                          | Violated Principle 
|-----------------------|------------------------------------------------------|--------------------
| WannaCry (2017)       | Ransomware disabled hospital systems worldwide       | Availability             
| Equifax Breach (2017) | Personal data of 143M users leaked                   | Confidentiality & Integrity    
| Twitter Hack (2020)   | Insider access to admin tools                        | Confidentiality & Accountability


